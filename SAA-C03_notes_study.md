# Exam-SAA-C03

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

# Module 3 : AWS Networking 

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

# Module 4 : AWS Storage.

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

+ Amazon EBS use cases.

    + Operating systems.

    + Databases.

    + Enterprise applications.

    + Big data analytics engines.

+ EBS volumens types.

    + SSD Volumes.

    + HDD Volumes.

+ Amazon EBS benefits.

    + High availability.

    + Data persistence.

    + Data encryption.

    + Flexibility.

    + Backups.

+ Amazon EBS Snapshots.

    + EBS snapshots are incremental backups that only save the blocks on the volume that have changed after your most recent snapshot.

## Object Storage with Amazon S3.

Object storage is built for the cloud and delivers virtually unlimited scalability, high durability, and cost effectiveness.

Multiattach volumes not support whithin Amazon S3.

Amazon S3 is design for have 99.99% of availability.

Is design for eleven 11 , for example, 99.9999999999%

Firs step is create one bucket.

For naming buckets there are rules.

Amazon S3 uses cases.

    + Backup and restore.

    + Media hosting.

    + Software delivery.

    + Data lakes.

    + Static Websites.

    + Static content.

Security in Amazon S3.

    + Everithing is private en Amazon S3.

    + Amazon S3 and IAM policies.

    + Amazon S3 bucket policies.

    + Amazon S3 storage classes.

    + Amazon S3 versioning.

    + Managing your storage lifecycle.

## Chosing  the right storage service.

    + Amazon EC2 instance store.
    
    + Amazon EBS.

    + Amazon S3.

    + Amazon EFS.

    + Amazon FsX.

### Demostration createting a S3 bucket.

Answers 100% ok in the first intent.

# Module 5: Introductiong to databases on AWS.

+ More popular database are relational database, more selected in the history.

    + MySQL.
    
    + PostgreSQL.

    + Oracle.

    + Microsoft SQL.

    + Amazon Aurora.

+ More Benefits use Relational database.

    + Complex SQL.

    + Reduced redundancy.

    + Familiarity.

    + Accuracy.

+ Choose between unmanaged and managed databases.

    + Unmanaged instances.

        + Defined responsbility for this model.

    + Managed instances.

        + Defined responsbility for this model.

### Amazon RDS.

+ More commoms engine into Amazon RDS.

    + Aurora.

        + Can auto scale up to 128 tebibytes (TiB).

    + MySQL.

    + MariaDB.

    + PostgreSQL.

    + Oracle.

    + Microsoft SQL Server.

+ Support engine for Amazon RDS.

    + Comercial :  Oracle and SQL Server.

    + Open source : MySQL, PostgreSQL, MariaDB.

    + Aurora.

+ Databases instances.

+ Storage on Amazon RDS.

+ Amazon RDS in an Amazon Virtual Private Cloud.

+ Backup data.

    + Automatic backup.

        + Retain backup.

        + Point-in-time recovery.

    + Snapshots.

+ Redundancy with Amazon RDS Multi-AZ.

+ Amazon RDS security

### Purpose-Built Databases

+ Amazon DynamoDB.

    + Is a NoSQL Database, is key-value pair.

+ Amazon ElastiCache.

    + Is a fully managed, in-memory caching solution.

+ Amazon MemoryDB for Redis.

    + MemoryDB is a Redis-compatible, durable, in-memory database service that delivers ultra-fast performance.

+ Amazon DocumentDB ( with MongoDB compatibility ).

    + Amazon DocumentDB has API compatibility with MongoDB.

+ Amazon Keyspace ( for apache Casandra).

    + Amazon Keyspaces is a scalable, highly available, and managed Apache Cassandra compatible database service.

+ Amazon Neptune.

    + Graphics database.

+ Amazon QLDB.

    + Amazon Quantum Ledger Database

### Amazon DynamoDB.

+ Is a Serverless Dabatabase, fully managed NoSQL database.

+ No required a schema like MySQL or SQL Server Database.

    + Don't create database and tables, only create tablas standalone.

+ Amazon DynamoDB uses cases.

    + Develop software applications.
    
    + Create media metadata stores.
    
    + Scale Games Platforms.

    + Delivery seamless retail experiences.

### Choosing the Right Database Service.

+ Amazon RDS, Aurora, Amazon Redshift
    
    + Database type : Relational.

    + Uses cases : Traditional application ERP, CRM, Ecommerce.

+ DynamoDB.

    + Database type : Key-value.

    + Uses cases : High-traffic web applications, ecommerce systems, gaming applications.

+ Amazon ElastiCache for Memcached, Amazon ElastiCache for Redis.

    + Database type : In-memory

    + Uses cases : Caching, session management, gaming leaderboards, geospatial applications

+ Amazon DocumentDB.

    + Database type : Document.

    + Uses cases : Content management, catalogs, user profiles

+ Amazon Keyspaces.

    + Databases type : Wide column

    + Uses cases : High-scale industrial applications for equipment maintenance, fleet management, route optimization

+ Neptune.

    + Databases type : Graph.

    + Uses cases : Fraud detection, social networking, recommendation engines.

+ Timestream.

    + Databases type : Time series.

    + Uses cases : IoT applications, Development Operations (DevOps), industrial telemetry.

+ Amazon QLDB.

    + Databases type : Ledger.

    + Uses cases : Systems of record, supply chain, registrations, banking transactions

+ The industry of software going to the microservices.










**[⬆ Back to Top](Exam-SAA-C03)**