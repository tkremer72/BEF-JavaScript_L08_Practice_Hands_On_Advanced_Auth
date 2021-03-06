# Lesson 8 Practice Hands-On

# Directions

In this Hands-On exercise, you will continue working with the project from this lesson, ExpressL08. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page.

# Setup

Open up your terminal/command prompt.

Navigate to your desktop in your terminal:

cd Desktop
Then, navigate to the Express-Course directory in your terminal:

cd Express-Course
Finally, navigate to the express_lesson_eight directory:

cd express_lesson_eight
Open your express_lesson_eight project within VS Code (or you can open the folder within VS Code directly):

code .
# Requirements

# Step 1

Run a migration to add a new column "Admin" into the users table

The data type should be a boolean
Change the migration folder to include a default value of false
Don't forget to change the model to match

# Step 2

Within MySQL Workbench, give at least one of your users a value of true for the Admin column

# Step 3

Write the code so when a user log in using JWT, their Admin status is added to the token

Look at the signUser function

# Step 4

Add another get route called /:id that returns the information about the user in the database with that Id.

# Step 5

Use the token to check if the user who logs in is an Admin. If they are an admin then allow them access the newly created /:id route.
