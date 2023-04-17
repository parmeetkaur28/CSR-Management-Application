<div align="center">

# Job Hive

</div>

## Job Hive - Excellance towards job opportunities

Introduction:
Corporate Social Responsibility (CSR) has become an increasingly important aspect of modern business practices. CSR refers to a company's commitment to ethical, social, and environmental responsibility in its operations and interactions with stakeholders. In recent years, CSR has evolved from a peripheral concern to a fundamental aspect of business strategy. Many companies are now embracing CSR as a core value and integrating it into their daily operations.


Problem statement:
This project aims to reduce the manual labour that is required to organise and administer the CSR initiatives across multiple locations.

Used Tech Stack
1. Django
2. Sqlite
3. html
4. CSS
5. PHP
6. Javascript
7. Node.js

#### Install

1. Create a virtual environment

    `virtualenv venv`

    Or

    `python3.8 -m venv venv`

2. Activate it

    `source venv/bin/activate`

3. Clone the repository and install the packages in the virtual env:

    `pip install -r requirements.txt`

4. Add `.env` file.

    `cp .env.dev.sample .env`

5. Add Github client ID and client secret in the `.env` file

#### Run

1.With the venv activate it, execute:

    python manage.py collectstatic

*Note* : Collect static is not necessary when debug is True (in dev mode)

2. Create initial database:

    `python manage.py migrate`


3. Load demo data (optional):

    `python manage.py loaddata fixtures/app_name_initial_data.json --app app.model_name`

4. Run server:

    `python manage.py runserver`
