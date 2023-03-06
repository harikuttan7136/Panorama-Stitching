# Panorama-Stitching using Hessian Corner Detection
Given the frames stitching the images together to create a good panorama. For more detail refer to the report and the code

Python code is available in .ipynb file.
Steps involved in the stitching process is 

•	Gaussian blurring: blurring the image using the gaussian blur technique
•	Hessian corner detection: to find the key points
•	Descriptor finding: to find the descriptor around the key points(a patch is taken around keypoint)
•	Matching descriptors: to find the best match descriptors between the frames
•	Affine transformation: to find the affine transformation matrix between the frames
•	RASAC : to fithe nd best fit affine transformation matrix 
•	Pairwise Stitching: Stitching the two images together after applying best-fit fit affine transform
•	Multi Stitching: an algorithm to stitch all the images together using a  pairwise stitching function
