# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Prerequisites: Python 3.10+, Git.
 git clone https://github.com/kq244466666-commits/lab01--github-kq244466666--
 cd lab01--github-kq244466666--
 python -m venv .venv
 source .venv/bin/activate # Windows: .venv\Scripts\Activate.ps1
 pip install -r requirements.txt
 pip install -e .




## Run

python -m assistant "where is the IT helpdesk?"
# -> IT Helpdesk: room E.005, open Mon-Fri 08:00-17:00.

## Test

python -m pytest -q
# -> 4 passed in 0.03s

## Project structure


lab01-github-kq24446666-/
├── data/
│   └── offices.csv         
├── docs/
│   └── README.md            
├── scripts/
│   └── check_env.py         
├── src/    
│   └── assistant
│   └── assistant.egg-info        
├── tests/ 
│   └── _pycache_
│   └── test_smoke.py          
├── ui/    
│   └── README.md
└──                       
```
