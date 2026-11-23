# Diabetes Patient Readmission and Hospital Care Analytics

Excel and Power BI project analysing **hospital readmission** in diabetes patients, using the [Diabetes 130-US Hospitals (1999-2008)](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008) dataset from UCI.

## What it does
- **Cleaned** 101,766 hospital records in Excel down to **69,989** (one encounter per patient, expired/hospice and invalid rows removed).
- **Modelled** the data in Power BI as a star schema with fact and dimension tables.
- **Built** calculated columns and DAX measures inside the report.
- **Delivered** a 4-page interactive report: Overview, Risk factors, Care pathway, Medications, with slicers, bookmarks, drill-down and a drill-through page.

## Key findings
- **9.0%** of patients were readmitted within 30 days.
- Risk rises with age (6.2% under 30 to 10.6% at 80+) and with earlier hospital stays (8.1% with none, 26.5% with three or more).
- Patients sent home had a 6.9% rate, against about 15% for nursing/rehab facilities and hospital transfers.
- Results show associations, not causes.

## Files
| File | Description |
|---|---|
| `Diabetes Readmission and Hospital Care Analytics.pbix` | Power BI report (open in Power BI Desktop) |
| `Power BI report PDF .pdf` | PDF export of all four dashboards, viewable without Power BI |
| `Data_Cleaning_and_Pre_Processing.xlsx` | Cleaned dataset with fact and dimension tables, with Raw Data and IDS mapping |

## Tools
Excel, Power Query, Power BI, DAX

## Author
Amita Maria Abraham, [GitHub](https://github.com/amita-abraham)
