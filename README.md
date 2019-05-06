# Graphics-BGI-c-
Shape drawing and Area filling algorithm in computer graphics using BGI environment.
------------------------------------------------------------------------------------------------------------------------------------------
-> I have used an open source IDE called CodeBlocks for configuring <graphics.h> library, also to build and run the .cpp program file.
Link for the IDE:-
http://www.codeblocks.org/downloads

Running the code/file:-
-> You may use the program file "area_filling.cpp" in CodeBlocks or any other compiler to build and run the code, or else
I have also included the an executable file "area_filling.exe" that can be directly run on a Windows platform.

Note:- 
-> The BGI console is limited to 600x600 px, so the scope of the input coordinates is limited to the mentioned pixel values.
-> For reference you may use MS Paint to get the coordinates of the desired shape you want to draw on BGI console, eg:- Screenshot.png

area_filling.cpp/area_filling.exe:-
-> After the running the program, you may choose one of the options by the respective numeric input to draw a specific shape.
-> I have mentioned all the tried input coordinates in the respective comment sections of a .cpp file which you may use to check the working of the code.
-> 1.Circle:- Enter the center coordinates and then the radius of the circle.
-> 2.Rectangle:- Enter the end point coordinates of diagonal i.e left-top(x0, y0) to right-bottom(x1, y2) for a rectangle.
-> 3.Triangle or polygon :- 
	-Enter the number(n) of edges for the triangle i.e 3 or polygon i.e more than 3 edges, Enter the coordinates for all vertices as (xt0,yt0), (xt1, yt1).....(xt (n-1), yt (n-1))
	-Enter the seed points for the triangle, this coordinate of pixel value should be COMPLETELY INSIDE THE DRAWN SHAPE, NOT ON THE EDGE AND OUTSIDE
	 OF THE SHAPE.
	-Enter 'Y' if you want to fill the area of the shape.




