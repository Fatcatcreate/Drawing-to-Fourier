# Fourier Drawing Visualizer

## Introduction
This project is inspired by [3Blue1Brown's Fourier Transform video](https://www.youtube.com/watch?v=r6sGWTCMz2k). The video beautifully explains how the Fourier Transform can decompose complex signals into simple circular motions. This visualization brings that concept to life, allowing users to draw their own shapes and see how they can be reconstructed using epicycles.

## Features
- **Draw and Transform**: Users can draw any shape on a canvas, which is then transformed into a series of rotating circles using the Discrete Fourier Transform (DFT).
- **SVG Import**: Upload an SVG file to extract paths and visualize its Fourier series representation, uses basic interpretation of the file.
- **Customizable Animation**: Control the number of circles and the speed of animation.
- **Trace Path**: See how the Fourier-transformed function reconstructs the original shape over time.

## How It Works
1. **Drawing Input**: Users draw a shape on the canvas.
2. **Resampling**: The drawn path is resampled to ensure a uniform number of points.
3. **Discrete Fourier Transform (DFT)**: The resampled points are transformed into complex frequency components.
4. **Epicycle Animation**: The sorted Fourier components are used to animate a series of rotating circles that trace the original shape.

## Controls
- **Play/Pause**: Toggle the Fourier animation.
- **SVG Upload**: Import SVG paths for visualization.
- **Number of Circles**: Adjust the number of epicycles used for reconstruction.
- **Animation Speed**: Modify the speed of the drawing process.

## Installation & Usage
Simply open the `index.html` file in a browser and start drawing! No additional setup is required.

## Credits
- Inspired by [3Blue1Brown](https://www.3blue1brown.com/) and his amazing explanatory video on the Fourier Transform.


