# Secure AWS Infrastructure with Private Database Access

## Project Overview

This project demonstrates how to securely access AWS services without exposing sensitive resources to the Internet. We use an **EC2 instance** as a sensitive database hosted in a private subnet and leverage **AWS VPC Endpoints** to access AWS services like S3 and DynamoDB without requiring Internet access.

---

## Technologies Used
- **AWS Services**:
  - **VPC**: Virtual Private Cloud for network isolation.
  - **EC2**: Hosts the sensitive database in a private subnet.
  - **Bastion Host**: A public instance for accessing private instances.
  - **Security Groups**: Firewall rules for controlling traffic.
  - **Elastic IP**: Static IP address for installing AWS service on database.
  - **IAM Role**: Role-based access control for AWS resources.
  - **VPC Endpoint**: Private connection to AWS services without Internet access.

---

## Getting Started
To deploy this project, follow the step-by-step guide.
- **Wiki**: Detailed documentation and setup instructions: [Wiki](https://github.com/your-username/your-repo/wiki)


© 2025 Pyae Soe Kyaw | Made with ❤️ and ☕ in Meiktila, Myanmar
