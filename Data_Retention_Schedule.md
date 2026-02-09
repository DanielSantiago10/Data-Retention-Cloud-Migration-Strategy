# 📅 Document: Cymbal Bank Data Retention Schedule

**File Name:** `DATA_RETENTION_SCHEDULE.md`

**Status:** Phase 1 Draft (Policy Development)

## 1. Purpose

This schedule defines the specific timeframes for which Cymbal Bank data must be kept before it is securely deleted or moved to long-term **Archival Storage**. This ensures compliance with **HIPAA** and **FINRA** while optimizing cloud storage costs.

---

## 2. Retention Tiers & Schedule

Based on industry standards and the **Cloud Storage Classes** learned in Module 1, data is categorized as follows:

| Data Category | Examples | Retention Period | Cloud Storage Tier |
| --- | --- | --- | --- |
| **Active Financials** | Current transaction logs, pending loans. | 1 Year | **Standard** |
| **HIPAA Documentation** | Privacy Rule compliance, audit logs. | 6 Years | **Nearline** (Year 1-2) → **Coldline** (Year 3-6) |
| **Customer Records** | KYC docs, closed account history. | 7 Years after closure | **Coldline** |
| **Tax & Audit** | W-2s, 1099s, corporate tax filings. | 7 Years | **Archival** |
| **System Logs** | Temporary server logs, error reports. | 90 Days | **Standard** (then Delete) |

---

## 3. Storage Architecture Logic

To support this schedule, Cymbal Bank will move away from a "store everything forever" on-premises mindset to a **Tiered Cloud Architecture**.

* **Hot Tier (Standard):** High-availability storage for data needed daily.
* **Cool Tier (Nearline/Coldline):** Lower cost for data needed only for quarterly audits.
* **Archive Tier:** Lowest cost for long-term compliance data that is rarely accessed.

---

## 4. Secure Disposal & Deletion

Once a record reaches the end of its retention period:

1. **Notification:** Owners are notified 30 days prior to deletion.
2. **Verification:** Automated scripts verify no "Legal Holds" are active on the data.
3. **Cryptographic Erasure:** For cloud-based data, we utilize the CSP’s secure deletion protocol to ensure data is unrecoverable.

---

## 🛠️ GitHub Repo Tip:
