<!-- create a basic readme with instructions -->

# Recipe Finder Web App
Uses RapidAPI for fetch recipes based on feeded ingredients.

## Setup
1. Clone the repo to your local machine.
```bash
$ git clone https://github.com/AJV009/recipe-finder.git
```
2. Install dependencies.
```bash
$ pip install flask requests python-dotenv
```
3. Subscribe to (RapidAPI Spoonacular)[https://rapidapi.com/spoonacular/api/recipe-food-nutrition/] and create a `.env` file with the following variable.
```bash
rapidapi_key=<your_rapidapi_secret_key>
```
4. Run the app.
```bash
$ python app.py
```
5. Launch 5000 localhost (server)[http://127.0.0.1:5000/]