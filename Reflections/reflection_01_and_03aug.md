# Class Reflection – 01-09-2026 & 03-09-2026

## Topics Covered

- Discussion of individual student projects and their technical requirements
- Introduction to matrices, matrix rank and the equation AX = B
- Using matrices to represent equations related to triangles
- Converting mathematical problems into programming inputs
- JavaFX canvas and mouse events
- Drawing circles and connecting graphical objects using arrows
- Introduction to binary trees and hierarchical data structures
- Understanding root, parent and child nodes
- Representing trees through ASCII characters
- Vertical and horizontal structures in text-based graphics
- Differences between console-based and graphical applications
- Remote computing and supercomputing systems
- SSH, daemon processes, login nodes and master nodes
- Unit testing and acceptance testing
- FXML and its application in JavaFX
- Splash screens and application loading
- Automatic serialization
- Background tasks and progress bars
- Threads and thread cancellation

## Class Notes and Understanding

### 1. Learning Through Project Discussions

An important part of these classes involved discussing the projects assigned to different students. What I found interesting was that the discussions were not limited to the requirements of one particular project. Instead, we were introduced to several programming concepts through the problems and challenges that students were expected to solve.

I realised that project discussions can be a useful way of understanding how theoretical concepts become relevant when applied to an actual task. Different projects required different approaches, and even though the projects were being developed using programming, their underlying requirements varied considerably.

For instance, some involved mathematical calculations, while others required graphical representations, data structures or interaction with remote systems. Listening to these discussions helped me understand that programming is not restricted to writing instructions in a particular language. It also involves identifying the nature of a problem and deciding which concepts or tools would be appropriate to solve it.

This made me look at programming projects as a combination of smaller problems rather than one large coding task.

### 2. Matrices, Matrix Rank and AX = B

We were introduced to the use of matrices in representing and solving mathematical problems. One of the important concepts discussed was expressing a system of linear equations in the form:

**AX = B**

Here, A represents the coefficient matrix, X represents the unknown variables and B represents the constant values.

The concept of matrix rank was also discussed. As I understood it, rank helps us identify the number of linearly independent rows or columns in a matrix. It becomes useful when analysing systems of linear equations and determining whether they have a unique solution, multiple solutions or no solution.

Initially, I viewed matrices mainly as a mathematical topic involving rows, columns and calculations. However, this discussion helped me understand that they can also be used as a structured way of representing information that a computer can process.

I found the connection between mathematics and programming particularly interesting because it demonstrated that mathematical concepts do not necessarily remain limited to textbook problems. They can become part of the logic behind a software application.

I would still like to understand matrix rank and its application to solving equations more thoroughly, but the discussion gave me a clearer idea of why matrices are useful in computational problems.

### 3. Converting Triangle Equations into a Programming Problem

The discussion about a student's project involving triangle equations helped extend the previous concept of matrices.

The task involved taking mathematical equations as input and using them within a programming application. This made me think about the difference between how a person understands a mathematical problem and how a computer needs that problem to be presented.

A person can look at an equation and understand the relationship between its different components. A computer, however, needs the information to be represented in a structured format before it can perform calculations.

One way of doing this is by identifying the coefficients and variables and organising them into matrices. Once the equations have been represented in this form, the program can process the information through mathematical operations.

What I took away from this discussion was the importance of breaking down a problem before attempting to code it. Rather than immediately thinking about the programming language, it is necessary to understand the mathematical structure of the problem first.

This also helped me recognise that programming often requires translating information from one form into another.

### 4. JavaFX Canvas and Mouse Events

Another interesting discussion involved a JavaFX project in which circles had to be drawn on a canvas through mouse interactions and then connected using arrows.

The concept introduced here was event-based interaction. Instead of a program simply executing a fixed sequence of instructions, it can respond to an action performed by the user.

For example, when a user clicks on a particular location on the canvas, the application can identify the mouse event and use the cursor coordinates to determine where a circle should appear.

The requirement of connecting these circles using arrows introduced another aspect of graphical programming. The program needs to identify the positions of the objects and draw connections between them while also indicating the direction of those connections.

I found this interesting because it made me think about how much coordination happens behind something that looks relatively simple on a screen.

A circle appearing after a mouse click may seem like a small feature, but the application needs to recognise the event, obtain the relevant coordinates and generate the graphical object at the correct position.

This discussion gave me a better understanding of how user interaction becomes part of the logic of an application.

### 5. Binary Trees and Their Structure

The classes also introduced binary trees, which are a way of organising data through a hierarchical structure.

Unlike a linear arrangement of elements, such as an array or a list, a tree represents relationships between different elements through connected nodes.

The first node is called the root node. A node that connects to other nodes below it is known as a parent, while the connected nodes below it are called children.

In a binary tree, each node can have a maximum of two children, generally referred to as the left child and the right child.

I found this concept useful because it introduced a different way of looking at how information can be organised. Until now, I had mostly associated storing information with arranging elements in a sequence. The idea of representing relationships through levels and branches helped me understand why different data structures are required for different situations.

Binary trees can be useful in applications involving searching, organising information and representing hierarchical relationships.

Although I am still familiarising myself with how these structures work, I could understand the basic idea of how one element can be connected to other elements without everything being arranged in a straight sequence.

### 6. ASCII Trees and Text-Based Representation

Along with binary trees, we discussed representing tree structures using ASCII characters.

An ASCII tree uses ordinary characters to show the connections between different nodes. Instead of displaying a tree through a graphical interface, the structure can be represented directly through text.

The arrangement of characters is important because spacing and positioning help communicate the relationship between different nodes. Vertical and horizontal lines can be used to indicate branches and connections.

I found this topic interesting because it showed that the representation of information does not always require advanced graphics or visual elements.

A structure that might normally be displayed using diagrams can also be communicated through a simple text-based format. However, doing this requires careful attention to the positioning of characters so that the hierarchy remains understandable.

This also connected to the broader discussion about consoles and graphical interfaces. It showed me that even a simple terminal can be used to communicate information in a structured and meaningful way.

### 7. Console, Terminal and Graphical Applications

We also discussed the differences between console-based applications and applications that use graphical user interfaces.

A console-based application primarily communicates through text. The user enters commands or information, and the program provides a response through textual output.

Graphical applications, on the other hand, use visual elements such as buttons, windows, images, shapes and other interface components.

One thing I understood from this discussion was that the choice between these two approaches depends on what an application is expected to accomplish.

A console-based application can be suitable for tasks where the main requirement is processing information or displaying results. It can also make it easier to focus on the underlying functionality without having to build a complete graphical interface.

A graphical application is more appropriate when visual interaction and ease of use are important.

Earlier, I tended to associate a more visually developed application with a better application. However, this discussion helped me realise that appearance alone does not determine how effective a program is. The design should depend on its purpose and the needs of the person using it.

### 8. Remote Computing and Supercomputing Systems

Another topic introduced during the classes was connecting to remote computers and working with more powerful computing systems.

We discussed how users can access another computer through a network and perform operations without physically using that machine.

SSH, or Secure Shell, was introduced as a method of establishing a secure connection with a remote system. Through this connection, users can execute commands and work with files on another computer.

We also discussed login nodes and master nodes in the context of larger computing systems.

A login node provides an entry point through which users access the system, while the discussion of master nodes introduced the idea of how larger computing environments organise their operations.

This topic made me realise that computing does not always have to take place on the device immediately in front of us. Some tasks require access to systems with greater computing capabilities, and remote connections make this possible.

I found this particularly interesting because it introduced me to an aspect of computing that is not usually visible when using an ordinary personal computer.

### 9. SSH and Daemon Processes

The discussion of remote systems also introduced daemon processes.

A daemon is a process that operates in the background and provides particular services without requiring continuous interaction from the user.

This helped me understand that a computer performs several operations that are not necessarily visible on the screen. Even when a user is interacting with a simple application, background processes may be responsible for handling communication and other necessary operations.

In the context of remote computing, these background processes help systems remain available to respond to requests.

I found this concept useful because it changed my understanding of how much activity takes place beyond the commands that a user directly enters.

It also made me realise that understanding a computer system involves looking beyond its visible interface and considering the processes that allow it to function.

### 10. Unit Testing and Acceptance Testing

Testing was another important topic discussed in relation to software development.

We were introduced to unit testing and acceptance testing, which serve different purposes during the development of an application.

Unit testing involves checking individual components of a program to determine whether they work as expected. For example, a particular method or function can be tested independently to verify its output.

Acceptance testing focuses on whether the completed application meets the requirements for which it was developed.

This distinction helped me understand that testing is not simply about checking whether a program runs without displaying an error.

Individual components may function correctly when tested separately, but the complete application must also satisfy the expectations of its intended users.

I realised that testing should be considered an important part of the development process rather than something that is done only after all the coding is finished.

### 11. FXML in JavaFX Applications

We also discussed FXML and its role in developing JavaFX applications.

FXML provides a way to describe the structure of a user interface separately from the Java code that handles the application's functionality.

This means that interface elements can be organised in a separate file rather than having everything written directly into the main Java program.

I understood this as a way of separating the visual arrangement of an application from the logic that makes it work.

This can make a project easier to organise, particularly when an application contains several interface components.

The discussion also helped me understand why a programming project may contain different types of files. A complete application is not necessarily made up of Java source files alone. It may also require files that define the interface and other resources.

### 12. Splash Screens

A splash screen was another concept introduced during the classes.

It is the screen that appears when an application is launched, usually displaying the application's name, logo or loading information.

Although it may appear to be a small design element, a splash screen can serve a practical purpose by informing users that the application is starting.

This made me think about the importance of considering the user's experience even before the main application becomes available.

An application should not only perform its intended functions but should also communicate with its users during different stages of operation.

### 13. Automatic Serialization

We also briefly discussed automatic serialization.

Serialization involves converting an object's data or state into a format that can be stored or transferred. This information can later be reconstructed when required.

I understood the basic purpose of serialization as allowing information within a program to be preserved instead of existing only temporarily while the program is running.

The idea of automatic serialization also introduced the possibility of handling this process without manually converting every individual part of an object.

Although this was one of the concepts I found less familiar, it helped me recognise that data management is another important part of developing larger applications.

### 14. Progress Bars and Background Tasks

The classes also covered progress bars and their relationship with background tasks.

A progress bar gives the user an indication of how much of a particular operation has been completed. It becomes useful when an application performs a task that takes some time.

We discussed how performing a lengthy operation on the main application thread can cause the interface to stop responding.

Background tasks help address this issue by allowing longer operations to take place without unnecessarily interrupting the user's interaction with the application.

This made me understand that developing an application involves more than ensuring that its functions produce the correct output. It is also necessary to consider how the application behaves while those functions are being executed.

A program that performs the correct operation but becomes unresponsive during the process may still provide a poor experience.

### 15. Threads and Thread Cancellation

Threads were another concept discussed in connection with background operations.

A thread represents a separate path of execution within a program. Using multiple threads can allow certain tasks to run independently instead of making the entire application wait for one operation to finish.

This becomes particularly important in graphical applications where the interface should remain responsive even when the program is performing a lengthy task.

We also discussed thread cancellation, which refers to stopping an operation that is currently running.

For example, if a user starts a lengthy process and then decides that it is no longer required, the application should have a way to handle that request.

This introduced me to the idea that programming also involves planning for situations in which an operation needs to be interrupted rather than simply allowing every process to run until completion.

I found this useful because it showed how the behaviour of a program needs to be considered under different circumstances, not just when everything proceeds as expected.

## Combined Reflection

The classes held on 1 September and 3 September introduced us to a wide range of concepts through discussions of individual student projects. Although the topics covered were quite different from one another, I gradually began to recognise that they were connected through a common idea: solving problems by choosing appropriate methods, structures and tools.

One of the things I found valuable about these classes was the opportunity to encounter concepts that were not necessarily part of one single programming task. The discussions moved from mathematical representations to graphical applications, data structures, remote computing and software testing. Initially, these topics seemed like separate areas of programming. However, looking at them together helped me understand that developing an application requires several different kinds of knowledge.

The discussion of matrices and triangle equations particularly helped me recognise the relationship between mathematics and programming. A mathematical problem first needs to be understood before it can be converted into instructions that a computer can process. The representation of equations through AX = B showed me how mathematical information can be organised into a form suitable for computation. I realised that the process of programming does not always begin with writing code. Sometimes, the more important first step is understanding the problem and finding a suitable way to represent it.

The JavaFX discussion introduced a different aspect of programming. The idea of drawing circles through mouse interactions and connecting them using arrows helped me understand how applications respond to user actions. Something as simple as clicking on a screen involves the program recognising an event, processing information about the mouse position and producing the required graphical output. This made me more aware of the logic that exists behind visual elements in an application.

I also found the discussions of binary trees and ASCII representations useful because they introduced me to different ways of organising and displaying information. Binary trees demonstrated how data can be arranged through hierarchical relationships, while ASCII trees showed that these relationships can be communicated even without a graphical interface. Connecting this to the discussion of consoles and terminals helped me understand that the method of displaying information should depend on the purpose of the application rather than simply on how visually developed it appears.

Another important area of learning was remote computing. Before these discussions, I mainly associated using a computer with performing tasks directly on my own device. Learning about SSH, remote systems and login nodes introduced me to a larger computing environment in which different machines can be accessed and used for specific purposes. The discussion of daemon processes also helped me understand that many operations take place in the background without requiring direct interaction from the user.

The concepts related to JavaFX development, including FXML, splash screens, serialization, progress bars and threads, helped me look at applications from a broader perspective. I began to understand that developing software is not only about making its main functionality work. The way an application is organised, how it stores information, how it communicates its progress and how it responds when a user wants to stop an operation are also important considerations.

The discussion of unit testing and acceptance testing further strengthened this understanding. A program may contain individual components that work correctly, but that does not automatically mean the complete application fulfils its intended purpose. Testing helps examine the different parts of a program as well as whether the final product meets its requirements.

I would say that not every concept discussed during these classes became completely clear to me immediately. Topics such as matrix rank, serialization and thread management are areas that I would like to revisit and understand in greater depth. However, I found it useful to be introduced to them in the context of actual programming requirements rather than only learning their definitions independently.

One thing I would like to explore further is how these different concepts can work together within a single project. For example, a graphical application may use mathematical calculations, organise information through data structures, perform operations in the background and rely on testing to verify its functionality. Thinking about such connections helps me understand why learning individual programming concepts is important.

If I had to explain the overall learning from these classes to someone new to programming, I would say that developing software is similar to solving a problem through several connected stages. First, the problem needs to be understood. Then, the information must be organised in a suitable way, the appropriate tools and methods must be selected, and the solution must be developed and tested. The final application should not only work but should also be understandable and usable.

Overall, these two classes helped me move beyond looking at programming as simply writing code to produce an output. I began to see it as a broader process involving mathematical reasoning, logical organisation, user interaction, system management and continuous testing. My biggest takeaway was that a successful application depends not on one programming concept alone, but on how several different concepts are brought together to solve a particular problem.
