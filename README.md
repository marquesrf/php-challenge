

![](https://lh3.googleusercontent.com/-SjJCP2AntwI/XoYRxI-hBjI/AAAAAAAABA4/bFi0th7AKGgQFVIOB8L-GiWSZriYhI6MgCK8BGAsYHg/s0/2020-04-02.png)
# Instituto Atlântico Fullstack Developer Challenge

Hi! this is a simple challenge for the Fullstack Developer job position at Instituto Atlântico. This challenge consists of creating a simple REST API and showing the results in a Web Page. You can use any language, framework, lib and database you desire, but we are specially looking for someone with good PHP and JavaScript skills! To start, create a new branch for this repo, and when you're done, submit a Pull Request for us to review your code.

### API Description

In this challenge you will create an API for a library with these conditions:

* **Login, Register and Logout:** Authentication

  _Create routes for session handling with JSON Web Tokens._
  
* **Books:** Entity

  _Routes for creating, editing, listing and deleting books. Books must have a Title and an unit count for how many copies exist in the library._
  
* **Users:** Entity

  _Routes for creating, editing, listing and deleting users. Keep it simple: Give them a name, email and password._
  
* **Book Rents:** Relationship

  _Users will be able to rent books. The API must be able to associate rented books to users, date of rent, the payment value, status(the rent can be ongoing, late or paid) and the rent expiration date. The API must also be able to list all ongoing book rents, and must have routes for the user to deliver the book and set rent status to paid. Also remember that books have limited copies! If there are no more copies of a book, an user cannot rent it until another user delivers a copy of that book._
  
 ### Frontend Description

Having created the API, you must now request and exhibit data following these directions:

* **Login/Register:**

  _Create a Login/Register page. Unauthenticated users should always be redirected to this page. The user should also be able to Logout. This can be a simple button and does not require a full page._
  
* **Home Page**

  _The home page should be a list of all available books. The user can select a book to rent, which will take him to the next page: **Checkout**. Creating a shopping cart for adding multiple books is not necessary, but it will be a big bonus._
  
* **Checkout** 

  _This is the checkout page for a book rent. This could be a modal instead of a full page. Here the user will select the date of rent, and an expiration date of 1 week will be shown. The user must cofirm the action. The book status and the total amount of available books should be updated accordingly._
  
* **My Books**

  _This page should list all books which the current user has rented, showing the date of rent, expiration date and status. Pending or late books should have an action button to pay for the book, followed by a confirmation modal or prompt._
  
* **Error Handling:** 

  _There are many possible situations where an API request might fail. Make sure that you catch all of those errors and correctly show them to the end user._
  
  
### Some observations and tips

* Make sure to write a nice README telling us a bit about your code, like what libs or frameworks you used.
* The README must also include instructions to run your code.
* You will be evaluted for: code writing, patterns, structure, readibility, size and elegance (among other things).
* Your ability to write and document consistent code in english will also be evaluated.
* **Push your code even if you do not meet all the requirements**. We are looking to see if you are capable of learning new things and how you work, any effort will count.
* Feel free to make any changes or add something to the challenge, just remember to tell us about it in the README.
* There's almost no right or wrong for the architecture of the project. If you feel more confident in doing server-side templating rather than a Single Page App, then do it! Just make sure there's room to show you have a good grasp of JS and CSS3.
* Use your creativity on the Frontend! This is your chance to show your CSS3 and HTML5 skills to create a nice, responsive design.
* Consider how you will manage dependencies in your application. _Tip: if using PHP, use [Composer](https://getcomposer.org/)_
* Unit Tests will be a big bonus.
* Virtualization is not mandatory, but will be a bonus. At Atlântico, we often use [Docker](https://www.docker.com/), and you can use [Docker Toolbox](https://docs.docker.com/toolbox/overview/) if your computer does not meet the requirements for Docker Desktop.
*  Hosting is not mandatory for this challenge and you will not be penalized, but it will be a bonus. There are some free hosting services like [Heroku](https://www.heroku.com/free).


**Good Luck!**
