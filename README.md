# 🏭 OEE & TPM Manufacturing Dashboard

### 📊 From Production Data → Loss Analysis → Improvement Actions

An **Excel-based Manufacturing Analytics Dashboard** developed to evaluate equipment effectiveness using **Overall Equipment Effectiveness (OEE)** and **Total Productive Maintenance (TPM)** principles.

The project transforms production and downtime data into meaningful KPIs, identifies the major sources of losses, and presents the findings through an interactive dashboard to support **data-driven continuous improvement**.

---

## 🎯 01 | Business Problem

In manufacturing, high production output does not always mean high equipment efficiency.

Machines may lose productive time because of:

* Equipment breakdowns
* Setup and adjustment
* Minor stoppages
* Reduced operating speed
* Defective production
* Startup losses

Therefore, the objective is to understand **where productive time is being lost and why**.

---

# 🔄 02 | Project Flow

```text
                 RAW PRODUCTION DATA
                         │
                         ▼
              DATA PREPARATION & CLEANING
                         │
                         ▼
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
     AVAILABILITY    PERFORMANCE      QUALITY
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                   OEE CALCULATION
                         │
                         ▼
              EQUIPMENT PERFORMANCE
                    ANALYSIS
                         │
                         ▼
                LOSS IDENTIFICATION
                         │
                         ▼
              SIX BIG LOSSES ANALYSIS
                         │
                         ▼
                TPM OPPORTUNITIES
                         │
                         ▼
              INTERACTIVE DASHBOARD
                         │
                         ▼
             ACTIONABLE INSIGHTS
```

### In simple words:

**Collect → Calculate → Compare → Identify Losses → Find Root Causes → Prioritize Actions → Improve**

---

# 🧮 03 | OEE Calculation

The core of the project is **Overall Equipment Effectiveness (OEE)**.

### OEE consists of three components:

**Availability × Performance × Quality = OEE**

### 🟢 Availability

Measures how much of the planned production time the machine was actually available for production.

**Availability = Operating Time / Planned Production Time**

---

### 🔵 Performance

Measures whether the machine is operating at its expected/ideal production speed.

**Performance = Ideal Cycle Time × Total Count / Operating Time**

---

### 🟠 Quality

Measures the proportion of production that meets quality requirements.

**Quality = Good Count / Total Count**

---

### ⭐ Overall Equipment Effectiveness

**OEE = Availability × Performance × Quality**

This provides a single KPI while still allowing the analysis to identify **which component is causing poor OEE**.

---

# ⚙️ 04 | From OEE to Losses

OEE tells us **how well the equipment is performing**.

The next question is:

> **“What is causing the loss in performance?”**

This project therefore moves from OEE measurement to **loss analysis**.

### Six Big Losses

| OEE Component    | Major Losses                           |
| ---------------- | -------------------------------------- |
| **Availability** | Equipment Failures, Setup & Adjustment |
| **Performance**  | Idling & Minor Stops, Reduced Speed    |
| **Quality**      | Process Defects, Startup/Yield Losses  |

This approach helps convert a KPI into a **specific improvement opportunity**.

---

# 🔍 05 | Equipment & Loss Analysis

The calculated metrics are used to compare:

* Equipment-wise OEE
* Availability performance
* Performance efficiency
* Quality performance
* Downtime
* Production losses
* Major loss categories

The analysis helps identify **which machines require attention and what type of loss should be addressed first**.

---

# 🔧 06 | TPM Connection

The analysis is then connected with **Total Productive Maintenance (TPM)**.

Instead of stopping at:

> ❌ “OEE is low.”

The project aims to reach:

> ✅ “OEE is low because of a specific loss, and that loss requires a specific improvement action.”

This creates a practical improvement cycle:

**Loss Identified → Cause Investigated → TPM Action → Performance Improvement**

---

# 📊 07 | Interactive Dashboard

The final dashboard brings the complete analysis together in one place.

### Dashboard includes:

📌 **Overall OEE KPI**
📌 **Availability, Performance & Quality**
📌 **Equipment-wise comparison**
📌 **Downtime & loss analysis**
📌 **Six Big Losses visualization**
📌 **Performance trends**
📌 **TPM improvement opportunities**
📌 **Key manufacturing insights**

The dashboard is designed to provide a **quick management-level view** while allowing deeper analysis of the underlying losses.

---

# 🛠️ 08 | Tools & Techniques

### 💻 Tools

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Excel Formulas
* Conditional Formatting
* Data Visualization
* Interactive Dashboarding

### 🏭 Manufacturing Concepts

* Overall Equipment Effectiveness (OEE)
* Total Productive Maintenance (TPM)
* Six Big Losses
* Downtime Analysis
* Equipment Performance
* Preventive Maintenance
* Root Cause Analysis
* Continuous Improvement

---

# 📁 09 | Project Structure

```text
OEE-TPM-Dashboard/
│
├── 📊 OEE_TPM_Dashboard.xlsx
│
├── 📄 README.md
│
└── 📷 Dashboard/
      └── Dashboard Preview
```

The Excel workbook contains the **data, calculations, analysis and visualization** required to reproduce the dashboard.

---

# 💡 10 | Business Value

The project demonstrates how manufacturing data can be converted into **actionable operational intelligence**.

It can help teams:

✅ Identify major production losses
✅ Detect low-performing equipment
✅ Understand the reason behind poor OEE
✅ Prioritize maintenance activities
✅ Focus TPM initiatives on high-impact losses
✅ Monitor manufacturing KPIs
✅ Support continuous improvement decisions

---

# 🚀 11 | End-to-End Outcome

The key idea behind the project is:

```text
              PRODUCTION DATA
                     ↓
              OEE MEASUREMENT
                     ↓
             LOSS IDENTIFICATION
                     ↓
              ROOT-CAUSE FOCUS
                     ↓
             TPM IMPROVEMENT
                     ↓
             BETTER EQUIPMENT
               EFFECTIVENESS
```

Rather than treating the dashboard as only a reporting tool, the project uses it as a **decision-support system for manufacturing improvement**.

---

## ⭐ Key Takeaway

> **“Measure the performance. Identify the loss. Find the cause. Take action. Improve.”**

This project demonstrates the practical application of **OEE, TPM, manufacturing KPIs and Excel analytics** to understand equipment performance and drive continuous improvement.

---

### 👩‍💻 Skills Demonstrated

**Manufacturing Analytics • Excel Dashboarding • OEE • TPM • Six Big Losses • Downtime Analysis • KPI Analysis • Data Visualization • Continuous Improvement**
