<div align="center">

# Job Hive

</div>

## Job Hive - Excellance towards job opportunities

### Introduction:
Corporate Social Responsibility (CSR) has become an increasingly important aspect of modern business practices. CSR refers to a company's commitment to ethical, social, and environmental responsibility in its operations and interactions with stakeholders. In recent years, CSR has evolved from a peripheral concern to a fundamental aspect of business strategy. Many companies are now embracing CSR as a core value and integrating it into their daily operations.


### Problem statement:
This project aims to reduce the manual labour that is required to organise and administer the CSR initiatives across multiple locations.

Used Tech Stack
1. Django
2. Sqlite
3. HTML
4. CSS
5. PHP
6. Javascript
7. Node.js
8. Python

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
    
    
 #### Results--

    
Home page:
    
![tia1](https://user-images.githubusercontent.com/84987833/232560927-5d46da1d-a558-46e2-861b-5ebc47185162.png)

![tia2](https://user-images.githubusercontent.com/84987833/232560974-0798ddf5-cddf-4327-9783-1793893f0075.png)

![tia3](https://user-images.githubusercontent.com/84987833/232561065-8f69c756-7bec-4c91-a3ed-7236e94734e7.png)

Applied Jobs:
    
   ![tiaa4](https://user-images.githubusercontent.com/84987833/232558918-a51dbd84-b7d2-4217-b4ba-52173f28db85.png)
   

Admin Dashboard:
    
    
   ![tia5](https://user-images.githubusercontent.com/84987833/232559113-a81e8a7b-ca15-4986-b01e-41c9aea08da3.png)
      
   ![tia6](https://user-images.githubusercontent.com/84987833/232559215-bbaf1afe-15ad-4be8-a938-b8f7ad018050.png)
