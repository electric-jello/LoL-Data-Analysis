# LoL-Data-Analysis
League of Legends match data analysis: KDA, win rates, champion picks, and role-based insights using Python and Pandas.

# LoL Data Analysis Project

## Overview
This project analyzes League of Legends match data to explore trends in player performance, champion picks, win rates, and in-game statistics such as KDA and first blood. The goal is to practice data cleaning, visualization, and basic analysis skills using Python (Pandas, Seaborn, Matplotlib) and Excel.

## Files
- **notebooks/LoL_match_analysis.ipynb** - Jupyter Notebook with full code and visualizations.  
- **scripts/LoL_match_analysis.py** - Python script exported from the notebook.  
- **data/LoL_matches_cleaned.csv** - Cleaned dataset compiled manually from match histories.  
- **images/** - Folder containing generated plots (KDA distribution, champion pick frequency, first blood win rate, etc.).  
- **README.md** - GitHub-friendly description and overview.  
- **LICENSE** - MIT open-source license.  

## Data Source
- Currently, the dataset was manually collected from public match histories using the League of Legends client and [Op.GG](https://www.op.gg/).  
- In future work, data could also be sourced programmatically from the League of Legends API (requires developer key).  

## Purpose
- Demonstrates data cleaning, aggregation, and visualization techniques.  
- Shows basic insights like:  
  - KDA distribution across matches  
  - Win rates by role, team side, and first blood  
  - Most-picked champions per role  
- Serves as a portfolio example for aspiring data scientists, showing the ability to handle real game data and create visualizations.  

## Usage
1. Clone the repository.  
2. Open `notebooks/LoL_match_analysis.ipynb` in Jupyter or Google Colab.  
3. Run the notebook cells to reproduce visualizations.  
4. Alternatively, run `scripts/LoL_match_analysis.py` to execute the analysis via Python directly.  
5. Use `data/LoL_matches_cleaned.csv` for any additional analysis or experimentation.  

## Contact
For questions or collaboration, you can reach out at savana.s.jones@gmail.com
