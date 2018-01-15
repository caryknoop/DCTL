# DCTL
DaVinci Resolve DCTL files

A collection of DCTL files that may be useful.

# C_Color_Balance

Shows the color balance by perceptual luminance level as a horizontal stoke on the bottom of the screen. Shows alternating stripes when a particulat luminance level is absent.

Variables:

```
const float ZOOM          = 1.0f; // Increase to ZOOM into the shadows.
const int   SAMPLE        = 32;   // Lower for more accuracy, raise for better performance.
const int   PANEL_COUNT   = 20;   // Defines the number of horizontal panels (25 max or increase arrays)
const int   PANEL_SPACING = 20;   // The larger the number the smaller the height of the panels. 
``` 
