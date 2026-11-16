# Class Reflection – [Add Date]

## Topics Covered

- Entry point and execution of a Java application
- Maven, JAR files, and repositories
- Dependencies, transitive dependencies, and JavaFX packages
- Java versions, source version, runtime version, and backward compatibility
- UTF-8 and character sets
- JUnit and different types of testing
- CI/CD pipelines, YAML files, integration, and deployment

## Notes

### 1. Entry Point, Maven, JAR Files, and Repositories

In this class, we discussed what happens when a Java application is executed and the different processes involved in running a program. One of the first concepts was the **entry point** of a program. The entry point is where the execution of a program begins. In Java, this is generally the `main()` method. I understood that writing instructions is not enough; the program also needs a defined starting point from which the computer can begin executing them.

We then discussed **Maven** and how it helps manage a Java project. Maven automates several tasks, including compiling source code, managing dependencies, running tests, and packaging the application. We also discussed the `mvn install` command, which builds and installs the project into the local repository.

Another concept was a **JAR (Java Archive) file**. It is a packaged file that can contain compiled Java classes and other resources required by an application. JAR files make it easier to distribute and use Java applications and libraries.

This led to the discussion of **local and remote repositories**. A local repository is stored on our own computer and keeps downloaded dependencies and project packages for future use. A remote repository is hosted elsewhere and allows Maven to download the required libraries and packages. I found this useful because it explained how developers can reuse existing libraries without manually downloading and managing every file themselves.

### 2. Dependencies, Transitive Dependencies, and JavaFX Modules

We also discussed **dependencies**, which are external libraries or packages that a project needs to use particular functionalities. Instead of writing every feature from scratch, developers can include existing libraries in their projects.

An interesting concept was **transitive dependencies**. When we add one dependency, it may depend on other libraries to function properly. Maven can identify and download these additional dependencies automatically. This explains why a project may contain several libraries even when we have directly added only a few.

We also explored some JavaFX packages, including **Controls, FXML, Web, and Media**. Each provides a different set of functionalities. Controls contains interface elements such as buttons, FXML helps define the structure of a user interface, Web provides support for displaying web content, and Media supports multimedia features such as audio and video.

Another concept was a **BOM (Bill of Materials)**. I understood that it helps manage the versions of related dependencies in a project. When several libraries are being used together, keeping their versions compatible is important. A BOM provides a central way to manage these versions and reduce the chances of compatibility issues.

### 3. Java Versions, Source Version, Runtime Version, and Compatibility

We discussed different Java versions, including releases such as **Java 17**, and why version compatibility matters when developing software.

The **source version** refers to the Java language version that the source code is written for and compiled against. The **runtime version** refers to the Java environment used to execute the compiled application. These concepts helped me understand that the version used during development and compilation is not necessarily the same as the environment in which the application eventually runs.

We also discussed **backward compatibility**. It refers to the ability of newer versions of a technology to continue supporting older code or functionality. This is important because organisations may have large applications that were developed using older Java versions. They cannot simply rewrite an entire application every time a new version is released.

I realised that version compatibility is not just a technical detail; it also affects how easily software can be maintained, updated, and used across different systems.

### 4. UTF-8 and Character Sets

Another topic that I found interesting was **character sets and UTF-8**. A character set provides a way to represent different characters, including letters, numbers, and symbols, so that computers can process and display them.

We discussed why different character sets exist and why representing text is more complicated than it might initially seem. Different languages use different characters, so computers need a system that can represent a wide range of them.

UTF-8 is a widely used character encoding that can represent characters from many languages and writing systems. This helped me realise that even something as simple as displaying a sentence on a screen depends on how the computer encodes and interprets the characters.

It also made me understand why consistent character encoding is important when transferring information between applications, files, and different computer systems. Without it, text may not be displayed correctly.

### 5. JUnit and Different Types of Testing

We also discussed **JUnit**, a testing framework used in Java, and the importance of testing during software development. Earlier, I mostly associated testing with running the entire application and checking whether it worked. However, I understood that software needs to be tested at different levels.

One type of testing we discussed was **unit testing**. It focuses on testing individual methods or small parts of a program to check whether they behave as expected. This makes it easier to identify errors in a particular section of the code.

However, even if individual components work correctly on their own, they may not necessarily work properly when combined. This is where **integration testing** becomes important. It checks whether different modules or components of an application work together correctly.

We also discussed **black-box testing**, where the behaviour of a system is tested without needing to examine its internal code. The focus is on providing inputs and checking whether the outputs match the expected results.

These different approaches helped me understand that testing is not a single activity. Each type focuses on a different aspect of the software and helps identify problems that might otherwise go unnoticed.

### 6. CI/CD Pipelines, YAML, Integration, and Deployment

The final part of the class focused on how software development works in a more professional environment. We discussed **CI/CD pipelines**, which help automate different stages of the development process.

CI stands for Continuous Integration, while CD can refer to Continuous Delivery or Continuous Deployment. These practices help developers regularly integrate changes into a shared project and automate processes such as building and testing the application.

We also discussed **YAML files**, which are commonly used to define configuration settings and workflow instructions. In a CI/CD pipeline, a YAML file can specify the steps that need to be performed, such as compiling the code, running tests, and preparing the application.

Another important distinction was between **integration and deployment**. Integration involves bringing different parts of a project together and checking whether they function correctly as a complete system. Deployment is the process of making the application available in the environment where it is intended to run or be accessed.

This discussion helped me understand that writing the code is only one part of software development. An application also needs to be built, tested, integrated, and eventually made available to its users.

## Reflection

This class helped me look at Java development from a much wider perspective. Earlier, I mostly thought about programming in terms of writing a Java file, understanding the syntax, and getting the program to run. However, the concepts discussed in this class showed me that there are several processes involved between writing the code and delivering a working application.

One concept that I found particularly interesting was Maven and its dependency management system. I had come across dependencies before, but I did not fully understand what happened behind the scenes when one was added to a project. Learning about transitive dependencies and repositories helped me understand how Maven manages the additional libraries a project needs. It also made me realise how much of the development process can be automated instead of being handled manually.

The discussion about testing also changed the way I look at a working program. Earlier, I might have considered a program successful if it ran once without showing an error. Now I understand that this does not necessarily mean that every part of it is correct. Unit testing helps check smaller components individually, while integration testing checks whether those components work properly together. Black-box testing adds another perspective by focusing on the behaviour of the application rather than its internal implementation.

I also found the discussion about Java versions and character encoding useful because these are things that are easy to overlook when learning programming. A program does not exist in isolation. It needs to work within a particular environment, and even something as basic as displaying text correctly depends on how characters are represented and interpreted.

The biggest takeaway for me was understanding that software development does not end once the code has been written. There is a complete process involved in taking an idea and turning it into something that can actually be used. The application needs an entry point, the required dependencies, a build process, proper testing, integration with other components, and eventually deployment.

Overall, this class helped connect several concepts that I had previously viewed as separate topics. It made me realise that learning programming is not only about understanding how to write code but also about understanding what happens to that code throughout its development. I think the most important lesson was the idea of taking responsibility for the software we create, rather than focusing only on whether it runs successfully on our own computer.
