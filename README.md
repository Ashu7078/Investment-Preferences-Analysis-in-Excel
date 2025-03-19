# Investment Preferences Analysis in Excel

## Overview

This project analyzes participants' investment preferences, including the distribution of investments across different avenues and the reasons behind their choices. The analysis is performed using **Excel Pivot Tables** and **Charts** to create a visual representation of the data.

## Files Included

- **Investment\_Analysis.xlsx** - Contains all Pivot Tables, Charts, and summarized data.
- **Data\_set 2.csv** - The original dataset containing participant responses.
- **README.md** - This guide explaining how to perform the analysis.

## Steps to Perform Analysis

### **Step 1: Load Data into Excel**

1. Open **Microsoft Excel**.
2. Click **File → Open → Browse**.
3. Select `Data_set 2.csv` and click **Open**.
4. Ensure the data is correctly formatted and saved as an **Excel Workbook (.xlsx)**.

### **Step 2: Summarize Investment Avenues Using a Pivot Table**

1. Select the dataset (Press **`Ctrl + A`**).
2. Go to **Insert → PivotTable**.
3. Select **New Worksheet** and click **OK**.
4. In the PivotTable Fields panel:
   - Drag **Investment\_Avenue** to the **Rows** area.
   - Drag **Investment\_Avenue** again to the **Values** area and select **Count**.
5. The Pivot Table now displays the count of participants choosing each investment type.

### **Step 3: Create a Bar Chart for Investment Distribution**

1. Select the PivotTable data.
2. Go to **Insert → Column Chart → Clustered Column Chart**.
3. Customize the chart:
   - Add a **Title**: "Investment Preferences Distribution".
   - Label **X-Axis** (Investment Avenues) and **Y-Axis** (Number of Participants).
   - Adjust colors and fonts for better clarity.

### **Step 4: Summarize Reasons for Investment Choices Using Pivot Tables**

1. Insert a new **PivotTable**.
2. Drag **Investment Type** (Equity, Mutual Funds, etc.) to the **Columns** area.
3. Drag **Reason for Investment** (Capital Appreciation, Tax Benefits, etc.) to the **Rows** area.
4. Drag **Reason for Investment** again to the **Values** area and set it to **Count**.

### **Step 5: Create a Stacked Bar Chart for Investment Reasons**

1. Select the summarized PivotTable data.
2. Go to **Insert → Bar Chart → Stacked Column Chart**.
3. Customize the chart:
   - Add a **Title**: "Reasons for Investment Choices".
   - Label **X-Axis** (Investment Reasons) and **Y-Axis** (Number of Participants).
   - Add a **Legend** to differentiate investment types.

### **Step 6: Customize Charts for Better Presentation**

- Apply a **Chart Style** from the **Design Tab**.
- Add **Gridlines** for clarity.
- Enable **Data Labels** to display exact values.
- Resize and adjust the charts for better visibility.

### **Step 7: Save the Excel File**

1. Click **File → Save As**.
2. Choose **Excel Workbook (.xlsx)**.
3. Name the file **Investment\_Analysis.xlsx** and click **Save**.

## Final Output

✅ **Investment Preferences Summary (Pivot Table)**  
✅ **Investment Distribution (Bar Chart)**  
✅ **Reasons for Investment Choices (Pivot Table)**  
✅ **Stacked Bar Chart for Investment Reasons**  

This file is now ready for **presentation and reporting**. 🚀

---

## Additional Notes

- Ensure that your **column headers** are correct before creating Pivot Tables.
- You can modify **chart colors, labels, and sizes** to match your presentation style.
- If you need to update the data, **refresh the Pivot Tables** by right-clicking and selecting **Refresh**.

For any questions, feel free to reach out! 😊

---

## Author
**Ashish**

