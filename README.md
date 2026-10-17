# EN3160 Assignment 2 – Fitting and Alignment

**Name:** A.H.T.M. Weerakoon

## Contents
| Question | Topic | Method |
|---|---|---|
| Q1 | Sunflower detection | Scale-normalised LoG, scale-space extrema |
| Q2 | Line + circle fitting | RANSAC (own implementation), constrained least squares |
| Q3 | Image overlay | 4-point homography, perspective warp, alpha blending |
| Q4 | PCB alignment | SIFT, BFMatcher + ratio test, RANSAC homography |

## Run
pip install -r requirements.txt
jupyter notebook en3160_a02.ipynb

Q3 point-clicking uses an OpenCV window, so run the notebook locally (not in Colab).
