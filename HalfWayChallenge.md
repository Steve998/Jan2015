# Half Way Challenge

1. What is a class?

A guide to how an object is built

2. What is an attribute?

Things the object stores in variables

3. What is an object?

an instance of a class

4. What type of object is a PORO?

Plain Old Rails Object

5. What is a Rails model?

class that stores instance of data

6. What is your absolute favorite meal?

nothing is absolute (except zero, but that is just a term used for a measurement) but I do like breakfast

7. What is the difference between a locally scoped variable and an instance variable?
scoped variables are made available to all models  Instance variable belongs to an object


8. Why do we use version control like git?

To recover and/or use previous versions of code for various reasons. Can also have branches of code for several people to work on at same time

9. What is the difference between git and GitHub?

git is a command GitHub is the product for version control



10. What is your ideal vacation?

Good question. I have no real answer at this time.

11. What does the pattern of Separation of Concerns mean and why do we use it?

Separate tasks into pieces. Working on smaller more manageable pieces is easier
and more productive

12. What does the pattern MVC mean?

Model View Controller

13. What is the difference between a Rails model and a database table? What is their relationship?
Database table holds the data; Model tells how to deal with the data


14. How do we modify the database for our Rails app?

rails g migration add_field_to_table field:string

15. What do you do to relax?

take a short break and do something else before returning to the tasks at hand

16. What is a gem and how do we use them in our Rails apps?

Allows programmer to add functionality to apps using libraries. Used by setting up in a Gem file then running command ‘bundle install'

17. In what part of a Rails application do we tell it how to handle an HTTP request to a specific path, like: `http://localhost:3000/movies`?

the Routes table?

18. In what part of a Rails application do we hold data provided by the user, in order to use it, save it to the database, or retrieve it from the database?

The Model

19. In what part of a Rails application do we render data, in HTML, to present to the user?

The View

20. What TV show do you never want to miss?

lol. No TV show is really that important

21. What part of a Rails application processes actions, uses models, and directs flow to the proper view?

The Controller

22. If your app gave you the following error message, on this line of code, what would it indicate?


        undefined method `downcase' for nil:NilClass


        <%= user.name.downcase %>

  The name has a value of nil

23. What gem did we use to paginate our Collections?
 The will_paginate


24. What gem did we use to provide upload functionality?

Carrierwave and fog


25. What is your favorite musical artist or group?

Wide variety depending on mood and really enjoy the live music but not really into rap and hip hop. Some of the artists I have seen live are The Alarm, The Smithereens, Van Halen, Grateful Dead (also JGB and Ratdog), The Rolling Stones, Guns and Roses, James Taylor, Bruce Springsteen, The Clash, Jimmy Buffett, Arlo Guthrie.

26. What technology do we use to style HTML in the browser?

Stylesheets using CSS or SCSS

27. What type of view templates have we been using in our class to create dynamic HTML?

Bootstrap

28. What type of helpers do we use to check data against certain rules and requirements before it is saved to our database?

Validations

29. What are model associations?

This is how we can connect different models together by describing the relationship between the data in the tables.  has_many, has_one

30. Based on the name, if The Iron Yard wasn't a code school, what else might it be?

Odd question but A place to store iron similar to junk in a junk yard.

31. What code would you use to find the a User record in the database with an id of 17?
User.find_by( id: 17 )


32. If you want to use an image inside your app, in what directory do you put it?

app/assets/images

33. What helper do you use to create a form to edit or create a specific resource?

generate. this can also be just the letter 'g'

34. What does this mean? `||=`
This will assign the variable on left side to the value on right if it is not already assigned. This includes assigning it to nil

35. What is your nickname? If you don't have one, what do you wish it was?
No comment


36. What is a scope? Please provide one example.
Setting up a subset of a collection. I can give an example when I get caught up and fully understand the purpose

37. What is _rake_? Give some examples of how and when we use it?

rake is the rails equivalent to unix make. it sets up commands to be run including other rake commands
After creating a migration to add a column to a data base table, run the command
'be rake db:migrate' to make the database change

38. How do you deploy your app to Heroku?

push code to github

heroku create

git push heroku master

heroku run rake db:migrate

39. What gem can we use to provide a fast, yet custom and robust, administrative section for our apps?

gem activeadmin

40. What is does _anopisthographic_ mean?

having pages with writing only on one side (had to look this one up)

41. If a User has many ParkingTickets, and the `user` variable points to a User object, what code would you use to get all the ParkingTickets?

user.parkingtickets.all


42. If an Address model has a postal code attribute, what code would you use to get all Addresses from the database with a postal code of _33771_?

Address.all.find_by postal_code: ‘33771'

43. How do you create a new Book object in the database, if a Book class has the following required attributes: title, author, publish_year, pages?

Book.new will create the new object

44. If we get this message in our log after attempting to save an object, what does it mean?


        Unpermitted parameters: first_name

Attempting to add a parameter for attributte first_name and it is not part of the object

45. What one question do you wish I would have asked?
Saw this question but do not really have an answer, yet.
