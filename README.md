# Mask-Classification-Model

This model predicts whether someone is wearing a mask, not wearing a mask, or wearing a mask incorrectly. The model is based on a **pretrained ResNet** architecture and achieves around **90% test accuracy**.

## Directory Structure

To run the model, you must have your own datasets in the following directory structure:


### Folder Details:

- **mask_data/**: This folder holds the training data. Inside this folder, you will find:
  - **annotations/**: Contains XML files with annotations for the mask images.
  - **images/**: Contains the image files with people either wearing a mask correctly, incorrectly, or not wearing a mask at all.

- **test_mask_data/**: This folder holds the testing data. It follows the same structure as `mask_data`:
  - **annotations/**: Contains XML files with annotations for the test images.
  - **images/**: Contains the images for testing the model.


