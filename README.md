# Utilization (Unused Days) Report
Healthcare service utilization report (with anonymized/dummy data for privacy). The dashboard tracks Unused insurance authorizations across treatment facilities with a focus on Against Treatment Advice (ATA) discharges - a key performance indicator in treatment settings.

This Excel-based dashboard tracks unused bed days across behavioral health facilities, with a special focus on *Against Treatment Advice (ATA)* discharges. The tool was built to help clinical and operational leaders visualize patient retention trends, measure facility-level performance, and inform resource allocation.

## 🔧 Tools Used

- Microsoft Excel
- Power Query (ETL + data prep)
- Pivot Tables & Pivot Charts
- Data Validation & Slicers
- Stacked Bar, Combo, and Scatter Plot Charts
- Conditional Formatting & Named Ranges

## 📊 Key Features

- **ATA Rate Tracking:** Measures the rate of ATA discharges over time, by facility, and by clinician
- **Month-over-Month Trends:** Stacked bar chart clearly breaks out ATA vs. non-ATA unused days and shows trends month-to-month
- **Capacity-Normalized Scatter Plot:** Shows ATA rate vs. average daily census *adjusted for facility size*
- **Dynamic Filtering:** Slicers enable filtering by facility and month; data validation dropdowns allow filtering by clinician and insurance provider
- **Clean Anonymized Dataset:** Facility names, clinicians, and sensitive data replaced with fictional or coded values (e.g., “Everlake Recovery Center”)

## 🔍 Insights Generated

- Identified **March** as a performance outlier, with unusually high ATA rates
- Highlighted which facilities had low census (relative to capacity) but also high ATA discharges
- Opened new pathways for quality improvement: reinforcing our ATA block protocol, reviewing patient satisfaction data to identify gaps in engagement, and tailoring training based on facility-specific trends.
- Tool can support future analysis of **clinician-level retention** and **payer-driven authorization lengths vs. revenue impact** — opening the door for deeper insights into retention patterns and reimbursement alignment. For example, we’ll be able to assess the profitability of certain insurers or which clinicians have higher retention outcomes.

## 🧭 How to Use

- Open the Excel file
- Use slicers/lists to explore data by **facility** and **month**
- Use data validation dropdowns to filter by **primary counselor** or **insurance company**
- View stacked bar charts and trend lines for ATA vs. total unused days
- When adding new data, the formulas in the "Data Prep" worksheet will update, including the ability select the newly added month from the data validation list.
- Once new data has been added, refresh the Power Query data model to automatically update the monthly trend chart. 

> This version is fully anonymized for portfolio purposes.

---

## 🤝 Author

Built by Dan Hutcheson, a behavioral health professional and software developer passionate about creating tools that improve clinical decision-making and operational efficiency.

