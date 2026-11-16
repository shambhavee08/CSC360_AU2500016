# Class Reflection – 18-08-2026

## Topics Covered

- Moving Square in Computer Graphics
- Understanding Coordinate Systems
- Using Coordinates to Create Motion
- Java Graphics Application Structure
- Introduction to JFrame and Java Packages
- Maven Project Structure and Build Files
- Understanding `pom.xml` and the `target` Folder
- Objects, Classes and Static Fields in Java
- Importance of Developing Logic Before Coding
- Algorithm Development and Problem-Solving

## Notes

### 1. Moving Square in Computer Graphics

One of the main concepts discussed during this class was creating a moving square using Java Graphics. Although drawing a square may seem like a basic programming task, making it move requires us to understand several things before writing the actual code.

We first need to decide where the square should appear on the screen, what its dimensions should be and how its position will change. We also need to consider the relationship between the coordinates of the square and the dimensions of the screen.

This discussion helped me understand that creating a graphical object is not simply about displaying a shape. We also need to define its properties and decide how it should behave when the program is running.

I found it useful that the class focused on understanding the problem before moving towards implementation. It showed me that even a simple graphical task requires planning and logical thinking.

### 2. Coordinate System and Motion

Another important concept covered was the use of coordinates to control the position of graphical objects.

A square is positioned on the screen using its x and y coordinates. These values determine where the object appears, and changing them allows us to reposition it.

The concept of motion was particularly interesting because I learned that an object does not actually move on its own. Instead, its position is repeatedly updated, and the screen displays the object at its new location.

For example:

- Increasing the x-coordinate moves the square towards the right.
- Decreasing the x-coordinate moves it towards the left.
- Increasing the y-coordinate moves it downwards.
- Decreasing the y-coordinate moves it upwards.

This helped me understand the relationship between coordinates and movement. Before learning about this, I would have thought of motion as something that simply happens when an animation is played. However, I now understand that it can be created through repeated changes in an object's position.

It also made me realise why understanding the initial position of an object is important before attempting to control its movement.

### 3. Java Graphics Application Structure

The class also helped me understand the basic structure of a Java Graphics application and how its different components work together.

We discussed `JFrame`, which provides the main window for a Java Swing application. It acts as the container in which graphical elements can be displayed.

Another concept introduced was Java packages. Packages help organise related classes and provide a structured way of arranging code within a project.

I understood that a Java application is not necessarily made up of one continuous block of code. Instead, it can contain multiple classes and packages, each performing a particular role.

This made me appreciate the importance of understanding how different parts of a project are connected rather than viewing every file or class as an independent element.

### 4. Maven Files and Project Organisation

We also revisited the organisation of Java projects and the purpose of certain files and folders used during development.

The `pom.xml` file was discussed as an important part of a Maven project. It contains project-related information and manages dependencies, plugins and build configurations.

We also learned about the `target` folder, which stores the output generated during the build process. Unlike the source files that developers create and modify, the contents of this folder are generally generated automatically when Maven builds the project.

This helped me understand the difference between files that are part of the original project structure and those that are produced as a result of executing build operations.

I found this useful because it gave me a better idea of how a Java project is organised beyond the source code that we directly work on.

### 5. Objects, Classes and Static Fields

Another important part of the session involved understanding objects and static fields in Java.

I learned that a class acts as a blueprint that defines the properties and behaviours that its objects can have. An object is an instance of a class and represents something created using that blueprint.

For example, a class can define the general properties of a square, while individual square objects can have their own positions or dimensions.

We also discussed static fields. Unlike ordinary instance fields, static fields belong to the class itself rather than to individual objects. They can be accessed through the class and are shared across its instances.

This distinction helped me understand that not every variable in Java belongs to a particular object. Some information is associated with the class as a whole.

Although I am still developing a stronger understanding of object-oriented programming, this discussion helped me distinguish between classes, objects and the information associated with them.

### 6. Logic Before Coding

One of the most important ideas I took away from this class was the importance of developing the logic of a program before beginning to code.

The discussion focused on understanding what a program is supposed to accomplish and identifying the steps required to achieve that result.

Using the moving-square example, we first needed to decide what movement meant, identify the square's initial position and determine which coordinates would need to change.

These steps could then be organised into an algorithm before being translated into Java code.

I understood that this approach helps avoid writing code without having a clear idea of the expected outcome. It also makes it easier to identify possible mistakes in the logic before they become part of the actual implementation.

The concept made me realise that programming is not limited to writing code in a particular language. A significant part of it involves analysing a problem, planning a solution and organising the steps needed to solve it.

## Reflection

This class helped me develop a better understanding of how graphical objects are created and controlled through programming. What I found particularly interesting was that the movement of something as simple as a square could be explained through changes in coordinates. It made me look at graphical movement differently because I could now connect what appears on the screen with the calculations and instructions taking place behind it.

The moving-square example was probably the most useful part of the session for me. I realised that before making an object move, it is necessary to understand its initial position and decide how that position should change. The relationship between the x and y coordinates made the concept easier to understand because it gave a clear explanation of how an object can move in different directions.

I also found the discussion about Java's structure useful. Learning about JFrame, packages, Maven files and the target folder helped me understand that building an application involves more than writing the main program. Different components have different responsibilities, and knowing how they fit together makes it easier to understand the overall project.

The discussion about classes, objects and static fields was another important learning experience. These concepts helped me understand how Java organises information and functionality. I realised that classes and objects are related but serve different purposes, and that static fields behave differently from variables associated with individual objects. I would still like to practise these concepts further to become more comfortable identifying their uses in actual programs.

However, the idea that stood out to me the most was developing logic before coding. I sometimes tend to think about the code that needs to be written before fully understanding the problem itself. This class made me realise that approaching a programming task in this way can make it unnecessarily confusing. Taking time to understand the expected output, identify the required inputs and plan the sequence of operations can make the actual coding process much more manageable.

I think this approach is useful beyond Computer Graphics as well. Whether the task involves creating a graphical object or developing a larger application, having a clear plan can help make the solution more organised.

Overall, this session helped me understand the connection between logical thinking, mathematical concepts and Java programming. My biggest takeaway was that writing code is only one stage of programming. Understanding the problem and developing the right approach beforehand are equally important parts of creating a working application.
