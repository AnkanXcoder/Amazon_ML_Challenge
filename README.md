# 🔗 Business Entity Resolution

<p align="center">
  A machine learning project for matching business records across multiple noisy data sources.
</p>

<p align="center">
  🤖 Machine Learning &nbsp; • &nbsp; 🔍 Entity Matching &nbsp; • &nbsp; 🧹 Data Preprocessing
</p>

---

## 📌 Overview

This project focuses on **business entity resolution**, the process of identifying records that refer to the same real-world business across different datasets.

The data comes from multiple independent sources where business information may contain inconsistencies such as spelling variations, abbreviations, missing values, and different formatting.

The goal is to identify matching records across the sources and create reliable entity mappings.

---

## 🎯 Problem

The same business can appear differently across datasets because of:

- Typos and spelling variations
- Different capitalization
- Punctuation differences
- Address formatting
- Missing address components
- Legal suffix variations
- Alternative business names
- Inconsistent data formats

The objective is to find matching **Source 2** and **Source 3** records for each **Source 1** entity.

---

## 🔄 Matching Workflow

```text
Source Records
      ↓
Data Preprocessing
      ↓
Candidate Generation
      ↓
Similarity Features
      ↓
Entity Matching
      ↓
Match / No Match
      ↓
Final Entity Mapping
```

---

## 🧠 Key Components

### 🧹 Data Preprocessing

Clean and standardize business information before matching.

Examples:

- Text normalization
- Case normalization
- Punctuation removal
- Missing value handling
- Address standardization

### 🔎 Candidate Generation

Reduce the number of possible comparisons by generating a smaller set of likely candidates.

### 📊 Similarity Features

Compare business records using attributes such as:

- Business name
- Address
- City
- State
- Other available entity attributes

### 🤖 Entity Matching

Use similarity-based and machine learning approaches to determine whether two records represent the same business.

### 📋 Final Mapping

Generate the final matched records between the source datasets.

---

## 📂 Project Structure

```text
business-entity-resolution/
│
├── 📁 notebooks/
│   └── data preprocessing and analysis notebooks
│
├── 📁 student_resource/
│   └── processed ML-ready datasets
│
├── 📄 matching_results.tsv
├── 📦 RunTime_Error_Final_Code.zip
├── 📄 README.md
├── 📄 .gitignore
└── 📄 .gitattributes
```

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

---

## 📊 Dataset

The project works with multiple independent business datasets containing noisy and inconsistent entity information.

The main challenge is to determine which records across the datasets refer to the **same underlying business entity**.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/AnkanXcoder/business-entity-resolution.git
```

### 2. Navigate to the project

```bash
cd business-entity-resolution
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebooks

Open the notebooks inside the `notebooks/` directory using **Jupyter Notebook, VS Code, or Google Colab**.

---

## 📈 Project Output

The project produces:

- Processed ML-ready datasets
- Candidate matching results
- Entity similarity information
- Final business record mappings

The matching results are stored in:

```text
matching_results.tsv
```

---

## 💡 What I Practiced

- Data preprocessing
- Text normalization
- Entity resolution
- Record linkage
- Candidate generation
- Feature engineering
- Similarity-based matching
- Machine learning workflow
- Handling noisy real-world data
- Git and GitHub

---

## 🎯 Project Goal

The goal is to build a reliable pipeline that can transform inconsistent business records into a structured set of **matched real-world entities**.

Entity resolution is useful in areas such as:

- Customer data integration
- Business databases
- Data deduplication
- Master data management
- Fraud detection
- Data consolidation

---

## 👨‍💻 Author

### Ankan Sen

**B.Tech Computer Science & Engineering Student**

Interested in:

- 📊 Data Science
- 🤖 Machine Learning
- 📈 Data Analytics
- 🐍 Python
- 🗄️ SQL

<p align="center">
  <a href="https://github.com/AnkanXcoder">
    <img src="https://img.shields.io/badge/GitHub-AnkanXcoder-black?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/ankan-sen-2725b9325">
    <img src="https://img.shields.io/badge/LinkedIn-Ankan%20Sen-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
</p>

---

<p align="center">
  Built with 🐍 Python • 🤖 Machine Learning • 🔍 Entity Resolution
</p>
