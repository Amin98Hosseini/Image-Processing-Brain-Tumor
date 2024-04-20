# Digital Image Processing Project (Image-Processing-Brain-Tumor)

## Objective
The objective of this assignment is to implement various image processing techniques using Python and OpenCV. Students will work on rotation, cropping, color space conversions, affine and perspective transformations, histogram equalization, gamma correction, and color indexing.

## Tasks
1. **Image Rotation**
   - Write a Python function to rotate an input image by a specified angle.
   - Implement rotation using both nearest neighbor interpolation and bilinear interpolation.
   - Test your functions on a sample image by rotating it by different angles (e.g., 45 degrees, 90 degrees).

2. **Image Cropping**
   - Create a function to crop an input image to a specified region of interest (ROI).
   - Test your function by cropping different regions from a sample image.

3. **Affine Transformation**
   - Implement affine transformation techniques such as translation, scaling, shearing, and reflection.
   - Create functions to apply these transformations individually and combine them to perform complex transformations.
   - Test your functions on sample images and observe the effects of each transformation.

4. **Perspective Transformation**
   - Develop a method to perform perspective transformation to correct distortions caused by the viewpoint of the camera.
   - Implement perspective transformation using OpenCV functions like `cv2.getPerspectiveTransform()` and `cv2.warpPerspective()`.
   - Apply perspective transformation to rectify skewed or tilted images and evaluate the results.

5. **Color Indexing**
   - Develop a method to index colors in an image using k-means clustering.
   - Apply k-means clustering to group similar colors in the image into k clusters.
   - Visualize the indexed colors by replacing each pixel with its nearest centroid color.
   - Experiment with different values of k and analyze the effect on the resulting image.

6. **Color Space Conversion**
   - Implement functions to convert an image from RGB color space to other color spaces such as HSV, LAB, and YCbCr.
   - Display the original image along with its converted versions in each color space.
   - Compare and analyze the differences in representation among different color spaces.

