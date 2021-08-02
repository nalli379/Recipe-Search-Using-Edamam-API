# Recipe-Search-Using-Edamam-API
Search and open url links to recipes based on ingredient, dish type and cooking time.

Description: 
The Recipe Search Program asks the user to input an ingredient, dish type (starter, side dish, main or dessert) and maximum cooking time. The search refines the Edamam API URL request that calls up to 20 results per search. The user can open a url link to any of the recipes requested and can open any number of recipe urls per search. The program loops to the beginning if the user chooses to make a new search.

Installation:
Python 3.9.6 64-bit

Python Modules
- pyspellchecker
- webbrowswer
- requests
- system exit

Text Files
- Ingredient List Text File

API
Edamam API registration required to access Edamam API APP ID and APP Key

Usage: 
- Enter an Ingredient (checks distance of up to 2 letters against a list of ingredients in a text file using Levenshtein Distance)
- Enter Dish type (Starter, Side Dish, Main or Dessert)
- Enter Maximum Cooking Time

The Edamam Request API is edited based on the user's search criteria and returns up to 20 results per search.

- Enter a recipe number to open the recipe url - the user can open multiple recipe urls

- Make a new search to loop the program to the start.

Contributing: Jemilah contributed a separate spell check program which we adapted into a function that loops and fit it into the search program.

Credits: Natalie and Jemilah

![Recipe Search Edamam - 1](https://user-images.githubusercontent.com/88142518/127854010-9900466f-f877-432e-a379-c6503ac51993.png)
![Recipe Search Edamam - 2](https://user-images.githubusercontent.com/88142518/127854014-1ce17ab4-a30b-4859-b9c9-d8ece1dcccff.png)
![Recipe Search Edamam - 4](https://user-images.githubusercontent.com/88142518/127854015-96b635b4-3193-4e68-b993-b12a1f0fca53.png)
![Recipe Search Edamam - 5](https://user-images.githubusercontent.com/88142518/127854017-7051baaa-529d-483f-8033-6fef11fdbd6a.png)
![Recipe Search Edamam - 6](https://user-images.githubusercontent.com/88142518/127854018-50c744fc-a959-4690-9e24-3242006a15c0.png)
![Recipe Search Edamam - 7](https://user-images.githubusercontent.com/88142518/127854019-1592eda0-e22b-413c-a0f1-e1980923a01d.png)
![Recipe Search Edamam - 8](https://user-images.githubusercontent.com/88142518/127854021-e5fdf24d-a8ce-4a4e-a90d-4722f675075a.png)
![Recipe Search Edamam - 9](https://user-images.githubusercontent.com/88142518/127854024-3bfcebe8-7f23-495a-917f-faa6cb29685f.png)
![Recipe Search Edamam - 10](https://user-images.githubusercontent.com/88142518/127854029-70929e18-a624-4633-a70c-3b1a0fc9508c.png)
![Recipe Search Edamam - 11](https://user-images.githubusercontent.com/88142518/127854034-24ae1f46-c543-45e8-b52c-24e91e779e1d.png)
![Recipe Search Edamam - 12](https://user-images.githubusercontent.com/88142518/127854035-41cd9251-880f-4a50-a5f8-25ecb44481ce.png)
![Recipe Search Edamam -3](https://user-images.githubusercontent.com/88142518/127854036-70dca860-cfe8-41a0-be52-bae401cd659b.png)
