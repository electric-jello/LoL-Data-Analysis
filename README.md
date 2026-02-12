# League of Legends Match Data Analysis

## Project Overview
This project analyzes match data from **League of Legends** to explore patterns in champion picks, roles, KDA (Kills/Deaths/Assists), win rates, and other gameplay statistics. The goal is to practice **data collection, cleaning, and visualization** using Python (`pandas`, `seaborn`, `matplotlib`) and build a portfolio-ready project.

## Dataset
The dataset contains manually collected match data including:
- Match ID
- Game duration
- Patch version
- Queue type (ranked, flex)
- Team (blue/red)
- Role (top, jungle, mid, ADC, support)
- Champion played
- Win/loss result
- Kills, deaths, assists
- CS (creep score) and CS per minute
- Gold earned, damage dealt, vision score
- First blood and subjective game review

**Current size:** ~211 rows  
**Sources:** Data manually collected from the League of Legends client and Op.GG. In future work, data collection could be automated with the League of Legends API (requires a developer key).

## Files Included
- `notebooks/LoL_match_analysis.ipynb` – Notebook with all code and visualizations
- `scripts/LoL_match_analysis.py` – Python script version
- `data/LoL_matches_cleaned.csv` – Cleaned dataset
- `images/` – Graph exports (optional)
- `LICENSE` – MIT License
- `README.md` – This file

## Key Visualizations
Examples of insights you’ll find:
- Win/loss rates by team side (blue vs red)
- KDA distribution across players
- First blood impact per role
- Most-picked champions by role

## How to Run
1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install pandas seaborn matplotlib


## Contact
For questions or collaboration, you can reach out at savana.s.jones@gmail.com
