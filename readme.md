# 📊 Ookla Open Data Downloader For MOROCCO

Welcome to the **Ookla Open Data Downloader & Processor**!  
This project is a **Python Jupyter Notebook** designed to automate the retrieval, filtering, and consolidation of internet speed test data from **Ookla's Open Data hosted on AWS** — specifically tailored for **Morocco**.

---

## 📜 Overview

This repository contains a Jupyter notebook that:

1. 📥 **Downloads Ookla Open Data from AWS**  
   - **Parametrized download** — you can control:
     - 📅 The years to fetch via the `years` variable  
       *(example: `years = [2023, 2025]`)*
     - 📡 The connection types via the `ctype` variable  
       *(options: `["fixed", "mobile"]`)*

2. 🗺️ **Filters the data to include only records within Morocco**  
   - Uses **GeoPandas** and shapefiles for accurate geographic filtering.

3. 📂 **Concatenates all filtered data into a single file** for easy downstream analysis.

---

## 🐍 Python Environment Setup

To ensure compatibility and isolate dependencies, it's recommended to run this notebook inside a **Python virtual environment**.

### 📦 Create and Activate Virtual Environment

#### 🔹 Windows (CMD / PowerShell)
```Powershell
python -m venv jupyter
venv\Scripts\activate
```

```bash
python -m venv jupyter
source venv\Scripts\activate
```

### 📚 Install Requirements
Once the environment is active, install the required packages using:

```bash
pip install -r requirements.txt
```

### 🚀 Run the Notebook

To launch the notebook environment:
```bash
jupyter notebook
```
## 📑 License

This project is licensed under the MIT License

## 🙌 Acknowledgements

-   📊 Ookla Open Data Initiative 

