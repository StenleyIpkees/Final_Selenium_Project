# Final_Selenium_Project

Alexandr Medvedev test project (c) 2020

Course "Автоматизация тестирования с помощью Selenium и Python" on Stepik.org. Module 4 (Page_Object).

Author
Alexandr Medvedev

Python version
3.7.4

Chromedriver
In the file conftest.py was added path to chromedriver. Please, remove path to chromedriver OR add your path (if needed).
browser = webdriver.Chrome('../chromedriver/chromedriver.exe', options=options)

Run tests in test_main_page.py
pytest -v --tb=line --language=en test_main_page.py

Run tests in test_product_page.py
pytest -v --tb=line --language=en -m need_review
