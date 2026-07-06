# Python CI Workflow Practice

This project is a simple Python GitHub Actions practice project.

## Structure

.github/workflows/python-ci.yml
GitHub Actions workflow file.

app/main.py
Main Python code.

tests/test_main.py
Pytest test file.

requirements.txt
Python dependencies.

## Run locally

Create virtual environment:

python -m venv .venv

Activate on Linux/macOS:

source .venv/bin/activate

Activate on Windows PowerShell:

.\.venv\Scripts\Activate.ps1

Install dependencies:

pip install -r requirements.txt

Run app:

python -m app.main

Run tests:

pytest

## Push to GitHub

git init

git add .

git commit -m "ci: add python workflow"

git branch -M main

git remote add origin YOUR_REPOSITORY_URL

git push -u origin main

Then open your GitHub repository and check the Actions tab.
