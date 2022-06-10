# Money Manager App

This is a personal money management application used to store tracks of your money flow.
This app is developed from flutter by using **Dart** as main language and **Hive** is used as database.

## Features

There are two screen:- **Transactions** and **Categories**. 
The Navigation between two screens is done by bottom navigation bar.
A Floating Action Buttom is placed at bottom right corner common to both screens with actions corresponding the screen.

### Transactions

This is used to display the stored transaction activites made by the user.
This Screen has **Add Transactions Button** which redirects to a new screen with a form for adding Transaction details.
The List of Transactions displayed could be deleted using a leftward sliding motion poping a delete option to confirm your request for delete.

### Categories

The Categories screen is divided into two screens: **Income** and **Expense**.
The Navigation between two screens is done by Tabbar.
Both **Income** and **Expense** Screens show a list of categories stored in that particular category type.
This Screen has **Add Category Button**  which displays a popup showing necessary fields for category addition.
The List shown in **Income** and **Expense** has a delete button in each tile to completely delete that category from database.


**App UI screenshots are stored in Screenshots folder**
