# CVIT-workshop
This repo comprises the learnings of a 7-day long learning-by-doing sessions held at CVIT-workshop (Centre for Visual Information Technology, IIIT-H, India). <br /> These structured sessions presented me an opportunity to solidify my understanding of various DIP (Digital Image Processing) techniques by coding up corresponding implementations.

## Day-1 Learnings:

### Session 1:
    Implementations of:
    - Data structures e.g., *int*, *string*, *boolean*, *list*, *tuple*, *dict*
    - Conditional statements e.g., *if-else* and *loops*
    - Functions and File operations
    - Simple image manipulations via:
        - OpenCV, Numpy and matplotlib libraries
        - Histograms and thresholding
        - Chroma Keying

### Session 2:
    - Implementation of simple morphological operations on image like dilation, erosion, closing, etc.
    - Applied the aforementioned learnings to build a **Barcode Detection and Scanning System** via traditional image processing techniques

## Day-2 Learnings:
    For Day-2, the topic was "Document Image Processing"
    We tried to emulate some of the functionalities of well-known document image tools like CAMSCANNER in the most basic ways via DIP techniques
    The goal was to understand the primitive pipeline that some of these functionalites follow, and their corresponding challlenges

### Session 1:
    The notebooks have the implementations of:
    - Task 1: Skew correction in a document image
    - Task 2: Word-level and Line-level segmentation tasks

### Session 2:
    - Applied the aforementioned image processing methods along with template matching to code up a **Cheque Number Detection and Reading System**

## Day-3 Learnings:

### Session 1:
    - Learned the concept of Convex Optimization as to how it plays a vital role in terms of removing high frequency noise from the signal
    - Implemented the convex optimization via CVXPY library
    - Solved the problem of Cinematic Shot Generation using Convex Optimizaiton
      **Overview of the problem**: Automatically focusing on a subject of interest in a video in a manner that the generated sub-clip is aesthetically pleasing
      **Input**: Given the per-frame bounding box data focussed on subject of interest (noisy)
      **Output**: Generate temporally consistent bounding boxes on the subject of interest such that the generated sub-clip is aesthetically pleasing.

### Session 2:
    - How to interpret medical images encoded in '.dcm' format

## Day-4 Learnings:
    - Learned the basics of 3D Computer vision

### Session 1:
    - Implemented basic operations like Rotation, Translation etc. using Pymeshlab

### Session 2:
    - Implemented 3D image manipulation techniques using Open3D
    
## Day-5 Learnings:

### Session 2:
    - Task1: Implemented a simple multi-layer perceptron network to classify animal species   
    - Task2: Implemented a simple face-detector via a pre-trained model
    
## Day-6 Learnings:

### Session 1:
    - Demo of how to use WandB to log model training results

### Session 2:
    - Implemented a basic example of image captioning
    
## Day-7 Learnings:

### Session 1:
    - Handwritten digit recognititon using LeNet-5

### Session 2:
    - Task1: Implemented an MLP network to read the time from an analog clock image    
    - Task2: Implemented a CNN to read the time from an analog clock image
