Problem Statement:

The core problem addressed by this project is the manual, error, and time-consuming process of calculating the total nutritional intake (calories, Protein, Carbohydrates, and Fat) from a multi-item meal, based on a fixed,  pre- defined weekly menu. Without a tool, users would need to manually look up or sum the nutritional v values of each item for a specific day and mean, considering the quantity consumed for each.


Scope of the Project:

The scope of this project is limited to providing a console-based, interactive utility for calculating and reporting the aggregated nutritional values of a single meal (breakfast, lunc, snacks, or dinner) on   any given day of the week.

The project encompasses:
Storing a static, hardcoded weekly menu and its associated nutrional data ( calories, protein, carbs, fat).
Handling user input fot the day of the week and the  meal type.
Displaying the available menu items for the selected day and meal.
Collecting integer quantity input from the user for each menu item.
Performing the multiplication and summation of nutritional values based on quantity.
Outputtinng the final calculated totals for the selected meal.
The project does not include: a graphical user interface(GUI), database integration, dynamic menu updating, user login, data persistence,  or recommendation for daily nutrional goals.


Target users:

The primarily targeted users for this simple nutritio calculator script are:
Individuals managing a fixed daily menu (e.g., college students in a mess/canteen,employees in a corporate cafeteria) who want a quick ay to estimate their nutrional intake.
Dietitians or fitness trainers who may use the script as a basic model or quick reference for pre-set Indian meal plans.
Individuals who are facing any health related issues and want to restrict or consume extra nutrition element.
Developers or students learning Python who need a practical example of working with nested dictionaries, user input, basic data validation and manipulation, and arithmetic calculations.


High-Level Features
Menu Storage: Maintain a structured, week-lomg menu (Monday to Sunday) covering four meal slots (breakfast, lunch, snacks, dinner) with detailed nutritional breakdown.
Meal selection: Allow users to specify the day and meal type they wish to calculate nutrition for.
Interactive Quantity Input: Prompt the user to enter the Quantity consumed for every item available in selected meal.
Total Nutritional Calculation: Compute the aggregate total of Caloies(kcal), Protein (g), Carbohydrates (g), and Fat (g) for the entire meal based on the entered quantities.
Input Validation (Basic): Check if the entered day and meal are present in the static menu data.
