# 📊 Livestock Statistics Visualization — Kazakhstan 2024

This project presents a Python-based data analysis and visualization pipeline focused on livestock development indicators in Kazakhstan for the year 2024. The goal is to extract, clean, and visualize data from a structured Excel dataset using widely adopted Python libraries. The visualizations include both histogram and bar chart representations for clearer interpretation of trends across different livestock categories.


# 📁 Project Overview

- **Data source**: Official statistical data on livestock from Kazakhstan, 2024. URL:https://stat.gov.kz/ru/industries/business-statistics/stat-forrest-village-hunt-fish/spreadsheets/?year=&name=18612&period=&type= 
- **File format**: Excel (`.xlsx`)
- **Sheet used**: `"1."` (skipping the first 5 header rows)
- **Main focus**:
  - Total number of livestock by category (`All_2024`)
  - Visual representation of top categories for comparison
- **Tools used**: `pandas`, `matplotlib`, `openpyxl`
![Снимок экрана 2025-04-23 035026](https://github.com/user-attachments/assets/56735d72-f3f9-457e-96ce-6272783e698d)
- **Basic inspection** was performed to understand the structure of the dataset:
df.head()
df.info()
df.describe()
df.dropna()
df.isnull().sum()
df_clean() 
![Снимок экрана 2025-04-23 035724](https://github.com/user-attachments/assets/d8f69743-f2b9-4ab5-8768-2775e6b578c0)
![Снимок экрана 2025-04-23 035746](https://github.com/user-attachments/assets/cf5bfdc7-07fb-4968-8032-4f9bd2d8bde7)
![Снимок экрана 2025-04-23 035805](https://github.com/user-attachments/assets/caaf4cff-a34d-4201-8e58-78050812db71)

# 📈 Key Features
- Loads and processes structured Excel data using `pandas`
- Cleans missing or placeholder values
- Generates two visualizations:
  - 📉 Histogram of total livestock across the top 10 categories
    ![Снимок экрана 2025-04-23 035937](https://github.com/user-attachments/assets/5868563c-6c73-4c46-a3f5-bd358803efe4)

  - 📊 Horizontal bar chart comparing categories by total livestock count
    ![Снимок экрана 2025-04-23 040001](https://github.com/user-attachments/assets/e161bee6-5170-43cc-a217-961800136c3f)

