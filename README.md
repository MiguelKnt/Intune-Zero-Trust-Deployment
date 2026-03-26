# Intune-Zero-Trust-Deployment
Zero Trust security lab using Microsoft Entra ID and Intune with Conditional Access, MFA, and endpoint compliance policies.

# 🛡️ Enterprise Zero Trust Deployment Lab

## 📌 Overview
Designed and implemented a Zero Trust security architecture using Microsoft Entra ID and Intune in a simulated enterprise environment.

---

## 🧱 Architecture
- Identity: Microsoft Entra ID  
- Device Management: Microsoft Intune  
- Security Controls: Conditional Access (MFA)  
- Endpoint Security: Compliance + Configuration Policies  

---

## 👥 User Configuration
- Created 10 users to simulate an enterprise environment  
- Assigned Microsoft 365 licenses  
- Established identity structure for testing  

---

## 🔐 Role Assignment
- Configured Global Administrator account  
- All other users assigned standard roles  
- Enforced least privilege access  

---

## 🎟️ Licensing
- Microsoft Entra ID Plan 1  
- Microsoft Intune Plan 1  

---

## 🔒 Conditional Access (MFA)
- Enforced MFA for all users  
- Excluded admin account to prevent lockout  
- Applied to all cloud applications  

---

## 🖥️ Intune Setup
- Initialized Microsoft Intune environment  
- Prepared Windows device management  

---

## 📋 Device Compliance Policy
- BitLocker required  
- Secure Boot required  
- TPM required  
- Antivirus required  
- Minimum OS version enforced  

---

## ⚙️ Configuration Policy (OS Hardening)
- BitLocker encryption enabled  
- Windows Firewall enabled (all profiles)  

---

## 🎯 Outcome
- Implemented identity-based access control  
- Enforced secure device compliance  
- Applied Zero Trust principles across identity and endpoints  
