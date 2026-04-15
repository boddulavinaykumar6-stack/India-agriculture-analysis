# India Agriculture Crop Production Analysis

## Overview

This project performs **Exploratory Data Analysis (EDA)** on an Indian agriculture dataset containing crop production information across states, districts, and years.

The analysis focuses on understanding crop production trends, identifying top producing states, and exploring the distribution of crops across India.

---

## Dataset

The dataset contains agricultural production data with the following columns:

* **State** – State where the crop is grown
* **District** – District within the state
* **Crop** – Type of crop
* **Year** – Agricultural year
* **Season** – Crop season (Kharif, Rabi, Whole Year, etc.)
* **Area** – Cultivated area
* **Area Units** – Measurement unit of area
* **Production** – Total crop production
* **Production Units** – Unit of production (Tonnes, Nuts, Bales)
* **Yield** – Crop yield

---

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Cleaning

The following preprocessing steps were performed:

* Checked dataset structure using `info()` and `shape`
* Identified missing values
* Removed rows containing missing values
* Standardized production units into a single column (**New Production**)

---

## Key Analysis Performed

### Top 5 Most Common Crops

Using `value_counts()` to identify frequently grown crops in the dataset.

### State-wise Crop Production

Calculated total crop production for each state to determine which state produces the most crops.

### Highest Rice Producing States

Filtered the dataset for **Rice** and calculated production totals for each state.

### Yearly Crop Production

Analyzed total production across different agricultural years to identify peak production years.

---

## Key Insights

Some insights obtained from the analysis:

* **Rice** is the most frequently recorded crop in the dataset.
* **Uttar Pradesh** shows the highest total crop production.
* **West Bengal** is the leading producer of rice.
* Recent agricultural years show higher production compared to earlier years.

---

## Project Structure

```
india-agriculture-analysis
│
├── agriculture_analysis.ipynb
├── README.md
└── dataset (optional)
```

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/india-agriculture-analysis.git
```

2. Install required libraries

```
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook

```
jupyter notebook agriculture_analysis.ipynb
```

---

## Author

Boddula Vinay kumar
