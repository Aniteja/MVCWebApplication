## MVCWebApplication
ASP.Net MVC is a web application framework developed by Microsoft which follows the Model-View-Controller pattern. It is an alternative 
implementation method for ASP.Net Web Forms. It is widely used in developing applications in the recent era because of its ease of use and efficiently divides an application into 3 seperate components - Model, View and Controller.

- Model : It is a set of classes which contain the data and the business logic.
- View : It represents the visual representation of the data to the user. 
- Controller : A class or set of classes that handle the user requests and handles the overall application working.

This project is a basic application developed in MVC which handles the login and signup of a user. When the user tries to access the login page, a request is sent to the controller to fetch the requested page and the associated variables and properties from the view and model. Once the user enters his credentials and requests to login, the application verifies for the credentials with the list of Users' Login Id and associated passwords. If it matches, it allows for a successful login and displays a complimentary message and a timestamp of the login. If the login credentials do not match, it displays an error message to verify the details and try to enter the correct details and 
login. Same is the case for a sign-up, where the application requests the user to enter all his basic details in order to sign up. Once the user enters all the details and clicks the button, the associated User ID and password are saved into the database.


