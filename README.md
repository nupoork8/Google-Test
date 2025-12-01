# MODULE 1 — Playwright Basics + Setup

✅ Goal of Module 1  
You will write one working test that:

- Opens Google
- Waits 3 seconds
- Closes the browser

This teaches:

- how Playwright runs tests (starting Playwright, launching a browser)
- how the page object works (navigation, basic actions)
- how to run tests with pytest
- how to structure a test file

## Prerequisites

- Python 3.8+
- pip

## Setup

Run:

```bash
pip install playwright pytest
python -m playwright install
```

## Project layout

```
/your-project
    /tests
        test_module1_playwright.py
    README.md
```
