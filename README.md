# AI-Detection-in-Agriculture
Detecting diseases in agri using superpixel approach
High-Level Structure
1. Preprocessing
Load the image.
Convert to LAB color space.
Define SLIC superpixel segmentation parameters.
2. Superpixel Segmentation (SLIC)
Initialize superpixels.
Refine clusters over 10 iterations.
Display the segmented image with boundaries.
3. K-means Clustering on Superpixels
Flatten image into features.
Run K-means (k=2) on the superpixels.
Assign cluster labels to pixels.
4. Extract Superpixel Features
Compute min/max LAB values for each superpixel.
Store color features.
Analyze mean values of A/B channels.
5. Display and Save Results
Show segmented image.
Save clustered image to Google Drive.
