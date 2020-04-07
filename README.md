# How to use an API

Today we are going to learn how to use an API with Python. An an API stands for Application Programming Interface–think of it as a way for you to use code to fetch data. We will be using Pro Publica's [Nonprofit API](https://projects.propublica.org/nonprofits/api) and NYC [OpenData's API](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9), but the concepts here apply to any API you find online.

### Creating an account

1. We will be exploring [NYC 311 data](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9).
2. Create a new account by clicking on `Sign up for an app token!` or through their [portal](https://data.cityofnewyork.us/signup).
3. Verify your email address.
4. Create a new app token.
5. Take note of your app token.
6. Read the 311 API [documentation](https://dev.socrata.com/foundry/data.cityofnewyork.us/erm2-nwe9) and Socrata [documentation](https://dev.socrata.com/consumers/getting-started.html).

### Getting set up in pandas.

1. Navigate to your `data-journalism` folder in terminal.
2. Create a new folder for this project and move into that directory.

   ```
   mkdir my-first-api
   cd my-first-api
   mkdir notebooks
   mkdir output
   ```

3. Install libraries we will need for this analysis.

   ```
   pipenv install jupyterlab
   pipenv install pandas
   pipenv install requests
   ```

4. Start Jupyter Lab

   ```
   pipenv run jupyter lab
   ```

5. Navigate to `notebooks` and create a Python 3 notebook inside of it.
