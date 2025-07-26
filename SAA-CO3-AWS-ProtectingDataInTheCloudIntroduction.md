# Protecting Data in the Cloud Introduction

![ProteccionDataintheCloudIntroduccion](image-9.png)

## AWS Backup.

+ AWS Backup for backup in cloud and onpremise.

![AwsBackup](image-10.png)

## Support AWS resources.

+ Included compute, services and databases.

### Compute services 

+ Included Amazon EC2, included amazon EC2 instance stores backup.
+ Windows volumen shadow copy services (VSS) on Amazon EC2.

### Storage Services.

+ Amazon Elastic block store (Amazon EBS)
+ Amazon Elastic File system (Amazon EFS)
+ Amazon Simple Storage Service (Amazon S3)
+ Amazon FSx for Windows File Server.
+ Amazon FSx for Lustre.
+ AWS Storage Gateway Volumes.

### Database services.

+ Amazon Relational database service (Amazon RDS) databases, included all database engine.
+ Amazon Aurora cluster.
+ Amazon DynamoDB Tables.
+ Amazon Neptune databases.
+ Amazon DocumentDB (with MongoDB compatibility) databases.

## AWS Backup features.

+ Centralized backup management.
+ Policy-based backup.
+ Automated backup scheduling.
+ Automated retention management.
+ Lifecycle management policies.
+ Incremental backup.
+ Cross-region backup.
+ Cross-account management and backup.
+ Backup activity monitoring.
+ Secure data.
+ Compliance.

## Uses cases.

+ Data recovery.
+ Data retention.
+ Disaster Recovery.
+ Compliance requerements.

+ There are two cases clearly defined.

+ Cloud native backup.
    + Provide console centralized.
    + Can back up key data stores, such as store volumen, databases and file systems.
        + Amazon EBS
        + Amazon RDS.
        + Amazon DynamoDB.
        + Amazon EFS.
        + Amazon FSx, Amazon EC2.
        + AWS Storage Gateway.

+ Hybryd backup.

AWS Backup integrates with storage gateway, a hybrid storage service to enables your onpremises applications to seamlessy use AWS Cloud Storage.

Pricing.

## Native service snapshots.

+ Snapshots are individial services which provide point-in-time copies the your date.
+ Snapshots are stored part of Amazon as part of the managed service, protect you data with 99.999999999 (11 9s).
+ Two core services allow snapshots, Amazon EBS and Amazon FSx for lustre refres to the service as backups.
  
  ![awsNativeServiceSnapshots](image-11.png)

## Amazon EBS snapshots.

## Amazon FSx for lustre snapshots.

+ FSx for lustre backups are file system consistent, highly durable, and incremental. To provide high durabiliy, FSx for lustre stores your backups in Amazon S3 with 99.999999999 (11 9s).
  
## Pricing.

+ Pay only for storage capacity.

## Cloud endure Disaster Recovery.

+ Use the same replication method to stage copies of your on-premise aplications.
+ Use to protect you most critica databases, including Oracle, MySQL, and SQL Server and enterprise application such as SAP.

## Cloud endure features.

+ Continuos replication.
+ Low cost staging area.
+ Automated machine conversion and orchestration.
+ Point-in-time recovery testing.
+ Non-disruptive disaster recovery testing.
+ Wide application and infrastructure support.

## Princing.

+ Billed for hourly for server registered.
+ Included continuos data replication.