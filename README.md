# HabitTracker
## Requirements
* Register one habit.
* This habit can't be tracked by time (ex. hours of sleep), only by quantity (ex. number of water glasses a day)
* The application should store and retrieve data from a real database
* When the application starts, it should create a sqlite database, if one isn’t present.
* It should also create a table in the database, where the habit will be logged.
* The app should show the user a menu of options.
* The users should be able to insert, delete, update and view their logged habit.
* Handle all possible errors so that the application never crashes.
* The application should only be terminated when the user inserts 0.
* Only interact with the database using raw SQL. You can’t use mappers such as Entity Framework.

# Runtime 
https://github.com/jordancopsey/HabitTracker/assets/77833509/d994f6ce-ba5e-4805-93ee-d82b51988eb1

# Challenges (To do)
* Let the users create their own habits to track. That will require that you let them choose the unit of measurement of each habit.
* Create a report functionality where the users can view specific information (i.e. how many times the user ran in a year? how many kms?) SQL allows you to ask very interesting things from your database.
