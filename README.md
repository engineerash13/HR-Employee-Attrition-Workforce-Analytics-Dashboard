# HR Employee Attrition & Workforce Analytics Dashboard

A Power BI dashboard analyzing HR employee data to uncover workforce composition, attrition patterns, performance distribution, and compensation insights — enabling data-driven HR decision-making.

**Author:** Ashwin Suryawanshi | **Tool:** Power BI Desktop

---

## Files in This Repository

| File | Description |
|------|-------------|
| `HR_Employee_Data_Analysis.pbix` | Power BI dashboard — 8 KPI cards, 6 charts across 1 page |

---

## Tools & Technologies

- **Power BI Desktop** — KPI cards, donut chart, pie chart, clustered bar charts, clustered column chart, slicers
- **Data Source:** `HR-emp-attrition dataset`

---

## Dataset

**Source:** HR Employee Attrition Dataset

| Column | Description |
|--------|-------------|
| `Department` | Employee department |
| `Gender` | Male / Female |
| `JobRole` | Employee job title |
| `OverTime` | Whether employee works overtime (Yes/No) |
| `Attrition` | Whether employee left the company (Yes/No) |
| `BusinessTravel` | Travel frequency (Non-Travel, Travel Rarely, Travel Frequently) |
| `Job Review` | Performance/job review rating |
| `Best/Bottom Performers` | Performance classification |
| `HourlyRate` | Employee hourly rate |
| `Emp With Current Manager` | Tenure with current manager (years) |
| `Total Employees` | Calculated measure — total headcount |
| `Total Male` / `Total Female` | Gender count measures |
| `% Total Male` / `% Total Female` | Gender percentage measures |

---

## Dashboard — Page 1

### KPI Cards (8)

| Card | Metric |
|------|--------|
| Total Employees | Overall headcount |
| Total Male | Count of male employees |
| Total Female | Count of female employees |
| Total Male Percentage | % male workforce |
| Total Female Percentage | % female workforce |
| Single | Count of single employees |
| Married | Count of married employees |
| Divorced | Count of divorced employees |
| Avg Hourly Rate | Average employee hourly rate |
| Employees Working With Current Manager Since 5 Years | Tenure loyalty metric |

### Charts (6)

| Visual | Type | Axis | Insight |
|--------|------|------|---------|
| Employees by Department & Gender | Donut Chart | Department (category), Gender (series), Total Employees | Gender distribution across departments |
| Overtime Distribution | Pie Chart | OverTime, Total Employees | Share of employees working overtime vs not |
| Employees by Job Review | Clustered Bar | Job Review, Total Employees | Performance review rating distribution |
| Best vs Bottom Performers | Clustered Bar | Best/Bottom Performers, Total Employees | Top vs low performer headcount split |
| Business Travel Frequency | Column Chart | BusinessTravel, Total Employees | Travel category breakdown across workforce |
| Attrition Count | Clustered Bar | Attrition (Yes/No), Total Employees | Employees who left vs retained |
| Employees by Job Role | Clustered Column | JobRole, Total Employees | Headcount distribution across all roles |

---

## Key Insights Enabled

- **Gender balance** — male/female KPI cards and % measures give instant workforce diversity view
- **Attrition flag** — bar chart directly shows how many employees left vs stayed
- **Performance split** — best vs bottom performer chart identifies talent concentration
- **Overtime risk** — pie chart highlights what proportion of staff are working overtime (burnout risk indicator)
- **Manager loyalty** — employees with 5+ years under same manager signals stable team relationships
- **Travel burden** — business travel column chart flags high-travel segments for wellbeing policies

---

## Suggested Repo Name

`HR-Employee-Attrition-Analytics-PowerBI`

---

## Topics

`power-bi` `hr-analytics` `employee-attrition` `workforce-analysis` `data-visualization` `business-intelligence` `kpi-dashboard`
