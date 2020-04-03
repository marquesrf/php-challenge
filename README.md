
# Instituto Atlântico PHP Developer Challenge

Hi! this is a simple challenge for the **#GDP-572** job position at Instituto Atlântico. This challenge consists of creating a simple REST API. You can use any framework, lib and database you desire, just make sure to show some of your core PHP and SQL skills! To start, simply **fork** this repository, and when you're done, submit a Pull Request for us to review your code.

### API Description

In this challenge you will create an API for a library with these conditions:

* **Login and Logout:** Authentication

  _Create routes for session handling with Json Web Tokens._
  
* **Books:** Entity

  _Routes for creating, editing, listing and deleting books. Books must have a Title and an unit count for how many copies exist in the library._
  
* **Users:** Entity

  _Routes for creating, editing, listing and deleting users. Keep it simple: Give them a name, email and password._
  
* **Book Rents:** Relationship

  _Users will be able to rent books. The API must be able to associate rented books to users, date of rent, the payment value, status(the rent can be ongoing, late or paid) and the rent expiration date. The API must also be able to list all ongoing book rents, and must have routes for the user to deliver the book and set rent status to paid. Also remember that books have limited copies! If there are no more copies of a book, an user cannot rent it until another user delivers a copy of that book._
  
### Some observations and tips

* Make sure to write a nice README telling us a bit about your code, like what libs or frameworks you used.
* The README must also include instructions to run your code.
* You will be evaluted for: code writing, patterns, structure, readibility, size and elegance (among other things).
* Your ability to write and document consistent code in english will also be evaluated.
* Push your code even if you do not meet all the requirements. We are looking to see if you are capable of learning new things and how you work, any effort will count.
* Feel free to make any changes or add something to the challenge, just remember to tell us about it in the README.
* Consider how you will manage dependencies in your application. _Tip: use [Composer](https://getcomposer.org/)_
* Unit Tests will be a big bonus.
* Virtualization is not mandatory, but will be a bonus. At Atlântico, we often use [Docker](https://www.docker.com/), and you can use [Docker Toolbox](https://docs.docker.com/toolbox/overview/) if your computer does not meet the requirements for Docker Desktop.
*  Hosting is not mandatory for this challenge and you will not be penalized, but it will be a bonus. There are some free hosting services like [Heroku](https://www.heroku.com/free).


**Good Luck!**
