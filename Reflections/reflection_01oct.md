Topics Covered
Why String is Immutable in Java
Binary Data and Binary Objects
Binary Cracking
Badges and Chips in UI
Image Shields and GIFs
Layout and Integer Values
Connecting Programming Concepts with User Interface and Applications
Understanding String Immutability
One of the topics discussed in class was why String is immutable in Java. I understood that immutability means that once a String object is created, its actual value cannot be changed. If we try to modify it, Java creates a new String object instead of changing the original one.

For example, if we have a String like "Hello" and then add something to it, the original "Hello" does not get modified. A new String is created for the new value.

At first, I thought that making String immutable was unnecessary, but after discussing it in class, I understood that it has important advantages. Strings are used very frequently in Java, so Java needs them to be reliable and safe. Immutability also helps with memory management, security, and sharing String objects.

This concept is also connected with how Java applications handle text. In our JavaFX work, we use Strings for things such as button text, labels, titles, HTML content, and messages. So understanding String is important even when we are mainly working on the user interface.

Binary Data and Binary Objects
We also discussed binary data and binary objects. Computers ultimately store and process information in binary form, using 0s and 1s. This helped me understand that the files and objects we normally see at the application level are represented internally as binary data.

A binary object can contain information in a form that is meant to be processed by a computer rather than directly read like normal text. This is important when dealing with files, images, compiled programs, and other digital resources.

I connected this topic with our practical programming work because when we use an image, GIF, or another resource in a project, the computer is not storing it as something we understand visually. It is storing the underlying digital information, which is represented in binary.

Binary Cracking
Another interesting topic was binary cracking. I understood this as examining or analysing a compiled binary rather than looking directly at the original source code. Normally, we write source code and then it is compiled into a form that the computer can execute.

This made me understand the difference between source code and the compiled form of a program. The source code is written and understood by the programmer, while the binary/compiled form is designed to be processed by the computer.

This topic was useful because it showed me that what we write in Java is not exactly what the computer finally executes. There are different stages between writing the code and running the application.

Badges and Chips
We also talked about badges and chips in user interfaces. These are small UI elements used to show short information such as a category, status, count, or label.

A badge is usually used to highlight a small piece of information, for example a notification count or status. A chip is generally a compact visual element that represents a category, option, tag, or piece of information.

I understood that these elements are not just for decoration. They help users understand information quickly without reading a large amount of text. This connects to the idea of designing a clear and understandable user interface.

Images, Shields and GIFs
We also discussed images, shields, and GIFs and how they can be used in projects.

An image can communicate information visually and can make an application or documentation easier to understand. A GIF can show movement or demonstrate how something works. This is especially useful in project documentation because instead of explaining every step through text, a GIF can show the actual working of the application.

Shields are small visual badges commonly used in project README files. They can display information such as the programming language, technology used, build status, or other project details.

I connected this with our GitHub project documentation. A README is not only about writing paragraphs. Visual elements such as badges, images, and GIFs can make the project easier to understand and can show the technologies and working of the project in a quick way.

Why Layout Values Can Be Stored as Integers
Another point that made me think was why a layout or position can sometimes be represented using integer values.

In a graphical application, objects need positions and dimensions. For example, a button or a square can have an x-coordinate, y-coordinate, width, and height. These values are numerical because the computer needs exact values to decide where an object should be placed.

Using integer values can be useful when we are dealing with fixed pixels or discrete positions. For example, a coordinate such as (100, 200) tells the program where an object should be placed.

This connects directly with the computer graphics concepts we studied earlier, where the screen is treated as a coordinate system. It also connects with JavaFX because UI elements are positioned and sized using numerical values.

Connection with the Concepts from the Book
The topics discussed in class can be connected with the broader idea of how a computer application works at different levels.

Earlier, we studied coordinates and graphical objects. Now I can see that a user interface is not only about placing buttons and labels on a screen. Behind the interface, there are data types, objects, memory, files, compiled code, and binary representations.

For example, when we create a JavaFX application, we write Java source code. The Java code uses objects such as Stage, Scene, layouts, buttons, labels, and other components. The application is then compiled and executed by the computer.

Similarly, when we use an image or GIF in a project, we are working with digital resources that are ultimately represented as binary data. When we use text, Java uses String objects, and understanding why Strings are immutable helps us understand how Java manages these objects.

The discussion about badges, chips, images, and GIFs also connected the programming side with the user-interface side. A good application needs both: the program should work correctly, and the interface should communicate information clearly to the user.

What I Learned
The main thing I learned from this class was that many concepts that look unrelated are actually connected. String immutability is related to how Java manages objects, binary data is related to how computers represent information, and UI elements such as badges, chips, images, and GIFs are related to how information is presented to users.

I also understood that when we build an application, we should not think only about the code that is visible on the screen. We should also think about what is happening behind the screen—how data is stored, how objects are created, how files are represented, and how the final program is executed.

This discussion helped me connect the theoretical concepts from the course with the practical work we are doing in Java and JavaFX. It also made me more curious about what happens internally when a program that we write is finally converted into something that the computer can execute.
