# Microsoft 365: Primetech Solutions — A Hands-On Admin Lab

## Overview

This repository documents the end-to-end setup and configuration of a secure, modern Microsoft 365 environment for a fictional company, **Primetech Solutions**. Tasked with onboarding 24 new hires, I acted as the sole Cloud Administrator, building the tenant from the ground up using a **Microsoft 365 Business Standard trial** and an **Intune** license.

This repository tells the story of that project. It's a step-by-step record of how I planned, built, and secured the tenant, demonstrating a real-world approach to deploying Microsoft 365. The labs cover everything from initial user setup to advanced security and automated device deployment with Autopilot.

## Key Accomplishments

- **Identity Foundation:** Established a full identity lifecycle process, including bulk user creation, group-based management, and delegated administration using role-assignable groups.
- **Security Posture Hardening:** Increased the **Microsoft Secure Score from 37.06% to 82.61%** by implementing Conditional Access, MFA, and comprehensive email threat policies (anti-phishing, anti-malware, anti-spam).
- **Modern Device Management:** Successfully configured and executed a **zero-touch Windows Autopilot deployment**, allowing a new device to be provisioned automatically with all company policies and applications.
- **Application Deployment at Scale:** Packaged and deployed critical third-party Win32 applications (Google Chrome, 7-Zip, Wireshark) and the Microsoft 365 Apps suite via Intune.

## Key Skills Demonstrated

- **Identity & Access Management:** Bulk user onboarding (CSV), Microsoft Entra group management (Security, M365), Role-Based Access Control (RBAC) with role-assignable groups, Self-Service Password Reset (SSPR), Conditional Access, and MFA enforcement.
- **Licensing Administration:** Automated license assignment using **Group-Based Licensing**.
- **Collaboration Setup:** Secure configuration of Teams (Private, Shared, and Standard channels), SharePoint (Communication Sites, Team Sites), and OneDrive, including external sharing policies and B2B collaboration.
- **Security & Compliance:** Microsoft Secure Score analysis and improvement, email threat management (anti-phishing, anti-spam, anti-malware), and data recovery (version history, recycle bin).
- **Device Management (Intune):**
  - **Enrollment:** MDM automatic enrollment configuration and troubleshooting.
  - **Policy Management:** Creation of device **Compliance Policies** and **Configuration Profiles** (Settings Catalog).
  - **Windows Autopilot:** Hardware hash capture, deployment profile creation, and zero-touch device provisioning.
  - **Application Deployment:** Deployment of Microsoft 365 Apps and packaging/deployment of **Win32 apps** (`.intunewin`).
- **Reporting & Monitoring:** Documenting and tracking key metrics and security improvements.
- **Troubleshooting:** Diagnosing and resolving real-world issues, including Intune enrollment failures and application detection rule conflicts.

## Repository Structure

Each folder represents a core chapter of the project. Inside, markdown files document specific tasks in the format:
**Scenario > Actions I Took > Outcome > Key Learning**

## Table of Contents

1. **[Identity & Access Management](./01_Identity_and_Access_Management/identity-setup.md)**
    - User Creation, Group Structuring, RBAC, SSPR, and Conditional Access.

2. **[User & Licensing Administration](./02_User_and_Licensing_Administration/user-license-management.md)**
    - Group-Based Licensing and Shared Mailbox Configuration.

3. **[Collaboration Tools](./03_Collaboration_Tools/teams-sharepoint-onedrive.md)**
    - Secure Baselines, Teams & Channels, SharePoint Sites, and File Recovery.

4. **[Security & Compliance](./04_Security_and_Compliance/security-hardening-and-compliance.md)**
    - Microsoft Secure Score Improvement and Email Threat Management.

5. **Device Management (Intune)**
    - **[Part 1: Setup and Enrollment](./05_Device_Management_Intune/01-intune-setup-and-enrollment.md)**
    - **[Part 2: Compliance and Configuration Policies](./05_Device_Management_Intune/02-compliance-and-configuration-policies.md)**
    - **[Part 3: Windows Autopilot Setup](./05_Device_Management_Intune/03-windows-autopilot-setup.md)**
    - **[Part 4: Application Deployment](./05_Device_Management_Intune/04-application-deployment.md)**

## Scenario Disclaimer

All companies, departments, and names ( ex **Primetech Solutions**, **Alex Carter**) are fictional and used solely for scenario context. This project was executed using a **30-day Microsoft 365 Business Standard trial** environment; all tasks included here are feasible within that plan.
