README.tools for MagChain 24Nov2011 package.

****** MagChainGLViewer ******
  Description: 3D visualization application for the MagChain program.
  
  Compilation: type "make" into the source folder and select the achitecture. 
  Requirements: C++ compiler together with the openGL development libraries. (As example, the freeGLUT distribution in openSUSE linux).

  List of available commands (this list can be visualized by pressing the right-mousse button over the application window.)

        'P': Set perspective.
        'O': Set orthographic.
        'T': Activate Translations.
        'R': Activate Rotations.
        'a': Place axis reference at the center of the box.
        'A': Place axis reference at origin.
        'x': Rotate/Translate clockwise respect to the axis.
        'X': Rotate/Translate anti-clockwise respect to the axis.
        'y': Rotate/Translate clockwise respect to the axis.
        'Y': Rotate/Translate anti-clockwise respect to the axis.
        'z': Rotate/Translate clockwise respect to the axis.
        'Z': Rotate/Translate anti-clockwise respect to the axis.
        '+': Zoom IN.
        '-': Zoom OUT.
        'p': Toggle Play/Pause.   
        'r': Resart movie.                        
        'q': Restart view. 
        'Q': Quit the application.

****** MagChainPyViewer.py ******
  Description: 3D Visualization of 'trajectoryCG.xyz' generated by MagChain

  Compilation: Non-required.
  Requirements: VPython script to be executed by VIDLE for VPython (with VPython libraries). Documentation on VPython can be found at:
       http://vpython.org/contents/doc.html
  and it can be downloaded:
       Linux: http://vpython.org/contents/download_linux.html
       Windows: http://vpython.org/contents/download_windows.html
       Mac: http://vpython.org/contents/download_mac.html

 Usage: 
	- Run "Representation.py" using IDLE in the same folder where the trajectory
	  generated by "MagChain" ("trajectoryCG.xyz") is.
	- To help the visualization of the trajectory:
	    · The perspective can be changed by moving the mouse while pressing the right button. 
	    · The image can be zoomed in/out by moving the mouse forward/backward while pressing the left and right buttons simultaneously.


****** attradius.cpp ******
  Description: Simple routine to create the required file containing the attraction radius for each object in the simulation according to the magnetic coupling parameter.
  
  Compilation: type "make" into the source folder.
  Requirements: C++ compiler.
