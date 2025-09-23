
# 📘 Phase 2: Org Setup & Configuration  

## 🔹 1. Introduction  
In this phase, we configure the Salesforce Developer Org to prepare the environment for building **SmartProperty CRM – Real Estate Engagement & Lead Conversion System**.  
The setup ensures the org has correct company settings, security, user hierarchy, and access policies.  

By the end of this phase, the system will be ready for **Phase 3: Data Modeling & Relationships**.  

---

## 🔹 2. Salesforce Editions  
- Using **Salesforce Developer Edition (Free)**  
- Provides:  
  - Custom Objects & Fields  
  - App Builder & Lightning Apps  
  - Users, Profiles, Roles, Permission Sets  
  - Reports & Dashboards  

---

## 🔹 3. Company Profile Setup  
**Navigation:** Setup → Company Settings → Company Information  
- Company Name → SmartProperty CRM  
- Default Currency → INR (₹)  
- Locale → English (India)  
- Time Zone → (GMT +5:30) India Standard Time  

---

## 🔹 4. Business Hours & Holidays  
**Navigation:** Setup → Company Settings → Business Hours  
- Business Hours → 9:00 AM – 6:00 PM, Monday to Saturday  
- Holidays (Examples):  
  - Republic Day (26th Jan)  
  - Diwali  
  - New Year (1st Jan)  

---

## 🔹 5. Fiscal Year Settings  
**Navigation:** Setup → Company Settings → Fiscal Year  
- Standard Fiscal Year → April 1 to March 31  

---

## 🔹 6. User Setup & Licenses  
**Navigation:** Setup → Users → New User  
- Created sample users:  
  - Sales Agent → Standard Salesforce License  
  - Property Manager → Salesforce Platform License  
  - Sales Manager → Standard Salesforce License  

---

## 🔹 7. Profiles  
**Navigation:** Setup → Profiles  
- Cloned **Standard User Profile → Sales Agent Profile**  
- Gave CRUD access to: Leads, Opportunities, and (later) Property Object  

---

## 🔹 8. Roles (Hierarchy)  
**Navigation:** Setup → Roles → Set Up Roles  
Hierarchy Defined:  
- Executive (Top level)  
- Sales Manager  
- Sales Agent  

(Ensures managers can view their team’s records.)  

---

## 🔹 9. Permission Sets  
**Navigation:** Setup → Permission Sets → New  
- Created: **Property Management Access**  
- CRUD access for Property Object (to be created in Phase 3)  
- Assigned to Property Manager user  

---

## 🔹 10. Organization-Wide Defaults (OWD)  
**Navigation:** Setup → Sharing Settings  
- Leads → Private  
- Opportunities → Private  
- Property (custom object – Phase 3) → Public Read/Write  

---

## 🔹 11. Sharing Rules  
**Navigation:** Setup → Sharing Settings → New Sharing Rule  
- Example: **Share Leads owned by “East Team” with West Team**  

---

## 🔹 12. Login Access Policies  
**Navigation:** Setup → Login Access Policies  
- Enabled: **Administrators Can Log In as Any User**  
- (Optional) Restricted logins by IP range for security  

---

## 🔹 13. Dev Org Setup & Sandbox Usage  
- Working in **Developer Edition Org (free)**  
- Sandboxes are **not available** in Developer Edition  
- Practice done directly in Dev Org  

---

## 🔹 14. Deployment Basics  
- Initial setup done directly in Dev Org  
- Future deployment methods:  
  - Change Sets (click-based)  
  - SFDX CLI + GitHub (for advanced version control)  

---

## ✅ Phase 2 Deliverables  
- Salesforce Developer Org created and verified  
- Company profile updated (currency, locale, timezone)  
- Business hours and holidays defined  
- Fiscal year configured  
- Users created (Agent, Manager, Property Manager)  
- Profiles cloned and updated  
- Roles defined in hierarchy  
- Permission sets created  
- OWD and Sharing Rules implemented  
- Login access policies updated  
