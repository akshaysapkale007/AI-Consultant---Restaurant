# 🍔 Restaurant Intelligence System

> AI-Powered Business Intelligence for Restaurant Operations

## 🎯 Project Overview

Built an end-to-end **AI-powered analytics system** that transforms raw restaurant POS (Point of Sale) data into actionable business insights and professional intelligence reports. The system combines **Python data analysis** with **Large Language Model (LLM) integration** to generate consultant-grade recommendations.

---

## 🤖 AI/LLM Integration

This project leverages **Generative AI** throughout the development and analysis pipeline:

| AI Application | Purpose |
|----------------|---------|
| **Code Generation** | AI-assisted development of analysis modules using Claude/Gemini |
| **Report Narrative** | LLM-generated business insights and recommendations |
| **Data Interpretation** | AI-powered pattern recognition and anomaly detection |
| **Action Plans** | Automated generation of prioritized recommendations with projected ROI |

**Key AI Capabilities:**
- Natural language business summaries from raw data
- Automated "What This Means" explanations for every metric
- AI-generated upsell scripts based on modifier analysis
- Intelligent 90-day action plan creation

---

## 📊 Problem Statement

Restaurant owners receive thousands of transaction records daily but lack the time and expertise to:
- Identify which menu items are underperforming
- Recognize customer churn before it impacts revenue
- Understand peak hour patterns for optimal staffing
- Compare employee performance fairly across different shifts
- Track multi-location performance separately

This system automates all of this analysis and generates executive-ready reports with specific, actionable recommendations.

---

## 🔧 Technical Stack

| Category | Technologies |
|----------|-------------|
| **Language** | Python 3.x |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib |
| **Report Generation** | python-docx |
| **AI/LLM** | Gemini API, Claude (development assistance) |
| **Analysis Methods** | Statistical analysis, cohort analysis, time series |

---

## 📈 Key Features

### 1. Menu Engineering Analysis
Applied BCG Matrix methodology to classify every menu item:

| Classification | Meaning | Action |
|---------------|---------|--------|
| ⭐ **Star** | High popularity + High profit | Protect and feature |
| 🧩 **Puzzle** | Low popularity + High profit | Promote heavily |
| 🐴 **Plowhorse** | High popularity + Low profit | Consider price increase |
| 🐕 **Dog** | Low popularity + Low profit | Consider removing |

---

### 2. Customer Segmentation & Churn Prediction

| Segment | Description |
|---------|-------------|
| **VIP Customers** | High lifetime spend - priority retention |
| **Repeat Customers** | 2+ visits - higher LTV than one-timers |
| **Churned Customers** | Regulars who stopped visiting - win-back targets |

**Methodology:** Enhanced customer tracking using Customer ID + Card data, with name association learning to link anonymous transactions.

---

### 3. Shift-Normalized Employee Performance

Traditional revenue-based comparisons are unfair (Friday 7pm server will always beat Tuesday lunch). 

**Solution:** Compare each employee to their specific shift average, providing fair performance assessment.

---

### 4. Multi-Location Analysis

Automatically separates and analyzes each restaurant location independently:
- Location-specific KPIs
- Separate employee rankings
- Individual customer bases
- Location-tailored recommendations

---

### 5. AI-Powered Report Generation

Generates comprehensive 9-page professional DOCX reports including:

1. **Executive Summary** - Key metrics and top 5 priorities
2. **Best Sellers** - Top items with growth trends
3. **Menu Engineering** - Complete item classification with action items
4. **Upsell Opportunities** - AI-generated scripts with projected impact
5. **Peak Hours Analysis** - Staffing recommendations by hour
6. **Day of Week Patterns** - Revenue optimization by day
7. **Team Performance** - Shift-normalized rankings
8. **Customer Loyalty** - VIPs, churn list, retention strategies
9. **90-Day Action Plan** - AI-generated implementation guide

---

## 💡 Insights Generated (Example Capabilities)

The system can identify:
- Revenue opportunities through upselling optimization
- At-risk customers before they churn completely
- Menu items that should be removed or promoted
- Top-performing employees and what makes them effective
- Optimal staffing patterns based on historical demand
- Price adjustment opportunities with projected impact

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    DATA INGESTION                           │
│  ┌─────────────┐   ┌─────────────┐   ┌─────────────┐       │
│  │  CSV File 1 │   │  CSV File 2 │   │  CSV File N │       │
│  └──────┬──────┘   └──────┬──────┘   └──────┬──────┘       │
│         └─────────────────┼─────────────────┘               │
│                           ▼                                 │
│              ┌────────────────────────┐                     │
│              │     ETL Pipeline       │                     │
│              └───────────┬────────────┘                     │
└──────────────────────────┼──────────────────────────────────┘
                           ▼
┌─────────────────────────────────────────────────────────────┐
│                   ANALYSIS ENGINE                           │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │    Menu      │  │   Customer   │  │   Employee   │      │
│  │ Engineering  │  │  Analytics   │  │ Performance  │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────┬───────────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────────┐
│              🤖 AI/LLM INTEGRATION LAYER                    │
│  ┌────────────────────────────────────────────────────┐    │
│  │  • Natural Language Insight Generation             │    │
│  │  • Recommendation Engine                           │    │
│  │  • Action Plan Creation                            │    │
│  └────────────────────────────────────────────────────┘    │
└─────────────────────────┬───────────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────────┐
│                  REPORT GENERATOR                           │
│           📄 Professional Intelligence Report               │
└─────────────────────────────────────────────────────────────┘
```

---

## 📋 Analysis Modules

| Module | Purpose |
|--------|---------|
| `analyze_summary` | High-level business metrics |
| `analyze_monthly_trends` | Seasonal patterns |
| `analyze_day_of_week` | Daily patterns |
| `analyze_customer_value` | Customer segmentation |
| `analyze_customer_churn` | Churn prediction |
| `analyze_item_trends` | Product lifecycle |
| `analyze_hourly_by_day` | Peak identification |
| `analyze_employee_shifts` | Staff performance |
| `analyze_shift_normalized` | Fair comparison |
| `analyze_modifier_revenue` | Upsell opportunities |
| `menu_engineering` | BCG classification |

---

## 🎯 Skills Demonstrated

### Technical
- **Python** (Pandas, NumPy, Matplotlib)
- **AI/LLM Integration** (Gemini, Claude)
- ETL Pipeline Development
- Statistical Analysis
- Automated Report Generation

### Analytics
- Menu Engineering (BCG Matrix)
- Customer Segmentation
- Cohort Analysis
- Churn Prediction
- Revenue Analysis

### Business
- Financial Modeling
- Strategic Recommendations
- Multi-location Analysis
- Stakeholder Reporting

---

## 📝 Note

*This repository showcases project methodology and architecture. Source code and client data are proprietary and not included.*

---

## 👤 Author

Finance AI Systems Analyst

---

## 📄 License

This project documentation is for portfolio purposes only.
