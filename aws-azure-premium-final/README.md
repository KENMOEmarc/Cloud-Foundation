<div align="center">

# ☁️ AWS ↔ Azure Services Mapping Reference

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws) ![Azure](https://img.shields.io/badge/Azure-Cloud-blue?style=for-the-badge&logo=microsoftazure) ![Mappings](https://img.shields.io/badge/140-Service_Mappings-success?style=for-the-badge)

</div>

> Note: the icon columns below assume you have extracted the official AWS and Azure SVG icon packs locally into `./assets/aws/` and `./assets/azure/`.
> The official download pages are listed at the end.

## Table of Contents

- [☁️ AWS ↔ Azure Services Mapping Reference](#️-aws--azure-services-mapping-reference)
  - [Table of Contents](#table-of-contents)
  - [🖥️ Compute \& Serverless](#️-compute--serverless)
  - [📦 Containers \& App Platform](#-containers--app-platform)
  - [💾 Storage, Transfer \& Backup](#-storage-transfer--backup)
  - [🌐 Networking, Delivery \& Edge](#-networking-delivery--edge)
  - [🔐 Security, Identity \& Governance](#-security-identity--governance)
  - [🗄️ Databases \& Caching](#️-databases--caching)
  - [📊 Analytics, Streaming \& Data](#-analytics-streaming--data)
  - [🤖 AI, ML \& Search](#-ai-ml--search)
  - [📩 Messaging, Integration \& Automation](#-messaging-integration--automation)
  - [📈 Observability, DevOps \& Migration](#-observability-devops--migration)
  - [📚 Official Documentation Links](#-official-documentation-links)
    - [AWS](#aws)
    - [Azure](#azure)
  - [Notes](#notes)

<a id="compute-serverless"></a>

## 🖥️ Compute & Serverless

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/EC2.svg" width="64" height="64" alt="EC2"> **EC2** | <img src="./assets/azure/Virtual-Machine.svg" width="64" height="64" alt="Virtual Machines"> **Virtual Machines** | Virtual servers / cloud compute instances |
| <img src="./assets/aws/EC2-Auto-Scaling.svg" width="64" height="64" alt="EC2 Auto Scaling"> **EC2 Auto Scaling** | <img src="./assets/azure/VM-Scale-Sets.svg" width="64" height="64" alt="VM Scale Sets"> **VM Scale Sets** | Automatic scaling of compute capacity |
| <img src="./assets/aws/Lambda.svg" width="64" height="64" alt="Lambda"> **Lambda** | <img src="./assets/azure/Function-Apps.svg" width="64" height="64" alt="Azure Functions"> **Azure Functions** | Serverless event-driven compute |
| <img src="./assets/aws/Elastic-Beanstalk.svg" width="64" height="64" alt="Elastic Beanstalk"> **Elastic Beanstalk** | <img src="./assets/azure/App-Services.svg" width="64" height="64" alt="App Service"> **App Service** | Managed application deployment platform |
| <img src="./assets/aws/Lightsail.svg" width="64" height="64" alt="Lightsail"> **Lightsail** | <img src="./assets/azure/App-Service-Plans.svg" width="64" height="64" alt="App Service Plans"> **App Service Plans** | Simplified VPS-style hosting |
| <img src="./assets/aws/Batch.svg" width="64" height="64" alt="Batch"> **Batch** | <img src="./assets/azure/Batch-Accounts.svg" width="64" height="64" alt="Azure Batch"> **Azure Batch** | Batch processing jobs |
| <img src="./assets/aws/EC2.svg" width="64" height="64" alt="Spot Instances"> **Spot Instances** | <img src="./assets/azure/Virtual-Machine.svg" width="64" height="64" alt="Spot Virtual Machines"> **Spot Virtual Machines** | Discounted interruptible compute |
| <img src="./assets/aws/EC2-Image-Builder.svg" width="64" height="64" alt="Image Builder"> **Image Builder** | <img src="./assets/azure/Image.svg" width="64" height="64" alt="Azure Image Builder"> **Azure Image Builder** | Golden image build automation |
| <img src="./assets/aws/App-Runner.svg" width="64" height="64" alt="App Runner"> **App Runner** | <img src="./assets/azure/Container-Instances.svg" width="64" height="64" alt="Container Apps"> **Container Apps** | Managed app deployment for containers |
| <img src="./assets/aws/Outposts-family.svg" width="64" height="64" alt="Outposts"> **Outposts** | <img src="./assets/azure/Azure-Stack.svg" width="64" height="64" alt="Azure Stack Hub"> **Azure Stack Hub** | Hybrid cloud infrastructure |
| <img src="./assets/aws/Local-Zones.svg" width="64" height="64" alt="Local Zones"> **Local Zones** | <img src="./assets/azure/Location.svg" width="64" height="64" alt="Edge Zones"> **Edge Zones** | Low-latency local compute |
| <img src="./assets/aws/Wavelength.svg" width="64" height="64" alt="Wavelength"> **Wavelength** | <img src="./assets/azure/Location.svg" width="64" height="64" alt="Edge Zones"> **Edge Zones** | Ultra-low-latency edge compute |
| <img src="./assets/aws/VMware-Cloud-on-AWS.svg" width="64" height="64" alt="VMware Cloud on AWS"> **VMware Cloud on AWS** | <img src="./assets/azure/AVS.svg" width="64" height="64" alt="Azure VMware Solution"> **Azure VMware Solution** | Managed VMware platform |
| <img src="./assets/aws/WorkSpaces-Family.svg" width="64" height="64" alt="WorkSpaces"> **WorkSpaces** | <img src="./assets/azure/Windows-Virtual-Desktop.svg" width="64" height="64" alt="Azure Virtual Desktop"> **Azure Virtual Desktop** | Managed virtual desktops |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="containers-app-platform"></a>

## 📦 Containers & App Platform

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/ECS-Anywhere.svg" width="64" height="64" alt="ECS"> **ECS** | <img src="./assets/azure/Container-Instances.svg" width="64" height="64" alt="Container Apps"> **Container Apps** | Managed container orchestration |
| <img src="./assets/aws/EKS-Anywhere.svg" width="64" height="64" alt="EKS"> **EKS** | <img src="./assets/azure/Kubernetes-Services.svg" width="64" height="64" alt="AKS"> **AKS** | Managed Kubernetes |
| <img src="./assets/aws/Fargate.svg" width="64" height="64" alt="Fargate"> **Fargate** | <img src="./assets/azure/Container-Instances.svg" width="64" height="64" alt="Container Apps Jobs"> **Container Apps Jobs** | Serverless containers |
| <img src="./assets/aws/Elastic-Container-Registry.svg" width="64" height="64" alt="ECR"> **ECR** | <img src="./assets/azure/Container-Registries.svg" width="64" height="64" alt="Container Registry"> **Container Registry** | Container image registry |
| <img src="./assets/aws/ECS-Anywhere.svg" width="64" height="64" alt="ECS Anywhere"> **ECS Anywhere** | <img src="./assets/azure/Azure-Arc.svg" width="64" height="64" alt="Azure Arc-enabled Kubernetes"> **Azure Arc-enabled Kubernetes** | Run containers outside the cloud |
| <img src="./assets/aws/EKS-Anywhere.svg" width="64" height="64" alt="EKS Anywhere"> **EKS Anywhere** | <img src="./assets/azure/Azure-Arc.svg" width="64" height="64" alt="Azure Arc-enabled Kubernetes"> **Azure Arc-enabled Kubernetes** | Kubernetes anywhere management |
| <img src="./assets/aws/CodeCatalyst.svg" width="64" height="64" alt="AWS Proton"> **AWS Proton** | <img src="./assets/azure/DevTest-Labs.svg" width="64" height="64" alt="Deployment Environments"> **Deployment Environments** | Template-based app delivery |
| <img src="./assets/aws/App-Mesh.svg" width="64" height="64" alt="App Mesh"> **App Mesh** | <img src="./assets/azure/Mesh-Applications.svg" width="64" height="64" alt="Service Mesh"> **Service Mesh** | Service-to-service networking |
| <img src="./assets/aws/Cloud-Map.svg" width="64" height="64" alt="Cloud Map"> **Cloud Map** | <img src="./assets/azure/DNS-Zones.svg" width="64" height="64" alt="Private DNS"> **Private DNS** | Service discovery and naming |
| <img src="./assets/aws/Elastic-Container-Service.svg" width="64" height="64" alt="Elastic Container Service Anywhere"> **Elastic Container Service Anywhere** | <img src="./assets/azure/Azure-Arc.svg" width="64" height="64" alt="Azure Arc-enabled Kubernetes"> **Azure Arc-enabled Kubernetes** | Hybrid container management |
| <img src="./assets/aws/Lightsail.svg" width="64" height="64" alt="Lightsail Containers"> **Lightsail Containers** | <img src="./assets/azure/Container-Instances.svg" width="64" height="64" alt="Container Instances"> **Container Instances** | Simplified container hosting |
| <img src="./assets/aws/Serverless-Application-Repository.svg" width="64" height="64" alt="Serverless Application Repository"> **Serverless Application Repository** | <img src="./assets/azure/Marketplace.svg" width="64" height="64" alt="Azure Marketplace"> **Azure Marketplace** | Reusable serverless app patterns |
| <img src="./assets/aws/CodeCatalyst.svg" width="64" height="64" alt="CodeCatalyst"> **CodeCatalyst** | <img src="./assets/azure/Dev-Console.svg" width="64" height="64" alt="Dev Center"> **Dev Center** | Integrated app delivery workspace |
| <img src="./assets/aws/Elastic-Beanstalk.svg" width="64" height="64" alt="Elastic Beanstalk Extensions"> **Elastic Beanstalk Extensions** | <img src="./assets/azure/App-Services.svg" width="64" height="64" alt="App Service"> **App Service** | Platform configuration and deployment |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="storage-transfer-backup"></a>

## 💾 Storage, Transfer & Backup

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/Simple-Storage-Service.svg" width="64" height="64" alt="S3"> **S3** | <img src="./assets/azure/Blob-Block.svg" width="64" height="64" alt="Blob Storage"> **Blob Storage** | Object storage |
| <img src="./assets/aws/Elastic-Block-Store.svg" width="64" height="64" alt="EBS"> **EBS** | <img src="./assets/azure/Disks.svg" width="64" height="64" alt="Managed Disks"> **Managed Disks** | Block storage for VMs |
| <img src="./assets/aws/EFS.svg" width="64" height="64" alt="EFS"> **EFS** | <img src="./assets/azure/Files.svg" width="64" height="64" alt="Azure Files"> **Azure Files** | Managed shared file storage |
| <img src="./assets/aws/FSx.svg" width="64" height="64" alt="FSx"> **FSx** | <img src="./assets/azure/Azure-NetApp-Files.svg" width="64" height="64" alt="Azure NetApp Files"> **Azure NetApp Files** | Enterprise file systems |
| <img src="./assets/aws/Simple-Storage-Service-Glacier.svg" width="64" height="64" alt="S3 Glacier"> **S3 Glacier** | <img src="./assets/azure/Storage-Accounts.svg" width="64" height="64" alt="Archive Storage"> **Archive Storage** | Long-term archival storage |
| <img src="./assets/aws/Storage-Gateway.svg" width="64" height="64" alt="Storage Gateway"> **Storage Gateway** | <img src="./assets/azure/Storage-Sync-Services.svg" width="64" height="64" alt="File Sync"> **File Sync** | Hybrid storage gateway |
| <img src="./assets/aws/DataSync.svg" width="64" height="64" alt="DataSync"> **DataSync** | <img src="./assets/azure/Data-Factory.svg" width="64" height="64" alt="Azure Data Factory"> **Azure Data Factory** | Data movement and synchronization |
| <img src="./assets/aws/Snowball.svg" width="64" height="64" alt="Snowball"> **Snowball** | <img src="./assets/azure/Data-Box.svg" width="64" height="64" alt="Data Box"> **Data Box** | Offline data migration |
| <img src="./assets/aws/Backup.svg" width="64" height="64" alt="AWS Backup"> **AWS Backup** | <img src="./assets/azure/Recovery-Services-Vaults.svg" width="64" height="64" alt="Azure Backup"> **Azure Backup** | Centralized backup |
| <img src="./assets/aws/Elastic-Disaster-Recovery.svg" width="64" height="64" alt="Elastic Disaster Recovery"> **Elastic Disaster Recovery** | <img src="./assets/azure/Recovery-Services-Vaults.svg" width="64" height="64" alt="Site Recovery"> **Site Recovery** | Disaster recovery orchestration |
| <img src="./assets/aws/Transfer-Family.svg" width="64" height="64" alt="Transfer Family"> **Transfer Family** | <img src="./assets/azure/Storage-Accounts.svg" width="64" height="64" alt="Storage Mover"> **Storage Mover** | Managed file transfers |
| <img src="./assets/aws/Simple-Storage-Service.svg" width="64" height="64" alt="S3 Replication"> **S3 Replication** | <img src="./assets/azure/Blob-Block.svg" width="64" height="64" alt="Blob Redundancy"> **Blob Redundancy** | Cross-region data replication |
| <img src="./assets/aws/Backup.svg" width="64" height="64" alt="Backup Audit Manager"> **Backup Audit Manager** | <img src="./assets/azure/Policy.svg" width="64" height="64" alt="Policy"> **Policy** | Backup compliance checks |
| <img src="./assets/aws/FSx-for-Lustre.svg" width="64" height="64" alt="FSx for Lustre"> **FSx for Lustre** | <img src="./assets/azure/Azure-HCP-Cache.svg" width="64" height="64" alt="Azure HPC Cache"> **Azure HPC Cache** | High-performance file storage |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="networking-delivery-edge"></a>

## 🌐 Networking, Delivery & Edge

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/Route-53.svg" width="64" height="64" alt="Route 53"> **Route 53** | <img src="./assets/azure/DNS-Zones.svg" width="64" height="64" alt="Azure DNS"> **Azure DNS** | Managed DNS |
| <img src="./assets/aws/Elastic-Load-Balancing.svg" width="64" height="64" alt="Elastic Load Balancer"> **Elastic Load Balancer** | <img src="./assets/azure/Load-Balancers.svg" width="64" height="64" alt="Load Balancer"> **Load Balancer** | Traffic distribution |
| <img src="./assets/aws/CloudFront.svg" width="64" height="64" alt="CloudFront"> **CloudFront** | <img src="./assets/azure/CDN-Profiles.svg" width="64" height="64" alt="Azure CDN"> **Azure CDN** | Content delivery network |
| <img src="./assets/aws/API-Gateway.svg" width="64" height="64" alt="API Gateway"> **API Gateway** | <img src="./assets/azure/API-Management-Services.svg" width="64" height="64" alt="API Management"> **API Management** | API publishing and security |
| <img src="./assets/aws/Direct-Connect.svg" width="64" height="64" alt="Direct Connect"> **Direct Connect** | <img src="./assets/azure/ExpressRoute-Circuits.svg" width="64" height="64" alt="ExpressRoute"> **ExpressRoute** | Dedicated private connectivity |
| <img src="./assets/aws/Site-to-Site-VPN.svg" width="64" height="64" alt="VPN"> **VPN** | <img src="./assets/azure/Virtual-Network-Gateways.svg" width="64" height="64" alt="VPN Gateway"> **VPN Gateway** | Secure site-to-site connectivity |
| <img src="./assets/aws/Transit-Gateway.svg" width="64" height="64" alt="Transit Gateway"> **Transit Gateway** | <img src="./assets/azure/Virtual-WANs.svg" width="64" height="64" alt="Virtual WAN"> **Virtual WAN** | Network hub architecture |
| <img src="./assets/aws/PrivateLink.svg" width="64" height="64" alt="PrivateLink"> **PrivateLink** | <img src="./assets/azure/Private-Link.svg" width="64" height="64" alt="Private Link"> **Private Link** | Private service access |
| <img src="./assets/aws/Global-Accelerator.svg" width="64" height="64" alt="Global Accelerator"> **Global Accelerator** | <img src="./assets/azure/Front-Doors.svg" width="64" height="64" alt="Front Door"> **Front Door** | Global traffic optimization |
| <img src="./assets/aws/WAF.svg" width="64" height="64" alt="WAF"> **WAF** | <img src="./assets/azure/Web-Application-Firewall-Policies(WAF).svg" width="64" height="64" alt="Web Application Firewall"> **Web Application Firewall** | Web traffic protection |
| <img src="./assets/aws/Cloud-WAN.svg" width="64" height="64" alt="Cloud WAN"> **Cloud WAN** | <img src="./assets/azure/Virtual-WANs.svg" width="64" height="64" alt="Virtual WAN"> **Virtual WAN** | Global network management |
| <img src="./assets/aws/Network-Firewall.svg" width="64" height="64" alt="Network Firewall"> **Network Firewall** | <img src="./assets/azure/Firewalls.svg" width="64" height="64" alt="Azure Firewall"> **Azure Firewall** | Managed network firewall |
| <img src="./assets/aws/VPC-Lattice.svg" width="64" height="64" alt="VPC Lattice"> **VPC Lattice** | <img src="./assets/azure/Application-Gateways.svg" width="64" height="64" alt="Application Gateway"> **Application Gateway** | Service-to-service connectivity |
| <img src="./assets/aws/Route-53.svg" width="64" height="64" alt="Route 53 Resolver"> **Route 53 Resolver** | <img src="./assets/azure/DNS-Zones.svg" width="64" height="64" alt="DNS Private Resolver"> **DNS Private Resolver** | Hybrid DNS resolution |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="security-identity-governance"></a>

## 🔐 Security, Identity & Governance

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/Identity-and-Access-Management.svg" width="64" height="64" alt="IAM"> **IAM** | <img src="./assets/azure/Azure-Active-Directory.svg" width="64" height="64" alt="Entra ID"> **Entra ID** | Identity and access management |
| <img src="./assets/aws/IAM-Identity-Center.svg" width="64" height="64" alt="IAM Identity Center"> **IAM Identity Center** | <img src="./assets/azure/Azure-Active-Directory.svg" width="64" height="64" alt="Entra ID"> **Entra ID** | Single sign-on and access control |
| <img src="./assets/aws/Key-Management-Service.svg" width="64" height="64" alt="KMS"> **KMS** | <img src="./assets/azure/Key-Vaults.svg" width="64" height="64" alt="Key Vault"> **Key Vault** | Key and secret management |
| <img src="./assets/aws/Secrets-Manager.svg" width="64" height="64" alt="Secrets Manager"> **Secrets Manager** | <img src="./assets/azure/Keys.svg" width="64" height="64" alt="Key Vault Secrets"> **Key Vault Secrets** | Secret storage |
| <img src="./assets/aws/Certificate-Manager.svg" width="64" height="64" alt="Certificate Manager"> **Certificate Manager** | <img src="./assets/azure/Key-Vaults.svg" width="64" height="64" alt="Key Vault Certificates"> **Key Vault Certificates** | Certificate lifecycle management |
| <img src="./assets/aws/GuardDuty.svg" width="64" height="64" alt="GuardDuty"> **GuardDuty** | <img src="./assets/azure/Security-Center.svg" width="64" height="64" alt="Defender for Cloud"> **Defender for Cloud** | Threat detection |
| <img src="./assets/aws/Inspector.svg" width="64" height="64" alt="Inspector"> **Inspector** | <img src="./assets/azure/Security-Center.svg" width="64" height="64" alt="Defender for Cloud"> **Defender for Cloud** | Security posture and vulnerability scanning |
| <img src="./assets/aws/Shield.svg" width="64" height="64" alt="Shield"> **Shield** | <img src="./assets/azure/DDoS-Protection-Plans.svg" width="64" height="64" alt="DDoS Protection"> **DDoS Protection** | DDoS protection |
| <img src="./assets/aws/Macie.svg" width="64" height="64" alt="Macie"> **Macie** | <img src="./assets/azure/Azure-Data-Catalog.svg" width="64" height="64" alt="Purview"> **Purview** | Sensitive data discovery |
| <img src="./assets/aws/Security-Hub.svg" width="64" height="64" alt="Security Hub"> **Security Hub** | <img src="./assets/azure/Azure-Sentinel.svg" width="64" height="64" alt="Sentinel"> **Sentinel** | Central security posture |
| <img src="./assets/aws/Detective.svg" width="64" height="64" alt="Detective"> **Detective** | <img src="./assets/azure/Azure-Sentinel.svg" width="64" height="64" alt="Sentinel"> **Sentinel** | Security investigation |
| <img src="./assets/aws/Cognito.svg" width="64" height="64" alt="Cognito"> **Cognito** | <img src="./assets/azure/Azure-AD-B2C.svg" width="64" height="64" alt="Entra External ID"> **Entra External ID** | Customer identity and sign-in |
| <img src="./assets/aws/Verified-Permissions.svg" width="64" height="64" alt="Verified Permissions"> **Verified Permissions** | <img src="./assets/azure/API-Management-Services.svg" width="64" height="64" alt="API Management"> **API Management** | Fine-grained authorization |
| <img src="./assets/aws/Directory-Service.svg" width="64" height="64" alt="Directory Service"> **Directory Service** | <img src="./assets/azure/Azure-AD-Domain-Services.svg" width="64" height="64" alt="Domain Services"> **Domain Services** | Managed directory services |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="databases-caching"></a>

## 🗄️ Databases & Caching

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/RDS.svg" width="64" height="64" alt="RDS"> **RDS** | <img src="./assets/azure/SQL-Database.svg" width="64" height="64" alt="Azure SQL Database"> **Azure SQL Database** | Managed relational database |
| <img src="./assets/aws/Aurora.svg" width="64" height="64" alt="Aurora"> **Aurora** | <img src="./assets/azure/SQL-Database.svg" width="64" height="64" alt="Azure SQL Hyperscale"> **Azure SQL Hyperscale** | High-performance relational database |
| <img src="./assets/aws/DynamoDB.svg" width="64" height="64" alt="DynamoDB"> **DynamoDB** | <img src="./assets/azure/Azure-Cosmos-DB.svg" width="64" height="64" alt="Cosmos DB"> **Cosmos DB** | NoSQL distributed database |
| <img src="./assets/aws/Redshift.svg" width="64" height="64" alt="Redshift"> **Redshift** | <img src="./assets/azure/Azure-Synapse-Analytics.svg" width="64" height="64" alt="Synapse Analytics"> **Synapse Analytics** | Data warehouse |
| <img src="./assets/aws/Neptune.svg" width="64" height="64" alt="Neptune"> **Neptune** | <img src="./assets/azure/Azure-Cosmos-DB.svg" width="64" height="64" alt="Cosmos DB Gremlin"> **Cosmos DB Gremlin** | Graph database |
| <img src="./assets/aws/DocumentDB.svg" width="64" height="64" alt="DocumentDB"> **DocumentDB** | <img src="./assets/azure/Azure-Cosmos-DB.svg" width="64" height="64" alt="Cosmos DB Mongo"> **Cosmos DB Mongo** | Document database |
| <img src="./assets/aws/ElastiCache.svg" width="64" height="64" alt="ElastiCache"> **ElastiCache** | <img src="./assets/azure/Cache-Redis.svg" width="64" height="64" alt="Azure Cache for Redis"> **Azure Cache for Redis** | In-memory caching |
| <img src="./assets/aws/MemoryDB-for-Redis.svg" width="64" height="64" alt="MemoryDB"> **MemoryDB** | <img src="./assets/azure/Cache-Redis.svg" width="64" height="64" alt="Azure Cache for Redis"> **Azure Cache for Redis** | Durable in-memory database |
| <img src="./assets/aws/OpenSearch-Service.svg" width="64" height="64" alt="OpenSearch Service"> **OpenSearch Service** | <img src="./assets/azure/Search-Services.svg" width="64" height="64" alt="Azure AI Search"> **Azure AI Search** | Search and analytics |
| <img src="./assets/aws/Timestream.svg" width="64" height="64" alt="Timestream"> **Timestream** | <img src="./assets/azure/Azure-Data-Explorer-Clusters.svg" width="64" height="64" alt="Data Explorer"> **Data Explorer** | Time-series database |
| <img src="./assets/aws/Quantum-Ledger-Database.svg" width="64" height="64" alt="QLDB"> **QLDB** | <img src="./assets/azure/Key-Vaults.svg" width="64" height="64" alt="Confidential Ledger"> **Confidential Ledger** | Immutable ledger database |
| <img src="./assets/aws/Keyspaces.svg" width="64" height="64" alt="Keyspaces"> **Keyspaces** | <img src="./assets/azure/Azure-Cosmos-DB.svg" width="64" height="64" alt="Cosmos DB Cassandra"> **Cosmos DB Cassandra** | Wide-column database |
| <img src="./assets/aws/Database-Migration-Service.svg" width="64" height="64" alt="Database Migration Service"> **Database Migration Service** | <img src="./assets/azure/Azure-Database-Migration-Services.svg" width="64" height="64" alt="Database Migration Service"> **Database Migration Service** | Database migration |
| <img src="./assets/aws/RDS.svg" width="64" height="64" alt="RDS Proxy"> **RDS Proxy** | <img src="./assets/azure/Azure-Database-PostgreSQL-Server.svg" width="64" height="64" alt="Flexible Server"> **Flexible Server** | Connection pooling for databases |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="analytics-streaming-data"></a>

## 📊 Analytics, Streaming & Data

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/Kinesis-Data-Streams.svg" width="64" height="64" alt="Kinesis Data Streams"> **Kinesis Data Streams** | <img src="./assets/azure/Event-Hubs.svg" width="64" height="64" alt="Event Hubs"> **Event Hubs** | Streaming data ingestion |
| <img src="./assets/aws/Kinesis-Firehose.svg" width="64" height="64" alt="Kinesis Data Firehose"> **Kinesis Data Firehose** | <img src="./assets/azure/Event-Hubs.svg" width="64" height="64" alt="Event Hubs Capture"> **Event Hubs Capture** | Managed stream delivery |
| <img src="./assets/aws/Kinesis-Data-Analytics.svg" width="64" height="64" alt="Kinesis Data Analytics"> **Kinesis Data Analytics** | <img src="./assets/azure/Stream-Analytics-Jobs.svg" width="64" height="64" alt="Stream Analytics"> **Stream Analytics** | Real-time stream processing |
| <img src="./assets/aws/Glue.svg" width="64" height="64" alt="Glue"> **Glue** | <img src="./assets/azure/Data-Factory.svg" width="64" height="64" alt="Data Factory"> **Data Factory** | Data integration and ETL |
| <img src="./assets/aws/Athena.svg" width="64" height="64" alt="Athena"> **Athena** | <img src="./assets/azure/Azure-Synapse-Analytics.svg" width="64" height="64" alt="Synapse Serverless"> **Synapse Serverless** | Serverless SQL queries on data lake |
| <img src="./assets/aws/EMR.svg" width="64" height="64" alt="EMR"> **EMR** | <img src="./assets/azure/HD-Insight-Clusters.svg" width="64" height="64" alt="HDInsight"> **HDInsight** | Big data processing |
| <img src="./assets/aws/Managed-Streaming-for-Apache-Kafka.svg" width="64" height="64" alt="MSK"> **MSK** | <img src="./assets/azure/Event-Hubs.svg" width="64" height="64" alt="Event Hubs Kafka"> **Event Hubs Kafka** | Managed Kafka |
| <img src="./assets/aws/Lake-Formation.svg" width="64" height="64" alt="Lake Formation"> **Lake Formation** | <img src="./assets/azure/Data-Lake-Storage-Gen1.svg" width="64" height="64" alt="Data Lake"> **Data Lake** | Data lake governance |
| <img src="./assets/aws/QuickSight.svg" width="64" height="64" alt="QuickSight"> **QuickSight** | <img src="./assets/azure/Power.svg" width="64" height="64" alt="Power BI"> **Power BI** | Business intelligence |
| <img src="./assets/aws/DataZone.svg" width="64" height="64" alt="DataZone"> **DataZone** | <img src="./assets/azure/Azure-Data-Catalog.svg" width="64" height="64" alt="Purview"> **Purview** | Data catalog and governance |
| <img src="./assets/aws/OpenSearch-Service.svg" width="64" height="64" alt="OpenSearch Serverless"> **OpenSearch Serverless** | <img src="./assets/azure/Search-Services.svg" width="64" height="64" alt="Azure AI Search"> **Azure AI Search** | Serverless search analytics |
| <img src="./assets/aws/Data-Pipeline.svg" width="64" height="64" alt="Data Pipeline"> **Data Pipeline** | <img src="./assets/azure/Data-Factory.svg" width="64" height="64" alt="Data Factory"> **Data Factory** | Data orchestration |
| <img src="./assets/aws/Clean-Rooms.svg" width="64" height="64" alt="Clean Rooms"> **Clean Rooms** | <img src="./assets/azure/Clean-Rooms.svg" width="64" height="64" alt="Clean Room"> **Clean Room** | Collaborative analytics |
| <img src="./assets/aws/Glue-DataBrew.svg" width="64" height="64" alt="Glue DataBrew"> **Glue DataBrew** | <img src="./assets/azure/Data-Factory.svg" width="64" height="64" alt="Data Factory"> **Data Factory** | No-code data preparation |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="ai-ml-search"></a>

## 🤖 AI, ML & Search

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/SageMaker.svg" width="64" height="64" alt="SageMaker"> **SageMaker** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Azure Machine Learning"> **Azure Machine Learning** | Machine learning platform |
| <img src="./assets/aws/Bedrock.svg" width="64" height="64" alt="Bedrock"> **Bedrock** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Azure OpenAI"> **Azure OpenAI** | Foundation model platform |
| <img src="./assets/aws/Rekognition.svg" width="64" height="64" alt="Rekognition"> **Rekognition** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Computer Vision"> **Computer Vision** | Image and video analysis |
| <img src="./assets/aws/Comprehend.svg" width="64" height="64" alt="Comprehend"> **Comprehend** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Language Service"> **Language Service** | Natural language processing |
| <img src="./assets/aws/Lex.svg" width="64" height="64" alt="Lex"> **Lex** | <img src="./assets/azure/Bot-Services.svg" width="64" height="64" alt="Bot Service"> **Bot Service** | Conversational AI |
| <img src="./assets/aws/Polly.svg" width="64" height="64" alt="Polly"> **Polly** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Speech Service"> **Speech Service** | Text-to-speech |
| <img src="./assets/aws/Transcribe.svg" width="64" height="64" alt="Transcribe"> **Transcribe** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Speech-to-text"> **Speech-to-text** | Speech-to-text |
| <img src="./assets/aws/Translate.svg" width="64" height="64" alt="Translate"> **Translate** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Translator"> **Translator** | Machine translation |
| <img src="./assets/aws/Textract.svg" width="64" height="64" alt="Textract"> **Textract** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="AI Document Intelligence"> **AI Document Intelligence** | Document extraction |
| <img src="./assets/aws/Forecast.svg" width="64" height="64" alt="Forecast"> **Forecast** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Azure ML Forecasting"> **Azure ML Forecasting** | Time-series forecasting |
| <img src="./assets/aws/Personalize.svg" width="64" height="64" alt="Personalize"> **Personalize** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Personalizer"> **Personalizer** | Real-time recommendations |
| <img src="./assets/aws/Kendra.svg" width="64" height="64" alt="Kendra"> **Kendra** | <img src="./assets/azure/Search-Services.svg" width="64" height="64" alt="Azure AI Search"> **Azure AI Search** | Enterprise search |
| <img src="./assets/aws/Amazon-Q.svg" width="64" height="64" alt="Amazon Q"> **Amazon Q** | <img src="./assets/azure/Cognitive-Services.svg" width="64" height="64" alt="Copilot"> **Copilot** | AI assistant for work and development |
| <img src="./assets/aws/CodeWhisperer.svg" width="64" height="64" alt="CodeWhisperer"> **CodeWhisperer** | <img src="./assets/azure/GitHub-Copilot.svg" width="64" height="64" alt="GitHub Copilot"> **GitHub Copilot** | AI coding assistance |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="messaging-integration-automation"></a>

## 📩 Messaging, Integration & Automation

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/Simple-Queue-Service.svg" width="64" height="64" alt="SQS"> **SQS** | <img src="./assets/azure/Storage-Queue.svg" width="64" height="64" alt="Queue Storage"> **Queue Storage** | Message queue |
| <img src="./assets/aws/Simple-Notification-Service.svg" width="64" height="64" alt="SNS"> **SNS** | <img src="./assets/azure/Service-Bus.svg" width="64" height="64" alt="Service Bus Topics"> **Service Bus Topics** | Publish/subscribe messaging |
| <img src="./assets/aws/EventBridge.svg" width="64" height="64" alt="EventBridge"> **EventBridge** | <img src="./assets/azure/Event-Grid-Topics.svg" width="64" height="64" alt="Event Grid"> **Event Grid** | Event routing |
| <img src="./assets/aws/Step-Functions.svg" width="64" height="64" alt="Step Functions"> **Step Functions** | <img src="./assets/azure/Logic-Apps.svg" width="64" height="64" alt="Logic Apps"> **Logic Apps** | Workflow orchestration |
| <img src="./assets/aws/MQ.svg" width="64" height="64" alt="MQ"> **MQ** | <img src="./assets/azure/Service-Bus.svg" width="64" height="64" alt="Service Bus"> **Service Bus** | Managed message broker |
| <img src="./assets/aws/AppSync.svg" width="64" height="64" alt="AppSync"> **AppSync** | <img src="./assets/azure/API-Management-Services.svg" width="64" height="64" alt="GraphQL"> **GraphQL** | Managed GraphQL APIs |
| <img src="./assets/aws/Simple-Workflow-Service.svg" width="64" height="64" alt="SWF"> **SWF** | <img src="./assets/azure/Function-Apps.svg" width="64" height="64" alt="Durable Functions"> **Durable Functions** | Workflow coordination |
| <img src="./assets/aws/Simple-Email-Service.svg" width="64" height="64" alt="SES"> **SES** | <img src="./assets/azure/Communication-Services-Email.svg" width="64" height="64" alt="Communication Services Email"> **Communication Services Email** | Transactional email |
| <img src="./assets/aws/AppFlow.svg" width="64" height="64" alt="AppFlow"> **AppFlow** | <img src="./assets/azure/Logic-Apps.svg" width="64" height="64" alt="Logic Apps"> **Logic Apps** | SaaS data integration |
| <img src="./assets/aws/EventBridge.svg" width="64" height="64" alt="EventBridge Pipes"> **EventBridge Pipes** | <img src="./assets/azure/Event-Grid-Topics.svg" width="64" height="64" alt="Event Grid"> **Event Grid** | Point-to-point event routing |
| <img src="./assets/aws/Simple-Notification-Service.svg" width="64" height="64" alt="SNS Mobile Push"> **SNS Mobile Push** | <img src="./assets/azure/Notification-Hub-Namespaces.svg" width="64" height="64" alt="Notification Hubs"> **Notification Hubs** | Push notifications |
| <img src="./assets/aws/Chime-SDK.svg" width="64" height="64" alt="Amazon Chime SDK"> **Amazon Chime SDK** | <img src="./assets/azure/Communication-Services.svg" width="64" height="64" alt="Communication Services"> **Communication Services** | Real-time communication |
| <img src="./assets/aws/AWS-B2B-Data-Interchange.svg" width="64" height="64" alt="AWS B2B Data Interchange"> **AWS B2B Data Interchange** | <img src="./assets/azure/Logic-Apps.svg" width="64" height="64" alt="Logic Apps"> **Logic Apps** | B2B document exchange |
| <img src="./assets/aws/Managed-Blockchain.svg" width="64" height="64" alt="Managed Blockchain"> **Managed Blockchain** | <img src="./assets/azure/Key-Vaults.svg" width="64" height="64" alt="Confidential Ledger"> **Confidential Ledger** | Shared ledger workflows |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="observability-devops-migration"></a>

## 📈 Observability, DevOps & Migration

| AWS | Azure | Description |
|---|---|---|
| <img src="./assets/aws/CloudWatch.svg" width="64" height="64" alt="CloudWatch"> **CloudWatch** | <img src="./assets/azure/Monitor.svg" width="64" height="64" alt="Azure Monitor"> **Azure Monitor** | Metrics, logs, and alarms |
| <img src="./assets/aws/CloudTrail.svg" width="64" height="64" alt="CloudTrail"> **CloudTrail** | <img src="./assets/azure/Activity-Log.svg" width="64" height="64" alt="Activity Log"> **Activity Log** | Audit logging |
| <img src="./assets/aws/CloudFormation.svg" width="64" height="64" alt="CloudFormation"> **CloudFormation** | <img src="./assets/azure/Bicep.svg" width="64" height="64" alt="ARM / Bicep"> **ARM / Bicep** | Infrastructure as code |
| <img src="./assets/aws/Cloud-Development-Kit.svg" width="64" height="64" alt="CDK"> **CDK** | <img src="./assets/azure/Bicep.svg" width="64" height="64" alt="Bicep"> **Bicep** | Infrastructure as code in code |
| <img src="./assets/aws/CodeBuild.svg" width="64" height="64" alt="CodeBuild"> **CodeBuild** | <img src="./assets/azure/Azure-DevOps.svg" width="64" height="64" alt="Azure DevOps Pipelines"> **Azure DevOps Pipelines** | Build automation |
| <img src="./assets/aws/CodePipeline.svg" width="64" height="64" alt="CodePipeline"> **CodePipeline** | <img src="./assets/azure/Azure-DevOps.svg" width="64" height="64" alt="Azure Pipelines"> **Azure Pipelines** | CI/CD pipelines |
| <img src="./assets/aws/CodeDeploy.svg" width="64" height="64" alt="CodeDeploy"> **CodeDeploy** | <img src="./assets/azure/Azure-DevOps.svg" width="64" height="64" alt="Release Pipelines"> **Release Pipelines** | Deployment automation |
| <img src="./assets/aws/CodeArtifact.svg" width="64" height="64" alt="CodeArtifact"> **CodeArtifact** | <img src="./assets/azure/Azure-Artifacts.svg" width="64" height="64" alt="Azure Artifacts"> **Azure Artifacts** | Package repository |
| <img src="./assets/aws/CodeCommit.svg" width="64" height="64" alt="CodeCommit"> **CodeCommit** | <img src="./assets/azure/Azure-Repos.svg" width="64" height="64" alt="Azure Repos"> **Azure Repos** | Git repositories |
| <img src="./assets/aws/X-Ray.svg" width="64" height="64" alt="X-Ray"> **X-Ray** | <img src="./assets/azure/Application-Insights.svg" width="64" height="64" alt="Application Insights"> **Application Insights** | Distributed tracing |
| <img src="./assets/aws/Systems-Manager.svg" width="64" height="64" alt="Systems Manager"> **Systems Manager** | <img src="./assets/azure/Automation-Accounts.svg" width="64" height="64" alt="Azure Automation"> **Azure Automation** | Fleet and configuration management |
| <img src="./assets/aws/Config.svg" width="64" height="64" alt="Config"> **Config** | <img src="./assets/azure/Policy.svg" width="64" height="64" alt="Policy"> **Policy** | Compliance and governance |
| <img src="./assets/aws/Trusted-Advisor.svg" width="64" height="64" alt="Trusted Advisor"> **Trusted Advisor** | <img src="./assets/azure/Advisor.svg" width="64" height="64" alt="Advisor"> **Advisor** | Optimization recommendations |
| <img src="./assets/aws/Migration-Hub.svg" width="64" height="64" alt="Migration Hub"> **Migration Hub** | <img src="./assets/azure/Azure-Migrate.svg" width="64" height="64" alt="Azure Migrate"> **Azure Migrate** | Migration tracking |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

## 📚 Official Documentation Links

### AWS
- AWS Architecture Icons: https://aws.amazon.com/architecture/icons/
- AWS Documentation: https://docs.aws.amazon.com/
- AWS Architecture Center: https://aws.amazon.com/architecture/

### Azure
- Azure Icons: https://learn.microsoft.com/en-us/azure/architecture/icons/
- Azure Documentation: https://learn.microsoft.com/en-us/azure/
- Azure Architecture Center: https://learn.microsoft.com/en-us/azure/architecture/

## Notes

- Several mappings are **closest equivalents**, not strict 1:1 matches.
- Rename icon files if your local SVG filenames differ from the slugs used here.
- The official icon pages confirm that AWS and Azure provide downloadable architecture icon packs for diagrams and documentation.
