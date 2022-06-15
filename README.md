# react-masterclass
Iteratively recreating the same application with Reach while progressively increasing the complexity of technologies involved

The iterations will be as follows.

 V1 - Base react with Hooks Context Etc
 V2 - Next JS

The application will be a meal tracker.

Meal has Items
Items have calories
You have a daily log

 Item
  name
  unit
  caloriesPerUnit
 
 ItemMeal
  Item
  quantity 
  Meal

 Meal
  items <List<ItemMeal>>
 
 Day
  calorieGoal 
 
 https://www.calorieking.com/us/en/developers/food-api/

 When you sign up (OAuth) you should create a default calorie limit and maximum calories per day.
 You need to set up the meals you ate
 You need to enter the items you ate for each meal. 
 When you exceed the calorie limit it'll show you visualizations of how well you did
 You will also have access to graphs about how well you have performed in the past.
 
 FireBase Backend for Simplicity
