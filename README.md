# Arabic Traffic Sign Image Preprocessing  

This repository focuses on **image preprocessing** for Arabic traffic sign images, preparing them for **machine learning classification**. The preprocessing steps are applied to the **ArTS dataset**, which includes **2,718 real images** and **57,078 augmented images**, covering **24 Arabic traffic sign categories** from **Khobar, Dammam, and Dhahran in Saudi Arabia**.  

## Motivation  

Image preprocessing is a critical step in **improving image quality** before applying machine learning models. This project explores various preprocessing techniques to ensure Arabic traffic sign images are **clear, standardized, and optimized** for future classification tasks.  

## Dataset  

- **Name:** Arabic Traffic Signs (ArTS)  
- **Size:** 2,718 real images, 57,078 augmented images *(augmentation provided by dataset, not performed in this project)*  
- **Categories:** 24 different Arabic traffic signs  
- **Source:** [ArTS Dataset on Mendeley](https://data.mendeley.com/datasets/4tznkn45mx/1)  

## Preprocessing Techniques  

1. **Image Loading & Grayscale Conversion**  
   - Ensures images are in **RGB format** and converts them to **grayscale** for simpler processing.  

2. **Contrast Enhancement & Noise Reduction**  
   - Improves image contrast and removes noise for better clarity.  

3. **Edge Detection & Sharpening**  
   - Uses **Laplacian filtering** to detect edges and sharpen images.  
   - Enhances details by subtracting the filtered image from the original.  

4. **Thresholding**  
   - Converts images to a **binary format** by setting pixels above a threshold to white and others to black.  

These preprocessing steps help enhance the quality and consistency of traffic sign images, making them more suitable for future classification tasks.  
