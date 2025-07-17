

# Thesis: Impact of Information and Communication Technology on Economic Growth

## Overview
This repository contains Python code developed for the thesis titled **"Impact of Information and Communication Technology on Economic Growth: Lessons for Vietnam"**. The study analyzes the influence of Information and Communication Technology (ICT) on economic growth across 21 countries, distinguishing between developed and developing nations, and draws lessons for Vietnam to leverage ICT for economic development. The analysis uses panel data from the World Bank for the period 2010–2020.

## Author
- **Student**: Bùi Minh Anh  
- **Student ID**: 1914410003  
- **Class**: Anh 3 – KTQT, Course 58  
- **Supervisor**: Dr. Phạm Thị Mỹ Hạnh  
- **Institution**: Faculty of International Economics, Foreign Trade University, Hanoi, Vietnam  

## Keywords
- Information and Communication Technology (ICT)
- Economic Growth
- GMM Regression
- Developed Countries
- Developing Countries
- Vietnam

## Research Summary
The thesis investigates the relationship between ICT development and economic growth using a panel dataset from the World Bank (2010–2020). The study employs a combination of classical linear panel data regression methods (OLS, FEM, REM, GLS, and Driscoll-Kraay standard errors) and the Generalized Method of Moments (GMM). Key findings include:
- ICT-related variables (mobile phone subscriptions, internet usage, ICT trade share, and high-tech exports) generally have a positive impact on economic growth.
- Fixed telephone subscriptions show a negative effect.
- The impact of internet usage is less pronounced in developing countries compared to developed ones.
- The research contributes to the limited quantitative studies on ICT in Vietnam and provides updated insights using modern data and methodologies.

## Repository Contents
This repository includes:
- **Data**: Panel dataset sourced from the World Bank (2010–2020).
- **Scripts**:
  - Python scripts for data cleaning, preprocessing, and analysis.
  - Implementation of panel data regression models (OLS, FEM, REM, GLS, Driscoll-Kraay).
  - GMM estimation for dynamic panel data analysis.
- **Notebooks**: Jupyter notebooks documenting the analysis workflow.
- **Results**: Output files or visualizations summarizing regression results and key findings.

## Prerequisites
To run the code, ensure you have the following Python libraries installed:
```bash
pip install pandas numpy statsmodels linearmodels matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <repository-name>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebooks or Python scripts to reproduce the analysis.

## Methodology
The analysis uses:
- **Data Source**: World Bank panel data (2010–2020) for 21 countries.
- **Variables**:
  - Dependent: Economic growth (e.g., GDP growth rate).
  - Independent: Mobile phone subscriptions, internet usage, ICT trade share, high-tech exports, fixed telephone subscriptions.
- **Models**:
  - Ordinary Least Squares (OLS)
  - Fixed Effects Model (FEM)
  - Random Effects Model (REM)
  - Generalized Least Squares (GLS)
  - Driscoll-Kraay standard errors for robust estimation
  - Generalized Method of Moments (GMM) for dynamic panel data.

## Key Findings
- Most ICT variables positively influence economic growth.
- Fixed telephone subscriptions have a negative impact.
- Internet usage plays a less significant role in developing countries.
- Policy implications for Vietnam include enhancing ICT infrastructure and promoting high-tech exports.

## Contact
For questions or feedback, contact Bùi Minh Anh via [email or institutional contact].

## Acknowledgments
- Supervisor: Dr. Phạm Thị Mỹ Hạnh
- Institution: Foreign Trade University, Hanoi
- Data Source: World Bank

