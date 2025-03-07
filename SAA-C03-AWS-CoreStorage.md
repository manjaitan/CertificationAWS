## Core AWS Storage services.

### Block Storage: Amazon EBS.

+ There are two types the block storage.
    + Amazon Elastic compute cloud ( Amazon EC2 ).
    + Amazon Block store ( Amazon EBS )

### Amazon EC2 instance store.

+ Provide storage ephimeral is attached in computer.
+ Only EC2 can be associated to the EC2 instance types.

### Instsance store lifetime.

+ The underlying disk drive fails.
+ The instance stops.
+ The instance hibernates.
+ The instance terminates.

### Amazon EBS features.

+ Single availability zone.
+ Persistent.
+ Volume types.
+ Elastic volumes.
+ High availability and high durability
+ Data encryption.
+ Nativa snapshot support.
+ AWS backup support.
+ Performance monitoring.

### Case of uses.

+ Enterprise application.
+ relational database.
+ nonrelational ( NoSQL ).
+ bit data analytics.
+ file systems and media workflows.

### Lift and shift on-premises applications using Amazon EBS.

### Pricing.

+ You pay only for what you use.

## File Storage: Amazon EFS.

+ There are

 three different managed file storage service.

### Amazon EFS

+ Can grow to petabyte scale.
+ Standar Storage classes.
+ One zone storage classes.
+ Offers
    + Simple interface.
    + File system access semantics.
    + Support authentication.
    + Provides the throughput, input operation for seconds.

### Amazon EFS features.

+ Fully managed.
+ Storage classes and lifecycle management.
+ Security and compliance.
+ Scalable performance.
+ Shared file systems with NFS v4.0 and v4.1 support.
+ Performance modes.
+ Throughput modes.
+ Elastic and scalable.
+ Encryption.
+ Containers and serverless file storage.
+ Data transfers and backup.

### Amazon EFS uses cases.

+ Containers serverless persistent file storage.
+ Move to managed file systems.
+ Analitics and machine learning.
+ Web serving and content management.
+ Application testing and development.
+ Media and entertainment.
+ Database backups.

### Pricing.

+ You pay only for used.

## Amazon FSx for lustre.

+ Is open-source.
+ Is designed for compute-intensive.

### Amazon FSx for lustre features.

+ High scalable performance.
+ Seamless access to data repositories.
+ Simple and fully managed.
+ Native-file-system compliant.
+ Cost optimized.
+ Secure and compliant.

### Amazon FSx for lustre use cases.

+ Horizontal uses cases.
+ Vertical uses cases.
    + Life science genomics.
    + Financial models.
    + Industrial design simulation.
    + Media special effects and rendering.
    + Seismic and reservir exploraion.
    + Any othe vertical where HOC and machine language are present.
        + Horizontal - Machine learning.
        + Horizontal - High performance computing.
        + Vertical - Genomics and life sciences.
        + Vertical - Media processing and transcofing.
        + Vertical - Autonomous vehucles.
        + Vertical - SAS Grib computing.

### Pricing.

## File Storage: Amazon FSx for Windows File Server.

### Amazon FSx for windows file server overview.

+ Amazon FSx for Windows File Server provides fully managed microsoft windows file servers.
+ Access to file storage over network, FSx for windows file server, SMB protocol.
+ File server incluying the following services:
    + Bussines applicactions.
    + Home directories.
    + Web serving.
    + Content management.
    + Data analytics.
    + Software build setups.
    + Media processing workloads.

### Amazon FSx for windows file server features.

+ Built on windows server.
+ Broadly accessible.
+ Fully managed.
+ Performance and scalability.
    + Performance.
    + Scale.
+ Security and compliance.
    + Encryption.
    + Compliance.
    + Identity-based authentication.
    + Access control and monitoring.
    + Network isolation.
    + File access auditing.
+ Availability and durability.
    + Highly available and durable.
    + Multi-AZ deplouments.
    + Support for high avalability Microsoft SQL server deployments.
+ Data protection.
    + Automated daily backups.
    + Easy file-level restores ( Microsoft Windows shadow copies )
    + Centralized backup and compliance with AWS Backup.
    + Cross-Region and cross-account backuo compliance.
+ Cost effectiveness.
    + Storage option.
    + Data deduplication.
    + User quotas.
+ Efficient migration with AWS DataSync.

### Amazon FSx for windows file server use cases.

+ Home directories.
+ Lift and shift windows applications.
+ Highly available Microsoft SQL Server deployments.
+ Media workflows.
+ Web serving and content management.
+ Data analytics.

### Pricing.

+ HDD y SDD storage.
+ Throughput capacity.
+ Backups.
+ Data transfer in and out FSx for Windows File Server across availability zones and VPC peering connections.
+ Data trasnfers out of FSx for Windows File server to other Regions.

