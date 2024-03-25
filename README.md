MVC


Model View Controller

Model = Database

View = Client

Controller = Server

What MVC is not:

MVC is not a framework.  It is a way of thinking organizationally when coding.   Many popular frameworks use the MVC structure but it is not a framework.  

Benefits of MVC:

•	Helps prevent repetition 
•	Makes is easier to structure everything.
•	Different programmers can work on different parts of the same project which can speed up the process
•	Easier modification and updates 

Model: 
– Only talks to the DB.  Giving or receiving items from DB.  Processing data to or from DB.  Controller speaks to the model and then the model talks to the DB.  Model will never contact the View directly.  

View:
-Only thing the user ever sees.  HTML/CSS is example.  Listens to the controller.  Never communicates with model.  View never makes decisions for itself. It only listens to the controller.

Controller:
-Interacts with the user.  The controller receives and processes GET/POST/PUT/DESTROY requests.  It’s the middle man.  Takes info from user, processes info and talks to DB if necessary, receives info from DB, Speaks to view to explain presentation to viewer.  The bulk of your code, or at least logic, is in the controller.

