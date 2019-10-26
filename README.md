# OpenGL Line Art 
This is a simple line art program that uses linear interpolation to create curves based on the equation `(1 - t) * a + t * b`

[Wikipedia Reference Link](https://en.wikipedia.org/wiki/Linear_interpolation)

## Usage
After compliation give the program executable the number of sides and number of lines to interpolate on.

**NOTE:** Be sure to place the OpenGL files `i.e. glut.h, glut32.lib, glut32.dll, glut.def` in the same directory as Source.cpp. These are necessary files for the compilation of the project. 

Running the program with 10 sides and 50 lines produces the following output

![Sample text](https://imgur.com/k1EyjUp)

![Sample text](https://imgur.com/7GLR5Mg)

## Acknowledgements
The OpenGL Utility Toolkit was originally written by Mark Kilgard

Download the full glut source [Here](https://user.xmission.com/~nate/glut.html) 