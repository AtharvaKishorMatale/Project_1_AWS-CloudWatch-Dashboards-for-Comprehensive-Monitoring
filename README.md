# Project_1_AWS-CloudWatch-Dashboards-for-Comprehensive-Monitoring

## Project Title
**AWS CloudWatch Dashboards for Billing, Logs, Network Performance, and Security & Compliance Monitoring**

## Objective
This project aims to develop a practical and cost-effective monitoring solution on AWS using CloudWatch. The goal is to build four interactive dashboards covering:

- **Billing**
- **Application Logs**
- **Network Activity**
- **Security & Compliance**

## Technology Stack
- **Monitoring:** Amazon CloudWatch, CloudWatch Agent, CloudWatch Logs Insights
- **Security:** AWS GuardDuty, AWS Config, AWS CloudTrail
- **Infrastructure:** Amazon EC2, Amazon S3, Application Load Balancer
- **Access Control:** AWS IAM

## Key Features & Implementation Highlights

### Billing & Cost Monitoring
- Real-time tracking of AWS spending
- Widgets for estimated charges and cost breakdown by service
- Enables proactive budget management

### Logs Monitoring
- CloudWatch Agent installed on EC2 to push system logs
- Real-time log analysis using CloudWatch Logs
- Detection of issues such as failed login attempts

### Network Performance Monitoring
- Dashboard uses ALB metrics
- Visualizes network performance for app delivery

### Security & Compliance Monitoring
- Integration with GuardDuty for threat detection
- AWS Config for compliance tracking
- Centralized visibility for security posture
