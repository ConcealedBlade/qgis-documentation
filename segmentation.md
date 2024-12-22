# Segmentation

## Overview
The main interface of the program is located under the **Segmentation** tab. Its primary function is to perform feature extraction using remote sensing images, utilizing the [**AerialFormer**](https://github.com/UARK-AICV/AerialFormer) model for image prediction and processing.

![Main Interface](segmentation.png)

## Operation Steps

1. **Select Image Sample**
   - Click the first "Browse..." button on the interface.
   - Choose the remote sensing image sample to be processed.

2. **Image Processing**
   - The system will use the [**AerialFormer**](https://github.com/UARK-AICV/AerialFormer) model to predict and process the input image.
   - Different features in the image will be marked with different colors, generating semantic segmentation results.

![Processing Result](segmentation_result.png)

?> **Technical Note**: **AerialFormer** is a multi-resolution Transformer model designed specifically for aerial remote sensing image segmentation tasks. It efficiently extracts feature information from images.

3. **Layer Overlay**
   - In the **Layer Tree** panel on the right side of the interface, you can adjust the pixel values of the grayscale mask layer (range: 0-255) to optimize the visual effect of the image and highlight target objects.
   - The output image can overlay other layers, such as the original image or the predicted label map, for easier comparison and analysis.

![Grayscale Mask](mask.png)

!> The layer overlay function is also available on other pages and will not be repeated here.