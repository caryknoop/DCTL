# DCTL
A collection of DaVinci Resolve DCTL files that may be useful.

# C_Mark
This DCTL works together with C_Analyze, it places information on the video.  
C_Analyze describes the changes made between the C_Mark and the C_Analyze nodes.

`````
__CONSTANT__ int LEVEL = 8;   // Must match the level in C_Analyze.
`````

# C_Analyze
This DCTL works togeher with C_Mark.  C_Mark places information on the video.
C_Analyzes describes the changes made between the C_Mark and C_Analyze nodes.

`````
__CONSTANT__ int LEVEL = 8;   // Must match the level in C_Analyze.
`````

# C_Color_Balance

Shows the color balance by perceptual luminance level as a horizontal stoke on the bottom of the screen. Shows alternating stripes when a particulat luminance level is absent.

````
__CONSTANT__ int  ZOOM          = 1;  // Increase to ZOOM into the shadows.
__CONSTANT__ int  SAMPLE        = 16; // Lower for more accuracy, raise for better performance.
__CONSTANT__ int  PANEL_COUNT   = 20; // The number of horizontal panels (26 max or increase arrays)
__CONSTANT__ int  PANEL_SPACING = 20; // The larger the number the smaller the height of the panels. 
````

# C_Channel_Viewer

Shows channels in RGB and LAB color spaces.

````
__CONSTANT__ int LAB = 1;   // Use 0 for RGB and 1 for LAB
````

