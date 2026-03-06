#  Healthcare Operations Intelligence Dashboard

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Streamlit](https://img.shields.io/badge/Dashboard-Streamlit-red)
![Pandas](https://img.shields.io/badge/Data-Pandas-green)
![Plotly](https://img.shields.io/badge/Visualization-Plotly-purple)

An **interactive healthcare analytics platform** built using **Python, Streamlit, Pandas, Numpy, and Plotly** that transforms fragmented hospital data into actionable insights for operational and strategic decision-making.

This dashboard provides hospital administrators with a **unified view of patient demand, clinical operations, staffing workload, and capacity planning** through interactive visualizations and real-time KPIs.

---

#  Live Dashboard

 **Streamlit App:**

https://priyanshi-kunte-healthcare-operations-dashboard-app-u9cwbw.streamlit.app/

---

#  Project Overview

Hospitals generate large volumes of operational data such as:

* patient visits
* appointments
* admissions
* surgeries
* staffing information
* bed utilization

However, these datasets often exist in **separate systems**, creating data silos that make decision-making difficult.

The **Healthcare Operations Intelligence Dashboard** consolidates these datasets into a single analytics platform that enables hospital leadership to:

* monitor operational KPIs
* analyze patient demand patterns
* optimize staffing allocation
* track clinical workload
* forecast future capacity requirements

---

#  Key Features

* Multi-page interactive analytics dashboard
* Real-time KPI monitoring
* Patient demographic analysis
* Clinical & surgical performance insights
* Operational efficiency monitoring
* Staffing workload optimization
* Capacity planning simulator
* Interactive filtering and drill-down analysis
* Downloadable datasets and PDF reports

---

#  Dashboard Modules

## 1. Executive Overview

Provides a high-level snapshot of hospital performance.

Includes:

* Total Patients
* Total Appointments
* Admissions
* Cancellation Rate
* Patient flow trends
* Department demand analysis
* Appointment completion rate

---

## 2️. Patient Demographics & Demand Analysis

Analyzes patient behavior and demand patterns.

Includes:

* Top visit reason
* Peak age group
* Top patient cities
* Gender distribution
* Age group analysis
* Patient distribution map
* Payment methods analysis
* Patient journey timeline

---

## 3️. Clinical & Surgical Intelligence

Analyzes surgical performance and clinical workload.

Includes:

* Procedure diversity
* Active surgeons
* Most common surgical procedures
* Department surgery distribution
* Surgery trends over time
* Surgeon workload heatmap

---

## 4️. Operational Efficiency & Capacity

Monitors operational efficiency and bed utilization.

Includes:

* Operational alerts
* Length of stay analysis
* Ward utilization
* Department deviation from average LOS
* Admissions vs discharges trends
* Bed turnover rate

---

## 5️. Staffing & Resource Optimization

Analyzes workforce allocation and workload.

Includes:

* Active doctors
* Nurse distribution by department
* Doctor workload heatmap
* Patient-to-nurse ratio
* Admissions vs staff comparison

---

## 6️. Intelligence & Capacity Planning

Supports strategic planning using predictive simulation.

Includes:

* Capacity planning simulator
* Future bed requirements
* Projected admissions
* Staffing requirement forecasting
* Revenue leakage estimation
* PDF report builder

---

#  Tech Stack

| Technology    | Purpose                            |
| ------------- | ---------------------------------- |
| **Python**    | Core programming language          |
| **Streamlit** | Dashboard interface                |
| **Pandas**    | Data processing and transformation |
| **NumPy**     | Numerical computations             |
| **Plotly**    | Interactive data visualization     |
| **Excel**     | Dataset storage                    |
| **GitHub**    | Version control                    |

---

#  System Architecture

The dashboard follows a **data analytics pipeline architecture**.

### 1️. Data Source

Hospital datasets stored in Excel files.

### 2️. Data Processing

Data cleaning, transformation, and aggregation using **Pandas and NumPy**.

### 3️. KPI Computation

Key performance indicators such as:

* admissions
* cancellation rate
* bed utilization
* length of stay

are calculated from processed data.

### 4️. Visualization Layer

Interactive charts are generated using **Plotly** and displayed through **Streamlit**.

### 5️. Decision Support

Hospital administrators use these insights for **operational monitoring and strategic planning**.

---

#  Project Structure

```
Healthcare-Operations-Dashboard
│
├── .streamlit
│   └── config.toml
│
├── data
│   └── dataFinal.xlsx
│
├── myPages
│   ├── data_loader.py
│   ├── page1.py
│   ├── page2.py
│   ├── page3.py
│   ├── page4.py
│   ├── page5.py
│   └── page6.py
│
├── Agile_document
│   ├── G2_Defence_Tracker.xls
│   ├── G2_Unit_testplan.xls
│   └── Priyanshi_agile_document.xls
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md
```

---

#  Installation & Running Locally

Follow these steps to run the dashboard on your local machine.

### 1️. Clone the Repository

```bash
git clone https://github.com/priyanshi-kunte/Healthcare-Operations-Dashboard.git

# Navigate to the project folder
cd Healthcare-Operations-Dashboard
```

### 2️. Create and Activate Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
```

**Windows**

```bash
venv\Scripts\activate
```

**macOS / Linux**

```bash
source venv/bin/activate
```

### 3️. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️. Run the Dashboard

```bash
streamlit run app.py
```

After running the command, the application will open automatically in your browser at:

```
http://localhost:8501
```

### Data

Dataset used: data/dataFinal.xlsx

Ensure the file is present in the data/ folder before running the app.

### Documentation

Agile documentation (product backlog, sprint backlog, tasks, impediments, retrospectives) is available at:

Agile_document/Priyanshi_agile_document.xls

### Contributors

Group Project (Internship)

Individual contributions tracked via Agile documentation

### Notes

venv/ and cache files are intentionally excluded from the repository.

.streamlit/config.toml is included to keep UI/theme consistent.

---

#  Future Improvements

Possible enhancements include:

* real-time hospital database integration
* AI-based patient demand forecasting
* integration with hospital information systems
* multi-hospital analytics platform
* mobile dashboard support

---

#  Author

**Priyanshi Kunte**
GitHub:
https://github.com/priyanshi-kunte

---

If you found this project helpful, please **star the repository**.

---
