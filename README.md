# Playwright Automation

From my data analyst internship at **Autonmis** (Apr 2025). I spent about 2–3 weeks testing the company's data platform, and wrote these Python scripts with Playwright to test it automatically.

## What the scripts do
- Log in and save the session, so the other tests can reuse it
- Open the dashboards from the home page
- Create a SQL notebook
- Attach a data source to a notebook
- Open projects, notebooks and dashboards one after another
- Report "Application error detected" if a page crashes

## How to run
1. `pip install playwright`
2. `playwright install`
3. Put your own username and password where the scripts say `USERNAME` / `PASSWORD`. No real passwords are stored in this repo.
4. Run a script, for example `python login_autonmis.py`.

## Tools
Python, Playwright.
