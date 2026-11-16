# ReconcileKit Lite — Free Offline Spreadsheet Comparison Studio

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Zero Telemetry](https://img.shields.io/badge/Privacy-100%25%20Offline%20%7C%20Zero%20Telemetry-success.svg)](#privacy--security-guarantee)
[![Languages](https://img.shields.io/badge/Languages-7%20Supported-purple.svg)](#-multi-language-support)
[![Platform](https://img.shields.io/badge/Platform-Single--File%20HTML5-orange.svg)](#)

> **Fast, private, and deterministic spreadsheet reconciliation — 100% client-side in your browser.**  
> Compare CSV, TSV, and Excel (XLSX) files, detect modified cells, additions, and removals, and export difference logs without cloud exposure.

---

### 🚀 Quick Links
- **[👉 Launch Live Demo on GitHub Pages](https://tinkomi.github.io/reconcilekit-spreadsheet-diff/)**
- **[💎 Upgrade to ReconcileKit PRO ($15) on Gumroad](https://mcjinster.gumroad.com/)**

---

![ReconcileKit PRO Cover](assets/cover.png)

## ⚡ What is ReconcileKit?

Data analysts, ecommerce merchants, accountants, and software engineers frequently compare two versions of tabular datasets:
- **Supplier Price Lists vs. Internal Inventory**
- **Monthly Billing Reports vs. Bank Statements**
- **Pre-Migration Database Dumps vs. Post-Migration CSVs**

Existing online diff checkers require uploading confidential financial or customer data to third-party cloud servers. General-purpose text diff tools only show line changes, lacking understanding of primary keys or column relationships.

**ReconcileKit** solves this by providing a complete in-browser spreadsheet comparison studio:
1. **100% Offline & Private:** Zero server uploads, zero network calls, GDPR and HIPAA friendly.
2. **Key-Based Record Matching:** Matches rows deterministically using primary keys (SKU, ID, Email).
3. **Deterministic 4-Way Classification:** Identical, Modified, Added, and Removed.
4. **Interactive Explorer:** Searchable, sortable diff viewer with old vs. new values and drift calculations.

---

## 📸 Feature Showcase

### 1. Deterministic 4-Way Diff Engine
![Deterministic 4-Way Reconciliation Diff](assets/gallery-01.png)
- **Identical:** Records present in both files with all columns matching.
- **Modified:** Records present in both files with specific cell-level deviations highlighted.
- **Added:** New records present in the incoming file only.
- **Removed:** Prior records missing from the incoming file.

### 2. Exception Review Queue & Audit Deliverables (PRO)
![Exception Review Queue & 1-Click Audit ZIP](assets/gallery-02.png)
- **Review Queue:** Review discrepancies row-by-row, choose explicit actions (Keep Baseline, Use Incoming, Manual Override), and enter audit notes.
- **1-Click Audit Pack ZIP:** Exports a certified 3-file package containing the Reconciled Master CSV, Structured Exception Log CSV, and Executive Markdown Audit Report.

---

## ⚖️ Edition Comparison: Lite vs. PRO

| Feature | ReconcileKit Lite (Free) | ReconcileKit PRO ($15) |
| :--- | :---: | :---: |
| **Pricing** | **Free (MIT License)** | **$15 (One-time purchase)** |
| **Deployment** | Single-File HTML5 | Single-File HTML5 |
| **Zero-Telemetry Offline Execution** | ✅ Yes | ✅ Yes |
| **File Formats** | CSV, TSV, XLSX | CSV, TSV, XLSX |
| **Delimiter Auto-Detection** | ✅ Yes (Comma, Tab, Pipe, Semicolon) | ✅ Yes |
| **Primary Key Matching** | Single Column Key | **Composite Keys (Up to 4 columns)** |
| **Column Name Mapping** | Same Header Names | **Custom Header Mapping (A → B)** |
| **4-Way Record Classification** | ✅ Yes | ✅ Yes |
| **Cell-Level Value Drift** | ✅ Yes | ✅ Yes |
| **Numeric & Tolerance Rules** | ❌ None (Strict) | **Absolute & Relative % Thresholds** |
| **Text Normalization** | ❌ None | **Trim, Ignore Case, Collapse Spaces** |
| **Interactive Exception Queue** | ❌ None | **Approve, Reject, Flag + Notes** |
| **Explicit Reconciliation Actions** | ❌ None | **Keep A, Use B, Manual Override** |
| **Difference Log CSV Export** | ✅ Yes | ✅ Yes |
| **Reconciled Master CSV Export** | ❌ None | **✅ Yes (Clean merged deliverable)** |
| **Audit Trail Markdown Report** | ❌ None | **✅ Yes (Executive sign-off summary)** |
| **1-Click Certified Audit ZIP** | ❌ None | **✅ Yes (Full ZIP deliverable)** |
| **Comparison Profile Save/Load** | ❌ None | **✅ Yes (JSON Profile)** |
| **Multi-Language Interface** | **7 Languages** | **7 Languages** |

---

## 🌐 Multi-Language Support

ReconcileKit includes native, instant in-app switching between 7 languages:
- 🇺🇸 **English** (Default)
- 🇪🇸 **Español**
- 🇫🇷 **Français**
- 🇧🇷 **Português**
- 🇨🇳 **简体中文**
- 🇯🇵 **日本語**
- 🇰🇷 **한국어**

All translations are embedded directly in the standalone HTML file without external font or API calls.

---

## 🛡️ Privacy & Security Guarantee

- **Zero Network Traffic:** The application contains zero tracking pixels, zero analytics scripts, and zero API calls.
- **Local Browser Execution:** All spreadsheet parsing, key matching, and ZIP compression occur exclusively inside browser RAM.
- **Formula Injection Guard:** When exporting CSVs, cell values beginning with `=`, `+`, `-`, or `@` are safely neutralized to prevent formula execution in Microsoft Excel.

---

## 💻 Quick Start

1. Clone or download this repository:
   ```bash
   git clone https://github.com/tinkomi/reconcilekit-spreadsheet-diff.git
   ```
2. Double-click `index.html` to open it in Chrome, Edge, Safari, or Firefox.
3. Drag and drop File A (Baseline) and File B (Incoming).
4. Select your primary key and click **Run Reconciliation Diff ⚡**.

---

## 📄 License

This open-source Lite edition is released under the **MIT License**.  
Commercial PRO edition available on Gumroad.
