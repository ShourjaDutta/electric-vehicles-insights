# ⚡ Electric Vehicles Dashboard

This repository contains a Power BI dashboard that provides a comprehensive analysis of electric vehicles (EVs) across the United States. It highlights key insights such as total vehicle distribution, popular EV models, manufacturers, clean fuel eligibility, and geographical trends.

---

## 📂 Dataset Description

The dataset used for this dashboard contains detailed records of over **150,000 electric vehicles** registered in the U.S., and includes the following key fields:

| Column Name                  | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| `VIN (1-10)`                | Vehicle Identification Number prefix                                       |
| `County`                    | County of vehicle registration                                             |
| `City`                      | City of vehicle registration                                               |
| `State`                     | U.S. state where the vehicle is registered                                 |
| `Postal Code`               | ZIP code                                                                   |
| `Model Year`                | Manufacturing year of the EV                                               |
| `Make`                      | Manufacturer name (e.g., Tesla, Nissan)                                    |
| `Model`                     | Specific EV model (e.g., Model Y, Leaf)                                    |
| `Electric Vehicle Type`     | Type of EV – Battery Electric (BEV) or Plug-in Hybrid (PHEV)               |
| `CAFV Eligibility`          | Whether the vehicle qualifies for Clean Alternative Fuel Vehicle programs |
| `Electric Range`            | Estimated range of the vehicle on a full charge                            |
| `Electric Utility`          | Name of the electricity provider                                           |
| `2020 Census Tract`         | Geographical identifier for demographic analysis                           |

---

## 📊 Dashboard Highlights

- **Total Vehicles Analyzed**: **150.42K**
- **Average Range**: **67.83 miles**
- **Vehicle Types**:
  - **BEVs (Battery Electric Vehicles)**: 116.75K (77.61%)
  - **PHEVs (Plug-in Hybrid Electric Vehicles)**: 33.67K (22.39%)

### 🔍 Interactive Visuals

- **Total Vehicles by Model Year**: Line chart showing EV adoption trends from 2010 to 2024.
- **Total Vehicles by State**: US map indicating distribution and hotspots of EV usage.
- **Total Vehicles by Make**: Horizontal bar chart ranking manufacturers.
- **Clean Alternative Fuel Vehicle (CAFV) Eligibility**: Donut chart showing eligibility breakdown.
- **Total Vehicles by Model**: Treemap of popular models.
- **Filters Available**: `City`, `Electric Utility`, `Model Year`, and `Model`.

---

## 📁 File Structure
📁 Electric_Vehicles_Dashboard
├── Electric_Vehicles_Dashboard.pbix # Power BI dashboard file
├── .gitignore # Git ignored files and folders
└── LICENSE # MIT License for open-source use
|__ README.md


---

## 🚀 How to Use

1. **Install Power BI Desktop**:  
   Download from [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/)

2. **Open the Project**:
   - Clone this repository or download the `.pbix` file.
   - Open `Electric_Vehicles_Dashboard.pbix` using Power BI Desktop.

3. **Explore the Dashboard**:
   - Use filters like city, utility, and model year to customize insights.
   - Hover over visualizations for detailed metrics.

---

## 💡 Insights

- Tesla leads the EV market significantly.
- Most EVs have ranges around 68 miles (dataset average).
- Significant growth in EVs between 2018–2023.
- Highest EV registrations found in states like California.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

