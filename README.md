# RUC SYSTEM.


A Django web application uploads a txt file, reads it and sorts it using sorting algorithms, and also provides a PDF report.


## ✨ Main features

This project demonstrates the use of Django business functions: 1. Customer CRUD operations. 2. Coordinate storage (Lat/Lon). 3. Interactive map display. 4. Direct link to Google Maps.

* **Secure File Upload:** It allows the uploading of delimited text files (CSV, TXT).
* **Intelligent Processing:** Use the Pandas library to read files with variable delimiters (| or tab \t), clean data (dropna) and load them into the database.
* **Algorithmic Implementation:** It shows the implementation of sorting algorithms such as TimSort and Quicksort on the loaded data.
* **PDF Report Generation:** Create dynamic, formatted PDF reports using the ReportLab library, ready to download.
* **Load History:** It keeps a record of uploaded files (name and number of records).



## 🛠️ Technologies Used

* **Language:** Python 3.12.3
* **Framework Web:** **Django**



---

## 🚀 Installation and Start-up


### 1. Clone the Repository

```bash
git clone <URL of your repository on GitHub>
cd weather_project




# Create the virtual environment
python3 -m venv env

# Activate the virtual environment
# In Linux/macOS:
source env/bin/activate
# In Windows (CMD):
# .\env\Scripts\activate
