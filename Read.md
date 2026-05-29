# Tips Data Analysis – 10 Essential Visualizations

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Dataset
- **Name:** Tips data_set (built‑in from Seaborn)
- **Rows:** 244
- **Columns:** total_bill, tip, sex, smoker, day, time, size
- **Source:** [Seaborn](https://github.com/mwaskom/seaborn-data)


### create conda environment 
conda create -p .env python=3.x.x
### activate environment 
conda activate D:\Tips_data_anaylist_report\.env 

### instalation of libraries 
pip install pandas numpy matplotlib seaborn ipykernel

### Dependencies
- Python 3.10        ← Your project needs Python version 3.10
- pandas             ← For data manipulation (DataFrames)
- numpy              ← For numerical operations
- matplotlib         ← For basic plotting
- seaborn            ← For statistical visualizations

## Folder Structure
data_anaylist_report/
.env/    # Virtual environment
 data/    # tips.csv
 Script/  # Jupyter notebook with analysis
  pictures/  # Saved chart images
 requirements.txt  # Python packages
  README.md  # This file

## How to Run
1. Activate virtual environment (`.env/`)
2. Install packages: `pip install -r requirements.txt`
3. Launch Jupyter and open `Script/your_notebook.ipynb`
4. Run all cells

**Key insight**:
- Highest bill payed by smkores.
- Highest bill  and tip payed by male
- more customers on satureday.
- more chance to get high Tip at Dinner Time.
- most bill payed in range $10-$20 

## Author
- **Name:** Majid Mehmood
- **GitHub:** [github.com/yourusername](https://github.com/majidalimajid561)
- **Email:** majid.official561@gmail.com
