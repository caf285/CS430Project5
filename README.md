# CS430Project5

DEC 9 (repository update)
-----
+ Remaining Required Functionality
  - Keyboard shortcuts for the following quad manipulation: Pan, Shear
  
+ Updated Functionality
  - Read loaded PPM file into an image buffer (P3, with added alpha channel)
  - Apply image to quad. 
  
+ Comments
  - Do I get extra credit points for making a raspberry pi retro console? Probably not. OMG are those things cool. As a fellow gamer, I highly recommend.
  
DEC 8 (repository update)
-----
+ Remaining Required Functionality
  - Keyboard shortcuts for the following quad manipulation: Pan, Shear
  - Read loaded PPM file into an image buffer (P3, with added alpha channel)
  - Apply image to quad.

+ Updated Funtionality
  - Triangle poly is now a quad
  - Keyboard shortcuts now control quad manipulation
  - Quad manipulation now includes: Horizontal Scale, Vertical Scale, Rotation
  - PPM File can now be loaded, but no information is read
  - Great Odin's Raven! ... The spinning has stopped (replaced clock function for rotation by keypress)
 
 + Comments
   - I'm not sure at this point, but it seems like the quad manipulation commands are actually skewing the active window rather than the shape presented on the window. I will look for an alternative, but I want to finish all other functionality first.

DEC 7 (repository creation)
-----
+ Required Functionality
  - Keyboard Support for stretching and skewing the poly (pan, rotate, scale, shear)
  - Read an image file and apply the image to the poly
  - create square poly for image map
  - stop the spinning ... OH GOD STOP THE SPINNING
  - Name program ezview (called by "ezview image.ppm")

+ Current Functionality
  - Spinning colorful triangle

The Sample C code given in class finally runs on my machine using Xcode. 17 hours of searching later, and I found a tutorial for how to install GLFW. The website certainly did not help at all ... and seemingly, neither did the lectures. Please, if you want to have us paint a beautiful image for you, then give us a paint brush. OK. Xcode works ... holy hell. Now for the requirements.
