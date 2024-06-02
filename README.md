# Azure Honeynet Project - Real World Cyber Attacks
![Screenshot 2024-06-02 at 3 17 02 PM](https://github.com/mahin12/Honey-Net-Project/assets/27288616/922ae4e9-8daa-4b63-9fb0-42212833071e)


## Introduction

I’m excited to share my latest project, which is about setting up a honeynet in Azure to mimic real cyber attacks. This project shows off my skills in keeping Azure secure, handling incidents, and making the environment stronger.

## Objective

The main goal of this project was to create virtual machines in Azure that are easy to attack on purpose. This way, I could attract and study cyber attacks. Doing this helped me learn how attackers think and act, and it also proved that I can deal with security problems fast and well.

## Technologies, Regulations, and Azure Components Employed:

- Azure Virtual Network (VNet)
- Azure Network Security Group (NSG)
- Virtual Machines (2x Windows, 1x Linux)
- Log Analytics Workspace with Kusto Query Language (KQL) Queries
- Azure Key Vault for Secure Secrets Management
- Azure Storage Account for Data Storage
- Microsoft Sentinel for Security Information and Event Management (SIEM)
- Microsoft Defender for Cloud to Protect Cloud Resources
- Windows Remote Desktop for Remote Access
- Command Line Interface (CLI) for System Management
- PowerShell for Automation and Configuration Management
- NIST SP 800-53 Revision 5 for Security Controls
- NIST SP 800-61 Revision 2 for Incident Handling Guidance

## Methodology

#### Setting up the honeynet: 
I started by setting up several virtual machines in Azure that were easy to hack, to create a not-so-secure setup.

#### Watching and studying: 
I set up Azure to collect logs from different sources into one place for analysis. Then, I used Microsoft Sentinel to make visual maps of attacks, set off alerts, and note down any incidents from the data.

#### Measuring security: 
For a day, I kept an eye on how secure the environment was, noting down important security details. This gave me a starting point to see how things improved after I fixed the problems.

#### Handling incidents and making things secure: 
Once I took care of the incidents and found out where the weak spots were, I made the environment stronger by following the best security practices and advice specific to Azure.

#### Checking things after fixing them: 
After making everything secure, I watched the environment for another day to check the security details again. This helped me see how much things had improved compared to before.


## Methodology
### Architecture before implementing Hardening Measures and Security Controls
![Screenshot 2024-06-02 at 4 32 05 PM](https://github.com/mahin12/Honey-Net-Project/assets/27288616/7d8f13c5-628b-4274-949b-7ff2740811eb)

Prior to the implementation of hardening strategies and security protocols:

During the initial phase, addressed as "BEFORE," resources were deliberately made publicly accessible online. This configuration was designed to be vulnerable to lure cyber assailants and study their methods. The **Virtual Machines** were set up with completely open **Network Security Groups (NSGs)** and deactivated internal firewalls, permitting free entry from all origins. Furthermore, every other asset, including **storage accounts** and **databases**, was established with public-facing internet endpoints, foregoing the use of any **Private Endpoints** to enhance security.

### Architecture After implementing Hardening Measures and Security Controls
![Screenshot 2024-06-02 at 4 30 08 PM](https://github.com/mahin12/Honey-Net-Project/assets/27288616/7822892f-1964-4a45-ab49-a406ae9f28b7)
