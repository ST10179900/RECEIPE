
# Recipe Program

This project is a program that indicates and intstructs how to use a recipe and find recipes.
A set of instructions that outlines how to prepare or manufacture something, especially a dish of prepared cuisine. A sub-recipe or sub recipe is a recipe for an ingredient that is mentioned in the main recipe's instructions.
Open the application and choose a recipe from the list of top or new recipes. Furthermore, he has the option of using the search engine to clarify his requirements.
The user views the dish he wants and learns what ingredients are required as well as how difficult the cooking process is.
The provided code looks to be a C# console application for managing a recipe book. The code has several classes, including Recipe, Ingredient, and RecipeManager.
The Ingredient class defines an ingredient's attributes, such as its name, quantity, unit of measurement, calories, and food group.
A recipe is represented by the Recipe class, which includes a list of ingredients and steps. It also has other methods, including AddIngredient, AddStep, Scale, ResetQuantities, and GetTotalCalories.
The RecipeManager class manages a recipe list and provides methods for adding, removing, and retrieving recipes.
The program's Main method contains numerous options for managing the recipe book, such as adding a recipe, removing a recipe, presenting a list of recipes, displaying the specifics of a recipe, and so on measuring a recipe, resetting recipe quantities, and erasing all data are all options.The AddRecipe method asks the user for the name of the recipe, the number of ingredients, and the number of stages. The user is then prompted for information on each ingredient and step, which is then added to the recipe. After that, the recipe is saved in the RecipeManager.
The RemoveRecipe function requests the user for the recipe's name before removing it from the RecipeManager. The RecipeManager's DisplayRecipeList function displays a list of recipe names.
The DisplayRecipeDetails method asks the user for the name of a recipe and then displays the recipe's specifics, such as the list of ingredients, steps, and total calories. A warning is issued if the total calories surpass 300.
The ScaleRecipe method requests that the user enter the name of a recipe as well as a new scale factor. The recipe is then scaled by the supplied factor, and the revised details are displayed. The ResetRecipeQuantities method invites the user to input the name of a recipe before resetting the quantities of all ingredients in the recipe to their original values.
The ClearAllData function asks the user to confirm that they want to erase all data. If the user confirms, all recipes in the RecipeManager are deleted.

