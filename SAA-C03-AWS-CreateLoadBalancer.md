instance 1: subnet-085a8be5c18f10a7b
instance 2: subnet-028ea6c372151805b
nsg load balancer: 

i-0ca087d1d07b5b5ad
i-00ac26cf641111658

aws elbv2 register-targets --target-group-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:targetgroup/TG1/074488ce1a4d878c --targets Id=i-0ca087d1d07b5b5ad

aws elbv2 register-targets --target-group-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:targetgroup/TG2/074ebaeced54419c  --targets Id=i-00ac26cf641111658


aws elbv2 create-listener --load-balancer-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:loadbalancer/app/whizlabs-LB/17646347f185e038 --protocol HTTP --port 80 --default-actions Type=forward,TargetGroupArn=arn:aws:elasticloadbalancing:us-east-1:711863567759:targetgroup/TG1/074488ce1a4d878c

aws elbv2 create-rule --listener-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:listener/app/whizlabs-LB/17646347f185e038/5623e839de01d350 --priority 10 --conditions Field=path-pattern,Values='/images/*' --actions Type=forward,TargetGroupArn=arn:aws:elasticloadbalancing:us-east-1:711863567759:targetgroup/TG1/074488ce1a4d878c

aws elbv2 create-rule --listener-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:listener/app/whizlabs-LB/17646347f185e038/5623e839de01d350 --priority 5 --conditions Field=path-pattern,Values='/work/*' --actions Type=forward,TargetGroupArn=arn:aws:elasticloadbalancing:us-east-1:711863567759:targetgroup/TG2/074ebaeced54419c


aws elbv2 describe-target-health --target-group-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:targetgroup/TG1/074488ce1a4d878c

aws elbv2 describe-target-health --target-group-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:targetgroup/TG2/074ebaeced54419c


# Delete 

```
aws elbv2 delete-load-balancer --load-balancer-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:loadbalancer/app/whizlabs-LB/17646347f185e038
aws elbv2 delete-target-group --target-group-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:targetgroup/TG1/074488ce1a4d878c
aws elbv2 delete-target-group --target-group-arn arn:aws:elasticloadbalancing:us-east-1:711863567759:targetgroup/TG2/074ebaeced54419c
aws ec2 terminate-instances --instance-ids i-00ac26cf641111658 i-0ca087d1d07b5b5ad i-02186aa82a257f31c

```