# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup
Prerequisites: Python 3.10+, Git.
```
git clone git@github.com:<NQThuan25127515>/lab01-<NQThuan25127515>.git
cd lab01-<NQThuan25127515>
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
pip install -e .
```
## Run
```
python -m assistant "where is the IT helpdesk?"
# -> IT Helpdesk: room E.005, open Mon-Fri 08:00-17:00.
```
## Test
```
pytest -q
# -> 4 passed
```
## Project structure
```
lab01-<NQThuan25127515>/
├── pytest_cache/
├── .venv/
├── data/
├── docs/
├── scripts/
├── src/
├── tests/
├── ui/
├── .gitignore/
├── pyproject.toml/
├── README.md/
├── requirements.txt/
```