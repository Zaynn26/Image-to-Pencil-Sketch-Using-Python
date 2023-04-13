# Image-to-Pencil-Sketch-Using-Python
This code uses the OpenCV library to convert an image to a pencil sketch. Here are the steps involved in the process:

Read the input image and convert it to grayscale using cv2.cvtColor function.
Invert the grayscale image using the formula inverted_gray_image = 255 - gray_image.
Apply Gaussian blur to the inverted image using cv2.GaussianBlur function.
Blend the grayscale image and the blurred image using the "divide" blending mode using cv2.divide function.
Save the resulting pencil sketch image using cv2.imwrite function.
The resulting pencil sketch image will be saved in the same directory as the input image.
