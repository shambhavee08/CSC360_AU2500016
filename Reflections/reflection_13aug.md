# Class Reflection – 13-08-2026

## Topics Covered

- Introduction to Maven and its purpose
- Understanding the `pom.xml` file
- Basics of Computer Graphics
- Pixels and coordinate systems
- Algorithm for creating a square
- Calculating the position of a square using its centre and side length
- Drawing and moving graphical objects in Java
- Maven project structure
- Understanding `src`, `main`, `java`, `resources` and `test`
- Purpose of the `.gitignore` file
- Introduction to `JFrame`
- Difference between development tools and build tools
- Understanding colours and RGB values in Java Graphics
- Translation and other geometric transformations

## Notes

### 1. Maven and the `pom.xml` File

One of the topics introduced during this class was Maven and how it helps in managing Java projects. I learned that Maven is not a programming language but a project management and build tool. It helps developers organise their projects and perform tasks such as compiling code, managing dependencies, running tests and preparing applications for execution.

We also discussed the `pom.xml` file, which plays an important role in a Maven project. It contains information about the project, including its dependencies, plugins and build configurations. I understood that Maven uses this file to determine how the project should be managed and built.

Earlier, I mostly associated programming projects with the actual code written by a developer. This discussion helped me realise that there are several supporting files and tools that contribute to making a project functional and organised.

### 2. Introduction to Computer Graphics, Pixels and Coordinates

The class also introduced the fundamentals of Computer Graphics and how visual objects are represented on a computer screen.

I learned that a digital screen consists of tiny elements called pixels, which together form the images and shapes that we see. Each pixel contributes to the overall appearance of an image.

Another important concept was the coordinate system used to determine the position of graphical objects. In Java Graphics, the coordinate `(0,0)` is located at the upper-left corner of the screen. The x-coordinate increases as we move towards the right, while the y-coordinate increases as we move downwards.

This was slightly different from the coordinate system I was more familiar with in mathematics, where the positive y-direction usually points upwards. Understanding this difference is important because the position of an object in a graphical application depends on the coordinate system being used.

I realised that before drawing an object, it is necessary to understand where it should be placed and how its dimensions will be represented through coordinates.

### 3. Developing an Algorithm to Create a Square

One of the more interesting activities in this class was understanding how to create a square through an algorithm before moving on to its actual Java implementation.

Although a square appears to be a very simple shape, drawing it through programming requires us to calculate the exact positions of its corners.

We considered the centre of the square as `(Cx, Cy)` and its side length as `L`. Since the square extends equally in all directions from its centre, half of its side length is used to calculate the positions of its four corners.

The coordinates can be represented as follows:

- **Upper-left corner:** `(Cx - L/2, Cy - L/2)`
- **Upper-right corner:** `(Cx + L/2, Cy - L/2)`
- **Lower-left corner:** `(Cx - L/2, Cy + L/2)`
- **Lower-right corner:** `(Cx + L/2, Cy + L/2)`

For example, if the centre of the square is `(200,150)` and its side length is `100`, half of the side length will be `50`. Using this value, we can calculate the coordinates of all four corners.

What I found useful about this exercise was that it demonstrated the importance of planning the logic before writing the actual code. Instead of randomly assigning positions to the corners, we can use a mathematical relationship to calculate them accurately.

It also helped me understand how geometry can be converted into a set of instructions that a computer can follow.

### 4. Drawing and Moving a Square Using Java Graphics

After understanding the algorithm, we discussed how the square could be implemented using Java Graphics.

The position of a graphical object depends on its x and y coordinates. By changing these values, we can move the object from one location to another on the screen.

We also explored how graphical objects can be assigned colours. Java allows us to work with predefined colours as well as the RGB colour system, where different combinations of red, green and blue values produce different colours.

Another important point was that a square can be drawn by specifying its position, width and height. Since all four sides of a square are equal, the width and height must have the same value.

The concept of translation was also connected to this example. Translation involves shifting an object from one position to another without changing its shape or size. In the moving-square example, this can be achieved by updating its coordinates.

The class also introduced other geometric transformations, including rotation, scaling and shearing. These transformations help modify the position, size or appearance of graphical objects.

This made me understand that even basic graphical movements are supported by mathematical operations happening within the program.

### 5. Understanding the Maven Project Structure

We also learned about the general structure of a Java project created using Maven.

A Maven project follows a particular folder organisation, which helps keep the source code, resources and tests separate.

The main `src` directory generally contains two important folders:

- **main:** Contains the actual application code and resources.
- **test:** Contains the code used for testing the application.

Within the `main` directory, there are further folders:

- **java:** Contains the Java source code.
- **resources:** Contains additional files and resources required by the application.

Understanding this structure helped me recognise that different files serve different purposes within a project.

I also realised that maintaining an organised folder structure becomes increasingly important as a project grows and contains multiple classes and supporting files.

### 6. The Purpose of `.gitignore`

Another concept covered during the class was the `.gitignore` file.

This file is used to specify which files and folders should be excluded from version control. This means that certain files do not need to be tracked or uploaded to a Git repository.

For example, temporary files, generated build folders or files containing local configurations may not need to be included in a shared repository.

I understood that `.gitignore` helps maintain a cleaner repository by preventing unnecessary files from being tracked.

This also made me think about the importance of managing a project properly, especially when multiple people are working on the same codebase.

### 7. JFrame and Java Graphical Applications

We were also introduced to `JFrame`, which is a component of Java Swing used to create the main window of a graphical application.

It provides a window in which other graphical components can be placed and displayed.

Learning about JFrame helped me understand how Java applications can move beyond text-based output and provide users with a visual interface.

It also gave me an idea of how different graphical components are organised within a window to create an interactive application.

### 8. Development Tools and Build Tools

Towards the end of the discussion, we explored the difference between development tools and build tools.

Development tools are used during the process of writing, editing, running and testing code. They provide an environment in which programmers can develop and examine their applications.

Build tools, on the other hand, help automate tasks such as compiling code, managing dependencies, running tests and preparing the final application.

Maven was discussed as an example of a build and project management tool.

This distinction helped me understand that developing software involves different stages, and different tools are used to support each stage.

## Reflection

This class helped me understand how something as simple as drawing a square on a computer screen involves a combination of mathematics, logical thinking and programming. Before this discussion, I would have considered creating a square to be a fairly straightforward task. However, learning about coordinates and the algorithm behind it made me realise that even basic graphical elements need to be represented through a clear set of instructions.

The activity that stood out to me was calculating the four corners of a square using its centre and side length. I found it interesting that instead of individually guessing the position of each corner, we could derive all four coordinates using just two pieces of information. It made me understand the importance of identifying patterns and mathematical relationships before attempting to write code.

I also found the discussion about moving a square useful because it connected the mathematical concept of translation with something visible on the screen. The idea that changing the values of coordinates can shift an entire graphical object helped me understand how programming can be used to manipulate visual elements. It also made me curious about how the other transformations, such as rotation and scaling, can be implemented.

Apart from Computer Graphics, learning about Maven and the structure of a Java project gave me a better understanding of what happens outside the actual coding process. Earlier, I would not have paid much attention to folders such as `resources` or `test`, or files like `pom.xml` and `.gitignore`. However, I now understand that these components help organise a project and make it easier to manage as it becomes more complex.

I particularly liked understanding the purpose of `.gitignore` because it connected the classroom discussion to how we actually maintain our programming projects on GitHub. It showed me that writing code is only one part of development; keeping the project organised is equally important.

Some of the concepts, especially the different geometric transformations and their implementation, are areas I would like to explore further. I understand their basic purpose, but I would like to become more comfortable with translating these mathematical ideas into Java instructions.

Overall, this session helped me connect concepts that I had previously viewed separately. Mathematics provides the calculations, algorithms organise the steps, and programming makes it possible to execute them. My biggest takeaway was that before trying to make something work on a computer, it is important to understand the logic behind what I am trying to create.
