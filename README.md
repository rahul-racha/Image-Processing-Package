# Image Processing Package
This repository contains a standalone image package (prototype package) independent of the operating system. It implements 
features coverering various aspects of image processing concepts and techniques. The package is developed using [MATLAB's 
App Designer](https://www.mathworks.com/products/matlab/app-designer.html). 

# Features
The tool allows to open a local image, process it and save the processed image.
### Convert images into different color models (CMYK, RGB, CMY, HSI)
- CMYK Model

  <img src="./resources/cmyk-model.png" height="300">
  
- | RGB                                              |  CMY                                             | HSI                                              |
  |--------------------------------------------------|--------------------------------------------------|--------------------------------------------------|
  |<img src="./resources/rgb-model.png" width="200"/>|<img src="./resources/cmy-model.png" width="200"/>|<img src="./resources/hsi-model.png" width="200"/>| 
#
### Enhance images quality (histogram processing)
- Brightness (0.1 - 0.9) and contrast (0.1 - 0.9) values can be set to control histogram processing.
|                                                            |                                                            |
|------------------------------------------------------------|------------------------------------------------------------|
| <img src="./resources/hist-full.png" height="200"/>        | <img src="./resources/hist-half.png" width="250"/>         |
