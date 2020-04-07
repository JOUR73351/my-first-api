# NYT Bestsellers Analysis

Today we are going to learn how to use an API with Python. An an API stands for Application Programming Interface–think of it as a way for you to use code to fetch data. We will be using NYT's Books API. NYT also has other APIs for their articles, movie reviews, tags, top stories, etc.

Typically, you will need to create an account and/or get an API key to authenticate yourself when using the API.

### Creating an account

1. Create a new account through their [portal](https://developer.nytimes.com/accounts/create).
2. Verify your email address.
3. Check out the [Get Started](https://developer.nytimes.com/get-started) page.
4. Follow the steps to register an app.
5. Take note of your API key.

### Getting set up in pandas.

1. Navigate to your `data-journalism` folder in terminal.
2. Create a new folder for this project and move into that directory.

   ```
   mkdir nyt-bestsellers
   cd nyt-bestsellers
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

5. Make new folder called `notebooks` and create a Python 3 notebook inside of it.

6.
