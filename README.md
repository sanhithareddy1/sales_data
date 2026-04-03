# Walmart Sales Data Analysis

## 📌 Overview
This project is an end-to-end data analysis solution designed to extract meaningful business insights from Walmart sales data. It demonstrates the complete data workflow—from data ingestion and cleaning to SQL-based analysis and business problem-solving.

The project leverages Python for data processing, SQL (MySQL & PostgreSQL) for querying, and structured analytical techniques to answer key business questions. It is ideal for aspiring data analysts aiming to strengthen their skills in data manipulation, SQL, and building data pipelines.

---

## 🚀 Project Workflow

### 1. Set Up the Environment
**Tools Used:** Visual Studio Code (VS Code), Python, MySQL, PostgreSQL  
**Goal:** Create a structured workspace and organize project folders for efficient development.

---

### 2. Set Up Kaggle API
- Download your Kaggle API token (`kaggle.json`) from your Kaggle account settings
- Place it in the `.kaggle/` directory
- Use the command:
```
kaggle datasets download -d <dataset-path>
```

---

### 3. Download Walmart Sales Data
- Source: Kaggle
- Store dataset inside the `data/` folder

---

### 4. Install Required Libraries & Load Data
Install dependencies:
```
pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
```

Load dataset into Pandas DataFrame for processing.

---

### 5. Exploratory Data Analysis (EDA)
- Understand dataset structure
- Inspect column types and distributions
- Use:
```
df.info()
df.describe()
df.head()
```

---

### 6. Data Cleaning
- Remove duplicate records
- Handle missing values (drop/fill appropriately)
- Fix inconsistent data types
- Format currency values
- Validate cleaned dataset

---

### 7. Feature Engineering
- Create new column:
```
Total_Amount = unit_price * quantity
```
- Enhances downstream SQL analysis

---

### 8. Load Data into Databases
- Connect to MySQL & PostgreSQL using SQLAlchemy
- Automatically create tables
- Insert cleaned data into both databases
- Verify data using SQL queries

---

### 9. SQL Analysis & Business Insights
Solve real-world business problems using SQL:
- Revenue trends by branch and category
- Best-selling product categories
- Sales performance by city, time, and payment method
- Peak sales periods
- Customer buying patterns
- Profit margin analysis

---

### 10. Project Documentation & Publishing
Include:
- README.md (this file)
- Jupyter Notebooks (if used)
- SQL scripts
- Dataset or instructions to access it

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- SQLAlchemy
- MySQL
- PostgreSQL
- Kaggle API
- VS Code

---

## 📂 Project Structure
```
walmart-sales-analysis/
│
├── data/                # Raw dataset
├── notebooks/           # Jupyter notebooks
├── scripts/             # Data processing scripts
├── sql/                 # SQL query files
├── outputs/             # Results and insights
└── README.md            # Project documentation
```

---

## ⚙️ Requirements
- Python 3.8+
- MySQL
- PostgreSQL
- Kaggle API Key

### Python Libraries:
- pandas
- numpy
- sqlalchemy
- mysql-connector-python
- psycopg2

---

## ▶️ Getting Started

Clone the repository:
```
git clone <repo-url>
```

Install dependencies:
```
pip install -r requirements.txt
```

Set up Kaggle API, download dataset, and follow the workflow steps to run the project.

---

## 🎯 Key Outcomes
- Built a complete data analysis pipeline
- Strengthened SQL querying skills
- Generated actionable business insights
- Gained hands-on experience with real-world datasets

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 👩‍💻 Author
Sanhitha Reddy

