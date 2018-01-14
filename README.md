# DCTL
DaVinci Resolve DCTL files

A collection of DCTL files that may be useful.

C_Color_Balance
  Shows the color balance by luminance level. Shows stripes when a luminance level is absent.

Variables:

```
COLOR_SPACE                  = 0;       // Use 0 for Rec709, other color spaces not yet implemented.
const float ZOOM             = 1.0f;    // Increase to ZOOM into the shadows.
const int   SAMPLE           = 32;      // Lower for more accuracy, raise for better performance.
const int   PANEL_COUNT      = 20;      // Defines the number of horizontal panels (25 max or increase arrays)
const int   PANEL_SPACING    = 20;      // The larger the number the smaller the height of the panels. 
``` 
