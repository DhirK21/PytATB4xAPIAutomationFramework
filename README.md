Python API Automation Framework
Hybrid Custom API Automation Framework include the proper folder structure

![354955159-3c7d5fe5-207a-42e7-84fe-f4d53354d987](https://github.com/user-attachments/assets/3be5e6a9-7c1a-4a67-91c5-dbfda8fca174)


Tech Stack

- Python 3.12
- Requests - HTTP Requests
- PyTest - Testing Framework
- Reporting - Allure Report, PyTest HTML
- Test Data - CSV, Excel, JSON, Faker
- Advance API Testcase - jsonschema
- Parallel Execution - x distribute (xdist)

- How to Install Packages

pip install requests pytest pytest-html faker allure-pytest jsonschema

How to run your Testcase Parallel 

pip install pytest-xdist 

How to run the Basic Test with Allure report

 pytest tests/tests/crud/test_create_booking.py  --alluredir=allure_result -s
