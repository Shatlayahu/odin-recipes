# Odin-recipes website
Welcome to my recipe website! This project is a simple HTML-based site designed to showcase and share delicious recipes.

## Features
- **Easy Navigation**: Simple and intuitive navigation to browse through various recipes.
- **Detailed Recipes**: Each recipe includes a list of ingredients and step-by-step instructions.

## How to Use

1. **Open the Website**: Open the index.html file in your web browser.
2.	**Browse Recipes**: Navigate through the available recipes using the links provided.
3.	**View Recipe Details**: Click on a recipe to view its ingredients and instructions.

## Customization 
1. **Adding new recipes**: Create a new HTML file in recipes folder, name it after your recipe. And link it from the  main page. You have to add at least one picture of the recipe, place that picture in the images folder.
2. **Recipe page**: Your recipe must contain one picture, brief description, ingredients with exact measurements and detailed steps. 

## Example Recipe HTML Structure

Here’s an example structure for a recipe HTML file:

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Recipe Name</title>
</head>
<body>
    <h1>Recipe Name</h1>
    <hr>
    <br>
    <img src="../images/recipe.jpg" alt="recipe">
    <h2>Ingredients</h2>
    <ul>
        <li>Ingredient 1</li>
        <li>Ingredient 2</li>
        <li>Ingredient 3</li>
    </ul>
    <h2>Instructions</h2>
    <ol>
        <li>Step 1</li>
        <li>Step 2</li>
        <li>Step 3</li>
    </ol>
</body>
</html>
```

## Contributing

Feel free to fork this repository and make improvements. Pull requests are welcome!