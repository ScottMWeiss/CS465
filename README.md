# CS465

Architecture

    Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
For this project, Express HTML was more used for the client-side of the application, due to its use for quick loading of static content. JavaScript was used to provide the interactivity which includes dynamic updates to the HTML content. With the Angular Single-Page Application (SPA), this admin-side of the application was used for more dynamic interactions and would deal with interactive elements such as CRUD operations from the application or from the MongoDB Compass or Postman applications.

    Why did the backend use a NoSQL MongoDB database?
With this project, a NoSQL MongoDB database was used for its flexibility and scalability. The MongoDB structure can allow for quick and easy changes to data if needed, as well as easily viewing the structure of existing data.

Functionality

    How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
JavaScript Object Notation (JSON) is different from JavaScript in that it's more used as a lightweight way of storing and transporting data, while JavaScript is more of a solid core programming language that helps to enable aspects like HTML websites. JSON helps to be a communicator for frontend and backend development, such as the SPA making requests to get data from the database.
    
    Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
A few instances where the code was refactored for functionality and efficiency were in some of the component.html files. One example would be in the trip-listing.component.html file where a 'class' attribute was set to put the number of columns for putting in the trip cards. This made the site more user friendly to view and use. Another would be in the trip-card.component.html file where the editTrip functionality was changed to only allow if a user was logged in. This helps to benefit the project by streamlining the code, making it both consistent and easily manageable as the project scales.

Testing

    Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
Using various methods such as the GET, POST, and PUT functions through Postman allowed data from the MongoDB database to be collected or changed through implementation in the codebase. The API endpoints would be how the client would communicate through the server using said methods. Security testing was initially performed through Postman, first registering a user with sample data which provided a web token, and then using that sample data to send to the login, which would give back the token from earlier, which could then be added to give authorization to make and edit entries. These tokens were verified through jwt.io to ensure they were successful.

Reflection

    How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
This course served as a great introduction into the world of full stack development. Learning more about the structure of a website as well as putting it all together will be helpful knowledge moving forward into the professional world.




