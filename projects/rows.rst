This will help you do your project.

*****************
Rows
*****************

  
Draw a horizontal line across row 0. ::

   from microbit import *

   while True:
      y = 0
      for x in range(0, 5):
         display.set_pixel(x, y, 9)
  
Draw a horizontal line across row 0 and 4. ::

   from microbit import *

   while True:
      y = 0
      for x in range(0, 5):
         display.set_pixel(x, y, 9)
      y = 4
      for x in range(0, 5):
         display.set_pixel(x, y, 9)
            
Draw a horizontal line across row 0, 2, 4. ::

   from microbit import *

   while True:
      row_list = [0, 2, 4]
      for y in row_list:
         for x in range(0, 5):
            display.set_pixel(x, y, 9)
	

More
===============

Try variations.

	* This is a bulleted list.
	* It has two items, the second item uses two lines.


	#. This is a numbered list.
	#. It has two items too.
