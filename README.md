# Eat-Da-Burger!

-A Node, Express, Handlebars, and MySQL burger app that lets users input the names of burgers they'd like to eat and then devour them! 

## Functionality

Using an home-grown ORM, the app has 3 basic CRUD functions...

1.READ all entries from the MySQL database and display them to the DOM using Handlebars.

2.UPDATE a selected burger by clicking "Devour It", which hits a /burger/eat/:id route in Express to change its "devoured" status in the MySQL database. It then re-routes the webpage back to the index, where the burger is now in the devoured column (via Handlebars)

3.CREATE a new burger using the "Place Order" form, which hits a /burger/create route in Express to insert a new burger into the MySQL database. It then re-routes the webpage back to the index, where the burger is now in the ready to be eaten column (via Handlebars)

## Installation 
To run the application locally, first clone this repository with the following command.

``` git clone https://github.com/Duckiebee/burger.git ```

-Next, cd into the folder where the repo was cloned to your computer and install the application dependencies.

``` npm install ```

-Finally, run the node server locally.

``` node server ```

Now, open the local application on port 3000 at the URL: http://localhost:3000/.
