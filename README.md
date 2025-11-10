**Question 1  :  what is Asp.Net Core ?**

ASP.NET Core is a free and open-source web framework developed by Microsoft. It runs on any operating system (Windows, Linux, macOS) and is used to develop web applications, REST APIs, and other modern web services. The term 'open source' means it is free to use and its source code is publicly available
                                
**Question 2  :  Different between both**

**ASP.NET (Classic) **                                                                                    ** ASP.NET Core**
Runs only on Windows                                                                                      Runs on Windows, Linux, macOS (Cross-platform)
Closed source (mostly)                                                                                    Open Source
Uses System.Web (monolithic pipeline)  all in one                                                         Uses a lightweight, modular middleware pipeline
Supports Web Forms, MVC, Web API, SignalR separately                                                      Suppots  Unified Programming Model
Deployment: IIS only                                                                                      Deployment: Kestrel, IIS, Nginx, Docker, etc.

**Question 3 : What is mvc  ?**

MVC (Model-View-Controller) is a design pattern widely used to build software applications by separating concerns into three distinct roles
Model: Responsible for creating the data model and implementing business logic
View: Represents the user interface (UI)
Controller: Handles user input and interactions. It acts as an intermediary between the Model and View

**Question  4 What is middileware** 

In ASP.NET Core, middleware is a software component that processes HTTP requests and responses. During this processing, middleware components are arranged in a sequence called a pipeline, which follows a chaining system. Each middleware can handle the request and response or pass control to the next middleware in the pipeline.

Question **What Is Dependency Injection   and its  Types**
In ASP.NET Core, Dependency Injection (DI) is a design pattern that allows for decoupling of components, making the application more modular, testable, and maintainable
**Constructor Injection (Most Common in ASP.NET Core)
Setter Injection (Property Injection)
Method Injection**

Q. **Kestral Server**
Kestrel is a cross-platform web server for ASP.NET Core. Kestrel is the web server that's included and enabled by default in ASP.NET Core project templates
in  ASP.Net Core by Defualt Use Kestrel Server when not host on IIS In Program.cs file UseKestrel Internally by this  line  **var biulder =WebApplication.CreateBuilder(ags)**
and  Run the  Kestrel Server  by **aap.Run()**

**Q Static in C#**
In C#, the static keyword is used to define members that have only one copy for the entire class.
A static member belongs directly to the class, not to any specific object.
It can be accessed without creating an object of the class
it 's Uses 
**Static Variable (Field)**                  A variable that has only one copy for the entire class.
**Static Method**                        A method that can be called without creating an object
**Static Class**                         A class that cannot be instantiated (no object), and only contains static members
**Static Constructor**                   A special constructor that runs once automatically before the first use of the class.

