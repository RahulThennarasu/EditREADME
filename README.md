# Final-Project

# Web Programming with Python and JavaScript

This website is a food sharing platform powered by [Django](https://www.djangoproject.com/). In this platform, readers can search, create, rate, and buy food items or browse for recipes to cook!

# Distinctiveness and Complexity:

This project is not a social network as it does not have the features used in the Network project in the course. This is a connection to only the user and the website itself. The like feature operates in a different way and the website's CSS differs from any of the other projects.
This project is not a e-commerce website and is different from project 2, as it doesnt have bid features or a category feature. The buy feature completely differs from the bid and auction features in project 2 aswell. The project contains small aspects from each project I have made and learned from!

## Files

### capstone folder 

In the capstone folder there is 1 file I modified that django created. In the settings.py file, I installed an app called recipes, which is important, because this app makes the program work.

### recipes folder

In the recipes folder I created, there are 2 folders and 4 files I modified.

#### The four files:

In the models.py file I created 4 models for the website to function with the features. The models are labeled as User, Category, Listing, and Comment.

In the admin.py file, I have registered the models I created mentioned above.

In the urls.py, file I created there are 15 paths in total which the user can login, logout, register into an account. Create, edit, and buy a recipe, and comment on recipes.

In the views.py file, I firstly imported all the models I created. Afterwords, I wrote code for each of the paths I created in the urls.py file. This file is very important because it displays all the features and functions I created. 

#### static folder

There are 2 files called styles.css and index.js. The styles.css folder has the written css for the website and the index.js file contains the like feature.

#### templates folder

In the templates folder there 8 html files I created and modified. The index.html file contains the html and javascript for the homepage of the website. The layout.html file, creates the paths in the nav bar, which are labeled as "Available Recipes", "Add Recipe", "Bought Ingredients", "Log In", "Log Out", and "Register". It also links the styles.css and index.js files. It links fonts and images I used as well. The login.html and register.html are for the user to create and login to an account with their username, email, and password. The create.html file contains how the user can make their own recipe with the given requirements. The listing.html file contains the details of each recipe. It allows the user to like, comment, and buy the recipe. The watchlist.html file contains the watched and bought recipes the user has encountered. They can refund their purchase or buy a recipe. The search.html file contains the code for the search feature on how the user can find a recipe.


# Features explained in depth

## Main Page

In the main page, you can search text in any part of the recipes by inputing any words in the input box, and click the blue "Search" button.

if you just want to read a new recipe, just click "Available Recipes" button on the top, and you will get some recipes randomly. Additionally, you don't need to log in for those actions.

![mainpage](https://user-images.githubusercontent.com/97413501/209048132-1aae4c93-bd34-458a-89f9-bcb8f1bf530b.png)

## URLs

At the top of the main page are 4 links which are labeled as, Available Recipes, Add Recipe, Bought Ingredients, and Logout.
I will get into detail on what these links do.

## Result Page

In the result page, you can get recipes with title, and it's information of what the dish is. If you don't satisfied with those results, you can continue to search in the top search bar.

## Add Recipe

In this link users will able to share a recipe they made. They must incldue a description, the recipe name, the imageof the dish, the ingredients, the price, and what kind of dish it is.

![addpage](https://user-images.githubusercontent.com/97413501/209049269-8f29c653-1d18-4e63-a705-ec9302a09a94.png)

## Recipe/Dish Page

When the user clicks on a recipe, they are greeted with buying the ingredients, learning the name of the dish, it's information, ingredients, and recipe. Below, they also know who the chef/creator is, the price of the ingredients, and they are allowed to rate and crique the dish. It is followed with a bright blue Like buton as well.

![dishpage](https://user-images.githubusercontent.com/97413501/209048830-e63e8484-f724-4fe9-aa79-5493a327b4b1.png)

## Like Feature

Using JavaScript, I have created a Like button which allows the user to like any dish they find interesting.

![likebutton](https://user-images.githubusercontent.com/97413501/209050153-fddc69dd-7d73-4a6f-bdf5-2ee9d095929e.png)

## Comment Feature

In the recipe page, users are also allowed to rate and comment on dishes they find fascinating. I really enjoyed creating this feature because of how simple, yet powerful it is.

![commentfeature](https://user-images.githubusercontent.com/97413501/209050372-10e8a9c8-ce45-4b73-a645-3f0a3d12c125.png)

## Bought Ingredients

This link will lead to what dishes the user has bought from the available recipes.

![boughtpage](https://user-images.githubusercontent.com/97413501/209050520-8f498193-2f5d-45d7-a903-bb8566b5f13b.png)

## Edit feature

This feature allows you to interact with the recipes you have made. You are able to edit the dishes title. This was done using Javascript and the AJAX request to django view.

![editpage](https://user-images.githubusercontent.com/97413501/209049850-ac237df2-801a-470f-9242-bd0842610980.png)

## Pagination

This website also has a pagination feature that i learned from this course. You are able to click "Next" and "Previous" to move from a page to page. This is very helpful as it organizes the website much better. 

## Django Admin and Superuser: Backend

Creating a superuser in this project is especially helpful when the webiste includes models. I used /admin to help me delete certain recipes when I wanted to.

# Requirements
There are no requirements for this program to work properly.

# Additional comments

Thanks for all people make [CS50's Web Programming with Python and JavaScript](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript) possible. I really enjoyed working with Javascript, Python, HTML, and CSS.

December 21, 2022



 











