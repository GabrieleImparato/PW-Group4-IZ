# PW-Group4-IZ


- GitHub Repository project work, class: Software Architecture Design
- Group 4: I-Z

Team Members:
- Lucia Nancy Lavista
- Gabriele Imparato
- Mario Ripesi
- Mariapia Lombardi

-----------------------------------------------------------------------------------------------
The program is used to make drawings composed of one or more geometrical shapes. The user is presented with a window that is initially empty.

The user can choose a geometrical shape to add; using the mouse on the window, the shape is added on the selected position.

The shapes supported must include: line segments, rectangles, ellipses.

The user must be able to choose the color of the shape to be added (at least 8 different colors must be supported). Also, if the shape is a closed contour (e.g. a rectangle), the user must be able to choose the color of the interior of the shape.

The user must be able to save the drawing on a file, and to load a drawing previously saved.

The user can select a shape of the drawing with a mouse operation. The user can delete the selected shape, can move it to a different position, can change its color(s) or its size.

The user can perform the Cut, Copy and Paste operations (as normally found in programs) with shapes.

All the operations that change the drawing must be undoable, with an unlimited number of undo levels.

The user can send a shape "to the front" or "to the back" of the drawing; thishas a visibleeffectwhentwo or more shapes are overlapping (asshown in the following figure).

The user must be able to change the zoom level with which the drawing is shown in the user interface. At least 4 different zoom levels must be supported.

The user interface must support a drawing surface that is larger than the size of the window; the user can scroll to the portion of the drawing of interest.

The user interface can display an optional grid to help the user positioning the shapes. The user must be able to turn the grid on or off, and also to choose the size of the grid.

The user must be able to enter an arbitrary polygon (not just a regular one) as a shape. The user must be able to enter a text string as a shape (in this case, also the user can choose the size of the characters).

The user must be able to rotate a shape by an arbitrary angle (i.e. not necessarily a multiple of 90°). The user must be able to "mirror" a shape horizontally or vertically. The user must be able to "stretch" a shape, horizontally or vertically.

The user must be able to select more than one shape, and then "group" the selected shapes. The created group will behave as a single shape in successive operations (e.g. when selected moved). The user must be able to "ungroup" a previously grouped set of shapes.

The user must be able to add new "shape creation commands" to the application: the user selects a shape and gives it a name; later, when the user executes the corresponding shape creation command, the program adds to the drawing a new copy of that shape (note that the shape might have been removed from the drawing, or might have been modified; the command must create a copy that reproduces the shape as it was when the user created the new command).

The "shape creation commands" must be saved within the drawing file. Additionally, the user must be able to "export" the shape creation commands to a "shapes library file", or to "import" them from such a file (for instance, the user may want to import a library of shapes representing electrical components).



