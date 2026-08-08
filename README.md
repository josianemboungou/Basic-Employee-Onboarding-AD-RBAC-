# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement

Before this project, the fictional company named "Northstar Medical Group" had its IT operations being run by a MSP because they did not have the leadership or money to do it themselves. Over time, the Active Directory became disorganized and difficult to manage. User accounts were created without consistent standards, access permissions were often incorrect or excessive, and departments lacked clear structure. Offboarding and onboarding were unreliable that former employees sometimes retained access for months, while new hires frequently waited days for basic access because no documented process existed. The lack of structure and documentation created a serious security and compliance risks.

## Solution Overview

The solution was to rebuild the Active Directory from scratch to create a secure and organized system. User accounts will follow clear standards; Organizational Units have been created to structure departments and RBAC is in place to enforce the least privilege access. All processes and incident resolutions are fully documented, so the environment remains understandable, auditable, and easy to operate.

## Video Walkthrough
[Add your video walkthrough link placeholder here]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Created OU with Security Groups
* Diagnosed and resolved a multi-cause access issue (Wrong OU, wrong group membership and wrong Role)
