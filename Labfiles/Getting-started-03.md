# Getting Started with Implementing and Using Privileged Identity Management
 
### Estimated Duration: 30 Minutes
 
## Overview
 
This lab walks you through configuring Privileged Identity Management (PIM) in Microsoft Entra ID to govern privileged role access. You will assign roles to users with controlled, time-bound settings and manage existing assignments — reinforcing secure, least-privilege access practices within your organization.
 
## Objectives
 
Upon completing this lab, you will be able to:
 
- Assign the Global Administrator role to multiple users using Microsoft Entra Privileged Identity Management.
- Configure time-bound, eligible role assignments with defined start and end dates.
- Review and manage existing Entra role assignments from the Assignments dashboard.
- Transition eligible role assignments to active status with a justified duration.
- Remove users from eligible role assignments when access is no longer required.
 
## Architecture
 
This lab operates within the Microsoft Entra ID ecosystem. Privileged Identity Management (PIM) acts as the governance layer, enabling administrators to control how and when privileged roles are accessed. Role assignments can be configured as either **eligible** — requiring users to activate access on demand — or **active**, granting immediate permissions for a defined period. Assignment policies ensure all access events are justified, time-bound, and auditable.
 
## Explanation of Components
 
- **Microsoft Entra ID:** A cloud-based identity and access management service that provides SSO, MFA, and conditional access. It serves as the central identity platform for managing users and enforcing access policies throughout this lab.
 
- **Privileged Identity Management (PIM):** A Microsoft Entra feature that enables just-in-time, approval-based access to privileged roles. It reduces the risk associated with standing privileged access by making elevated permissions temporary and reviewable.
 
- **Eligible Assignments:** A role assignment type where users must complete a required action — such as MFA or providing a justification — before the role becomes active. This ensures privileged access is never persistent by default.
 
- **Active Assignments:** A role assignment type that grants immediate, continuous access to a role's permissions. These are time-bound and used when on-demand activation is not practical.
 
- **Role Assignment Duration:** A governance control within PIM that enforces expiry on role assignments. Defining start and end dates ensures access is automatically revoked when no longer needed, without manual intervention

## Accessing Your Lab Environment

Once you're ready to dive in, your virtual machine and lab guide will be right at your fingertips within your web browser.

![](../media/intropupd.png)

### Virtual Machine & Lab Guide
 
Your virtual machine is your workhorse throughout the workshop. The lab guide is your roadmap to success.

## Exploring Your Lab Resources
 
To get a better understanding of your lab resources and credentials, navigate to the **Environment** tab.

![](../media/introp1upd.png)

## Utilizing the Split Window Feature
 
For convenience, you can open the lab guide in a separate window by selecting the **Split Window** button from the Top right corner.

![](../media/introp2upd.png)
 
## Managing Your Virtual Machine
 
Feel free to start, stop, or restart your virtual machine as needed from the **Resources** tab. Your experience is in your hands!

![](../media/resourcesupd.png)

## Let's Get Started with Azure Portal

1. On your Lab virtual machine, click on the **Azure Portal** icon to sign in to the Azure.

    ![](../media/signin0-0903.png)    

1. On the Sign in blade, you will see a login screen, in which enter the following email/username and password and then click on Sign in.

    * Azure Username/Email:  <inject key="AzureAdUserEmail"></inject>

        ![](../media/signin1-0903.png)

    * **Temporary Access Pass**:  <inject key="AzureAdUserPassword"></inject>

        **Note**: Refer to the **Environment** tab for any other lab credentials/details.

        ![](../media/signin2-0903.png)
  
1. If you see the pop-up **Stay Signed in?** click **Yes**.

    ![](../media/g3.jpg)

1. If you see the pop-up **You have free Azure Advisor recommendations!** close the window to continue the lab. 

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.

    ![](../media/g4.jpg)

## Support Contact

The CloudLabs support team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:

- Email Support: cloudlabs-support@spektrasystems.com
- Live Chat Support: https://cloudlabs.ai/labs-support

Click **Next** from the bottom right corner to embark on your Lab journey!

![](../media/up4.png)

### Happy Learning!!
