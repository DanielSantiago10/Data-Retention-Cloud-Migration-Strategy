# Project: Data Retention & Cloud Migration Strategy

### Organization: Cymbal Bank (Digital Transformation Initiative)

**Role:** Junior Cloud Security Analyst

## 📌 Project Overview

This project addresses a critical infrastructure and compliance gap at Cymbal Bank. Currently, the organization operates on an **On-premises** model that has reached physical storage capacity. Without a formal **Data Retention Policy**, the bank faces a dual threat: the accidental deletion of legally required data and the accumulation of high-risk, "cold" data on expensive local hardware.

The objective of this proposal is to transition Cymbal Bank from a restricted physical storage model to a scalable, secure, and cost-effective **Public Cloud** or **Hybrid Cloud** environment.

---

## 📉 Risk Assessment & Impact Analysis

The "cost of doing nothing" is estimated at **$300,000+**.

* **Compliance Risk:** Failure to meet industry standards (e.g., HIPAA) could result in fines up to **$250,000**.
* **Operational Risk:** Potential loss of business-critical data due to "emergency deletions" could cost **$50,000+** in wasted labor and rework.
* **Infrastructure Risk:** Current storage is nearing 100% capacity, threatening system **Resiliency** and increasing the likelihood of downtime.

---

## 🚀 Proposed Mitigation Strategy: The Three-Phase Plan

To address these risks while remaining cost-conscious, I have designed a 10-week implementation roadmap:

### Phase 1: Policy Development (5 Weeks)
> 📂 **Project Assets:** View the full [Data Retention Schedule](https://github.com/DanielSantiago10/Data-Retention-Cloud-Migration-Strategy/blob/main/Data_Retention_Schedule.md) for detailed compliance timelines.
* Define a formal **Data Retention Schedule** (identifying **Structured** vs. **Unstructured** data).
* Collaborate with Legal and IT to ensure compliance with data governance regulations.
* Categorize data into "Hot" (frequent access) and "Cold" (archival) tiers.

### Phase 2: Cloud Storage Integration (3 Weeks)
> 📝 **Decision Log:** See why we chose our Cloud Service Provider in the [Selection Guide](https://github.com/DanielSantiago10/Data-Retention-Cloud-Migration-Strategy/blob/main/CSP_Selection_Guide.md)
* Migrate data to a Cloud Service Provider (CSP) to leverage **Virtualization** and **Redundancy**.
* Implement **Object Storage** (Buckets) for unstructured data (images, PDFs, documents).
* Utilize **Archival Storage Classes** for cold data to minimize **OpEx** (Operational Expenditure).

### Phase 3: Training & Review (2 Weeks)

* Educate employees on new data handling protocols.
* Establish **Audit Logs** and **Access Controls** within the cloud environment.
* Set a cycle for annual policy reviews to adapt to changing legal requirements.

---

## 🛠️ Technical Competencies Applied

This project utilizes the core principles of Cloud Cybersecurity:

| Concept | Application in Project |
| --- | --- |
| **Resiliency** | Using cloud **Redundancy** across different **Zones** and **Regions** to prevent data loss. |
| **Scalability** | Moving away from fixed on-prem hardware to a cloud model that grows with the bank's data. |
| **Zero-Trust** | Ensuring all cloud-based data is protected by strict authentication and encryption. |
| **Ephemerality** | Using temporary instances for data processing to reduce the attack surface for cybercriminals. |

---

## 📖 Key Definitions

* **On-premises:** Infrastructure physically located in the organization's office.
* **Public Cloud:** On-demand computing and storage resources shared via the internet.
* **Redundancy:** Replicating data across multiple locations to avoid a single point of failure.
* **Unstructured Data:** Data not organized in a predefined format (images, videos, etc.).
* **Virtualization:** Creating virtual versions of physical infrastructure to maximize efficiency.

---

## 🏁 Conclusion & Recommendations

By moving to a cloud-based storage model, Cymbal Bank will not only mitigate a $300,000 financial risk but also improve its overall security posture. We move from a **CapEx** model (buying expensive servers) to a flexible **OpEx** model (paying only for what we use), ensuring long-term sustainability.
