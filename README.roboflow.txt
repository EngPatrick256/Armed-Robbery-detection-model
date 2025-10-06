
Armed Robbery - v2 2025-02-06 2:19pm
==============================

This dataset was exported via roboflow.com on March 11, 2025 at 3:04 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 20715 images.
Armed-robbery are annotated in YOLOv11 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:

The following transformations were applied to the bounding boxes of each image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 16 percent of the bounding box
* Random exposure adjustment of between -17 and +17 percent
* Random Gaussian blur of between 0 and 2.5 pixels
* Salt and pepper noise was applied to 4 percent of pixels


