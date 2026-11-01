# FUTURE_DS_03
Bank Marketing Analytics Dashboard
# Bank Marketing Analytics Dashboard

This repository contains the comprehensive diagnostic tracking deliverables for the **Bank Telemarketing & Client Acquisition** project. The analytics platform ingests detailed customer demographic fields, previous campaign touches, and contextual macroeconomic variables, mapping the absolute baselines required to maximize fixed-deposit subscription run rates.

## 📁 Repository Structure

The workspace is systematically organized around the following project components:

*   **`Bank_Telemarketing_Data.csv`**: The primary relational ledger capturing account histories, structural balance indicators, and historic follow-up results.
*   **`Bank_Marketing_Analytics_Briefing.pdf`**: A high-fidelity, corporate executive summary providing structural diagnostic chart read-outs, segment margin breakdowns, and conversions analyses.
*   **`Dashboard_Layout_Preview.png`**: A clean visual framework render capturing the high-impact interface panel design across all core client segments.

## 📊 Core Performance Metrics

Based on the verified marketing transaction registries, the baseline customer portfolio shapes the following master business performance variables:

| Metric Indicator | Performance Value | Strategic Operational Definition |
| :--- | :--- | :--- |
| **Total Customers** | 11,162 | The cumulative volume of prospective and active account holders evaluated in the campaign frame. |
| **Success Customers** | 5,289 | The volume sub-segment of consumers who actively executed a regular new fixed-deposit product sign-up. |
| **Failure Customers** | 5,873 | The parsed customer group who passed the communication cycles without executing a deposit contract. |
| **Success Rate** | 47.38% | The cross-sectional campaign transaction conversion rate, mapping macro product penetration health. |
| **Average Balance** | \$1,528.54 | The historical mean balance capital held across the tracking registries. |
| **Average Duration** | 371.99 Seconds | The average processing length of a single continuous consumer connect event row. |

## 📊 Data Dictionary

The campaign analytical frameworks decode transaction patterns utilizing the following continuous and categorical database parameters:

*   **age**: Discrete demographic vector segmenting consumer age layers.
*   **job & marital**: Categorical parameters profiling active employment status and structural single/married family indicators.
*   **education**: Tiered profile dimension tracking educational fulfillment levels (Primary, Secondary, Tertiary, Unknown).
*   **balance**: Continuous capital value indexing active account cash holdings.
*   **housing & loan**: Binary financial flags marking external liability obligations, such as active real estate or personal credit lines.
*   **contact & day/month**: Logistics markers tracking individual communication pipeline routes and date timestamps.
*   **duration**: Call duration in seconds, functioning as the primary benchmark for customer interest depth.
*   **campaign**: Continuous iteration tracker counting total sequential connections pushed to an account row during the period.
*   **pdays & previous**: Interval integers capturing lag days since last campaign touch alongside total gross contact cycles.
*   **poutcome**: Nominal categorical historical anchor tracking previous campaign success metrics (Success, Failure, Other, Unknown).
*   **deposit**: The target binary parameter recording final subscription execution.

## 🛠️ Technology Stack

The data engineering and programmatic reporting ecosystem utilizes the following baseline environment configurations:

*   **Data Aggregation Matrix**: Python 3.10+ (anchored on optimized Pandas loops) & Microsoft Excel.
*   **Document Layout Compilation**: Programmatic PDF compilation orchestrated via WeasyPrint and CSS3 Print-Media style architectures.
*   **Visual Assets Suite**: High-impact repository asset charts mapped via Matplotlib and Seaborn algorithmic libraries.

## ⚙️ How to Run & Requirements

### 1. Prerequisites
Verify that a clean local installation of Python 3.10 or a higher release version is registered in your active session console variables.

### 2. Dependencies Configuration
Install the required vector computation and visualization distributions through your terminal workspace:
```bash
pip install pandas openpyxl weasyprint toolz matplotlib seaborn
```

### 3. Pipeline Execution
To ingest raw customer matrices, compute conversion rates, and automatically re-export all formatted workspace layout deliverables, run:
```bash
python generate_marketing_dashboard.py
```
