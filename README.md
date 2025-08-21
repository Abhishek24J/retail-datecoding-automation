# retail-datecoding-automation

A Python automation script that processes raw retail scan data to identify products nearing expiry and generates structured, print-ready Excel reports. 

Previously, staff had to scan every single perishable item daily and mark them down manually. With this solution, only one weekly scan is needed, producing organized reports that staff can use to markdown expiring products—reducing labor, improving accuracy, and significantly cutting wastage costs.

---

## ✨ Features
- Renames columns for consistency (`Talker Count` → `Date`)
- Cleans and sorts data by **Commodity Name → Date**
- Inserts blank rows for readability between commodity groups
- Adds `Today / Tomorrow / Gone` placeholders
- Auto-adjusts Excel column widths
- Creates a styled Excel table for easy analysis, ready to print

---

## 🛠 Tech Stack
- Python  
- Pandas  
- OpenPyXL  

---

## 📂 Project Files
- `Datecoding_retail.py` → main automation script  
- `requirements.txt` → dependencies  
- `Datecoding_Input.xlsx` → sample raw input  
- `Datecoding_Output.xlsx` → sample processed output  

---

## ⚙️ Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/Abhishek24J/retail-datecoding-automation.git
cd retail-datecoding-automation
pip install -r requirements.txt
```

---

## 🚀 Usage

Run the script with default filenames:

```
python Datecoding_retail.py
```

---

## 📊 Sample Input and Output

<p align="center"> <b>Raw Input (unorganized scan export)</b><br>
<img src="assets/datecoding_input_pic.png" alt="Input Pic" width="775"> </p>

<br>

<p align="center"> <b>Processed Report (auto-formatted, print-ready)</b><br> 
<img src="assets/datecoding_output_pic.png" alt="Output Pic" width="775"> </p>

---

## 👨💻 Author

Created by **Abhishek Javalkoti** — Master’s Graduate from the University of Sydney, and a Data Analysis & Consulting Enthusiast.  

🔗 Connect with me:  
- [LinkedIn](https://www.linkedin.com/in/abhishekjavalkoti/)  
- [GitHub](https://github.com/Abhishek24J)  
