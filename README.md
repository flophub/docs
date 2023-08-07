
### Welcome to our Marketplace!

 We're excited to have you as part of our platform. We created `flophub` to improve upon existing marketplaces in terms of Maintenance, Simplicty, Price, Security and Dependability

 To ensure a smooth onboarding process, please use this guide to familiarize yourself with our platform's features, guidelines, and best practices.

### Platform Overview:
This document provides a high-level overview of our GPU rental marketplace, explaining its purpose, benefits, and how it works. It covers key information about the two-sided nature of our platform, including the roles and responsibilities of both renters and GPU owners.

### Account Setup Guide:
This guide walks you through the process of setting up your account on our platform. It includes step-by-step instructions for creating an account, verifying your identity, and configuring your profile. It also explains the importance of providing accurate and detailed information to build trust within the community.

### Listing Your GPUs:
For GPU owners, this document outlines the process of listing your GPUs for rental on our platform. It covers creating a listing, specifying GPU details, setting availability and pricing, and establishing rental terms. Additionally, it provides guidance on optimizing your listings to attract potential renters.

### Renting a GPU:
For renters, this guide explains how to browse and search for available GPUs on our platform. It walks you through the process of selecting a GPU, reviewing listing details, checking availability, and initiating a rental request. It also covers best practices for communication with GPU owners.

### Rental Agreement and Terms:
To ensure a secure and transparent rental experience, we have established a comprehensive rental agreement and terms of service. This document outlines the rights and obligations of both renters and GPU owners, including payment terms, cancellation policies, liability, and dispute resolution processes.

### Safety and Security Guidelines:
Your safety and security are our top priorities. This document provides guidelines on maintaining a secure environment while using our platform. It covers topics such as account security, identity verification, safe communication practices, and data protection.

### Customer Support:
We are committed to providing excellent customer support. This section includes information on how to reach our support team for any questions, concerns, or issues you may encounter during your journey on our platform. It also explains our response time and support channels available to assist you.

### Community Guidelines:
We foster a supportive and inclusive community on our platform. These guidelines outline the expected code of conduct for all users, promoting respectful communication, fair practices, and responsible use of the marketplace. Familiarize yourself with these guidelines to contribute to a positive community experience.

### FAQ:
Our frequently asked questions document addresses common queries from both renters and GPU owners. It covers topics such as payments, insurance, technical specifications, platform features, and dispute resolution. Please review this document for quick answers to your questions.

##### What is FlopHub?
FlopHub is a platform for buying and selling computational power. It is a marketplace for people who need computational power and people who have computational power to sell.

##### How does FlopHub work?
Flophub uses multiple open source and internal tools to bring together hardware users and sellers leveraging a variant of Kubernetes as a backbone.

##### How do I buy computational power?
You can make a client account and book one or more machines instantly.

##### How do I sell computational power?
Simply run the script on your Ubuntu machine and your machine will become a node on our network within seconds! 

##### What if I have a Windows machine I want to rent out?
Coming soon: A method for adding a Windows-based node to our network.

##### What if I have a Mac with Apple M1/M2 that I want to rent out?
Apple Silicon has demonstrated its ability to perform heavy machine learning compute at an electrical cost of ~$.01/hour. We are actively working on a solution allowing a Mac based node at the same time apple is building ML libraries that work on Silicon. For the time being, most models are built for Nvidia.

##### How do I get paid?
You can see how much money you have earned in the dual dashboard. Payout will happen automatically as soon as possible as long as you have added your payment information.

##### How do I add credit to my account?
You do not need to add credit, however you will be asked for credit card information before you can open a session, similar to AWS.

##### How do I withdraw money from my account?
There is no account to withdrawl from -- payouts to hosts are paid automatically and an authorization is places on a clients credit cars at the time of booking. The client is billed for the usage upon closure of a session or at periodic intervals when pending use reaches a threshold.

##### How do I add a node to my account?
When you book an additional node, you will be billed per node at the time you add that node to your namespace. You will instantly have access to it in your local kubectl context accessible via terminal.

##### How do I remove a node from my account?
Simply remove it using our CLI or on the website by clicking 'remove node' in the dashboard.

##### How can I remove all existence of flophub from my machine?
```k3s-killall.sh && k3s-agent-uninstall.sh``

##### What about Quantum Computers?
While GPU processing is favorable today, we are poised to be the first open marketplace for Qubits.

We hope these onboarding documents provide you with a comprehensive understanding of our Two-Sided GPU Rental Marketplace. Should you have any further questions, feel free to reach out to our customer support team. We wish you a successful and rewarding experience as part of our community!

##### Terms of Service

Welcome to our GPU rental marketplace! Before you proceed to use our platform, please take a moment to review the following Terms of Service ("TOS") carefully. By accessing or using our services, you acknowledge that you have read, understood, and agree to comply with these terms. If you do not agree with any part of these terms, please refrain from using our platform.

Introduction
Our platform facilitates the rental of GPU resources between two sides: hosts (those who lease GPU machines) and users (those who rent GPU resources). The platform acts as an intermediary and does not own or operate any of the GPU machines.

Account Creation and Eligibility
2.1. To use our platform, users and hosts must create accounts. You agree to provide accurate and up-to-date information during registration and maintain the confidentiality of your account credentials.

2.2 We reserve the right to suspend or terminate any account found in violation of these terms or suspected of fraudulent activities.

GPU Rental Transactions
3.1. Our platform enables users to browse available GPU machines and hosts to list their GPU machines for rental.

3.2. Users may rent GPU resources on a short-term or long-term basis, as per the offerings provided by the hosts.

3.3. Once a rental transaction is initiated, users agree to pay the applicable fees as presented on the platform.

3.4. Hosts agree to provide the GPU resources as described in their listings and maintain the machines in good working condition.

3.5. The platform may charge service fees for facilitating the rental transactions, and such fees will be disclosed before the transaction is finalized.

Host Responsibilities
4.1. Hosts agree to provide accurate information about their GPU machines, including specifications and availability.

4.2. Hosts must ensure that their GPU machines are kept in good working condition, adequately cooled, and comply with any legal and regulatory requirements.

4.3. Hosts shall not engage in any activities that may harm or compromise the security and integrity of their GPU machines or the platform.

4.4. Hosts acknowledge that they are responsible for any taxes, fees, or other charges applicable to their rental income.

User Responsibilities
5.1. Users agree to use the rented GPU resources for legitimate purposes only, including but not limited to rendering, artificial intelligence, machine learning, and scientific calculations.

5.2. Users shall not use the rented GPU resources for any illegal, unethical, or malicious activities, including hacking, data breaches, or copyright infringement.

5.3. Users shall not attempt to exploit or gain unauthorized access to the platform or the host's GPU machines.

5.4. Users are responsible for the data and software they use on the rented GPU machines and must comply with all applicable licenses and intellectual property rights.

Liability and Disputes
6.1. The platform acts as an intermediary and is not liable for any damages or losses incurred during the GPU rental transactions.

6.2. Users and hosts agree to resolve any disputes arising from their transactions amongst themselves. However, the platform may provide dispute resolution assistance if required.

Modification of Terms
7.1. We reserve the right to update or modify these Terms of Service from time to time. Any changes will be communicated to users and hosts through their accounts or via email.

7.2. Continued use of the platform after the modifications signify acceptance of the updated Terms of Service.

Termination
8.1. Users and hosts may terminate their accounts at any time by following the instructions provided on the platform.

8.2. The platform may terminate or suspend any account that violates these Terms of Service or poses a threat to the platform's integrity.

Intellectual Property
9.1. The platform and all associated content, trademarks, and logos remain the property of the platform owners.

9.2. Users and hosts may not use, reproduce, or modify any platform content without explicit permission.

Governing Law and Jurisdiction
10.1. These Terms of Service shall be governed by the laws of the jurisdiction where the platform is registered.

10.2. Any disputes related to these terms shall be subject to the exclusive jurisdiction of the courts in that jurisdiction.

By using our platform, you agree to abide by these Terms of Service. If you have any questions or concerns, please contact us at the provided support email.

Thank you for being a part of our GPU rental marketplace community!

<!-- ## About
We created `flophub` to solve the following problems:
- Maintenance
- Ease of Use
- Price
- Security
- Dependability
<!-- ```bash
echo "Run flophub"
```
> Sample quote
?> Sample hint
!> Sample warning 
_sample grey and italic_
<!-- <div align="center">
    <a href="https://github.com/MichaelCurrin/docs/generate">
        <img src="https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge" 
            alt="Use this template"
            title="Create repo from template">
    </a>
</div> -->
<!-- <div align="center">
    <a href="https://github.com/MichaelCurrin/docs">
        <img src="https://img.shields.io/static/v1?label=MichaelCurrin&message=docs&color=blue&style=for-the-badge&logo=github" 
            alt="MichaelCurrin - docs"
            title="Go to template repo">
    </a>
</div> -->
[![Made with latest Docsify](https://img.shields.io/npm/v/docsify/latest?label=docsify)](https://docsify.js.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/MichaelCurrin/docs/blob/master/README#license)
<!-- [![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/docs.svg)](https://GitHub.com/flophub/docs) -->