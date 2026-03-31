<div align="center">

# ☁️ AWS ↔ Azure Services Mapping Reference

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws) ![Azure](https://img.shields.io/badge/Azure-Cloud-blue?style=for-the-badge&logo=microsoftazure) ![Mappings](https://img.shields.io/badge/140-Service_Mappings-success?style=for-the-badge)


</div>

> Note: the icon columns below assume you have extracted the official AWS and Azure SVG icon packs locally into `./assets/aws/` and `./assets/azure/`.
> The official download pages are listed at the end.

## Table of Contents

- [🖥️ Compute & Serverless](#compute-serverless)
- [📦 Containers & App Platform](#containers-app-platform)
- [💾 Storage, Transfer & Backup](#storage-transfer-backup)
- [🌐 Networking, Delivery & Edge](#networking-delivery-edge)
- [🔐 Security, Identity & Governance](#security-identity-governance)
- [🗄️ Databases & Caching](#databases-caching)
- [📊 Analytics, Streaming & Data](#analytics-streaming-data)
- [🤖 AI, ML & Search](#ai-ml-search)
- [📩 Messaging, Integration & Automation](#messaging-integration-automation)
- [📈 Observability, DevOps & Migration](#observability-devops-migration)
- [📚 Official Documentation Links](#-official-documentation-links)

<a id="compute-serverless"></a>

## 🖥️ Compute & Serverless

| AWS | Azure | Description |
|---|---|---|
| ![EC2](./assets/aws/ec2.svg) **EC2** | ![Virtual Machines](./assets/azure/virtual-machines.svg) **Virtual Machines** | Virtual servers / cloud compute instances |
| ![EC2 Auto Scaling](./assets/aws/ec2-auto-scaling.svg) **EC2 Auto Scaling** | ![VM Scale Sets](./assets/azure/vm-scale-sets.svg) **VM Scale Sets** | Automatic scaling of compute capacity |
| ![Lambda](./assets/aws/lambda.svg) **Lambda** | ![Azure Functions](./assets/azure/azure-functions.svg) **Azure Functions** | Serverless event-driven compute |
| ![Elastic Beanstalk](./assets/aws/elastic-beanstalk.svg) **Elastic Beanstalk** | ![App Service](./assets/azure/app-service.svg) **App Service** | Managed application deployment platform |
| ![Lightsail](./assets/aws/lightsail.svg) **Lightsail** | ![App Service Plans](./assets/azure/app-service-plans.svg) **App Service Plans** | Simplified VPS-style hosting |
| ![Batch](./assets/aws/batch.svg) **Batch** | ![Azure Batch](./assets/azure/azure-batch.svg) **Azure Batch** | Batch processing jobs |
| ![Spot Instances](./assets/aws/spot-instances.svg) **Spot Instances** | ![Spot Virtual Machines](./assets/azure/spot-virtual-machines.svg) **Spot Virtual Machines** | Discounted interruptible compute |
| ![Image Builder](./assets/aws/image-builder.svg) **Image Builder** | ![Azure Image Builder](./assets/azure/azure-image-builder.svg) **Azure Image Builder** | Golden image build automation |
| ![App Runner](./assets/aws/app-runner.svg) **App Runner** | ![Container Apps](./assets/azure/container-apps.svg) **Container Apps** | Managed app deployment for containers |
| ![Outposts](./assets/aws/outposts.svg) **Outposts** | ![Azure Stack Hub](./assets/azure/azure-stack-hub.svg) **Azure Stack Hub** | Hybrid cloud infrastructure |
| ![Local Zones](./assets/aws/local-zones.svg) **Local Zones** | ![Edge Zones](./assets/azure/edge-zones.svg) **Edge Zones** | Low-latency local compute |
| ![Wavelength](./assets/aws/wavelength.svg) **Wavelength** | ![Edge Zones](./assets/azure/edge-zones.svg) **Edge Zones** | Ultra-low-latency edge compute |
| ![VMware Cloud on AWS](./assets/aws/vmware-cloud-on-aws.svg) **VMware Cloud on AWS** | ![Azure VMware Solution](./assets/azure/azure-vmware-solution.svg) **Azure VMware Solution** | Managed VMware platform |
| ![WorkSpaces](./assets/aws/workspaces.svg) **WorkSpaces** | ![Azure Virtual Desktop](./assets/azure/azure-virtual-desktop.svg) **Azure Virtual Desktop** | Managed virtual desktops |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="containers-app-platform"></a>

## 📦 Containers & App Platform

| AWS | Azure | Description |
|---|---|---|
| ![ECS](./assets/aws/ecs.svg) **ECS** | ![Container Apps](./assets/azure/container-apps.svg) **Container Apps** | Managed container orchestration |
| ![EKS](./assets/aws/eks.svg) **EKS** | ![AKS](./assets/azure/aks.svg) **AKS** | Managed Kubernetes |
| ![Fargate](./assets/aws/fargate.svg) **Fargate** | ![Container Apps Jobs](./assets/azure/container-apps-jobs.svg) **Container Apps Jobs** | Serverless containers |
| ![ECR](./assets/aws/ecr.svg) **ECR** | ![Container Registry](./assets/azure/container-registry.svg) **Container Registry** | Container image registry |
| ![ECS Anywhere](./assets/aws/ecs-anywhere.svg) **ECS Anywhere** | ![Azure Arc-enabled Kubernetes](./assets/azure/azure-arc-enabled-kubernetes.svg) **Azure Arc-enabled Kubernetes** | Run containers outside the cloud |
| ![EKS Anywhere](./assets/aws/eks-anywhere.svg) **EKS Anywhere** | ![Azure Arc-enabled Kubernetes](./assets/azure/azure-arc-enabled-kubernetes.svg) **Azure Arc-enabled Kubernetes** | Kubernetes anywhere management |
| ![AWS Proton](./assets/aws/aws-proton.svg) **AWS Proton** | ![Deployment Environments](./assets/azure/deployment-environments.svg) **Deployment Environments** | Template-based app delivery |
| ![App Mesh](./assets/aws/app-mesh.svg) **App Mesh** | ![Service Mesh](./assets/azure/service-mesh.svg) **Service Mesh** | Service-to-service networking |
| ![Cloud Map](./assets/aws/cloud-map.svg) **Cloud Map** | ![Private DNS](./assets/azure/private-dns.svg) **Private DNS** | Service discovery and naming |
| ![Elastic Container Service Anywhere](./assets/aws/elastic-container-service-anywhere.svg) **Elastic Container Service Anywhere** | ![Azure Arc-enabled Kubernetes](./assets/azure/azure-arc-enabled-kubernetes.svg) **Azure Arc-enabled Kubernetes** | Hybrid container management |
| ![Lightsail Containers](./assets/aws/lightsail-containers.svg) **Lightsail Containers** | ![Container Instances](./assets/azure/container-instances.svg) **Container Instances** | Simplified container hosting |
| ![Serverless Application Repository](./assets/aws/serverless-application-repository.svg) **Serverless Application Repository** | ![Azure Marketplace](./assets/azure/azure-marketplace.svg) **Azure Marketplace** | Reusable serverless app patterns |
| ![CodeCatalyst](./assets/aws/codecatalyst.svg) **CodeCatalyst** | ![Dev Center](./assets/azure/dev-center.svg) **Dev Center** | Integrated app delivery workspace |
| ![Elastic Beanstalk Extensions](./assets/aws/elastic-beanstalk-extensions.svg) **Elastic Beanstalk Extensions** | ![App Service](./assets/azure/app-service.svg) **App Service** | Platform configuration and deployment |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="storage-transfer-backup"></a>

## 💾 Storage, Transfer & Backup

| AWS | Azure | Description |
|---|---|---|
| ![S3](./assets/aws/s3.svg) **S3** | ![Blob Storage](./assets/azure/blob-storage.svg) **Blob Storage** | Object storage |
| ![EBS](./assets/aws/ebs.svg) **EBS** | ![Managed Disks](./assets/azure/managed-disks.svg) **Managed Disks** | Block storage for VMs |
| ![EFS](./assets/aws/efs.svg) **EFS** | ![Azure Files](./assets/azure/azure-files.svg) **Azure Files** | Managed shared file storage |
| ![FSx](./assets/aws/fsx.svg) **FSx** | ![Azure NetApp Files](./assets/azure/azure-netapp-files.svg) **Azure NetApp Files** | Enterprise file systems |
| ![S3 Glacier](./assets/aws/s3-glacier.svg) **S3 Glacier** | ![Archive Storage](./assets/azure/archive-storage.svg) **Archive Storage** | Long-term archival storage |
| ![Storage Gateway](./assets/aws/storage-gateway.svg) **Storage Gateway** | ![File Sync](./assets/azure/file-sync.svg) **File Sync** | Hybrid storage gateway |
| ![DataSync](./assets/aws/datasync.svg) **DataSync** | ![Azure Data Factory](./assets/azure/azure-data-factory.svg) **Azure Data Factory** | Data movement and synchronization |
| ![Snowball](./assets/aws/snowball.svg) **Snowball** | ![Data Box](./assets/azure/data-box.svg) **Data Box** | Offline data migration |
| ![AWS Backup](./assets/aws/aws-backup.svg) **AWS Backup** | ![Azure Backup](./assets/azure/azure-backup.svg) **Azure Backup** | Centralized backup |
| ![Elastic Disaster Recovery](./assets/aws/elastic-disaster-recovery.svg) **Elastic Disaster Recovery** | ![Site Recovery](./assets/azure/site-recovery.svg) **Site Recovery** | Disaster recovery orchestration |
| ![Transfer Family](./assets/aws/transfer-family.svg) **Transfer Family** | ![Storage Mover](./assets/azure/storage-mover.svg) **Storage Mover** | Managed file transfers |
| ![S3 Replication](./assets/aws/s3-replication.svg) **S3 Replication** | ![Blob Redundancy](./assets/azure/blob-redundancy.svg) **Blob Redundancy** | Cross-region data replication |
| ![Backup Audit Manager](./assets/aws/backup-audit-manager.svg) **Backup Audit Manager** | ![Policy](./assets/azure/policy.svg) **Policy** | Backup compliance checks |
| ![FSx for Lustre](./assets/aws/fsx-for-lustre.svg) **FSx for Lustre** | ![Azure HPC Cache](./assets/azure/azure-hpc-cache.svg) **Azure HPC Cache** | High-performance file storage |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="networking-delivery-edge"></a>

## 🌐 Networking, Delivery & Edge

| AWS | Azure | Description |
|---|---|---|
| ![Route 53](./assets/aws/route-53.svg) **Route 53** | ![Azure DNS](./assets/azure/azure-dns.svg) **Azure DNS** | Managed DNS |
| ![Elastic Load Balancer](./assets/aws/elastic-load-balancer.svg) **Elastic Load Balancer** | ![Load Balancer](./assets/azure/load-balancer.svg) **Load Balancer** | Traffic distribution |
| ![CloudFront](./assets/aws/cloudfront.svg) **CloudFront** | ![Azure CDN](./assets/azure/azure-cdn.svg) **Azure CDN** | Content delivery network |
| ![API Gateway](./assets/aws/api-gateway.svg) **API Gateway** | ![API Management](./assets/azure/api-management.svg) **API Management** | API publishing and security |
| ![Direct Connect](./assets/aws/direct-connect.svg) **Direct Connect** | ![ExpressRoute](./assets/azure/expressroute.svg) **ExpressRoute** | Dedicated private connectivity |
| ![VPN](./assets/aws/vpn.svg) **VPN** | ![VPN Gateway](./assets/azure/vpn-gateway.svg) **VPN Gateway** | Secure site-to-site connectivity |
| ![Transit Gateway](./assets/aws/transit-gateway.svg) **Transit Gateway** | ![Virtual WAN](./assets/azure/virtual-wan.svg) **Virtual WAN** | Network hub architecture |
| ![PrivateLink](./assets/aws/privatelink.svg) **PrivateLink** | ![Private Link](./assets/azure/private-link.svg) **Private Link** | Private service access |
| ![Global Accelerator](./assets/aws/global-accelerator.svg) **Global Accelerator** | ![Front Door](./assets/azure/front-door.svg) **Front Door** | Global traffic optimization |
| ![WAF](./assets/aws/waf.svg) **WAF** | ![Web Application Firewall](./assets/azure/web-application-firewall.svg) **Web Application Firewall** | Web traffic protection |
| ![Cloud WAN](./assets/aws/cloud-wan.svg) **Cloud WAN** | ![Virtual WAN](./assets/azure/virtual-wan.svg) **Virtual WAN** | Global network management |
| ![Network Firewall](./assets/aws/network-firewall.svg) **Network Firewall** | ![Azure Firewall](./assets/azure/azure-firewall.svg) **Azure Firewall** | Managed network firewall |
| ![VPC Lattice](./assets/aws/vpc-lattice.svg) **VPC Lattice** | ![Application Gateway](./assets/azure/application-gateway.svg) **Application Gateway** | Service-to-service connectivity |
| ![Route 53 Resolver](./assets/aws/route-53-resolver.svg) **Route 53 Resolver** | ![DNS Private Resolver](./assets/azure/dns-private-resolver.svg) **DNS Private Resolver** | Hybrid DNS resolution |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="security-identity-governance"></a>

## 🔐 Security, Identity & Governance

| AWS | Azure | Description |
|---|---|---|
| ![IAM](./assets/aws/iam.svg) **IAM** | ![Entra ID](./assets/azure/entra-id.svg) **Entra ID** | Identity and access management |
| ![IAM Identity Center](./assets/aws/iam-identity-center.svg) **IAM Identity Center** | ![Entra ID](./assets/azure/entra-id.svg) **Entra ID** | Single sign-on and access control |
| ![KMS](./assets/aws/kms.svg) **KMS** | ![Key Vault](./assets/azure/key-vault.svg) **Key Vault** | Key and secret management |
| ![Secrets Manager](./assets/aws/secrets-manager.svg) **Secrets Manager** | ![Key Vault Secrets](./assets/azure/key-vault-secrets.svg) **Key Vault Secrets** | Secret storage |
| ![Certificate Manager](./assets/aws/certificate-manager.svg) **Certificate Manager** | ![Key Vault Certificates](./assets/azure/key-vault-certificates.svg) **Key Vault Certificates** | Certificate lifecycle management |
| ![GuardDuty](./assets/aws/guardduty.svg) **GuardDuty** | ![Defender for Cloud](./assets/azure/defender-for-cloud.svg) **Defender for Cloud** | Threat detection |
| ![Inspector](./assets/aws/inspector.svg) **Inspector** | ![Defender for Cloud](./assets/azure/defender-for-cloud.svg) **Defender for Cloud** | Security posture and vulnerability scanning |
| ![Shield](./assets/aws/shield.svg) **Shield** | ![DDoS Protection](./assets/azure/ddos-protection.svg) **DDoS Protection** | DDoS protection |
| ![Macie](./assets/aws/macie.svg) **Macie** | ![Purview](./assets/azure/purview.svg) **Purview** | Sensitive data discovery |
| ![Security Hub](./assets/aws/security-hub.svg) **Security Hub** | ![Sentinel](./assets/azure/sentinel.svg) **Sentinel** | Central security posture |
| ![Detective](./assets/aws/detective.svg) **Detective** | ![Sentinel](./assets/azure/sentinel.svg) **Sentinel** | Security investigation |
| ![Cognito](./assets/aws/cognito.svg) **Cognito** | ![Entra External ID](./assets/azure/entra-external-id.svg) **Entra External ID** | Customer identity and sign-in |
| ![Verified Permissions](./assets/aws/verified-permissions.svg) **Verified Permissions** | ![API Management](./assets/azure/api-management.svg) **API Management** | Fine-grained authorization |
| ![Directory Service](./assets/aws/directory-service.svg) **Directory Service** | ![Domain Services](./assets/azure/domain-services.svg) **Domain Services** | Managed directory services |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="databases-caching"></a>

## 🗄️ Databases & Caching

| AWS | Azure | Description |
|---|---|---|
| ![RDS](./assets/aws/rds.svg) **RDS** | ![Azure SQL Database](./assets/azure/azure-sql-database.svg) **Azure SQL Database** | Managed relational database |
| ![Aurora](./assets/aws/aurora.svg) **Aurora** | ![Azure SQL Hyperscale](./assets/azure/azure-sql-hyperscale.svg) **Azure SQL Hyperscale** | High-performance relational database |
| ![DynamoDB](./assets/aws/dynamodb.svg) **DynamoDB** | ![Cosmos DB](./assets/azure/cosmos-db.svg) **Cosmos DB** | NoSQL distributed database |
| ![Redshift](./assets/aws/redshift.svg) **Redshift** | ![Synapse Analytics](./assets/azure/synapse-analytics.svg) **Synapse Analytics** | Data warehouse |
| ![Neptune](./assets/aws/neptune.svg) **Neptune** | ![Cosmos DB Gremlin](./assets/azure/cosmos-db-gremlin.svg) **Cosmos DB Gremlin** | Graph database |
| ![DocumentDB](./assets/aws/documentdb.svg) **DocumentDB** | ![Cosmos DB Mongo](./assets/azure/cosmos-db-mongo.svg) **Cosmos DB Mongo** | Document database |
| ![ElastiCache](./assets/aws/elasticache.svg) **ElastiCache** | ![Azure Cache for Redis](./assets/azure/azure-cache-for-redis.svg) **Azure Cache for Redis** | In-memory caching |
| ![MemoryDB](./assets/aws/memorydb.svg) **MemoryDB** | ![Azure Cache for Redis](./assets/azure/azure-cache-for-redis.svg) **Azure Cache for Redis** | Durable in-memory database |
| ![OpenSearch Service](./assets/aws/opensearch-service.svg) **OpenSearch Service** | ![Azure AI Search](./assets/azure/azure-ai-search.svg) **Azure AI Search** | Search and analytics |
| ![Timestream](./assets/aws/timestream.svg) **Timestream** | ![Data Explorer](./assets/azure/data-explorer.svg) **Data Explorer** | Time-series database |
| ![QLDB](./assets/aws/qldb.svg) **QLDB** | ![Confidential Ledger](./assets/azure/confidential-ledger.svg) **Confidential Ledger** | Immutable ledger database |
| ![Keyspaces](./assets/aws/keyspaces.svg) **Keyspaces** | ![Cosmos DB Cassandra](./assets/azure/cosmos-db-cassandra.svg) **Cosmos DB Cassandra** | Wide-column database |
| ![Database Migration Service](./assets/aws/database-migration-service.svg) **Database Migration Service** | ![Database Migration Service](./assets/azure/database-migration-service.svg) **Database Migration Service** | Database migration |
| ![RDS Proxy](./assets/aws/rds-proxy.svg) **RDS Proxy** | ![Flexible Server](./assets/azure/flexible-server.svg) **Flexible Server** | Connection pooling for databases |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="analytics-streaming-data"></a>

## 📊 Analytics, Streaming & Data

| AWS | Azure | Description |
|---|---|---|
| ![Kinesis Data Streams](./assets/aws/kinesis-data-streams.svg) **Kinesis Data Streams** | ![Event Hubs](./assets/azure/event-hubs.svg) **Event Hubs** | Streaming data ingestion |
| ![Kinesis Data Firehose](./assets/aws/kinesis-data-firehose.svg) **Kinesis Data Firehose** | ![Event Hubs Capture](./assets/azure/event-hubs-capture.svg) **Event Hubs Capture** | Managed stream delivery |
| ![Kinesis Data Analytics](./assets/aws/kinesis-data-analytics.svg) **Kinesis Data Analytics** | ![Stream Analytics](./assets/azure/stream-analytics.svg) **Stream Analytics** | Real-time stream processing |
| ![Glue](./assets/aws/glue.svg) **Glue** | ![Data Factory](./assets/azure/data-factory.svg) **Data Factory** | Data integration and ETL |
| ![Athena](./assets/aws/athena.svg) **Athena** | ![Synapse Serverless](./assets/azure/synapse-serverless.svg) **Synapse Serverless** | Serverless SQL queries on data lake |
| ![EMR](./assets/aws/emr.svg) **EMR** | ![HDInsight](./assets/azure/hdinsight.svg) **HDInsight** | Big data processing |
| ![MSK](./assets/aws/msk.svg) **MSK** | ![Event Hubs Kafka](./assets/azure/event-hubs-kafka.svg) **Event Hubs Kafka** | Managed Kafka |
| ![Lake Formation](./assets/aws/lake-formation.svg) **Lake Formation** | ![Data Lake](./assets/azure/data-lake.svg) **Data Lake** | Data lake governance |
| ![QuickSight](./assets/aws/quicksight.svg) **QuickSight** | ![Power BI](./assets/azure/power-bi.svg) **Power BI** | Business intelligence |
| ![DataZone](./assets/aws/datazone.svg) **DataZone** | ![Purview](./assets/azure/purview.svg) **Purview** | Data catalog and governance |
| ![OpenSearch Serverless](./assets/aws/opensearch-serverless.svg) **OpenSearch Serverless** | ![Azure AI Search](./assets/azure/azure-ai-search.svg) **Azure AI Search** | Serverless search analytics |
| ![Data Pipeline](./assets/aws/data-pipeline.svg) **Data Pipeline** | ![Data Factory](./assets/azure/data-factory.svg) **Data Factory** | Data orchestration |
| ![Clean Rooms](./assets/aws/clean-rooms.svg) **Clean Rooms** | ![Clean Room](./assets/azure/clean-room.svg) **Clean Room** | Collaborative analytics |
| ![Glue DataBrew](./assets/aws/glue-databrew.svg) **Glue DataBrew** | ![Data Factory](./assets/azure/data-factory.svg) **Data Factory** | No-code data preparation |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="ai-ml-search"></a>

## 🤖 AI, ML & Search

| AWS | Azure | Description |
|---|---|---|
| ![SageMaker](./assets/aws/sagemaker.svg) **SageMaker** | ![Azure Machine Learning](./assets/azure/azure-machine-learning.svg) **Azure Machine Learning** | Machine learning platform |
| ![Bedrock](./assets/aws/bedrock.svg) **Bedrock** | ![Azure OpenAI](./assets/azure/azure-openai.svg) **Azure OpenAI** | Foundation model platform |
| ![Rekognition](./assets/aws/rekognition.svg) **Rekognition** | ![Computer Vision](./assets/azure/computer-vision.svg) **Computer Vision** | Image and video analysis |
| ![Comprehend](./assets/aws/comprehend.svg) **Comprehend** | ![Language Service](./assets/azure/language-service.svg) **Language Service** | Natural language processing |
| ![Lex](./assets/aws/lex.svg) **Lex** | ![Bot Service](./assets/azure/bot-service.svg) **Bot Service** | Conversational AI |
| ![Polly](./assets/aws/polly.svg) **Polly** | ![Speech Service](./assets/azure/speech-service.svg) **Speech Service** | Text-to-speech |
| ![Transcribe](./assets/aws/transcribe.svg) **Transcribe** | ![Speech-to-text](./assets/azure/speech-to-text.svg) **Speech-to-text** | Speech-to-text |
| ![Translate](./assets/aws/translate.svg) **Translate** | ![Translator](./assets/azure/translator.svg) **Translator** | Machine translation |
| ![Textract](./assets/aws/textract.svg) **Textract** | ![AI Document Intelligence](./assets/azure/ai-document-intelligence.svg) **AI Document Intelligence** | Document extraction |
| ![Forecast](./assets/aws/forecast.svg) **Forecast** | ![Azure ML Forecasting](./assets/azure/azure-ml-forecasting.svg) **Azure ML Forecasting** | Time-series forecasting |
| ![Personalize](./assets/aws/personalize.svg) **Personalize** | ![Personalizer](./assets/azure/personalizer.svg) **Personalizer** | Real-time recommendations |
| ![Kendra](./assets/aws/kendra.svg) **Kendra** | ![Azure AI Search](./assets/azure/azure-ai-search.svg) **Azure AI Search** | Enterprise search |
| ![Amazon Q](./assets/aws/amazon-q.svg) **Amazon Q** | ![Copilot](./assets/azure/copilot.svg) **Copilot** | AI assistant for work and development |
| ![CodeWhisperer](./assets/aws/codewhisperer.svg) **CodeWhisperer** | ![GitHub Copilot](./assets/azure/github-copilot.svg) **GitHub Copilot** | AI coding assistance |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="messaging-integration-automation"></a>

## 📩 Messaging, Integration & Automation

| AWS | Azure | Description |
|---|---|---|
| ![SQS](./assets/aws/sqs.svg) **SQS** | ![Queue Storage](./assets/azure/queue-storage.svg) **Queue Storage** | Message queue |
| ![SNS](./assets/aws/sns.svg) **SNS** | ![Service Bus Topics](./assets/azure/service-bus-topics.svg) **Service Bus Topics** | Publish/subscribe messaging |
| ![EventBridge](./assets/aws/eventbridge.svg) **EventBridge** | ![Event Grid](./assets/azure/event-grid.svg) **Event Grid** | Event routing |
| ![Step Functions](./assets/aws/step-functions.svg) **Step Functions** | ![Logic Apps](./assets/azure/logic-apps.svg) **Logic Apps** | Workflow orchestration |
| ![MQ](./assets/aws/mq.svg) **MQ** | ![Service Bus](./assets/azure/service-bus.svg) **Service Bus** | Managed message broker |
| ![AppSync](./assets/aws/appsync.svg) **AppSync** | ![GraphQL](./assets/azure/graphql.svg) **GraphQL** | Managed GraphQL APIs |
| ![SWF](./assets/aws/swf.svg) **SWF** | ![Durable Functions](./assets/azure/durable-functions.svg) **Durable Functions** | Workflow coordination |
| ![SES](./assets/aws/ses.svg) **SES** | ![Communication Services Email](./assets/azure/communication-services-email.svg) **Communication Services Email** | Transactional email |
| ![AppFlow](./assets/aws/appflow.svg) **AppFlow** | ![Logic Apps](./assets/azure/logic-apps.svg) **Logic Apps** | SaaS data integration |
| ![EventBridge Pipes](./assets/aws/eventbridge-pipes.svg) **EventBridge Pipes** | ![Event Grid](./assets/azure/event-grid.svg) **Event Grid** | Point-to-point event routing |
| ![SNS Mobile Push](./assets/aws/sns-mobile-push.svg) **SNS Mobile Push** | ![Notification Hubs](./assets/azure/notification-hubs.svg) **Notification Hubs** | Push notifications |
| ![Amazon Chime SDK](./assets/aws/amazon-chime-sdk.svg) **Amazon Chime SDK** | ![Communication Services](./assets/azure/communication-services.svg) **Communication Services** | Real-time communication |
| ![AWS B2B Data Interchange](./assets/aws/aws-b2b-data-interchange.svg) **AWS B2B Data Interchange** | ![Logic Apps](./assets/azure/logic-apps.svg) **Logic Apps** | B2B document exchange |
| ![Managed Blockchain](./assets/aws/managed-blockchain.svg) **Managed Blockchain** | ![Confidential Ledger](./assets/azure/confidential-ledger.svg) **Confidential Ledger** | Shared ledger workflows |

[⬆ Back to top](#-aws--azure-services-mapping-reference)

<a id="observability-devops-migration"></a>

## 📈 Observability, DevOps & Migration

| AWS | Azure | Description |
|---|---|---|
| ![CloudWatch](./assets/aws/cloudwatch.svg) **CloudWatch** | ![Azure Monitor](./assets/azure/azure-monitor.svg) **Azure Monitor** | Metrics, logs, and alarms |
| ![CloudTrail](./assets/aws/cloudtrail.svg) **CloudTrail** | ![Activity Log](./assets/azure/activity-log.svg) **Activity Log** | Audit logging |
| ![CloudFormation](./assets/aws/cloudformation.svg) **CloudFormation** | ![ARM / Bicep](./assets/azure/arm-bicep.svg) **ARM / Bicep** | Infrastructure as code |
| ![CDK](./assets/aws/cdk.svg) **CDK** | ![Bicep](./assets/azure/bicep.svg) **Bicep** | Infrastructure as code in code |
| ![CodeBuild](./assets/aws/codebuild.svg) **CodeBuild** | ![Azure DevOps Pipelines](./assets/azure/azure-devops-pipelines.svg) **Azure DevOps Pipelines** | Build automation |
| ![CodePipeline](./assets/aws/codepipeline.svg) **CodePipeline** | ![Azure Pipelines](./assets/azure/azure-pipelines.svg) **Azure Pipelines** | CI/CD pipelines |
| ![CodeDeploy](./assets/aws/codedeploy.svg) **CodeDeploy** | ![Release Pipelines](./assets/azure/release-pipelines.svg) **Release Pipelines** | Deployment automation |
| ![CodeArtifact](./assets/aws/codeartifact.svg) **CodeArtifact** | ![Azure Artifacts](./assets/azure/azure-artifacts.svg) **Azure Artifacts** | Package repository |
| ![CodeCommit](./assets/aws/codecommit.svg) **CodeCommit** | ![Azure Repos](./assets/azure/azure-repos.svg) **Azure Repos** | Git repositories |
| ![X-Ray](./assets/aws/x-ray.svg) **X-Ray** | ![Application Insights](./assets/azure/application-insights.svg) **Application Insights** | Distributed tracing |
| ![Systems Manager](./assets/aws/systems-manager.svg) **Systems Manager** | ![Azure Automation](./assets/azure/azure-automation.svg) **Azure Automation** | Fleet and configuration management |
| ![Config](./assets/aws/config.svg) **Config** | ![Policy](./assets/azure/policy.svg) **Policy** | Compliance and governance |
| ![Trusted Advisor](./assets/aws/trusted-advisor.svg) **Trusted Advisor** | ![Advisor](./assets/azure/advisor.svg) **Advisor** | Optimization recommendations |
| ![Migration Hub](./assets/aws/migration-hub.svg) **Migration Hub** | ![Azure Migrate](./assets/azure/azure-migrate.svg) **Azure Migrate** | Migration tracking |

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
