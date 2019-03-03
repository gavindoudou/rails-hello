# README

This toy_app helps me understand the MVC pattern in Ruby on Rails.

Here is an example: 
1. The browser issues a request for the /users URL.

2. Rails routes /users to the index action in the Users controller.

3. The index action asks the User model to retrieve all users (User.all).

4. The User model pulls all the users from the database.

5. The User model returns the list of users to the controller.

6. The controller captures the users in the @users variable, which is passed to the index view.

7. The view uses embedded Ruby to render the page as HTML.

8. The controller passes the HTML back to the browser.

* ruby 2.6.0p0 (2018-12-25 revision 66547) [x86_64-linux]

* Rails 5.1.6

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions
