
# Medical-Image-Segmentation-using-Window-Segmenting

This Python script performs advanced image processing techniques on brain images, addressing tasks such as segmentation, filtering, and enhancement. The code is designed to handle both healthy brain and brain tumor images. It includes a comprehensive set of steps, including histogram analysis, Otsu thresholding, flood-fill segmentation, Gaussian smoothing, windowing, and histogram equalization.

## Description

Medical image processing plays a crucial role in understanding and diagnosing various neurological conditions. This script aims to provide a robust set of tools for processing brain images, enabling researchers and healthcare professionals to analyze and enhance medical imaging data.

The key features of the script include:

- **Histogram Analysis:** Understanding the pixel intensity distribution in the images.

- **Otsu Thresholding:** Automatically determining optimal thresholds for image binarization.

- **Flood-Fill Segmentation:** Accurate segmentation of brain regions using a flood-fill algorithm.

- **Gaussian Smoothing:** Applying a custom Gaussian filter to reduce noise and enhance features.

- **Windowing:** Focusing on specific intensity ranges to highlight specific structures.

- **Histogram Equalization:** Enhancing image contrast by redistributing pixel intensities.

The provided script utilizes popular Python libraries such as scikit-image, NumPy, and Matplotlib to achieve these tasks. It is intended to serve as a starting point for those working on medical image processing projects or looking to gain insights into the application of image processing techniques to brain imaging.

## Getting Started

### Prerequisites

Make sure you have the following Python libraries installed:

- `skimage`
- `numpy`
- `matplotlib`

Install them using:

```bash 
pip install scikit-image numpy matplotlib 
```
### Usage
#### **Clone the repository:**
```bash 
git clone https://github.com/aringhorui/Medical-Image-Segmentation-using-Window-Segmenting.git 
cd Downloads/Medical-Image-Segmentation-using-Window-Segmenting
```
#### **Run the Python script**
```bash 
python Medical_image_segmentation.py
```
## Code Structure

-   **Image Import and Visualization:**
    
    -   Import necessary modules and visualize original brain images.
-   **Histogram Analysis:**
    
    -   Calculate and display histograms for healthy and tumor images.
-   **Otsu Thresholding:**
    
    -   Implement Otsu's thresholding method for automatic binarization.
-   **Image Binarization:**
    
    -   Apply Otsu thresholds to binarize the images.
-   **Flood Fill Segmentation:**
    
    -   Implement a flood-fill segmentation algorithm for both healthy and tumor images.
-   **Gaussian Smoothing:**
    
    -   Apply a custom Gaussian smoothing filter to the images.
-   **Image Segmentation with Gaussian Filter:**
    
    -   Use flood-fill segmentation on images smoothed with a custom Gaussian filter.
-   **Histogram Equalization:**
    
    -   Perform histogram equalization on windowed brain images.
-   **Windowing and Histogram Analysis:**
    
    -   Apply windowing to the tumor image and perform custom histogram equalization.
-   **Visualization of Results:**
    
    -   Create multiple subplots to visualize results at different processing stages.
   
 ## Contact 
 - aringhorui@icloud.com
