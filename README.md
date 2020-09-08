# Facial Landmarks Detetcion 

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [File Structure](#file-structure)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Contributors](#contributors)
* [Resources](#resources)


<!-- ABOUT THE PROJECT -->
## About The Project 
|![Single face detection](https://github.com/prakash-2702/Facial_Landmarks_Detection/blob/master/assets/single%20face.PNG)|![Multiple face Detection]
(https://github.com/prakash-2702/Facial_Landmarks_Detection/blob/master/assets/multiple%20faces.PNG)|
|:---:|:---:|
|Single face detection|Multile face Detection|  
* Facial landmarks are used to localize and represent salient regions of the face, such as:
  1. Eyes
  2. Eyebrows
  3. Nose
  4. Mouth
  5. Jawline
  
**Steps followed in this process:**
  1. Initializing dlib's face detector (HOG-based).
  2. Pre-processing of the image (loading,resizing,converting to gray-scale).
  3. Detection of faces in the grayscale image.
  4. Determining the facial landmarks for the face region.
  5. Converting dlib's rectangle to a OpenCV-style bounding box.
  6. Looping over the (x,y) co-ordinates.
  7. Showing the output.

### File Structure
    .
    ├── facial_landmarks.py             # Driver code
    ├── HOG+Linear SVM Object Detector  # Pre-trained model link
    ├── images                          # images for testing
    ├── assets                          # for readme
    └── README.md 
    
<!-- GETTING STARTED -->
## Getting Started

### Prerequisites  
* Python
* OpenCV
* Numpy 
* Dlib 
* Imutils
* Argparse

### Installation
1. Clone the repo
```sh
git clone https://github.com/prakash-2702/Facial_Landmarks_Detection.git
```    
<!-- CONTRIBUTORS -->
## Contributors
* [Prakash Nadgeri](https://github.com/prakash-2702)
<!-- ACKNOWLEDGEMENTS AND REFERENCES -->
## Resources
* https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_tutorials.html
* [Histogram of Oriented Gradients and Object Detection](https://www.pyimagesearch.com/2014/11/10/histogram-oriented-gradients-object-detection/)
* [pyimagesearch](https://www.pyimagesearch.com/2017/04/03/facial-landmarks-dlib-opencv-python/)



