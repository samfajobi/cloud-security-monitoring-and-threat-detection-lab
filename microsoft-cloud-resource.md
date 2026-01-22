# 📘 Microsoft Cloud Services Overview

### *(Identity, Infrastructure, Security & Monitoring)*

This repository focuses on **cloud monitoring**, but understanding Microsoft’s cloud ecosystem is critical to knowing *what* you monitor and *why*.
This document explains the **core Microsoft cloud services**, their responsibilities, and how they work together in real organizations.

---

## 🧠 High-Level Architecture

Microsoft Cloud is built in **layers**, not isolated services:

* **Identity & Access** → Microsoft Entra ID
* **Productivity & Collaboration** → Microsoft 365
* **Infrastructure & Apps** → Azure
* **Device Management** → Intune
* **Security & Threat Detection** → Microsoft Defender
* **Cloud Security Posture** → Defender for Cloud
* **DevOps & Automation** → Azure DevOps

Understanding these layers makes monitoring and security far more effective.

---

## 🔐 Microsoft Entra ID (Azure Active Directory)

**Purpose:** Identity and access management

**What it manages:**

* Users & groups
* Authentication (MFA)
* Conditional Access
* App registrations & service principals
* Privileged Identity Management (PIM)

**Why it matters for monitoring:**

* Sign-in logs
* Risky user activity
* Privileged role activations

➡️ *Everything in Microsoft Cloud depends on Entra ID.*

---

## 🧑‍💼 Microsoft 365 Admin Center (Productivity Layer)

**Purpose:** Business productivity & collaboration

**Core services:**

* **Exchange Online** → Email & calendars
* **SharePoint Online** → Document management & intranet
* **Microsoft Teams** → Chat, meetings & collaboration
* **OneDrive** → Personal cloud storage

**Why it matters for monitoring:**

* Email threats
* Data access patterns
* Collaboration activity

➡️ *This is where day-to-day business happens.*

---

## ☁️ Azure Portal (Infrastructure Layer)

**Purpose:** Cloud infrastructure and application hosting

**Common Azure resources:**

* Virtual Machines
* App Services
* Storage Accounts
* Virtual Networks
* Databases
* Azure Monitor & Log Analytics

**Why it matters for monitoring:**

* Resource health
* Performance metrics
* Availability & cost
* Logs and diagnostics

➡️ *This is where workloads actually run.*

---

## 🔑 Azure RBAC (Resource Access Control)

**Purpose:** Authorization for Azure resources

**Common roles:**

* Owner
* Contributor
* Reader

**Scope levels:**

* Subscription
* Resource group
* Individual resource

**Why it matters for monitoring:**

* Track privilege changes
* Detect excessive permissions



