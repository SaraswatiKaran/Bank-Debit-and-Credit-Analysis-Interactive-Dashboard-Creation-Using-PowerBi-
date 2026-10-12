# Bank-Debit-and-Credit-Analysis (Interactive-Dashboard-Creation-Using-PowerBi)
## Project Objective
Bank Debit and Credit Analysis Dashboard 📊: An interactive Power BI dashboard tracking 127M+ in transaction volumes. It monitors cash flows, account activity ratios, and high-risk flags across banking branches. Features dynamic monthly trends, waterfall charts for transaction growth rates, and slice-and-dice data filtering by branch, risk, or month.

## Dataset Used:
-<a href="https://github.com/SaraswatiKaran/Bank-Debit-and-Credit-Analysis-Interactive-Dashboard-Creation-Using-PowerBi-/blob/main/bank_Credit%26Debitanalysis_dataset.xlsx">Dataset<a/>

## Questions (KPIs)

- Compare the total credit and debit volumes using single or combined charts.
- Which month experienced the highest transaction volumes and spikes?
- What is the overall Account Activity Ratio and Credit to Debit Ratio across the system?
- What percentage of total transactions are flagged as high risk?
- List the top performing branches contributing to total transaction volumes.
- Relation between monthly trends and branch transaction growth rates.
- Which banking entity (e.g., HDFC, Axis, SBI) is contributing maximum to the transaction volume?
- What is the distribution of transaction types across different secure and high-risk flags?

-Dashboard Interaction <a href="https://github.com/SaraswatiKaran/Bank-Debit-and-Credit-Analysis-Interactive-Dashboard-Creation-Using-PowerBi-/blob/main/powerbi_projectgithub.png">View Dashboard</a>

## Data Analysis Process:

### 1. Data Cleaning & Transformation (ETL):
*   **Data Ingestion:** Imported the raw banking transaction dataset into Power BI Desktop.
*   **Data Type Formatting:** Verified and corrected data types for timestamps, financial values (debits/credits), and branch attributes.
*   **Handling Nulls & Anomalies:** Cleansed missing values and handled irregularities in transaction logs.
*   **Conditional Columns:** Created custom flags for categorization, including the `High Risk Transaction Flag`.

### 2. Data Modeling & DAX Measures:
*   **Data Modeling:** Established relationships between transaction logs, branch directories, and chronological calendars.
*   **Key Measures Created:** Developed explicit DAX measures to calculate system health baselines:
    *   *Total Debit/Credit Volume* using `SUM()`.
    *   *Account Activity Ratio* and *Credit to Debit Ratio* using safe mathematical division via `DIVIDE()`.

### 3. Data Visualization & Dashboard Design:
*   **KPI Cards:** Placed high-level cards at the top for quick visibility into critical metrics (Total Volume, Activity Ratios).
*   **Trend Tracking:** Integrated a line chart to map monthly financial volumes and identify transaction spikes.
*   **Performance Rankings:** Designed bar charts to rank physical branches by volume and waterfall charts to visualize localized month-over-month growth.
*   **Risk Segmentation:** Utilized a clean pie chart distribution to isolate safe transactions from fraudulent anomalies.
*   **User Interactivity:** Added interactive slicers for Month, Risk Flag, Transaction Type, and Branch to let users slice and dice the data dynamically.

## Dashboard:
<img width="960" height="480" alt="powerbi_projectgithub" src="https://github.com/user-attachments/assets/32bf98ab-30c4-4056-b315-9b9daf10a1d3" />

