# Pythonic_Login_and_Web_Scraping
A Python Script for Logging into  a Web Application and Scraping Data

- This project was Used to Solve a **Data Ingression** Issue.
- There was need to **login to a web app and extract raw data** into a dataframe which would then be used for analysis.

**_WEB APP FUNCTIONALITY_**

- This web app only displays 50 records per page, hence a need to incrementally navigate to new pages.
- For the Use case, the client using this web app did not usually have data on more than 20 pages daily.
- A payload is sent upon client login usually containing an auto-generated token.




**LIBRARIES USED:**

    - Requests
    - Pandas
    - BeautifulSoup
