The Model-View-Controller (MVC) pattern is an architectural pattern that separates the concerns of data management, user interface, and user input control. It consists of three main components:

- **Model**: Represents the data and business logic of the application.

	In the MVC design pattern, the _model_ is the data layer which defines the business logic of the system and also represents the state of the application. The model [objects](https://www.edureka.co/blog/java-object/) retrieve and store the state of the model in a database. Through this layer, we apply rules to data, which eventually represents the concepts our application manages.

- **View**: Represents the user interface and displays the data from the model.

	This layer of the MVC design pattern represents the output of the application or the user interface. It displays the data fetched from the model layer by the controller and presents the data to the user whenever asked for. It receives all the information it needs from the controller and it doesn’t need to interact with the business layer directly.

- **Controller**: Handles user input and updates the model and view accordingly.

	The Controller is like an interface between Model and View. It receives the user requests from the view layer and processes them, including the necessary validations. The requests are then sent to model for data processing. Once they are processed, the data is again sent back to the controller and then displayed on the view.


![[Pasted image 20240128152859.png]]

1. The browser on the client sends a request for a page to the controller present on the server
2. The controller performs the action of invoking the model, thereby, retrieving the data it needs in response to the request
3. The controller then gives the retrieved data to the view
4. The view is rendered and sent back to the client for the browser to display

## Advantages

- Multiple developers can work with the three layers (Model, View, and Controller) simultaneously
- Offers improved _scalability_, that supplements the ability of the application to grow
- As components have a low dependency on each other, they are easy to maintain
- A model can be reused by multiple views which provides reusability of code
- Adoption of MVC makes an application more expressive and easy to understand
- Extending and testing of the application becomes easy

---
## Examples

![[Pasted image 20240128152719.png]]

1. Model: `Book.java`
2. View: `BookView.java`
3. Controller: `BookController.java`
4. Main class to run the application: `OnlineBookstore.java`

---
## ChatGPT Interview Questions

#### **Q1. What is the main purpose of MVC architecture in Java?**  

The MVC architecture aims to separate concerns and promote modularity in Java applications. It helps in organizing code, maintaining separation between data, presentation, and logic, and improving overall code quality and maintainability.

#### **Q2. How does MVC enhance code reusability?**  

MVC allows for code reuse by decoupling the Model, View, and Controller components. The Model can be reused across different views, and multiple views can be created for a single model. This separation enables developers to reuse components in different contexts, reducing code duplication and enhancing efficiency.

#### **Q3. How does MVC promote testability?**  

MVC facilitates unit testing by providing clear separation of concerns. Each component can be tested independently, making it easier to verify their functionality and detect issues. Testability is enhanced due to the modularity and well-defined responsibilities of the Model, View, and Controller.

#### **Q4. Can multiple views be associated with a single model in MVC?**  

Yes, in MVC, multiple views can be associated with a single model. This allows for different ways of presenting the same underlying data to users. Each view can cater to specific user interface requirements or target different devices or platforms.

#### **Q5. Does MVC restrict the choice of technologies in Java development?**  

No, MVC is a design pattern that can be implemented using various technologies and frameworks in Java development. The choice of technologies depends on the specific requirements of the application and the available tools and frameworks in the Java ecosystem.

---
## Resources

https://www.prepbytes.com/blog/java/mvc-architecture-in-java/
https://www.javatpoint.com/mvc-architecture-in-java
https://www.tutorialspoint.com/design_pattern/mvc_pattern.htm
https://medium.com/@maheshmaddi92/6-1-model-view-controller-mvc-52e7112d5fae