# Amphibian Vision: Deep Learning Frog & Toad Classifier
Combining transfer learning with Grad-CAM to visualise differences between frogs and toads.

Welcome to Amphibian Vision, a deep learning project focused on distinguishing between frogs and toads through images using the EfficientNetV2 model and Grad-CAM visualizations.

## Project Overview
Amphibians are fascinating creatures, and identifying them can be a bit tricky, especially when it comes to distinguishing between frogs and toads. This project aims to train a deep learning model that can not only classify these amphibians with high accuracy, but also highlight what features it uses for differentiating them.

The classifier is built upon the EfficientNetV2 model, fine-tuned on a subset of the iNaturalist 2021 dataset featuring various species of frogs and toads. It utilizes transfer learning, leveraging pretrained ImageNet weights for an effective and efficient training process.

Grad-CAM visualizations are then employed to help us interpret how our model makes its decisions. By highlighting the regions in the image that influence the model's decision the most, we can gain insights into which anatomical features our model deems crucial in distinguishing frogs from toads.

## Viewing the Project
This project is a Jupyter notebook and is best viewed on nbviewer:

https://github.com/Auxeno/amphibian-vision/blob/main/amphibian-vision.ipynb
