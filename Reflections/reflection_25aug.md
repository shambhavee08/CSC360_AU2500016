# Class Reflection – 25-08-2026

## Topics Covered

- Computer Graphics: Squares, Trees, Triangles and Image Analysis
- Understanding Trees and Parent–Child Relationships
- Introduction to ImageJ
- Maven and the `pom.xml` File
- Maven Build Lifecycle and Dependencies
- Java Source Files and Compiled `.class` Files
- Understanding `.xsd` Files and the `target` Folder
- Graphical User Interfaces (GUI) and Java Swing
- Swing Components: `JButton`, `JPanel` and `JList`
- Accessibility and Alternative Text
- Processes, Threads and Multithreading
- Thread Safety in Java Swing

## Notes

### 1. Computer Graphics, Trees and Image Analysis

During this class, we continued exploring the fundamentals of Computer Graphics by revisiting the program used to draw a simple square. Since we had already discussed the algorithm and coordinate calculations required to create a square, this session helped me connect those ideas with their actual implementation in Java.

We also discussed how we would gradually move towards creating more complex graphical objects, including trees and triangles. I found this interesting because it showed how graphical applications can be developed by starting with simpler elements and combining them to create more detailed structures.

Another concept introduced was the representation of trees through hierarchical relationships. A tree is not necessarily a visual representation of an actual tree; in programming, it can represent a structure in which different elements are connected through parent–child relationships. We also considered how these structures can be represented horizontally or vertically.

This helped me understand that the same information can be organised and displayed in different ways depending on the purpose of its representation.

We were also introduced to image analysis and the ImageJ package. This expanded my understanding of Computer Graphics because I realised that working with images does not always involve creating or modifying visual elements. It can also involve examining images and analysing the information contained within them.

### 2. Maven, `pom.xml` and the Build Process

We continued discussing Maven and its role in managing Java projects. This class helped me understand the different stages involved in converting source code into a usable application.

The `pom.xml` file acts as the main configuration file of a Maven project. It contains information about the project, its dependencies, plugins and build settings. Maven uses this information to manage the requirements of the project and carry out the build process.

We also discussed the following stages and concepts:

- **Dependencies:** These are external libraries or resources required by a project. Maven helps manage them so that developers do not have to manually handle every required library.
- **Validate:** This stage checks whether the project is correctly structured and contains the necessary information.
- **Compile:** During compilation, Java source files (`.java`) are converted into compiled `.class` files containing bytecode that can be executed by the Java Virtual Machine.
- **Test:** This stage runs the available tests to check whether different parts of the application are functioning as expected.
- **Package:** Once the required build stages are completed, the project can be packaged into a format such as a JAR file.
- **Clean:** This removes files generated during previous builds, allowing the project to be built again without relying on old generated output.
- **Target folder:** This folder stores the files generated during the build process, including compiled classes and other build-related output.

We also encountered `.xsd` files, which are associated with XML Schema definitions. These files help define the structure and rules that XML documents are expected to follow.

Understanding these different files helped me recognise that a Java project contains more than just the source code written by the programmer. There are configuration files, generated files and supporting resources that contribute to the overall development process.

I understood Maven as a tool that automates several stages of project management and building, making the process more organised and manageable.

### 3. GUI, Java Swing and Its Components

Another major topic covered during the session was the Graphical User Interface, commonly known as GUI.

A GUI allows users to interact with an application through visual elements instead of relying entirely on text-based commands. We discussed Java Swing as a framework that provides components for developing graphical interfaces.

Some of the components introduced included:

- **JButton:** A button that allows users to perform an action when clicked.
- **JPanel:** A container used to organise and group other components within an interface.
- **JList:** A component that displays a list of items and allows users to interact with the available options.

This discussion helped me understand how different elements come together to make an application interactive. Instead of simply displaying information, a graphical interface allows users to perform actions and navigate through an application.

### 4. Accessibility and Alternative Text

Along with GUI development, we also discussed accessibility and why it should be considered while designing applications.

Accessibility refers to designing software in a way that allows people with different abilities and requirements to use it effectively.

One example discussed was alternative text, commonly known as alt text. It provides a textual description of an image so that people using screen readers can understand the information conveyed through that image.

I found this topic particularly important because it made me realise that designing an interface is not only about making it visually appealing. It should also be understandable and usable for people who may interact with it differently.

This introduced me to the idea that accessibility should be considered as part of the development process rather than treated as an additional feature.

### 5. Processes, Threads and Multithreading

The final major topic discussed during the class involved processes and threads.

A process is an instance of a program that is currently running, whereas a thread is an individual path of execution within that process.

A single process can contain multiple threads, allowing different tasks to progress within the same application.

We discussed the difference between single-threaded and multithreaded execution. In a single-threaded program, tasks generally execute along one path, while multithreading allows multiple paths of execution to make progress within the same process.

This can be useful when an application needs to perform several operations without making the entire program wait for one particular task to finish.

However, the discussion also introduced the concept of thread safety. When multiple threads access shared resources, problems can occur if their access is not properly controlled.

This is especially important when working with Java Swing because its components are generally not thread-safe. Updating graphical components from different threads without following the appropriate rules can lead to unexpected behaviour.

I understood that multithreading can make an application more responsive, but it also requires careful management of shared resources and operations.

## Reflection

This class gave me a broader understanding of the different areas involved in developing a Java application. What I found interesting was how the discussion moved from basic Computer Graphics to project management, graphical interfaces and multithreading. Initially, these seemed like separate concepts, but I gradually started understanding how they contribute to different aspects of software development.

The discussion about creating squares, trees and triangles helped me understand how graphical objects can be built by combining simpler elements. I particularly liked the introduction to tree structures because it showed me that the concept of a tree in programming is not limited to its visual appearance. It represents relationships between different elements, which can be organised through parent and child nodes. The introduction to ImageJ also made me realise that Computer Graphics can involve analysing existing images rather than only creating new ones.

I found the Maven discussion useful because it helped me understand what happens to a Java project beyond the source code that we write. Earlier, I would mostly focus on the `.java` files and the actual program. However, learning about dependencies, compilation, testing, packaging and the `target` folder gave me a better idea of how a project moves through different stages before it becomes usable. I also found it helpful to understand the distinction between the original source files and the files generated during the build process.

The GUI and Java Swing discussion was another interesting part of the class because it connected programming with the way people actually interact with applications. Learning about components such as buttons, panels and lists helped me understand how individual elements contribute to an interface. However, the discussion about accessibility stood out to me even more. I had not previously thought much about how people with different abilities experience the same application. Understanding the purpose of alternative text made me realise that an interface should communicate information effectively to everyone, not just people who can see and interact with it in the usual way.

The concepts of processes and threads were probably among the more challenging topics for me. I understood the basic difference between a process and a thread, but the idea of multiple threads accessing the same resources made me realise that running several operations simultaneously can introduce complications. The discussion about thread safety in Java Swing helped me understand that making an application responsive is not simply about creating more threads; those threads also need to be managed properly.

One connection I found particularly interesting was between the GUI and multithreading. An application may have an interface that allows users to perform different actions, but if a lengthy operation prevents the interface from responding, the overall experience becomes frustrating. This made me understand why background tasks and proper thread management are important in graphical applications.

Overall, this session helped me see software development as something that involves much more than writing code and getting the expected output. It requires organising a project, understanding how information is represented, designing interfaces that people can use and ensuring that different operations work together correctly. My biggest takeaway was that a good application should not only function properly but should also be organised, responsive and accessible to the people using it.
