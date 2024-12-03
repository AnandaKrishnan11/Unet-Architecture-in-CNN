# U-Net Model for Image Segmentation

This repository contains two versions of the U-Net architecture for image segmentation tasks:

1. **Original U-Net**
2. **Enhanced U-Net**
3. **Attention U-Net**
4. **ResAttention U-Net**

## Model Descriptions

### Original U-Net
The original U-Net model is a convolutional neural network developed for biomedical image segmentation but is also effective for general image segmentation tasks.

### Enhanced U-Net with Batch Normalization
This model builds on the original U-Net by adding Batch Normalization layers, Dropout layers and padding after each convolutional layer. This modification helps the model learn more effectively and often results in improved accuracy.

### Attention UNet
An enhanced U-Net model incorporating attention mechanisms to improve focus on relevant spatial features, making it ideal for geospatial image segmentation tasks.

### ResAttention UNet
A U-Net variant that combines residual connections and attention gates to boost feature extraction and localization, designed for complex geospatial datasets.
