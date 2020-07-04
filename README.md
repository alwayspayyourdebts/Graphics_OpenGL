# Graphics_OpenGL
A Locomotive Olympics Logo using C language

National Institute of Technology, Silchar
 
Department of Computer Science and Engineering
2019
A Project Report On
	
LOCOMOTIVE OLYMPICS LOGO

Submitted By
                                
Ranit Nath				17-1-5-100
Manav Agrawal		  17-1-5-099
		          

                                                 
Under the guidance of 
Dr. Suganya Devi K
Assistant Professor Grade-I
NIT Silchar

                                        
                           



ABSTRACT

 This project is about the creation of Olympics logo.  We are implementing it using different primitives available in OpenGL library and combining them together in a required manner.
It highlights the key features of the data structures and its high-quality efficiency that is obtained on its usage in the application program. This project consists of Olympic logo which is constructed by using different primitives available in OpenGL library. It illustrates the role of different callback functions that provides easier way to accomplish our project in an effective manner.
The project has been implemented by efficiently using the data structures to obtain the optimized results and also various functions and features that are made available by the OpenGL software package have been utilized effectively.   


                                                                                         
INTRODUCTION
	Computers have become a powerful tool for the rapid and economical production of pictures. There is virtually no area in which graphical displays cannot be used to some advantage, and so it is not surprising to find the use of computer graphics so widespread. Although early applications in engineering and science had to rely on expensive and cumbersome equipment, advances in computer technology have made interactive computer graphics a practical tool. Today, we find computer graphics used routinely in such diverse areas as science, engineering, medicine, business, industry, government, art, entertainment, advertising, education, and training.
Computer graphics are graphics created using computers and, more generally, the representation and manipulation of image data by a computer. The development of computer graphics has made computers easier to interact with, and better for understanding and interpreting many types of data. Developments in computer graphics have had a profound impact on many types of media and have revolutionized animation, movies and the video game industry.
A major use of computer graphics is in design processes, particularly for engineering and architectural systems, but almost all products are now computer designed. Generally referred to as CAD, computer-aided design methods are now routinely used in the design of buildings, automobiles, aircraft, watercraft, spacecraft, computers, textiles, and many, many other products.
	Here we have used “OpenGL” as the graphics software system to implement our mini project, “Locomotive Olympics logo. Now let us have a quick look at OpenGL i.e. the existing system.



EXISTING SYSTEM

OpenGL is a library for doing computer graphics. By using it, we can create interactive applications which render high-quality color images composed of 3D geometric objects and images. OpenGL is window and operating system independent. As such, the part of our application which does rendering is platform independent.
	However, for OpenGL to be able to render, it needs a window to draw into. Generally, this is controlled by the windowing system on whatever platform we are working on. As OpenGL is platform independent, we need some way to integrate OpenGL into each windowing system.
	Every windowing system where OpenGL is supported has additional API calls for managing OpenGL windows, color maps and other features. These additional APIs are platform dependent. For the sake of simplicity, we are using an additional freeware library for simplifying interacting with windowing systems, GLUT.
	GLUT, the OpenGL Utility Toolkit is a library to make writing openGL programs regardless of windowing systems much easier. 

Block diagram of OpenGL
 
Figure 1: Graphics pipeline

To obtain an image, first we need to process the geometry of our object, for this we can employ the block diagram in figure1. This above figure is known as the graphics pipeline architecture. 
GRAPHICS CONCEPT USED

 Aim
To display the Olympic logo in a fanciful way.
Olympic logo overview
The Olympic symbols are icons, flags and symbols used by the International Olympic Committee to promote the Olympic Games. Some—such as the flame, fanfare, and theme—are more common during Olympic competition, but others, such as the flag, can be seen throughout the year.
The symbol/logo of the Olympic Games is composed of five interlocking rings, colored blue, yellow, black, green, and red on a white field. This was originally designed in 1912 by Baron Pierre De Coubertin, the founder of the modern Olympic Games. These five rings represent the five continents of the world- Asia, Africa, America, Australia, and Europe. Furthermore, each color ring represents one continent like black ring represents Africa and so on.
 
Figure 2: Olympic Logo
	

Project Description:
The Mini Project   locomotive Olympic logo demonstrates the use of various OpenGL functions and its applications to model the requirements of an application programmer. It also illustrates the use of mathematical functions to control the execution of the project that is presented.
It highlights the key features of the data structures and its high-quality efficiency that is obtained on its usage in the application program. This project consists of Olympic logo which is constructed by using different primitives available in OpenGL library and combining them together in a required manner. It illustrates the role of different callback functions that provides easier way to accomplish our project in an effective manner.











SYSTEM ARCHITECTURE DIAGRAM

SYSTEM REQUIREMENT 
 Hardware requirements
	Processor          : Intel 386 onwards
	RAM                   : At least 16mb of  RAM 
	Hard disk            : At least 100mb of hard disk free space 
	Monitor              : VGA compatible(CRT or LCD-TFT)
       Software Requirements
	Operating system      : UNIX/LINUX
	Language tool            : OpenGL
	Editor		        :  gedit
	Running Environment: Xming


MODULE SPLIT UP
The execution starts from the main function. The following steps show the flow of execution. Initialization of OpenGL and Window System followed by -
•	Initialization of Display window.
•	Display callback function is executed
•	Keyboard callback function is executed.
•	Visibility callback function is executed.
•	Menus are created, and the entries are attached to it.
•	View volume is adjusted.
•	Initially many stars are created.
•	The Event Loop continues to execute infinitely until the exit button is pressed.

MODULE DESCRIPTION



				OUTPUT SCREENSHOTS

 
Figure 5.1: Olympic Logo along with the menu list

 
Figure 5.2: The rings in the Olympic logo at random positions
The above two figures are the snapshots of our program’s output. Figure 5.1 shows the output when the program is executed, and a right mouse click is made. When a right mouse click is made a menu is popped up at the place where the mouse clicks happened; as shown in the fig 5.1. This menu list is a hierarchical menu, because the first menu entry contains sub-menu; which in turn contains 5 entries-
•	Re-initialize
 	Very Slow
 	Slow
 	Normal
 	Very Fast
 	Fast
•	Random position
•	Quit
When the cursor is placed on the “re-initialize” entry, sub-menu will be popped-up which contains further entries as mentioned above.
When “Very Slow” entry is clicked, the Olympic logo is redisplayed such that the motion of the rings from different positions will be very slow.
When “Slow” entry is clicked, the Olympic logo is redisplayed such that the motion of the rings from different positions will be slow.
When “Normal” entry is clicked, the Olympic logo is redisplayed such that the motion of the rings from different positions will be at normal speed.
When “Fast” entry is clicked, the Olympic logo is redisplayed such that the motion of the rings from different positions will be fast.
When “Very Fast” entry is clicked, the Olympic logo is redisplayed such that the motion of the rings from different positions will be very fast.
When the “random position” entry is clicked, the rings of the Olympic logo will be displayed at random positions on the screen as shown in fig 5.2.
When the “Quit” entry is clicked, the display window will get closed and program terminates.
CONCLUSION AND FUTURE WORK

Conclusion
The conclusion here - is that the application of this project. I.e., where all this project’s result can be used. This project would be helpful in websites which hosts information related to Olympics; in a manner to give a graphical home page for that website. Or it can also be used as a part of the game which wants to display the Olympic symbol with graphics effect.

Future work
	At the background of the logo, we can display some image related to Olympics.
	Providing the option to increase size of the logo.
	This project would be helpful in websites which hosts information related to Olympics; in a manner to give a creative home page for that website. 
	Or it can also be used as a part of the game which wants to display the Olympic symbol in a creative manner
REFERENCES

•	Computer Graphics using OpenGL by Hearn and Baker - BOOK
•	http://en.wikipedia.org/wiki/Computer_graphics - LINK
•	http://en.wikipedia.org/wiki/Opengl - LINK
•	http://en.wikipedia.org/wiki/Olympic_symbols - LINK


