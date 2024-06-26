| Domain | Item | Request Type | Requested Item Description |
|--------|------|--------------|----------------------------|
| Governance | Cloud Security Configuration Requirements | Policy/Procedures/Standards | Documentation on key cloud security configuration requirements for AWS and Azure, including their appropriateness and effectiveness. |
| Governance | Risk Assessment Methodology | Document | Details on the risk-based approach used for prioritizing cloud security controls. |
| Governance | Nimbus Tool Details | Document | Information on the specific version of Nimbus being used (open-source or paid) and its posture management functionality. |
| Accounts & Services | AWS Account Management Post-Creation | Document/Evidence | Documentation and evidence of actions taken after AWS account creation to ensure proper security and governance. |
| Accounts & Services | Azure Tenant Creation Process | Document/Evidence | Detailed documentation on the Azure tenant creation process, including security considerations and configurations. |
| Accounts & Services | Service Catalog Certification Process | Policy/Procedures/Standards | Documentation on the AWS Service Catalog certification process, including required approvals and stakeholders. |
| Virtual Machines | AMI Build and Release Process | Document/Evidence | Detailed documentation on the AMI build process using GitLab CI/CD and Packer, including release cadence and scheduling. |
| Virtual Machines | AMI Testing and Validation | Document/Evidence | Information on custom tests, Tenable vulnerability scanning, and manual security team reviews for AMIs. |
| Virtual Machines | AMI Deployment and Lifecycle Management | Document/Evidence | Documentation on AMI deployment to non-prod and prod environments, tagging processes, and automated updates in ECS. |
| Virtual Machines | Azure Image Management Process | Document/Evidence | Detailed information on the Azure image management process, including any handoffs with on-premises virtual machines. |
| Virtual Machines | Legacy OS Migration Plans | Document | Documentation on plans and timelines for migrating systems running unsupported operating systems (e.g., Windows Server 2012, SQL Server 2008). |
| Logging and Monitoring | Splunk and Cribble Usage | Document/Evidence | Information on how Splunk and Cribble are used for log aggregation, analysis, and alerting in the AWS environment. |
| Logging and Monitoring | VPC Flow Logs Management | Document/Evidence | Details on the capture, storage, and analysis of VPC flow logs, including plans to move them to Cribble. |
| Logging and Monitoring | Cloud Ops Alerting Process | Document/Evidence | Documentation on how the Cloud Ops team manages and responds to Splunk alerts, including the verification process for change control IDs. |
| Logging and Monitoring | Azure Monitoring Modernization | Document | Information on the ongoing efforts to modernize Azure monitoring and align it with CIS benchmarks. |
| Logging and Monitoring | Canary Testing for Event Flows | Document/Evidence | Plans or documentation for implementing periodic canary testing to ensure event flows and alerting mechanisms are functioning correctly. |
| Security and Compliance | AWS Config Usage | Document/Evidence | Information on how AWS Config is used (or plans to use it) to track and demonstrate compliance with AMI management policies. |


| Domain | Item | Request Type | Requested Item Description | Reasoning and Justification |
|--------|------|--------------|----------------------------|------------------------------|
| Data Analytics | PowerBI Security Dashboard Configurations | Configuration/Evidence | Provide configurations and screenshots of any existing PowerBI security dashboards for AWS and Azure environments. Include details on data sources, refresh rates, and user access controls. | To assess the current state of security data visualization and identify areas for improvement in real-time monitoring and reporting. |
| Data Analytics | Cloud Resource Inventory Analytics | Configuration/Evidence | Share any PowerBI reports or datasets used for tracking cloud resource inventory, including trends in resource creation, modification, and deletion across AWS and Azure. | To evaluate the effectiveness of asset management processes and identify potential unauthorized or misconfigured resources. |
| Data Analytics | Security Event Correlation Models | Configuration/Evidence | Provide documentation on any PowerBI data models or DAX queries used for correlating security events across multiple cloud services and on-premises systems. | To assess the sophistication of security event analysis and the ability to detect complex attack patterns across hybrid environments. |
| Data Analytics | Compliance Posture Tracking | Configuration/Evidence | Share PowerBI reports used for tracking compliance posture, including mappings to specific compliance requirements (e.g., CIS benchmarks, NIST frameworks) for both AWS and Azure. | To evaluate the effectiveness of compliance monitoring and reporting, and identify areas of non-compliance or control gaps. |
| Data Analytics | Identity and Access Analytics | Configuration/Evidence | Provide PowerBI reports or datasets used for analyzing IAM usage patterns, privileged access, and anomalies in both AWS and Azure environments. | To assess the effectiveness of identity governance and identify potential security risks related to over-privileged accounts or unusual access patterns. |
| Data Analytics | Cost vs. Security Optimization Analytics | Configuration/Evidence | Share any PowerBI models or reports used to correlate security posture with cloud spending, identifying areas where security improvements can lead to cost optimization. | To evaluate the balance between security investments and cost efficiency, and identify opportunities for optimization. |
| Data Analytics | Threat Intelligence Integration | Configuration/Evidence | Provide documentation on how threat intelligence feeds are integrated into PowerBI dashboards or reports for proactive threat detection in cloud environments. | To assess the organization's capability to leverage external threat intelligence for enhancing cloud security posture. |
| Data Analytics | Automated Control Testing Analytics | Configuration/Evidence | Share PowerBI reports or datasets used for automating security control testing, including coverage metrics and trend analysis of control effectiveness. | To evaluate the maturity of continuous control monitoring processes and identify areas for automation in security testing. |
| Data Analytics | Multi-Cloud Security Comparison | Configuration/Evidence | Provide any PowerBI dashboards or reports used for comparing security postures across AWS and Azure environments, including unified security scoring models. | To assess the consistency of security controls across different cloud platforms and identify platform-specific security gaps. |
| Data Analytics | Security Data Lineage and Quality | Configuration/Evidence | Share documentation on PowerBI data lineage for security datasets, including data quality metrics and any data cleansing processes applied to cloud security logs. | To evaluate the reliability and completeness of security data used for analytics and decision-making. |
| Data Analytics | PowerBI Embedding in Security Processes | Document/Evidence | Provide documentation on how PowerBI reports or dashboards are embedded into daily security operations, including any integrations with SIEM tools or ticketing systems. | To assess the level of integration of data analytics in security workflows and identify opportunities for improving operational efficiency. |
| Data Analytics | Custom Security KPI Tracking | Configuration/Evidence | Share PowerBI reports used for tracking custom security KPIs specific to the organization's cloud environments, including definitions and calculation methods. | To evaluate the alignment of security metrics with organizational goals and the effectiveness of performance tracking. |

| Domain | Item | Request Type | Requested Item Description | Reasoning and Justification |
|--------|------|--------------|----------------------------|------------------------------|
| Governance | IAM Policies for Cross-Account Access | Configuration/Evidence | Provide IAM policies and roles used for cross-account access in AWS, including trust relationships and permission boundaries. | To assess the principle of least privilege in cross-account access and identify potential security risks in resource sharing. |
| Governance | Azure RBAC Custom Role Definitions | Configuration/Evidence | Export of custom RBAC role definitions in Azure, including scope and assigned permissions. | To evaluate the granularity of access control in Azure and identify any over-permissive roles. |
| Accounts & Services | AWS Organizations Service Control Policies (SCPs) | Configuration/Evidence | Provide all SCPs applied at the organization and OU levels, including denied actions and conditions. | To understand how AWS accounts are restricted at the organization level and identify any gaps in baseline security controls. |
| Accounts & Services | Azure Management Group Hierarchy | Configuration/Evidence | Detailed structure of Azure Management Groups, including inherited policies and restrictions. | To assess the governance structure in Azure and how policies are inherited across the organization. |
| Accounts & Services | Terraform/CloudFormation Templates for Account Provisioning | Code/Configuration | Provide infrastructure-as-code templates used for provisioning new AWS accounts or Azure subscriptions. | To evaluate the consistency and security of the automated account creation process. |
| Virtual Machines | AMI Hardening Scripts | Code/Configuration | Provide scripts or configuration management code (e.g., Ansible playbooks, PowerShell DSC) used for hardening AMIs. | To assess the thoroughness of the hardening process and identify any missing security configurations. |
| Virtual Machines | Azure VM Image Definitions | Configuration/Evidence | Export of Azure Shared Image Gallery definitions, including image versions, regions, and replication status. | To understand the management and distribution of VM images in Azure and assess version control practices. |
| Virtual Machines | EC2 Instance Metadata Service (IMDS) Configuration | Configuration/Evidence | Provide the configuration for EC2 Instance Metadata Service, including the version (v1 or v2) and any IP restrictions. | To assess the protection against SSRF attacks and unauthorized access to instance metadata. |
| Virtual Machines | Azure VM Managed Identities Usage | Configuration/Evidence | List of Azure VMs using managed identities, including the assigned roles and scopes. | To evaluate the use of identity-based access for VMs and reduce reliance on credential-based authentication. |
| Networking | AWS Transit Gateway Configurations | Configuration/Evidence | Provide Transit Gateway configurations, including route tables, attachments, and any associated Network ACLs. | To assess the centralized network architecture and identify potential misconfigurations in cross-VPC routing. |
| Networking | Azure Virtual WAN Setup | Configuration/Evidence | Details of Azure Virtual WAN configuration, including hubs, connected virtual networks, and routing tables. | To evaluate the global transit network setup in Azure and identify any security gaps in inter-region connectivity. |
| Networking | AWS VPC Endpoint Policies | Configuration/Evidence | Provide VPC endpoint policies for all interface and gateway endpoints in use. | To assess the security of private connectivity to AWS services and identify any overly permissive policies. |
| Networking | Azure Private Link Configurations | Configuration/Evidence | List of Azure Private Link services and endpoints in use, including associated network security groups. | To evaluate the security of private connectivity to Azure PaaS services and identify any exposed endpoints. |
| Logging and Monitoring | AWS CloudTrail Log File Integrity Validation | Configuration/Evidence | Provide configuration details for CloudTrail log file integrity validation, including the SNS topic for notifications. | To ensure the integrity of CloudTrail logs and detect any tampering attempts. |
| Logging and Monitoring | Azure Activity Log Retention and Archiving | Configuration/Evidence | Details of Azure Activity Log retention settings and any long-term archiving solutions in place. | To assess compliance with log retention requirements and the ability to perform historical security analysis. |
| Logging and Monitoring | AWS Config Rules and Remediation Actions | Configuration/Evidence | List of all AWS Config rules in place, including custom rules and associated auto-remediation actions. | To evaluate the continuous compliance monitoring capabilities and automated remediation of misconfigurations. |
| Logging and Monitoring | Azure Policy Definitions and Assignments | Configuration/Evidence | Export of custom Azure Policy definitions and their assignments across the organization. | To assess the enforcement of security standards and identify any gaps in policy coverage. |
| Security and Compliance | AWS GuardDuty Findings and Integrations | Configuration/Evidence | Provide recent GuardDuty findings, configured threat intelligence feeds, and any integrations with SIEM or ticketing systems. | To evaluate the effectiveness of threat detection in AWS and the incident response process. |
| Security and Compliance | Azure Security Center Secure Score | Configuration/Evidence | Current Azure Security Center secure score, including a breakdown of recommendations and their implementation status. | To assess the overall security posture in Azure and identify priority areas for improvement. |
| Security and Compliance | AWS KMS Key Policies and Rotation Settings | Configuration/Evidence | Provide KMS key policies, including key administrators, key users, and key rotation settings for customer-managed keys. | To evaluate the management of encryption keys and ensure proper access controls and rotation practices. |
| Security and Compliance | Azure Key Vault Access Policies and Key Rotation | Configuration/Evidence | List of Key Vault access policies and key rotation settings for secrets and certificates. | To assess the security of secret management in Azure and ensure proper access controls and rotation practices. |
