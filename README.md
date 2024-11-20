# Simple_Object-Detection

Object Detection on the Oxford-IIIT Pet Dataset
This project demonstrates how to perform object detection on the Oxford-IIIT Pet dataset by calculating bounding boxes from segmentation masks and visualizing the results.

Dataset
Oxford-IIIT Pet Dataset
Source: Available via TensorFlow/Keras (tensorflow_datasets.load) or PyTorch (torchvision.datasets).
Purpose: Detect and localize pet objects in images using bounding boxes derived from segmentation masks.

Structure: The dataset includes images, segmentation masks, and labels for pet breeds.

# Project Workflow

1. Dataset Loading
Load the dataset using TensorFlow Datasets (tfds.load), including training and testing subsets.
Display dataset metadata for an overview.

2. Bounding Box Calculation
Method:
Identify non-background pixels in the segmentation mask.
Compute the minimum and maximum coordinates (xmin, xmax, ymin, ymax) to create a bounding box.

3. Visualization
Visualization Function:
Displays the pet image alongside the segmentation mask.
Overlays the calculated bounding box on the image.

   
# Running the Project
1. Install Dependencies:

2. Install the required libraries: tensorflow, numpy, matplotlib, opencv-python.
Refer to requirements.txt for version specifications.
Dataset Setup:

3. Load the Oxford-IIIT Pet dataset using TensorFlow Datasets.
Verify the dataset's structure and contents.
Visualization:

4. Run the visualize_pet_segmentation_with_contours function on sample images from the dataset.
Bounding boxes are displayed on pet images, with corresponding segmentation masks.

Outputs:

Bounding Boxes: Calculated (xmin, ymin, xmax, ymax) coordinates for each image.
Visualizations: Images with overlaid bounding boxes and segmentation masks for qualitative evaluation.

Dependencies
Python 3.x
TensorFlow
NumPy
Matplotlib
OpenCV
