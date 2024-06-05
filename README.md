1. Onion Architecture: (Yes/No) Have you heard of the Onion Architecture principle in software design?
   The onion architecture organizes software by putting its key parts at the center and surrounding them with layers. This makes it easier to manage and update the software later on.

2. MVC Pattern: (Yes/No) Are you familiar with the Model-View-Controller (MVC) pattern for building web applications?
   Yes, it divides web applications into three parts, the model, view, and controller.

3. Web API: (Yes/No) Do you understand the concept of building RESTful APIs using ASP.NET Core Web API?
   No.

4. Application & Bottlenecks: Onion Architecture: Benefits: (1-3 keywords) Briefly list some key benefits of using Onion Architecture in .NET Core projects. (e.g., separation of concerns, testability)
   -Modularity
   -Testability
   -Scalability

5. MVC: Components: (1-3 keywords each) Briefly describe the roles of the Model, View, and Controller in the MVC pattern.
   Model:
   -Manages data, Business logic
   View:
   -User Interface
  - Presents data to users
   Controller:
   -Interaction Management
   -Orchestrates communication

6. Web API: Differences from MVC: (Yes/No and Briefly Explain) Can you differentiate between traditional MVC applications and Web APIs? Briefly explain the main difference.
   Traditional MVC applications use Controllers to get data from Models and show it directly on web pages through Views. Web APIs, on the other hand, use Controllers to get data from Models but send this data back as JSON or 
   XML for other applications to use, without directly showing it to users.

7. Bottlenecks (Encountered): (Yes/No and Briefly Explain) Have you encountered any challenges with tight coupling between Model and Controller in MVC projects? If so, briefly describe the issue(s). (e.g., Difficulty in unit 
   testing controllers, logic changes rippling through the application)
    Indeed, alterations in one element can unintentionally impact another, resulting in challenges when testing controllers or causing logic adjustments to spread across the application, consequently elevating maintenance 
   burdens.

8. Web API: Differences from MVC: (Yes/No and Briefly Explain) Can you differentiate between traditional MVC applications and Web APIs? Briefly explain the main difference.
  Yes, frequent page refreshes in MVC applications can lead to performance overhead, especially when handling large amounts of data or complex interactions.
