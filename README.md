# **Onboard Automator - Azure AD Identity Management & Resource Provisioning**

Project Overview:
This project automates the onboarding process of new employees by managing Azure AD identities, assigning roles/groups, provisioning Azure resources, and sending personalized welcome emails. The entire workflow is built using Azure Logic Apps and integrates with Azure AD, Azure Resource Manager, and Azure Email Service.

Features & Workflow:

Trigger Event:
The workflow is triggered by a new employee hire event, which can come from sources like a SharePoint list entry or an email in a designated mailbox.

Azure AD User Creation:
Upon trigger, the workflow automatically creates a new user in Azure Active Directory (Azure AD) based on the details provided (like name, department, job position).

Role and Group Assignment:
The system dynamically assigns the correct roles and groups to the new employee based on their department or position, ensuring proper access control.

Resource Provisioning:
The workflow leverages Azure Resource Manager (ARM) to provision necessary resources such as Virtual Machines (VMs) and access permissions tailored to the new hire's role.

Welcome Email:
A personalized welcome email is sent to the new employee, containing important details like login credentials and further instructions using Azure Email Service.

Monitoring and Review:
The process is monitored through the Logic Apps run history and Azure AD logs, ensuring smooth operation and allowing for quick identification and resolution of any issues.

Technologies Used:

Azure AD: For user management and identity control.
Azure Logic Apps: For automating workflows and integrating services.
Azure Resource Manager: For provisioning resources like VMs, storage, and permissions.
Azure Email Service: For sending emails to new employees.
SharePoint: To trigger workflows based on a new hire entry.
Outcome:
The automated onboarding process significantly reduces manual work, minimizing human error and improving efficiency. It ensures new hires are promptly set up with the necessary resources and access, accelerating their productivity.
