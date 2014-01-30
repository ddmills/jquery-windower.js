# jquery.windower
Easily create re-sizable, closeable, and moveable HTML elements using jQuery.
## Usage
### Step 1: include the script!
### Step 2: Create an area where the window 'lives'
Define the area the windows live by adding the `gui_container` class to any html object.
### Step 3: Add a window
Define a window element by adding the `gui_window` class to an html object
### Step 4: Make it moveable
Create a handle for the window, by creating a child of the `gui_window` element and adding the `gui_handle` class.
### Step 5: Make it re-sizable
Create a resizing handle by creating another child of the `gui_window` element and adding the  `gui_resize` class
### Step 6: Make it closeable
Create a close button by creating a child element of the `gui_window` element and adding the `gui_closer` class. Note: closing elements simply callls `fadeOut()` on the `gui_window` element. you can quickly re-show it again with jQuery


## Notes
You can easily make windows have a minimum size by adding `min-height: 400px;` , `min-width: 500px;` to their css. Similiarly you can add `max-height` and `min-height`.
