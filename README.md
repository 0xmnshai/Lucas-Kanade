 
# Optical Flow Visualization with Lucas-Kanade

This repository contains a C implementation of the Lucas-Kanade optical flow algorithm to compute and visualize motion between consecutive frames of a video or image sequence. The code processes JPG frames, calculates the optical flow field, and overlays flow vectors as green arrows on the original images. The output can be stitched back into a video using FFmpeg.

## Features
- **Grayscale Conversion**: Converts RGB JPG images to grayscale for flow computation.
- **Lucas-Kanade Algorithm**: Computes optical flow between consecutive frames using spatial gradients and window-based matching.
- **Visualization**: Draws green flow vectors on the original RGB images using Bresenham's line algorithm.
- **Batch Processing**: Processes a sequence of frames from an input folder and saves results to an output folder.
- **Dependencies**: Uses the lightweight `stb_image.h` and `stb_image_write.h` libraries for image I/O.
