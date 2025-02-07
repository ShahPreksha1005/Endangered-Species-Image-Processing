# **Endangered Species Identification Using Camera Trap Images**  

## **Overview**  
This project applies digital image and video processing techniques to analyze images and video frames for endangered species identification. It covers thresholding, contrast stretching, filtering, morphological operations, feature detection, and connected component analysis.

## **Features**  
- **Image Processing:**  
  - Thresholding and binary conversion  
  - Contrast stretching for intensity enhancement  
  - Median filtering for noise reduction  
  - Edge detection using Canny algorithm  
  - Morphological operations for shape analysis  

- **Video Processing:**  
  - Frame extraction from video  
  - Grayscale conversion and thresholding  
  - Connected component analysis for object identification  
  - Bounding box visualization for detected components  

## **Libraries Used**  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-image (`skimage`)  
- SciPy  

## **Usage**  
1. Upload at least two images for processing.  
2. The script applies various image processing techniques, analyzes components, and extracts meaningful insights.  
3. For video processing, a sample wildlife video can be provided to extract and analyze frames.  

## **Results and Insights**  
- Number of identified objects in images  
- Total area covered by detected components  
- Density analysis of connected components  
- Edge detection highlighting key features  
- Morphological transformations for enhanced object identification  

## **Future Enhancements**  
- Integrating deep learning for species classification  
- Automating feature extraction from images  
- Applying real-time processing for live camera feeds  
