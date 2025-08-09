
 Features

* **Upload Dataset** – Load CSV datasets (e.g., from Kaggle).
* **Data Cleaning** – Detect and fix:

  * Inconsistent column names
  * Missing values in key columns
  * Non-numeric funding amounts
  * Invalid dates
* **Data Analysis** – Generate summaries:

  * Funding trends over time
  * Top sectors, cities, startups, and investors
  * Investment type distribution
* **Data Visualization** – Interactive charts:

  * Funding trends (line plot)
  * Top sectors, cities, startups, investors (bar charts)
  * Investment type distribution (count plot)
* **Recommendations** – Quick, pre-written insights based on data patterns.


 Requirements

Make sure you have **Python 3.7+** installed.
Install dependencies using:




 How to Run

1. Save the script as \ (or keep as).
2. Run the program:

   ```bash
  
3. Use the GUI to:

   * Upload your dataset (`Upload Kaggle Dataset`)
   * Review cleaning steps (`Show Cleaning Steps`)
   * Clean the data (`Clean Data`)
   * Analyze & visualize (`Analyze Data` / `Visualize Insights`)
   * Get recommendations 

---

## 📁 Dataset Format

The app expects a CSV file with columns like:

* **Date** – Funding date
* **Startup Name**
* **Industry Vertical**
* **City Location**
* **Investors Name**
* **Investment Type**
* **Amount in USD**

If column names differ, the app will clean and standardize them.

---

## 📸 Example Workflow

1. **Upload Dataset**
   Loads and previews data.
2. **Show Cleaning Steps**
   Highlights issues to fix.
3. **Clean Data**
   Fixes column names, missing values, invalid numbers/dates.
4. **Analyze Data**
   Displays text-based insights.
5. **Visualize Insights**
   Opens interactive charts.
6. **Recommendations**
   Displays strategic funding suggestions.
