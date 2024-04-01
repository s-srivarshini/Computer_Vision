# Computer Vision Toolkit

This toolkit offers a comprehensive suite of Python scripts designed for executing various computer vision tasks, including image transformations, convolutions, texture classification, video segmentation, and object counting, using popular libraries such as OpenCV and SciPy.

## Installation
To run the notebook and replicate the findings, ensure you have the following Python packages installed:
```bash
pip install numpy
pip install scikit-learn
pip install opencv-python
pip install matplotlib
pip install pandas
pip install scipy
```

### Usage
The toolkit is organized into separate functions, each designed to perform specific computer vision tasks:

1. **Transformations**: Includes functions for image rotation, translation, and skewing.
2. **Convolutions**: Demonstrates the application of convolution operations on images using custom kernels.
3. **Texture Classification**: Utilizes Local Binary Pattern (LBP) for texture analysis and classification.
4. **Video Segmentation**: Implements frame differencing techniques for background subtraction and moving object detection.
5. **Object Counting**: Counts moving objects in video sequences by analyzing frame differences.
   

### Detailed Description
- **Transformations**: The section includes a detailed matrix formulation for rotating and skewing images. It demonstrates how to perform these transformations with bilinear interpolation for pixel value estimation.
- **Convolutions**: This section provides examples of applying convolution operations with different kernels to analyze their effects on images, including blurring and edge detection.
- **Texture** **Classification**: Demonstrates how to divide an image into non-overlapping windows, compute the LBP for each window, and use this for texture classification.
- **Video** **Segmentation**: Discusses methods for creating a reference frame and counting moving objects in video sequences through frame differencing.
Object Counting: Offers a technique for counting moving objects across video frames using background subtraction and temporal averaging.
