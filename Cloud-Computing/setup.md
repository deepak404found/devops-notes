# Cloud Computing Setup & Commands ⚙️

[🔙 Back to Intro](./intro.md)

## Common Cloud Setup & Concepts 🛠️

Cloud computing involves various tools, services, and best practices that are essential for beginners and intermediate users. Below are some fundamental setups and key topics that are useful when working with cloud environments.

### **1. Cloud Accounts & Authentication**

Cloud platforms require users to create accounts and authenticate securely:

- Sign up for cloud services such as AWS, GCP, or Azure.
- Enable **Multi-Factor Authentication (MFA)** for enhanced security.
- Generate **API keys or service account credentials** for programmatic access.
- Use role-based access control (RBAC) to manage permissions securely.

### **2. Cloud CLI Tools**

To interact with cloud services more efficiently, install and configure CLI tools for automation and scripting:

- **AWS CLI**: Used to manage AWS resources via command line. [AWS CLI Installation Guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- **Google Cloud SDK (gcloud CLI)**: Manages GCP services with powerful automation features. [GCP SDK Installation Guide](https://cloud.google.com/sdk/docs/install)
- **Azure CLI**: Provides command-line access to Azure resources. [Azure CLI Installation Guide](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)

Configuration usually involves logging in and setting a default region or project:

```sh
aws configure  # Configure AWS CLI with credentials
gcloud auth login  # Authenticate with Google Cloud
az login  # Authenticate with Azure
```

### **3. Virtual Machines & Compute Services**

Compute services provide scalable processing power without needing physical infrastructure:

- **AWS EC2**: On-demand virtual machines with auto-scaling features.
- **GCP Compute Engine**: Customizable virtual machine instances.
- **Azure Virtual Machines**: Support for Linux and Windows VMs.
- Securely connect to VMs using **SSH (Linux/macOS)** or **RDP (Windows)**.

### **4. Storage Services**

Cloud platforms provide different types of storage for different use cases:

- **Object Storage**: AWS S3, GCP Cloud Storage, Azure Blob Storage.
- **Block Storage**: AWS EBS, GCP Persistent Disks, Azure Managed Disks.
- **File Storage**: AWS EFS, GCP Filestore, Azure Files.
- Use CLI commands or web consoles to store and retrieve data efficiently.

### **5. Networking & Security**

Networking in cloud computing ensures secure and optimized communication:

- **Virtual Private Cloud (VPC)**: Custom networking configurations for cloud environments.
- **Security Groups & Firewalls**: Restrict and control inbound/outbound traffic.
- **Load Balancers**: Distribute traffic across multiple instances.
- **Identity and Access Management (IAM)**: Role-based access controls for cloud resources.

### **6. Cloud Databases**

Managed cloud databases help store and manage data efficiently:

- **Relational Databases**: AWS RDS, GCP Cloud SQL, Azure SQL Database.
- **NoSQL Databases**: AWS DynamoDB, GCP Firestore, Azure CosmosDB.
- **Data Warehouses**: AWS Redshift, GCP BigQuery, Azure Synapse Analytics.

### **7. Serverless & Container Services**

Serverless computing allows execution of functions without managing infrastructure:

- **AWS Lambda, GCP Cloud Functions, Azure Functions**: Event-driven execution.
- **Container Services**: AWS ECS, GCP Cloud Run, Azure Container Apps.
- **Kubernetes Services**: AWS EKS, GCP GKE, Azure AKS for managing containerized workloads.

### **8. Monitoring & Logging**

Cloud platforms provide monitoring and logging services for application health and security:

- **AWS CloudWatch**: Logs, metrics, and alarms for AWS resources.
- **GCP Operations Suite (Stackdriver)**: Unified logging and monitoring.
- **Azure Monitor**: Tracks performance, logs, and alerts for resources.
- Use these tools to set up alerts for better system observability.

### **9. CI/CD & DevOps Tools**

Continuous Integration and Continuous Deployment (CI/CD) services enable automated workflows:

- **AWS CodePipeline, CodeBuild**: Automate builds and deployments.
- **GCP Cloud Build, Cloud Deploy**: Manage CI/CD pipelines for cloud applications.
- **Azure DevOps Pipelines**: End-to-end CI/CD automation.
- Integrate with GitHub, GitLab, or Bitbucket for version control.

### **10. Important Cloud Commands**

#### **AWS CLI Commands**

```sh
aws configure  # Set up AWS credentials
aws s3 ls      # List S3 buckets
aws ec2 describe-instances  # Show EC2 instances
```

For more commands, refer to the [AWS CLI Command Reference](https://docs.aws.amazon.com/cli/latest/reference/).

#### **GCP CLI Commands**

```sh
gcloud auth login  # Authenticate with Google Cloud
gcloud compute instances list  # List all VM instances
gcloud projects list  # Show available projects
```

For more commands, refer to the [GCP CLI Command Reference](https://cloud.google.com/sdk/gcloud/reference).

#### **Azure CLI Commands**

```sh
az login  # Authenticate with Azure
az vm list  # List all Virtual Machines
az storage account list  # Show storage accounts
```

For more commands, refer to the [Azure CLI Command Reference](https://docs.microsoft.com/en-us/cli/azure/reference-index?view=azure-cli-latest).

## Conclusion 🎯

Mastering these fundamental cloud computing topics allows users to efficiently deploy and manage cloud resources. Understanding key concepts such as security, automation, and scalability is crucial for cloud adoption. Always refer to official documentation for deeper learning and best practices.

[🔙 Back to Main README](../README.md)
