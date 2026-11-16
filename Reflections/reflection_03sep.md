# Class Reflection – 3 September 2026

## Topics Covered

- Generating an ASCII tree using Java text output
- Finding common elements between two lists and drawing arrows
- Creating a custom JavaFX splash screen using FXML

## Reflection

### 1. Visualisation Starts with Understanding the Data

The list-matching exercise helped me understand that interpreting the data is just as important as drawing the final visualisation. When two lists contain repeated values, simply saying that we need to connect their common elements is not enough. There can be different ways of interpreting this instruction. We could connect every matching occurrence, pair each occurrence only once, or create connections between distinct common values.

Each approach would produce a different visual result, even though the original requirement sounds the same. This made me realise that before deciding how to draw the arrows, we first need to understand what each arrow is supposed to represent.

The way data is stored also affects the result. For example, a data structure that keeps track of every position of a repeated value preserves more information than one that stores only a single position. Therefore, choosing the right data structure is not just about making the program efficient; it also affects the meaning of the visualisation.

### 2. Efficiency and Output Complexity

Another interesting aspect was understanding the relationship between algorithm efficiency and the amount of output being generated.

Using a lookup map can reduce unnecessary comparisons when finding common elements between two lists. However, it cannot eliminate the number of connections that actually need to be drawn. If repeated values result in a large number of matching pairs, the number of arrows can still grow significantly.

This helped me understand that even if the matching algorithm is efficient, the final visualisation may become crowded and difficult to interpret.

It also raised another question about how the information should be displayed. Instead of showing every connection at once, an application could group repeated values or allow users to select an element to view its connections. This showed me that performance and readability are two different problems that need to be considered separately.

### 3. ASCII Trees and the Importance of Layout

The exercise involving ASCII trees showed that visualisation is not limited to graphical interfaces or pixel-based drawings. Even when a tree is displayed using text characters, its layout still needs to be planned.

The arrangement of rows, columns, labels, and branches determines whether the tree is understandable. The width of labels and the spacing between different branches can affect how clearly the structure is displayed.

This made me realise that the basic challenge of arranging information remains similar across different forms of visualisation. The medium may change, but the need to organise the information properly does not disappear.

### 4. FXML and Separation of Concerns

We also discussed creating a custom JavaFX splash screen using FXML. One important idea I took away from this was the separation of the user interface from the Java code.

FXML allows the structure of a JavaFX interface to be described separately rather than placing every interface element directly inside Java code. This can make the application easier to organise and maintain.

However, I also understood that simply moving the interface elements into an FXML file does not automatically make the entire application well structured. If the controller is responsible for too many things, such as matching data, accessing files, and managing all the application state, the code can still become difficult to maintain and test.

A better approach is to keep the reusable logic separate from the presentation layer. This allows the application to be more organised and makes individual parts easier to work with.

### 5. Further Learning

There are a few things I would like to explore further based on these exercises.

For the list-matching exercise, I would first define how repeated values should be handled using small examples before implementing the arrows. This would help avoid confusion about what each connection represents.

For ASCII trees, I would experiment with different label widths and tree structures to understand how the layout changes. For the splash screen, I would explore how its progress display could reflect actual loading work, including situations where the application encounters an error.

I also found the distinction between a real progress display and a fixed delay interesting. A progress indicator should communicate the actual state of the application rather than simply showing an animation for a predetermined amount of time.

Overall, this class helped me understand that creating a visual application requires more than knowing how to display objects on a screen. The program needs to interpret information correctly, choose suitable data structures, organise the output, and separate its internal logic from the user interface. I also realised that a good visualisation should not only look correct but should communicate the underlying information clearly.
