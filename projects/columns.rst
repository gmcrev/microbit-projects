Project ideas.

*****************
Columns
*****************

  
Draw a vertical line down column 0. ::

   from microbit import *

   while True:
      x = 0
      for y in range(0, 5):
         display.set_pixel(x, y, 9)
  
Draw a vertical line down column 0 and 4. ::

   from microbit import *

   while True:
      x = 0
      for y in range(0, 5):
         display.set_pixel(x, y, 9)
      x = 4
      for y in range(0, 5):
         display.set_pixel(x, y, 9)
            
Draw a vertical line down column 0, 2, 4. ::

   from microbit import *

   while True:
      column_list = [0, 2, 4]
      for x in column_list:
         for y in range(0, 5):
            display.set_pixel(x, y, 9)
	

*****************
More
*****************

Try variations.
*****************

.. tip::
	* This is a bulleted list.
	* It has two items, the second item uses two lines.
.. note::
	#. This is a numbered list.
	#. It has two items too.

More examples to come.
