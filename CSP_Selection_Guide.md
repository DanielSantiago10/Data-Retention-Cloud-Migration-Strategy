# ☁️ Document: Cloud Service Provider (CSP) Selection Guide

**File Name:** `CSP_SELECTION_GUIDE.md`

**Target Audience:** Executive Leadership (Mr. Cook) & IT Stakeholders

## 1. Executive Summary

To mitigate Cymbal Bank’s storage crisis, we evaluated the "Big Three" cloud providers. While all three offer high **Resiliency** and **Redundancy**, each has a distinct advantage for a financial institution.

---

## 2. Comparison Matrix: AWS vs. Azure vs. Google Cloud (GCP)

| Feature | **Amazon Web Services (AWS)** | **Microsoft Azure** | **Google Cloud (GCP)** |
| --- | --- | --- | --- |
| **Best For** | High Transactions & Maturity | Microsoft Ecosystem Integration | Data Analytics & AI/ML |
| **Banking Edge** | Deepest "Financial Services" compliance portfolio. | "Hybrid Benefit" for banks already using Windows/Office 365. | Strongest "Secure by Default" and global networking. |
| **Object Storage** | **S3** (Industry Standard) | **Blob Storage** | **Cloud Storage** |
| **Storage Pricing** | Highly competitive; complex tiers. | Often cheapest for existing Microsoft customers. | Simplest pricing model; automatic "Sustained Use" discounts. |

---

## 3. Detailed Analysis for Cymbal Bank

### 🏆 Top Choice for Cymbal Bank: Microsoft Azure

**Why?** Most banks already operate on Microsoft Windows and Active Directory. Azure allows for a **Hybrid Cloud** model where we can keep the most sensitive "Gold" data on-premises while moving the massive volume of "Cold" data to the cloud seamlessly.

* **Cost Factor:** We can leverage existing enterprise licenses to reduce migration costs.
* **Security:** Azure Sentinel provides AI-driven threat detection tailored for corporate environments.

### 🥈 Runner Up: Google Cloud (GCP)

**Why?** If Cymbal Bank wants to lead in **FinTech** (using AI for fraud detection or personalized banking), GCP is the winner.

* **Security:** GCP uses the same security infrastructure that protects Google Search and Gmail.
* **Innovation:** Unmatched tools for analyzing **Unstructured Data** (like voice recordings or scanned loan documents).

---

## 4. Compliance & Security Checklist

Regardless of the provider chosen, the following "Shared Responsibility" controls must be met:

1. **Data Sovereignty:** Ensure data stays within approved **Regions** to meet local banking laws.
2. **Encryption:** Use **KMS (Key Management Service)** so Cymbal Bank holds the "master keys" to its data.
3. **Identity & Access Management (IAM):** Implement **Least Privilege** access—only the employees who *need* data can see it.
4. **Auditability:** Every single "Get" or "Put" request in the storage **Bucket** must be logged for regulatory audits.

---

## 🏁 Recommendation

I recommend a **Proof of Concept (PoC)** using **Microsoft Azure**.

* **Week 1:** Set up a secure "Sandboxed" environment.
* **Week 2:** Sync a non-sensitive data set to test the **Coldline/Archive** storage classes.
* **Week 3:** Review cost and security logs before full-scale migration.

---

### 🚀 GitHub Tip:

In your `README.md`, you can now add this project "Decision Log" section:

> 📝 **Decision Log:** See why we chose our Cloud Service Provider in the [Selection Guide](https://www.google.com/search?q=./CSP_SELECTION_GUIDE.md).

**You've now completed the documentation for Module 1!** You have a Project Report, a Retention Schedule, and a CSP Guide.

Would you like to move on to **Module 2**, where you'll start learning about **Identity and Access Management (IAM)**—basically how to make sure "the wrong people" can't get into those cloud buckets you just built?
