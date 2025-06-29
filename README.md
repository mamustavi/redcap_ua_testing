# REDCap User Acceptance Testing – CRP 109 Exam Project

This repository documents the **User Acceptance Testing (UAT)** and subsequent **corrections** of an existing REDCap project titled **"CRP 109 Exam Adnan"**. The project was originally provided with intentional design flaws and configuration issues for academic review and repair.

The REDCap project was systematically tested for functionality, usability, validation errors, and logic flow. Identified issues were documented and resolved to meet proper data management standards. 

## 🔍 Key Actions Performed

- Corrected validation types (e.g., email/phone fields)
- Standardized field names and choice numbering
- Fixed or added branching logic for conditional questions
- Enhanced inclusivity in demographic options
- Set proper min/max value ranges for numeric fields

## 📁 Files Included

| File | Description |
|------|-------------|
| `uat_metadata.xml` | Full corrected REDCap project metadata (importable) |
| `uat_error_log.docx` | Detailed log of identified issues and resolution steps |
| `uat_instruments.pdf` | Screenshots of updated instruments for visual reference |
| `uat_data_dictionary.csv` | Exported data dictionary showing all fields and logic |

## 🚀 How to Use the XML File in REDCap

1. Log into your **REDCap** instance.
2. Go to **Project Setup**.
3. Click **“Upload a REDCap project XML file”** under *Design your data collection instruments*.
4. Select `uat_metadata.xml` from your local machine.
5. REDCap will import the entire project structure (no records included).
6. Review and adjust if necessary for your local environment.

> ⚠️ **Note:** You will need project creation rights in REDCap to import this file.

## 🎯 Learning Objectives Met

- Demonstrated understanding of REDCap field types and validation
- Identified and resolved common design flaws
- Applied UAT principles including logging and documentation
- Improved data quality, consistency, and usability across multiple forms

## 📬 Contact

Created by **Adnan Mustavi**  
Feel free to reach out via GitHub or m.a.mustavi@gmail.com for questions or collaboration.
