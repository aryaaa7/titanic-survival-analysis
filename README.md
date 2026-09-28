# Titanic Survival Analysis

Beginner-friendly data analysis project using **Pandas, NumPy, Matplotlib and Seaborn**.

## Problem
Titanic jahaz par kin passengers ke bachne ke chances zyada the, aur kin factors (gender, class, age, family) ka kitna asar tha?

## Dataset
Titanic dataset (891 passengers), seaborn library se load hota hai.

## What I did
- Data cleaning: missing values handle kiye (`age` median se, `embarked` mode se, `deck` drop)
- NumPy se fare ki statistics aur outlier detection (IQR method)
- Pandas `groupby` aur `pivot_table` se survival analysis
- 5 chart figures (Matplotlib / Seaborn)

## Key findings
- Mahilaon ki survival rate ~74% vs purushon ki ~19%
- 1st class: 63%, 2nd class: 47%, 3rd class: 24%
- 1st class ki mahilaon mein 97% bachi; 3rd class ke purushon mein sirf 13.5%
- 12 saal se chhote bacchon ki survival rate 58%; 60+ age wale 23%

## How to run
```bash
pip install -r requirements.txt
jupyter notebook titanic_survival_analysis.ipynb
```
(Internet chahiye, kyunki dataset seaborn online se load karta hai.)

## Tech stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter
