# FAC & PHI Automation Script

This Python-based bot automates the extraction of Field-Aligned Current (FAC) and Magnetic Potential (PHI) from the Weimer simulation model. It launches the website, inputs parameters row-by-row from an Excel file, and retrieves results for analysis.

## 🔧 Features
- Uses Selenium to automate browser input and data extraction
- Processes solar wind data to simulate magnetic field effects
- Calculates RMS of PHI and FAC over time
- Automatically iterates through Excel rows

## 📁 Input
- Excel file containing solar wind parameters
- Mode selection and simulation time

## 📊 Output
- RMS values of FAC and PHI
- Optional CSV or plot visualization (if added)

## 🛠️ Technologies Used
- Python
- Selenium
- Pandas
- Excel

## 📌 Use Case
Useful for space weather modeling and magnetospheric research in academic and research labs.
