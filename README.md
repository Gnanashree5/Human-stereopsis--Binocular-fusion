# Human-stereopsis--Binocular-fusion

## Overview

This project demonstrates the concept of *Human Stereopsis* and *Binocular Fusion*. It simulates how the human brain combines slightly different images from each eye to perceive depth using synthetic stereo images.

### What is Stereopsis?

Stereopsis is the ability to perceive depth and 3D structure based on visual input from two eyes. It relies on:
- **Binocular Disparity**: The difference between the images formed on the left and right retinas due to their horizontal separation.
- **Correspondence Problem**: Matching points between the two images to calculate disparity.
- **Depth Perception**: Using the disparity to estimate how far objects are.

### What is Binocular Fusion?

Binocular fusion is the process by which the brain merges the slightly different images from each eye into one cohesive view. It plays a vital role in stereopsis by enabling depth perception.

---

## Code Description

### Synthetic Stereo Images
The code generates two synthetic images with a horizontal disparity to simulate left and right eye perspectives. A circle is drawn at slightly shifted positions in the two images.

### Computing Disparity
Using OpenCV's `StereoBM` algorithm, the code computes a disparity map that highlights differences between the two images. The disparity map helps visualize depth perception by mapping pixel shifts to depth values.

### Visualization
- The left and right images are displayed to illustrate the shifted perspectives.
- The disparity map is generated and displayed in color to represent relative depth.

---
<h2>Acknowledgements</h2>
<p>This notebook was done under guidance of  <a href="https://github.com/Victor-Ikechukwu">Dr. Agughasi Victor Ikechukwu</a></p>

