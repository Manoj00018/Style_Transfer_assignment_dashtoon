Style Transfer with PyTorch
Overview

This project utilizes PyTorch, a powerful deep learning library, to perform style transfer on images. The code implements a neural style transfer algorithm using a pre-trained VGG-19 model.
Libraries Used

    PyTorch: Deep learning library for building and training neural networks.
    Matplotlib: Plotting library for visualizing images and results.

Model

    VGG-19: A pre-trained convolutional neural network (CNN) from PyTorch's model zoo. It is used for feature extraction during style transfer.

Processes

    Image Loading and Preprocessing: Style and content images are loaded and processed using PyTorch transformations.
    Image Visualization: Matplotlib is employed to visualize style and content images along with their color palettes.
    Mask Generation: Masks are generated based on user-defined color matching orders or combined color palettes.
    VGG Model Loading: The VGG-19 model is loaded and prepared for feature extraction.
    Style Transfer Execution: The main style transfer algorithm is executed using PyTorch and VGG-19, resulting in an output image.
    Results Display: Matplotlib is used to display and optionally save the output image. 
