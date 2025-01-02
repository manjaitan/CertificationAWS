# Start 26 de Diciembre:
## Exam SAA-C03.



# AWS Technicals essentials:


# Module 1 : Introduction to amazon web services.


### Whats is AWS.

+

### AWS EC2

+

### AWS Global infractucture.

+

### Interacting wiht AWS.

+

### Protecting the AWS Root User.

+

### AWS identity and access management.

+ EC2.

+ AMI.


# Module 2 : AWS Compute:

### Containers.

+ Amazon ECS

    + Task definition for create application.

+ Amazon EKS

### Serverless

+ AWS Fargate

+ AWS Lambda

## Module 3 : AWS Networking 

+ VPC

+ Subnet

+ IP Address.

### Amazon VPC.

+ VPC

+ Subnet

+ Internet Gateway

    + Connect VPC to the internet.

+ Virtual Private Grateay.

    + Permit create a VPN between On-Premise data center and VPC.
    + Is created encryption connection.

+ AWS Direct connect.

    + To establish a secure physical connection between your on-premise data center and your Amazon VPC.

### Amazon VPC Routing.

+ A route table contains a set of rules, called routes, that determine where network traffic from your subnet or gateway is directed.

    + Main route table.

    + Custom routing table.

### Amazon VPC Security.

+ You have two options for Security VPC resources, there are ACL and Security group.

    + ACL is a firewall by level subnet.

    + NSG (network security group)

## Module 4 : AWS Storage.

### Storage types.

+ There are three diferents type the storage, File storage, Block storage, Object storage.

    + File Storage.

        + Case of uses:

            + web Serving.

            + Analitycs.

            + Media and entertainment.

            + Home Directories.

    + Block Storage (1 gbs file)

        + Is similary to singular unit.

        + Case of uses:

            + Transacational workloads.

            + Containers.

            + Virtual Machines.

    + Object Storage (1 gbs file)

        + Files are storage as objects.
        
        + Case iof uses.

            + Data Archiving.

            + Backup and recovery.

            + Rich media.

Relating back to traditional storage systems.

    + Block Storage is a similar a SAN.

    + File Storage is similary a SAN.

## File Storage with Amazon EFS ans Amazon FSx.


### Amazon EFS.

    +   Amazon Elastic File System (Amazon EFS) is a set-and-forget file system that automatically grows and shrinks as you add and remove files.

### Amazon FSx.

    + Amazon FSx is a fully managed service that offers reliability, security, scalability, and a broad set of capabilities that make it convenient and cost effective to launch, run, and scale high-performance file systems in the cloud.


## Block Storage with Amazon EC2 Instance Store and Amazon EBS.


