# Class Reflection – 8 September 2026

## Topics Covered

- Exception handling and error management
- Generic programming and collections
- Graphical user interfaces and event handling
- Swing and JavaFX
- Layouts and interface components
- Image processing

## Notes

### 1. Exception Handling and Error Management

In this class, we discussed **exceptions** and how Java handles unexpected situations during program execution. Earlier, I generally thought of errors as problems that simply caused a program to stop. However, I understood that Java provides mechanisms to identify and handle many of these situations so that the application can respond more appropriately.

We discussed the use of `try`, `catch`, and `finally`. A `try` block contains code that might produce an exception, while a `catch` block allows us to handle the exception if it occurs. The `finally` block contains code that is generally executed after the try-catch process, making it useful for tasks such as cleaning up resources.

We also learned about **checked and unchecked exceptions**. Checked exceptions are checked by the compiler and generally need to be handled or declared by the programmer. They can occur when working with files or external resources. Unchecked exceptions occur during runtime and are often associated with programming mistakes, such as `NullPointerException` or `ArithmeticException`.

I also tried understanding **assertions** separately because I initially found them confusing. An assertion checks whether a condition that the programmer expects to be true actually holds. It is mainly useful for identifying logical mistakes during development. I understood that assertions are different from exception handling and should not be used as a replacement for validating normal user input.

Another related concept was **logging**. Logging allows developers to record information about what is happening inside an application. Earlier, I would mostly use `System.out.println()` to check the execution of my code. However, logging systems provide a more organised way of recording information, warnings, and errors, which becomes especially useful when debugging larger applications.

### 2. Generic Programming and Collections

We also discussed **generic programming and collections**. I spent some time reading about generics after class because the syntax involving `<T>` was initially difficult for me to understand.

Generics allow classes and methods to work with different data types while maintaining type safety. For example, instead of writing separate code for collections of integers and strings, we can use a generic collection such as `List<T>`. This makes code more reusable and helps detect certain type-related errors during compilation.

We also discussed **collections**, which are used to store and manage groups of objects in Java. Some common examples include lists, sets, and maps.

A list maintains an ordered collection of elements and can contain duplicates. A set is useful when we want to store unique elements without duplicates. A map stores information in key-value pairs, allowing us to access values using their corresponding keys.

I tried looking at examples of these collections to understand when each one would be useful. This helped me realise that there is no single collection that is suitable for every situation. The choice depends on the kind of information we want to store and how we need to access it.

We also discussed **views**. A view provides another way of accessing existing data without necessarily creating a completely separate copy. This can be useful when we want to work with a particular part or representation of existing data while maintaining its connection to the original collection.

### 3. Graphical User Interfaces and Event Handling

Another major topic was **graphical user interfaces (GUIs) and event handling**. A GUI application works differently from a simple program that follows a fixed sequence of instructions. Users can interact with it in different ways, such as clicking buttons, selecting options, moving sliders, or entering text.

These interactions generate **events**. Event handling is the mechanism through which an application detects these events and performs the appropriate actions in response. For example, when a user clicks a button, an event is generated and the associated event handler executes the required code.

We also discussed the **event hierarchy**. Initially, I thought this was mainly something that needed to be memorised. However, after trying to understand it, I realised that different events are organised through relationships with more general event classes. Events related to mouse actions, keyboard input, and interface components can therefore be understood through a structured hierarchy.

This helped me understand why GUI applications are called **event-driven applications**. Instead of simply executing one fixed sequence of instructions, the application waits for user actions and responds to them as they occur.

### 4. Swing and JavaFX

We discussed **Swing and JavaFX**, which are two Java technologies used for developing graphical applications.

Swing has been used for a long time and provides various components for creating desktop interfaces. JavaFX is another framework that provides features such as controls, styling, FXML, media, and other facilities for building graphical applications.

We also discussed different **GUI components**, including buttons, labels, text fields, check boxes, radio buttons, and sliders. I tried relating these components to applications and forms that I regularly use, which made their purpose easier to understand.

A **check box** is generally used when users can select multiple independent options. For example, a form may allow someone to choose several preferences.

A **radio button** is used when the user needs to select one option from a group of choices. For example, when a form allows only one answer from several alternatives, radio buttons are suitable.

A **slider** allows users to select a value from a particular range by moving a control along a track. A common example is adjusting the volume of a device.

I understood that these components do not function independently of the rest of the application. They work together with event handling so that the application can respond to different user interactions.

### 5. Layouts and Interface Components

Another concept covered in class was **layouts**. Layouts determine how different components are arranged within a graphical interface. I realised that simply adding buttons, labels, and text fields to a window is not enough. They also need to be organised properly so that the interface remains clear and usable.

One of the layouts we discussed was **Grid Layout**. It divides the available space into rows and columns, allowing components to be arranged within a grid. I looked at some examples to understand why using layouts is generally more useful than manually fixing the position of every component.

We also discussed the **Master-Detail Layout**. In this arrangement, one section displays a list or collection of items, while another section displays more detailed information about the selected item. For example, an application could display a list of students, files, or products on one side and show the selected item's details on the other.

These layouts helped me understand that GUI design is not just about adding different components. The way information is arranged also affects how easily someone can understand and use an application.

### 6. Image Processing

Another interesting topic was **image processing**. Since this was different from the GUI concepts we had discussed, I tried reading about it separately to understand its basic principles.

Image processing involves using computers to analyse or modify digital images. I understood that a digital image can be represented as a collection of **pixels**, with each pixel containing information about colour or intensity at a particular position.

Once I understood that an image is essentially represented through pixel data, concepts such as histograms, filtering, and black-and-white conversion became easier to understand.

We discussed **histograms**, which show the distribution of pixel intensity values in an image. In a grayscale image, a histogram can show how many pixels have low, medium, or high intensity values. This can help us understand whether an image is generally dark, bright, or has a particular distribution of intensities.

We also discussed **image filtering**. Filtering involves applying operations to image data to modify an image or extract useful information. Filters can be used to reduce noise, blur an image, or highlight certain features. These operations can involve using the values of neighbouring pixels to calculate a new value for a particular pixel.

Another concept was converting an image into **black and white**. A grayscale image contains different shades between black and white, whereas a binary black-and-white image contains only two possible pixel values. A threshold can be used to classify pixels into these two groups.

I found this interesting because the final result may look like a simple visual change, but it involves processing the underlying pixel information.

## Reflection

This class helped me understand how Java programming connects several different areas, including error handling, data management, graphical interfaces, and image processing. Earlier, I mostly associated programming with writing code and getting the expected output. However, the topics discussed in this class showed me that there are many more aspects involved in developing an application.

The topic of **exception handling** was particularly useful because it made me realise that a program should be prepared for situations where something unexpected happens. Understanding checked and unchecked exceptions helped me see that not every problem is handled in the same way. I also explored assertions and logging independently after class, which helped me understand their different purposes.

I found **generics and collections** useful because they showed me how Java allows us to organise data and write reusable code while maintaining type safety. I had come across collections before, but understanding lists, sets, maps, generics, and views together gave me a clearer idea of how different types of data structures can be used depending on the requirement.

The GUI section was also interesting because it helped me understand that an application is not simply a collection of buttons and text fields. Event handling is what allows an application to respond to user actions, while the event hierarchy helps organise the different types of events. Learning about Swing and JavaFX also introduced me to the frameworks used to create graphical applications in Java.

I also tried exploring layouts and GUI components after class because I wanted to understand their practical applications instead of only remembering their definitions. Grid Layout and Master-Detail Layout helped me realise that organising information properly is an important part of designing an interface.

The introduction to **image processing** was another new area for me. Understanding images as collections of pixels helped me connect programming with visual information. Concepts such as histograms, filtering, and black-and-white conversion showed me how computers can analyse and modify images through calculations on pixel data.

Overall, I made an effort to read about several concepts after class so that I could understand them beyond their basic definitions. My biggest takeaway was that learning Java is not only about remembering syntax or making a program run. It is also about understanding how to handle unexpected situations, manage information, create interactive applications, and work with different forms of data. This class introduced me to several areas of programming that I would like to explore further.
