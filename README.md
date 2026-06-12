# Active Directory Security Hardening Lab (Windows Server 2025)
This project is a full Active Directory security lab built using Windows Server 2025 and Windows 11.  
The goal was to simulate a real enterprise environment, implement Group Policy security baselines, and enforce least privilege access across the domain.


# Lab Overview
- Deployed a Windows Server 2025 Domain Controller  
- Created a structured OU hierarchy for IT, Security, Operations, and Standard Users  
- Joined a Windows 11 workstation to the domain  
- Implemented enterprise security baselines through Group Policy  
- Hardened the environment using password policies, UAC controls, SMB protections, and removable storage restrictions  
- Validated all policies using a standard (non‑admin) user account  


# Security Controls Implemented

#**Password & Account Policies**
- Minimum password length  
- Password complexity  
- Account lockout thresholds  

#**UAC Hardening**
- Admin Approval Mode  
- Secure desktop elevation prompts  
- Deny elevation for standard users  

#**SMB & Guest Access Hardening**
- Disabled Guest account  
- Disabled insecure guest logons  
- Enforced modern SMB protections  

#**Removable Storage Control**
- Blocked USB storage read/write access  


# What I Learned
- How to deploy and manage an enterprise Active Directory environment  
- How to design and apply Group Policy security baselines  
- How to enforce least privilege access and validate policy enforcement  
- How to harden Windows systems against common misconfigurations  
- How to troubleshoot authentication, permissions, and GPO issues

  
# Why This Project Matters
This lab demonstrates hands on experience with:

- Windows Server administration  
- Active Directory design  
- Group Policy management  
- Enterprise security hardening  
- Real world troubleshooting  

These are core skills for help desk, sysadmin, and cybersecurity roles.
