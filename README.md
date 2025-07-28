<h1 align="center">📈 HR Analytics Dashboard</h1>

<p align="center">
  An interactive Tableau dashboard built to analyze HR data — including hiring trends, workforce demographics, and salary insights — with dynamic filtering and storytelling features.
</p>

---

## 📂 Project Contents

| File / Folder | Description |
|---------------|-------------|
| `images ` | Contains all the icons used in the dashbaord |
| `HR Dashboard.twbx` | Packaged Tableau workbook with all dashboards |
| `dataset.csv` | Example generated dataset (not versioned) |
| `README.md` | Project description and usage instructions |

---

## 📌 Dashboard Features

### 🔹 HR Summary View
- Total hires, active employees, and terminations over time
- Breakdown by department, job title, and location (HQ vs branches)
- Geo-distribution across states and cities

### 🔹 Demographics & Income Analysis
- Gender ratio and age/education level distributions
- Correlation: education vs. performance rating
- Salary comparison by gender, education, and age within departments

### 🔹 Employee Records View
- Detailed, filterable table of employee data (name, age, salary, role, etc.)
- Easy filtering by multiple attributes

---

## 🚀 Getting Started

### ✅ Prerequisites
- Tableau Desktop (2021.4 or higher recommended)
- Python 3.8+
- `pandas`, `numpy`, `faker` libraries

### 🔧 Setup Steps

```bash
# Clone the repository
git clone https://github.com/MdFardeenAkbar/Hr-Analytics-Dashboard.git
cd Hr-Analytics-Dashboard

# (Optional) Set up a virtual environment
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt  # Or install manually:
pip install pandas numpy faker
