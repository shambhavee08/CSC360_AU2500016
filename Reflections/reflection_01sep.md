# Class Reflection – 1 September 2026

## Topics Covered

- Converting three text equations into a drawn triangle
- Handling right-click events on a JavaFX canvas
- Connecting points using directed arrows
- Representing and drawing a binary tree
- Input validation, geometric calculations, and visual representation

## Notes

### 1. Converting Equations into a Triangle

One of the exercises involved converting three text equations into a drawn triangle. Unlike a situation where the vertices are already provided, this exercise requires the application to interpret the equations and calculate where the lines intersect.

This helped me understand that graphics programming involves more than simply drawing shapes. Before anything can be displayed, the application needs to interpret the input, perform the necessary calculations, and determine the coordinates that will be used for drawing.

An important consideration is that not every set of three equations will produce a valid triangle. For example, parallel lines do not intersect, and three lines meeting at the same point do not form a triangle. Therefore, the application needs to check whether the input actually produces a valid geometric shape before attempting to draw it.

We also considered the general equation form `ax + by = c`. This is useful because it can represent vertical lines as well, unlike slope-intercept form, which cannot directly represent them.

### 2. Handling Right-Click Events and Connecting Points

Another exercise involved working with a JavaFX canvas and handling right-click events. This introduced the idea of responding to user interactions rather than only displaying a fixed drawing.

We also discussed connecting points using directed arrows. The direction of an arrow is important because a connection from one point to another is not necessarily the same as a connection in the opposite direction.

An important idea from this exercise was that a graphics application should retain information about the objects and their relationships, rather than only storing the final drawing as pixels. If the application remembers the centres of the points and the connections between them, it becomes easier to redraw the diagram, move objects, select them, and potentially save the structure.

The arrow's direction and its position relative to the endpoints can then be calculated from the relationship between the connected points.

### 3. Representing and Drawing a Binary Tree

We also worked with the representation and visualisation of a binary tree. A binary tree is a structure in which nodes are connected through parent-child relationships.

This exercise helped distinguish between the actual structure of a tree and the way it is displayed on the screen. Even if all the parent-child relationships are correct, the visual representation may still be difficult to understand if the nodes overlap or are placed too close together.

A layout algorithm is therefore needed to decide where each node should appear. A recursive spacing approach can help arrange the nodes, although it may still create overlapping elements when the tree becomes deep or unbalanced.

This showed me that maintaining a correct data structure and creating a clear visual representation are two separate challenges.

## Reflection

### A Shared Structure Across Different Exercises

The triangle, circle-and-arrow, and binary-tree exercises initially appear to be separate graphics problems. However, I noticed that they follow a similar sequence: interpreting input, creating a meaningful representation, performing calculations, and finally displaying the result.

Recognising this connection helped me understand that graphics programming is not simply about writing separate drawing instructions for every shape. It involves developing a process that can take information, understand its structure, and convert it into something visual.

The triangle exercise was particularly interesting because the user provides equations instead of ready-made vertices. This means that understanding and interpreting the input becomes an important part of the problem itself.

### The Importance of Validating Input

Another important learning was that correctly formatted input does not automatically mean that the result will be valid. Three equations may be written correctly but still fail to produce a triangle.

For example, parallel lines do not intersect, coincident lines represent the same line, and three lines meeting at one point do not enclose a triangular region. This made me realise that a program should not only check whether the input is written correctly but also whether it makes sense for the problem being solved.

I also found the use of the general equation form `ax + by = c` interesting because it avoids limiting the application to only certain types of lines. It showed me how choosing the right way to represent information can make a program more flexible.

### Relationships Are More Important Than Just the Drawing

The circle-and-arrow exercise helped me understand why a graphics application should retain the relationships between objects. If a program only remembers the final pixels, changing or moving individual elements becomes difficult. However, if it stores the points and their connections, it becomes easier to modify and redraw the diagram.

The binary-tree exercise added another layer to this understanding. A tree can be structurally correct but still visually confusing. This made me realise that the way information is organised and the way it is presented are equally important when developing a visual application.

### Further Learning

If I were to extend these exercises, I would test the triangle application with vertical, parallel, concurrent, and nearly parallel lines to understand how it handles different geometric situations. For the diagrams, I would experiment with overlapping centres and deeper or unbalanced binary trees.

These would be additional tests to explore rather than exercises that have already been completed.

Overall, the biggest takeaway from this class was that a graphics application needs to do more than produce the expected visual output. It should also handle input carefully, maintain the underlying structure of the information, and present the result in a way that is understandable. I began to see how mathematical reasoning, data structures, user interaction, and visual design work together when developing a graphics-based application.
