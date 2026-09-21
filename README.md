# 🧹 File_Convertor - Data Sweeper (CSV & Excel)

A clean and interactive Streamlit web application that allows you to transform, clean, visualize, and convert your data between **CSV** and **Excel** formats seamlessly.

---

## 🚀 Features

- **File Upload:** Upload single or multiple files in `.csv` or `.xlsx` format.
- **Data Preview:** View file details (name, size in KB) and quick preview of data headers.
- **Data Cleaning:**
  - Remove duplicate rows with a single click.
  - Automatically fill missing numerical values with column means.
- **Column Selection:** Choose specific columns to keep or export.
- **Data Visualization:** Quick bar chart representation for numeric columns.
- **File Conversion & Download:** Convert files seamlessly between CSV and Excel formats and download them instantly.

---

## 🛠️ Installation & Setup

1. **Clone this repository:**
   ```bash
   git clone https://github.com/sajjadsahil015/File_Convertor.git
   cd File_Convertor
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit application:**
   ```bash
   streamlit run app.py
   ```

---

## 📦 Tech Stack

- **Python 3.10+**
- **Streamlit** (Web Interface)
- **Pandas** (Data Manipulation & Cleaning)
- **OpenPyXL** (Excel File Processing)
