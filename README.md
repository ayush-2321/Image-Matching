# Image-Matching
This project is divided into 3 parts. The report, as well as Python implementation, is included for all 3 parts.
## Image matching using traditional methods
This project aims to develop a robust and efficient image-matching algorithm for various applications in computer
vision. We discussed a few traditional approaches for feature extraction, such as SURF and
SIFT. We then used these extracted features for the image-matching task. To test these approaches, we have used one
of them(SIFT) for the face recognition task.

## Image matching using deep learning-based approaches
Our first report discussed traditional algorithmic
approaches such as SIFT and SURF detectors. Now, we will
discuss a learning-based approach to the image-matching
problem. The literature review for the report has been divided into two sections: classical machine learning-based
approach and deep learning-based approach. We further
tried implementing some face recognition approaches using the YALE face dataset. We also tried to train a deep
learning-based feature descriptor using the Homography
patches dataset.

## Image Matching challenege 2022
In our previous parts, we discussed different stages of
image matching in a learning-based approach. In our final report, we combine these stages to create an end-to-end
pipeline for relative pose estimation using fundamental matrix calculation. For testing our pipeline, we used the Image
Matching Challenge 2022 test dataset. We started with different state-of-the-art models as our baseline, such as SuperGLUE, DKM, LoFTR, etc. We then tried out their ensemble along with several test time augmentations. We also
discussed a commonly used clustering algorithm(DBSCAN)
and used it to find common scenes in both images in our final pipeline. We tested all our implementations through Kaggle submissions, and our best submission got placed in the
top 50 in the final leaderboard.
