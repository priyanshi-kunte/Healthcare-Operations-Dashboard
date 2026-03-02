
# Healthcare Operations Intelligence Dashboard

A Streamlit-based dashboard for analyzing healthcare operations, patient demographics, clinical trends, operational efficiency, and staffing optimization.

## Features
- Executive Overview with key KPIs  
- Patient Demographics & Demand Analysis  
- Clinical & Disease Intelligence  
- Operational Efficiency & Capacity  
- Staffing & Resource Optimization  
- Global filters (date, department, demographics)  
- Dark/Light theme toggle  
- Performance optimization using caching  
- Operational alerts, patient journey timeline, capacity planning simulator  
- PDF export for selected dashboard views  

## Tech Stack
- Python  
- Streamlit  
- Pandas  
- Plotly  

## Project Structure
├── app.py
├── myPages/
│ ├── page1.py
│ ├── page2.py
│ ├── page3.py
│ ├── page4.py
│ ├── page5.py
| ├── page6.py
│ └── data_loader.py
├── data/
│ └── dataFinal.xlsx
├── .streamlit/
│ └── config.toml
├── Agile_document/
│ ├── G2_Defence_Tracker.xls
│ ├── G2_Unit_testplan.xls
│ └── Priyanshi_agile_document.xls
├── .gitignore
└── README.md


## How to Run Locally
```bash
# (Optional) Create and activate virtual environment
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py

Data

Dataset used: data/dataFinal.xlsx

Ensure the file is present in the data/ folder before running the app.

Documentation

Agile documentation (product backlog, sprint backlog, tasks, impediments, retrospectives) is available at:

Agile_document/Priyanshi_agile_document.xls

Contributors

Group Project (Internship)

Individual contributions tracked via Agile documentation

Notes

venv/ and cache files are intentionally excluded from the repository.

.streamlit/config.toml is included to keep UI/theme consistent.


---

### Final 2 commands to publish this README
After pasting this into `README.md`:

```bash
git add README.md
git commit -m "Update README with project overview and setup"
git push
