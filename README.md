# 📌 GCDC - Graph-based Court Decision Clustering  

**GCDC** is a project focused on **clustering court decisions** using graph-based techniques. The repository contains data processing scripts and machine learning models to analyze and group legal texts.

## 🚀 Features
- **Graph-based clustering** of court decisions.
- **Text analysis** using key term extraction.
- **Pre-processed datasets** for further analysis.
- **Jupyter Notebook (`main.ipynb`)** with code implementation.

## 📁 Project Structure
- **`README.md`** – Project documentation  
- **`cd2LFs_crimLaw_Others_5k.json`** – Pre-processed legal data (JSON format)  
- **`main.ipynb`** – Jupyter Notebook with clustering implementation  
- **`requirements.txt`** – Dependencies and required libraries  
- **`top_k_terms_per_doc_scored_filtered.json`** – Key terms extracted from documents  

## 📊 Dataset Overview
- **`cd2LFs_crimLaw_Others_5k.json`**: Contains 5,000 legal documents classified under criminal law and other categories.
- **`top_k_terms_per_doc_scored_filtered.json`**: Contains the most relevant terms extracted from each document, ranked by importance.

## ⚙️ Installation
It is recommended to create a **separate virtual environment** before installing dependencies to avoid conflicts.

### 1️⃣ Create and activate a virtual environment:

**For Windows (CMD/PowerShell):**
```bash
python -m venv venv
venv\Scripts\activate
```

**For macOS/Linux**:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run Jupyter Notebook:
```bash
jupyter notebook main.ipynb
```

## 📌 Usage
Run the Jupyter Notebook to explore and analyze the dataset:
```bash
jupyter notebook main.ipynb
```

## 📜 License
This project is open-source. Feel free to contribute and improve it!

