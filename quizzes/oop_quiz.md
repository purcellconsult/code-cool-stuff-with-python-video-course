## OOP Quiz in Python

1) Write a simple class called ``Color`` which emulates the RGB color value system in python. The class should have an ``__init__`` method which has three parameters which are ```red```, ```blue```, and ```green```.  Each parameter represents the intensity of the color as an integer within the range of 0-255. If the user tries to create an instance of ``Color`` with values outside the range of 0-255 then an exception should occur.  The class should also have a method named ``create_rgb`` that displays the rgb values that the user entered in a tuple. 

2) Create a class called ```RightTriangle``` which models a right triangle. The class should contain the following:
	- **instance variables**: ```self.a``` and ```self.b```
	- **area_of_triangle**: ``1/2 * (a * b)``
	- **perimeter_of_triangle**:  ``a + b + sqrt(a^2 + b^2)``
	- The methods should display the area and perimeter respectively. Here's some sample output from the class:
		```
		r1 = RightTriangle(5, 2)  
		r1.area_of_triangle()  
		r1.perimeter_of_triangle()  
		 ```

		```
		r2 = RightTriangle(1, 4)  
		r2.area_of_triangle()  
		r2.perimeter_of_triangle() 
		``` 
  
		 ```
		r3 = RightTriangle(5, 6)  
		r3.area_of_triangle()  
		r3.perimeter_of_triangle()
		```


3)  Create a class called ``Car`` that has a constructor which accepts three arguments: ``year``, ``make``,  and ``model``.  The class will have several methods:
	- ``get_year``: Returns the year of the car.
	- ``get_make``: Returns the make of the car.
	- ``accelerate``: Has a keyword argument amount which is initially set to 5. The user can modify this initial amount, but the method should check that the speed of the car is less than 300, and that the amount of acceleration is less than 60. This is to make a more realistic simulation as most cars can't accelerate from 0 to 59 mph in a blimp.  Wrap the code in a ``try/except`` statement to ensure that the user provides valid input.
	- ``hit_brakes``: This method should have a keyword argument of 5. The method should check that the user speed is greater than 0, because you can't decelerate if you're already at rest. Also, the amount of speed in which the car decelerates should be less than 60. Wrap the code in a ``try/except`` statement to ensure that the user provides valid input. 
	- ``is_stopped``: Checks to see if the car is currently at rest. If it is return ``True`` else return ``False.`` 
	- ``is_moving``: Checks to see if the car is moving, if it is return ``True``, else return ``False.``
	- ``get_color``: Returns the color of the car.
	- ``speedometer``: Returns the speed of the car. 