# Construct 3 + Pixelmatch glue project / library
If you ever want to do pixel by pixel comparison of drawing canvas objects inside Construct 3, you might find this project useful. It's just some glue between the excellent Pixelmatch JavaScript library by Mapbox.

## Usage
If you want to use this in your project, just copy the PixelMatch event sheet, importsforevents.js and pixelmatch-5.3.0.module.js (either with its parent folders, or if you move/rename it, be sure to adjust the path in importsforevents.js) and that's it. To start the comparison, call the PIXELMATCH_startComparison function with the UIDs of the drawing canvas objects (they should have the exact same resolution). If the comparison succeeds, the function PIXELMATCH_onComparisonSuccess will be called with the amount of mismatching pixels.

## License
This C3 project is licensed under MIT, Pixelmatch is licensed under ISC.