

---

# ☁️ AWS ↔ Azure Services Mapping Reference

### *Comprehensive Cloud Services Comparison (100+ services)*

> Documentation sources: **AWS Official Docs** + **Microsoft Azure Official Docs**
> Format: `AWS | AZURE | DESCRIPTION`

---

# 🖥️ Compute Services

| AWS                      | AZURE                      | DESCRIPTION                               |
| ------------------------ | -------------------------- | ----------------------------------------- |
| 🖥️ **EC2**              | 🖥️ **Virtual Machines**   | Virtual servers / cloud compute instances |
| 📈 **EC2 Auto Scaling**  | 📈 **VM Scale Sets**       | Automatic scaling based on workload       |
| ⚡ **Lambda**             | ⚡ **Azure Functions**      | Serverless event-driven compute           |
| 📦 **Elastic Beanstalk** | 🌐 **App Service**         | Managed application deployment platform   |
| 🐳 **ECS**               | 🐳 **Container Instances** | Managed container runtime                 |
| ☸️ **EKS**               | ☸️ **AKS**                 | Managed Kubernetes service                |
| 🚀 **Fargate**           | 🚀 **Container Apps**      | Serverless containers                     |
| 💡 **Lightsail**         | 💡 **App Service / VMs**   | Simplified VPS hosting                    |
| 🏭 **Batch**             | 🏭 **Azure Batch**         | Batch processing jobs                     |
| 🌍 **Outposts**          | 🌍 **Azure Stack**         | Hybrid cloud infrastructure               |
| 📡 **Local Zones**       | 📡 **Azure Edge Zones**    | Low-latency local compute                 |
| 📶 **Wavelength**        | 📶 **Edge Zones**          | 5G edge cloud services                    |

---

# 💾 Storage Services

| AWS                    | AZURE                     | DESCRIPTION                        |
| ---------------------- | ------------------------- | ---------------------------------- |
| 🪣 **S3**              | 🪣 **Blob Storage**       | Object storage service             |
| 📁 **EFS**             | 📁 **Azure Files**        | Managed shared file storage        |
| 💽 **EBS**             | 💽 **Managed Disks**      | Block storage for VMs              |
| 🧊 **S3 Glacier**      | 🧊 **Archive Storage**    | Cold / archival storage            |
| 🚚 **Storage Gateway** | 🚚 **Azure File Sync**    | Hybrid storage gateway             |
| 📦 **FSx**             | 📦 **Azure NetApp Files** | Enterprise file systems            |
| 🔄 **DataSync**        | 🔄 **Azure Data Factory** | Data transfer and synchronization  |
| 🗃️ **Snowball**       | 🗃️ **Data Box**          | Offline large-scale data migration |

---

# 🌐 Networking & CDN

| AWS                          | AZURE                            | DESCRIPTION                      |
| ---------------------------- | -------------------------------- | -------------------------------- |
| 🌍 **Route 53**              | 🌍 **Azure DNS**                 | Managed DNS service              |
| 🔀 **Elastic Load Balancer** | 🔀 **Load Balancer**             | Traffic distribution             |
| 🌐 **CloudFront**            | 🌐 **Azure CDN**                 | Global content delivery          |
| 🔗 **Direct Connect**        | 🔗 **ExpressRoute**              | Dedicated private connectivity   |
| 🛡️ **WAF**                  | 🛡️ **Web Application Firewall** | Web traffic protection           |
| 🚪 **API Gateway**           | 🚪 **API Management**            | API publishing and security      |
| 🚦 **Transit Gateway**       | 🚦 **Virtual WAN**               | Network hub architecture         |
| 🔒 **PrivateLink**           | 🔒 **Private Link**              | Private service access           |
| 🌎 **Global Accelerator**    | 🌎 **Front Door**                | Global routing optimization      |
| 🔐 **VPN**                   | 🔐 **VPN Gateway**               | Secure site-to-site connectivity |

---

# 🔐 Security & Identity

| AWS                        | AZURE                         | DESCRIPTION                     |
| -------------------------- | ----------------------------- | ------------------------------- |
| 👤 **IAM**                 | 👤 **Entra ID**               | Identity and access management  |
| 🔑 **KMS**                 | 🔑 **Key Vault**              | Key and secrets management      |
| 🕵️ **GuardDuty**          | 🕵️ **Defender for Cloud**    | Threat detection                |
| 📜 **Certificate Manager** | 📜 **Key Vault Certificates** | SSL certificate management      |
| 🔐 **Secrets Manager**     | 🔐 **Key Vault Secrets**      | Secrets storage                 |
| 🧠 **Macie**               | 🧠 **Purview**                | Sensitive data discovery        |
| 🛡️ **Shield**             | 🛡️ **DDoS Protection**       | Anti-DDoS protection            |
| 🏢 **Directory Service**   | 🏢 **Domain Services**        | Managed Active Directory        |
| 🔍 **Inspector**           | 🔍 **Security Center**        | Vulnerability scanning          |
| 📊 **Security Hub**        | 📊 **Microsoft Sentinel**     | Centralized security monitoring |

---

# 🗄️ Databases

| AWS               | AZURE                                 | DESCRIPTION                    |
| ----------------- | ------------------------------------- | ------------------------------ |
| 🐘 **RDS**        | 🐘 **Azure SQL / MySQL / PostgreSQL** | Managed relational DB          |
| ⚡ **Aurora**      | ⚡ **Azure SQL Hyperscale**            | High-performance relational DB |
| 🌌 **DynamoDB**   | 🌌 **Cosmos DB**                      | NoSQL distributed database     |
| 📈 **Redshift**   | 📈 **Synapse Analytics**              | Data warehouse                 |
| 🔗 **Neptune**    | 🔗 **Cosmos DB Gremlin**              | Graph database                 |
| 📄 **DocumentDB** | 📄 **Cosmos DB Mongo API**            | Document DB                    |
| ⏱️ **Timestream** | ⏱️ **Data Explorer**                  | Time-series database           |
| 📚 **Keyspaces**  | 📚 **Cosmos Cassandra API**           | Wide-column database           |
| 📒 **QLDB**       | 📒 **Confidential Ledger**            | Immutable ledger DB            |

---

# 📊 Monitoring & DevOps

| AWS                    | AZURE                       | DESCRIPTION                  |
| ---------------------- | --------------------------- | ---------------------------- |
| 📈 **CloudWatch**      | 📈 **Azure Monitor**        | Metrics and logs             |
| 🕓 **CloudTrail**      | 🕓 **Activity Log**         | Audit logging                |
| 🧩 **CloudFormation**  | 🧩 **ARM / Bicep**          | Infrastructure as Code       |
| 🚀 **CodePipeline**    | 🚀 **Azure Pipelines**      | CI/CD pipeline               |
| 🧪 **CodeBuild**       | 🧪 **Pipelines Build**      | Build automation             |
| 📦 **CodeArtifact**    | 📦 **Azure Artifacts**      | Package repository           |
| 📝 **CodeCommit**      | 📝 **Azure Repos**          | Git repositories             |
| 🔍 **X-Ray**           | 🔍 **Application Insights** | Tracing / APM                |
| 📋 **Config**          | 📋 **Policy**               | Governance and compliance    |
| 💡 **Trusted Advisor** | 💡 **Advisor**              | Optimization recommendations |

---

# 📩 Messaging & Integration

| AWS                   | AZURE                     | DESCRIPTION            |
| --------------------- | ------------------------- | ---------------------- |
| 📬 **SQS**            | 📬 **Queue Storage**      | Message queue          |
| 📢 **SNS**            | 📢 **Service Bus Topics** | Publish / subscribe    |
| 🔄 **Step Functions** | 🔄 **Logic Apps**         | Workflow orchestration |
| 📡 **EventBridge**    | 📡 **Event Grid**         | Event routing          |
| 🔌 **MQ**             | 🔌 **Service Bus**        | Message broker         |
| 🌐 **AppSync**        | 🌐 **GraphQL API**        | GraphQL managed APIs   |

---

# 🤖 AI / Analytics / Big Data

| AWS                 | AZURE                       | DESCRIPTION               |
| ------------------- | --------------------------- | ------------------------- |
| 🧠 **SageMaker**    | 🧠 **Azure ML**             | Machine learning platform |
| 📊 **EMR**          | 📊 **HDInsight / Synapse**  | Big data analytics        |
| 🔥 **Kinesis**      | 🔥 **Event Hubs**           | Streaming data            |
| 🧪 **Glue**         | 🧪 **Data Factory**         | ETL service               |
| 🕵️ **Athena**      | 🕵️ **Synapse Serverless**  | Query data lake           |
| 📉 **QuickSight**   | 📉 **Power BI**             | Business intelligence     |
| 🎯 **Forecast**     | 🎯 **Azure ML Forecasting** | Predictive analytics      |
| 💬 **Lex**          | 💬 **Bot Service**          | Conversational AI         |
| 👁️ **Rekognition** | 👁️ **Computer Vision**     | Image analysis            |
| 🗣️ **Polly**       | 🗣️ **Speech Service**      | Text-to-speech            |

---

# 🌐 IoT & Edge

| AWS                   | AZURE                   | DESCRIPTION             |
| --------------------- | ----------------------- | ----------------------- |
| 📡 **IoT Core**       | 📡 **IoT Hub**          | Device communication    |
| 🏭 **IoT Greengrass** | 🏭 **IoT Edge**         | Edge computing          |
| 🏗️ **IoT SiteWise**  | 🏗️ **Digital Twins**   | Industrial IoT modeling |
| 📱 **FreeRTOS**       | 📱 **Azure RTOS**       | Embedded OS             |
| 📈 **IoT Analytics**  | 📈 **Stream Analytics** | IoT data analytics      |

---

# 🚚 Migration & Backup

| AWS                              | AZURE                              | DESCRIPTION              |
| -------------------------------- | ---------------------------------- | ------------------------ |
| 🚚 **Migration Hub**             | 🚚 **Azure Migrate**               | Migration tracking       |
| 🖥️ **Server Migration Service** | 🖥️ **Azure Migrate**              | Server migration         |
| 🗄️ **DMS**                      | 🗄️ **Database Migration Service** | DB migration             |
| 💾 **Backup**                    | 💾 **Azure Backup**                | Backup service           |
| 🏢 **Organizations**             | 🏢 **Management Groups**           | Multi-account governance |
| 🏛️ **Control Tower**            | 🏛️ **Landing Zones**              | Governance framework     |

---
