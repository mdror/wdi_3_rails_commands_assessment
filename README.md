# Rails Commands Quiz

Fork, clone, and write your answers directly in this file. Then submit a pull request.

### Question 1

I want to start a new Rails project/app called `BunnyApp`. What command should I type in the terminal?

rails new BunnyApp

### Question 2

I want to create a new model called `Bunny`, with the following attributes: name (string), color (string), and age (integer). What command should I type in the terminal?

rails generate model Bunny name:string color:string age:integer

### Question 3

What does the command in Question 2 do, exactly? What files are created, where are they located, and what does the database look like at this time? Explain.

It uses a rails generator to generate a model called Bunny which lives in the App directory and a database schema (which lives in the db directory) with three columns: name, color & age and specifies the datatypes for each as: string, string, integer

### Question 4

I want to create a database and make it reflect the new model I created in Question 2. What command(s) should I type in the terminal?
rake db:create
rake db:migrate



### Question 5

I want to look at the actual database that has been created. What command should I type in the terminal?

psql
/d Bunny


### Question 6

I want to see a list of all the URLs available in my app, along with the HTTP requests and controllers associated with them. What command should I type in the terminal?

rake routes

### Question 7

I have worked on my app and finally want to see it in action. What command should I type in the terminal, and where should I navigate to in my browser?

1.  rails server
2.  localhost:3000

