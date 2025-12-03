# Hybrid Entra ID + On-Prem Active Directory + Microsoft 365 Integration Lab

## Overview
This project demonstrates a **complete hybrid identity deployment**, integrating:

- **On-Premises Active Directory (AD DS)**
- **Microsoft Entra ID (Azure AD)**
- **Microsoft 365 Business Standard**
- **Password Hash Sync (PHS) via Entra Cloud Sync**
- **Full identity lifecycle validation** across Outlook, SharePoint, Teams, and OneDrive

This lab mirrors real-world MSP onboarding workflows and modern enterprise identity environments.

---

## Skills Demonstrated
- **Hybrid Identity Architecture** (AD DS ↔ Entra ID)
- **Entra Cloud Sync (Password Hash Sync)**
- **Global Admin MFA enrollment & cloud security basics**
- **Microsoft 365 licensing & provisioning**
- **Exchange, SharePoint, Teams, and OneDrive activation**
- **Identity lifecycle validation from on-prem → cloud**
- **Troubleshooting sync, domain health, and provisioning**
- **Professional documentation & lab reporting**

---

# Lab Walkthrough

## **Phase 1 — Entra Tenant Setup & Security Hardening**

### **Step 1 — Created Microsoft Entra ID tenant and core users**
![Step 1 – Entra tenant creation](screenshots/01-Entra-Tenant-Creation.png)

### **Step 2 — Enabled MFA for Global Admin using Microsoft Authenticator (iPhone)**
![Step 2 – MFA setup in Authenticator](screenshots/02-MFA-Setup-Authenticator.png)

---

## **Phase 2 — Hybrid Identity Connection (On-Prem AD → Entra)**

### **Step 3 — Entered on-prem AD domain admin credentials in the Entra Provisioning Agent**
![Step 3 – Entra agent AD credentials](screenshots/03-Entra-Agent-AD-Credentials.png)

### **Step 4 — Connected on-prem Active Directory domain (`cross-os.local`) in the agent**
![Step 4 – Connect Active Directory](screenshots/04-Connect-Active-Directory.png)

### **Step 5 — Created Cloud Sync configuration with Password Hash Sync enabled**
![Step 5 – Cloud Sync configuration](screenshots/05-Cloud-Sync-Configuration.png)

### **Step 6 — Cloud Sync configuration successfully activated**
![Step 6 – Cloud Sync activated](screenshots/06-Cloud-Sync-Activated.png)

### **Step 7 — Verified domain health, sync status, and active provisioning agent**
![Step 7 – Domain health verified](screenshots/07-Domain-Health-Verified.png)

### **Step 8 — Confirmed on-prem AD users are synced into Entra ID**
![Step 8 – AD users synced to Entra](screenshots/08-AD-Users-Synced-To-Entra.png)

---

## **Phase 3 — Microsoft 365 Licensing & Identity Enablement**

### **Step 9 — Assigned Microsoft 365 Business Standard license**
![Step 9 – M365 Business license assigned](screenshots/09-M365-Business-License-Assigned.png)

### **Step 10 — Assigned Microsoft Entra Suite license**
![Step 10 – Entra Suite license assigned](screenshots/10a-Entra-Suite-License-Assigned.png)

### **Step 11 — Confirmed Test User has both M365 and Entra Suite licenses**
![Step 11 – License assignment confirmed](screenshots/10b-License-Assignment-Confirmed.png)

---

## **Phase 4 — Full Cloud Identity Lifecycle Validation**

### **Step 12 — Logged into Microsoft 365 portal with synced on-prem Test User**
![Step 12 – M365 login with synced user](screenshots/11-01-M365-Login-Synced-User.png)

### **Step 13 — Exchange Online mailbox automatically provisioned (Outlook on the web)**
![Step 13 – Exchange mailbox provisioned](screenshots/11-02-Exchange-Mailbox-Provisioned.png)

### **Step 14 — SharePoint Online access verified**
![Step 14 – SharePoint access verified](screenshots/11-03-SharePoint-Access-Verified.png)

### **Step 15 — Microsoft Teams login & provisioning successful**
![Step 15 – Teams login verified](screenshots/11-04-Teams-Login-Verified.png)

### **Step 16 — OneDrive for Business successfully provisioned**
![Step 16 – OneDrive provisioned](screenshots/11-05-OneDrive-Provisioned.png)

---

# Key Takeaways
This project provided a **complete, end-to-end demonstration** of a modern hybrid identity environment:

- Local AD synchronized with Microsoft Entra ID  
- Secure MFA-enabled cloud authentication  
- Fully working Microsoft 365 services (Outlook, Teams, SharePoint, OneDrive)  
- Real MSP-style user onboarding workflow  
- Demonstrates understanding of both **on-prem** and **cloud identity systems**  

This lab reflects real-world identity engineering and is directly applicable to **Help Desk, System Administrator, MSP, Cloud Engineer, and Security roles**.
