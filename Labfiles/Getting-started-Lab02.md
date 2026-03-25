# Getting Started with Setup SSPR

### Overall Estimated Duration: 1 Hour

## Overview

This lab focuses on implementing Self-Service Password Reset (SSPR) in Microsoft Entra ID to strengthen identity security while making it easier for users to manage their own passwords without relying heavily on IT support. You will configure SSPR policies, set up multiple authentication methods, and enable password writeback to ensure smooth synchronization between cloud and on-premises environments. Using the Microsoft Entra Admin Center, you will build a secure and user-friendly password reset process that supports seamless account recovery, reliable identity verification, and policy-based access control, and then validate the end-user experience through the Microsoft My Account portal in a real-world enterprise scenario.

## Objectives

By completing this lab, you will gain practical experience in implementing and validating a secure SSPR solution:

- Configure Self-Service Password Reset (SSPR) for users in Microsoft Entra ID.
- Enable and customize authentication methods such as mobile phone, email, and security questions.
- Implement identity verification policies using multi-method authentication.
- Configure user registration settings for password reset readiness.
- Understand the role of password writeback in hybrid identity environments.
- Validate password reset functionality via the Microsoft My Account portal.
- Improve security posture by enforcing user-driven credential management with minimal administrative intervention.

## Architecture

- **Self-Service Password Reset (SSPR) Framework** integrates Microsoft Entra ID with on-premises identity systems to provide a secure and user-driven password recovery mechanism. Active Directory Domain Services (AD DS) continues to serve as the on-premises identity store, managing users and credentials, while SSPR enables users to reset their passwords independently without administrator intervention.

- **Microsoft Entra ID** acts as the **central identity control plane**, where SSPR policies are configured and enforced. It manages authentication methods such as mobile phone, email, and security questions to verify user identity during password reset. Password writeback, enabled through Microsoft Entra Connect, ensures that any password changes performed in the cloud are securely synchronized back to on-premises AD, maintaining consistency across environments.


## Explanation of Components

- **Microsoft Entra ID:** Microsoft Entra ID is a cloud-based identity and access management service that provides single sign-on (SSO), multi-factor authentication (MFA), and conditional access capabilities. It serves as the central identity provider for cloud and hybrid environments, enabling organizations to authenticate users, manage application access, and enforce security policies across the organization.

- **Self-Service Password Reset (SSPR):** SSPR is a feature within Entra ID that allows users to reset or unlock their accounts independently using pre-registered authentication methods. It reduces helpdesk workload, improves user experience, and ensures secure credential recovery through multi-factor validation.

- **Authentication Methods:** Authentication methods are used to verify a user’s identity before allowing a password reset. In this lab, methods such as mobile phone, email, and security questions are configured. These provide multi-layered verification, ensuring that only legitimate users can reset their credentials.

- **Microsoft Entra Admin Center:** Microsoft Entra Admin Center is the management portal where administrators configure SSPR settings, including enabling password reset, selecting authentication methods, and defining registration and policy controls.

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

    * **Temperory Access Pass**:  <inject key="AzureAdUserPassword"></inject>

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
