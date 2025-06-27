# 📊 Employee Log Extractor — Flask Web App

A powerful, intuitive, and professional-grade **log processing and report generation system** built with Python and Flask.  
This application enables HR/admin staff to upload multiple attendance log files (CSV), extract logs for one or more employees, and generate **beautiful, export-ready reports** in Excel, CSV, or HTML — all in seconds.

> 🚀 Designed for performance. Built for professionals. Perfect for institutional workflows.

---

## 🎯 Use Case

- 🏥 Hospitals, 🏫 Schools, 🏢 Offices — anywhere attendance logs or biometric exports are used.
- Upload `.csv` logs from biometric machines.
- Select employees by **name or ID**.
- Export professionally formatted **Excel reports** with individual employee sheets.
- Download print-ready **HTML and CSV** files.

---

## 🌟 Key Features

| Feature                             | Description                                                                 |
|-------------------------------------|-----------------------------------------------------------------------------|
| 📂 Upload Support                   | Accepts multiple `.csv` log files in one go                                 |
| 👨‍💼 Multi-Employee Extraction       | Search and extract logs for **multiple employees** simultaneously           |
| 📅 Month Detection                  | Auto-detects month and formats filenames accordingly                        |
| 📤 Export to Excel, CSV, HTML       | Generates clean, professional reports ready to download and share          |
| 📑 Excel with Multiple Sheets       | One sheet per employee, properly styled for official use                   |
| 🎨 Stylish Printable HTML           | View data in the browser in a clear, readable layout                        |
| 🔍 Real-time Logs & Messages        | Displays internal log summary on the results screen                         |
| ⚙️ Encoding Compatibility           | Supports UTF-8, ISO-8859-1, and auto fallback for log file decoding         |

---

## 🖼️ Screenshot
![image](https://github.com/user-attachments/assets/3dc4fdce-1069-4517-902d-ad22f313706a)


---

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Data Processing:** Pandas, CSV, OpenPyXL
- **Export:** XLSX, CSV, HTML
- **Frontend:** HTML, Jinja2 Templates, Bootstrap
- **Styling:** Excel formatting with borders, bold headers, alternating row colors

---
## 📦 Output Example

### ✅ Excel Report
- One workbook with multiple sheets  
- Each sheet = 1 employee  
- Styled headers, auto column widths, clean layout

### ✅ HTML Output
- Browser-rendered results  
- Downloadable and printable

### ✅ CSV Output
- Clean, structured logs per employee

---

## 🔐 Security Notes

- Internal-use only; no authentication  
- Can be extended with Flask-Login, rate limiting, or upload filtering

---

## 🚧 Future Enhancements

- 🔒 Add login for staff-only access  
- 🖨️ One-click bulk report printing  
- 📤 Cloud file upload/download support  
- 🌐 Multi-language support (EN, UR, AR)

---

## 🧪 Sample CSV Template

| Date       | Time     | Name           | ID        | Status   |
|------------|----------|----------------|-----------|----------|
| 2025-02-01 | 08:15 AM | Abdul Rafeek   | 35592423 | Present  |
| 2025-02-01 | 08:30 AM | Dr. Zainab     | 33559324  | Late     |

---



## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/Itzmirofficial/log-extractor-flask.git
cd log-extractor-flask
```

### 2. Create Virtual Environment

python -m venv venv
venv\Scripts\activate   # On Windows

### 3. Install Requirements

pip install -r requirements.txt

### 4. Run the Flask App

python app.py

Visit: http://localhost:5000


