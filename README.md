# DCTL
DaVinci Resolve DCTL files

A collection of DCTL files that may be useful.

# C_Color_Balance

Shows the color balance by perceptual luminance level as a horizontal stoke on the bottom of the screen. Shows alternating stripes when a particulat luminance level is absent.

Variables:
````
__CONSTANT__ int  ZOOM          = 1;  // Increase to ZOOM into the shadows.
__CONSTANT__ int  SAMPLE        = 16; // Lower for more accuracy, raise for better performance.
__CONSTANT__ int  PANEL_COUNT   = 20; // The number of horizontal panels (26 max or increase arrays)
__CONSTANT__ int  PANEL_SPACING = 20; // The larger the number the smaller the height of the panels. 
````

# C_Channel_Viewer

Shows channels in RGB and LAB color spaces.

Variables:
````
__CONSTANT__ int LAB = 1;   // Use 0 for RGB and 1 for LAB
````

