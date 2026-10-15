# Customer Sales & Analytics Dashboard

## 1. Project Overview
This project analyzes customer demographics, monthly income, locations, customer types, departments, and purchasing behavior. It combines data cleaning, exploratory data analysis (EDA), and dashboard visualization to identify useful business insights.

## 2. Problem Statement
Businesses need to understand their customers, where customers are located, and how purchasing behavior differs across departments and customer groups. This project uses data analytics techniques to prepare the dataset, explore patterns, and present findings that can support business decisions.

## 3. Dataset Information
- **Dataset:** Customer Analytics Dataset
- **Records:** 1,000
- **Columns:** 12

| Column | Description |
|---|---|
| `Customer_ID` | Customer identifier |
| `Name` | Customer name |
| `Age` | Customer age |
| `Gender` | Gender category |
| `Department` | Department/category |
| `Monthly_Income` | Monthly income |
| `City` | Customer city |
| `Customer_Type` | Customer segment/type |
| `Latitude` | Latitude coordinate |
| `Longitude` | Longitude coordinate |
| `Purchase_Amount` | Purchase amount |
| `Feedback` | Customer feedback |

**Privacy note:** Before making the repository public, check that you are allowed to share the dataset and that it contains no personal or sensitive information that should not be published.

## 4. Tools and Technologies
- Python
- Pandas and NumPy
- Jupyter Notebook
- Power BI
- Microsoft Excel (if used)
- GitHub

## 5. Data Cleaning Process
The data-cleaning workflow includes:
1. Inspecting dataset shape, column names, data types, and sample records.
2. Checking missing values and duplicate rows.
3. Standardizing column names and text/category values.
4. Converting numeric columns such as `Age`, `Monthly_Income`, `Latitude`, `Longitude`, and `Purchase_Amount` to suitable data types.
5. Handling missing values with an appropriate method, such as the median for numeric fields and the mode for categorical fields, where suitable.
6. Removing records confirmed to be duplicates.
7. Validating the cleaned dataset and exporting it for EDA and dashboard creation.

The cleaned dataset was previously reported to have **1,000 records, no missing values, and no duplicate rows**. Re-run the notebook to verify these results if the source data changes.

## 6. Exploratory Data Analysis (EDA)
The analysis covers:
- Customer count by city
- Total purchase amount by department
- Customer type distribution
- Average monthly income by department
- Customer age distribution
- Key metrics such as total customers, total purchase amount, average purchase amount, and average monthly income

## 7. Dashboard
### KPI Cards
- Total Customers
- Total Purchase Amount
- Average Purchase Amount
- Average Monthly Income

### Recommended Visuals
- Customers by City
- Purchase Amount by Department
- Customer Type Distribution
- Average Income by Department
- Age Distribution

### Recommended Filters / Slicers
- City
- Gender
- Department
- Customer Type

## 8. Key Business Insights
The following findings were observed in the current analysis. Validate them against the final dataset before submission:
- Ahmednagar had the highest customer count.
- Operations had the highest total purchase amount.
- Regular customers were the largest customer-type group.
- Marketing had the highest average monthly income.

## 9. Business Recommendations
- Focus customer engagement campaigns on cities with high customer counts.
- Consider loyalty and retention campaigns for the largest customer segment.
- Compare purchase totals by department to identify opportunities and investigate unusual results.
- Study income and purchase behavior across customer segments before designing targeted offers.
- Refresh the dashboard regularly so stakeholders can monitor key indicators.

## 10. Project Structure
Adjust these filenames to match the files you actually upload.

```text
Final-Data-Analytics-Project/
├── README.md
├── raw_dataset.csv
├── cleaned_customer_dataset.csv
├── data_cleaning.ipynb
├── EDA_analysis.ipynb
├── Customer_Analytics_Dashboard.pbix
└── dashboard_screenshot.png
```

If you created the dashboard in Excel rather than Power BI, include the Excel workbook and update the filename above.

## 11. How to Run
1. Download or clone this repository.
2. Install the Python libraries used by your notebooks:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run `data_cleaning.ipynb`.
5. Run `EDA_analysis.ipynb` using the cleaned dataset.
6. Open the `.pbix` file in Power BI Desktop, or open the Excel dashboard workbook if Excel was used.

## 12. Conclusion
This project demonstrates an end-to-end analytics workflow: understanding and cleaning data, validating data quality, exploring customer and purchase patterns, and presenting results in a dashboard. The analysis can support customer segmentation, marketing planning, and department-level decision-making.

## 13. Author
**Pravin Chavan**  
B.Sc. Computer Science | Aspiring Data Analyst

---

**Before submitting:** Ensure that the filenames match your repository, validate the reported insights, and add your GitHub or LinkedIn links only after you have created the repository and published the post.
