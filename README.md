## <div align="center"> Room Utilization Analysis </div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/a2aa45e7-317a-4c34-be08-f56b463eaa2a" alt="Project Banner" width="600" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.11%2B-blue" alt="Python Badge" />
  <img src="https://img.shields.io/badge/Dash-Framework-orange" alt="Dash Badge" />
  <img src="https://img.shields.io/badge/License-MIT-success" alt="License Badge" />
  <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen" alt="Contributions Badge" />
  <a href="https://github.com/user-attachments/files/18440413/Report.pdf" target="_blank"><img src="https://img.shields.io/badge/Download%20Report-PDF-blue" alt="Download Report Badge" /></a>
</div>

---

## 📌 Project Description
This project analyzes room occupancy data for the ground and first floors of a building, aiming to optimize space usage and scheduling. The analysis identifies key metrics such as utilization levels, patterns, and anomalies. A live dashboard built using Dash and Plotly visualizes findings interactively. Recommendations and a scalable solution are provided for real-time monitoring and future data needs.

---

## 🎥 Code & Output Preview
<div align="center">
  <img src="https://github.com/user-attachments/assets/18d220c9-5b34-4791-89d6-818dbc95ec65" alt="DashboardPreview" width="500" />
  <img src="https://github.com/user-attachments/assets/bba39614-9106-416b-966a-86d38f45ffcc" alt="Weekly Trends" width="500" />
  <img src="https://github.com/user-attachments/assets/44a44ae2-6ddd-41f9-90f4-78d7712d2399" alt="Hourly Trends" width="500" />
  <img src="https://github.com/user-attachments/assets/daf71db1-dc3b-4824-ae7c-440eec72ec44" alt="Anomalies" width="500" />
</div>

---

## 🚀 Installation & Usage

### Prerequisites
- **Python 3.11** or later.

### Installation Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Vamsi-Mudila/Room-Utilization-Analysis.git
   cd Room-Utilization-Analysis/workspace
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   - Navigate to the `workspace/` folder.
   - Open `Code.ipynb` in Jupyter Notebook or Jupyter Lab.
   - Execute all cells to perform the analysis and view results.

4. **Launch the Dash Dashboard**:
   - The notebook includes a cell to launch the Dash app.
   - Once executed, open the provided URL (e.g., http://127.0.0.1:8050/) in your browser.

---

## 📊 Key Features
- **Utilization Metrics**: Average, peak, underutilization, and overutilization levels.
- **Trends and Patterns**: Hourly and weekly room usage patterns.
- **Anomaly Detection**: Identifies irregular room usage using z-scores.
- **Interactive Dashboard**: Explore utilization metrics, trends, and anomalies visually.

---

## 🛠️ Project Structure
```
Room-Utilization-Analysis/
│
├── workspace/                 # Working files
│   ├── Code.ipynb             # Main Jupyter Notebook (analysis + dashboard)
│   ├── Wellbeing Occupancy_DataSet.xlsx  # Dataset for analysis
├── .gitignore                 # File specifying files and directories to ignore in Git
├── LICENSE                    # MIT License details
├── README.md                  # Main project documentation
├── Report.pdf                 # Detailed project report
```

---

## 🤝 Contributions
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some AmazingFeature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a pull request.

---

## ⚖️ License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 💖 Acknowledgements
- **Pandas, NumPy, Plotly**: For efficient data handling and visualization.
- **Dash Framework**: For creating the interactive dashboard.
- **Friends and Family**: For their unwavering support.
