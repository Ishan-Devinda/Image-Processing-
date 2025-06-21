Intruduction 
The assignment involves implementing four fundamental image processing tasks using 
Python with OpenCV and NumPy libraries: 
1. Reducing intensity levels (from 256 to specified powers of 2) 
2. Performing spatial averaging (3×3, 10×10, and 20×20 kernels) 
3. Rotating images (45° and 90°) 
4. Reducing spatial resolution (block averaging with 3×3, 5×5, and 7×7 non-overlapping 
patches)

This is the original image used:

![Image](https://github.com/user-attachments/assets/6274153b-d5a2-47e7-8f6c-3a9dd6c0a14e)

1. Reducing Intensity Levels in an Image 
Reduce the number of intensity levels from 256 to a specified power of 2 ( 2, 4, 
8, 16, 32, 64, 128, 256).
/n
Result:
![Q1](https://github.com/user-attachments/assets/672a9ce9-4bce-48a2-9eae-21c2c2e86402)

2 Spatial Averaging (Smoothing) with Different Kernels 
Apply a 3×3, 10×10, and 20×20 average filter to smooth the image.
Result:
![Q2](https://github.com/user-attachments/assets/287deceb-3e07-4bde-b405-e49225aa27c0)

3. Image Rotation by 45 and 90 Degrees 
Rotate the image by 45° and 90° using affine transformations. 

Result:
![Q3](https://github.com/user-attachments/assets/aa735b6a-352d-41d2-a90a-138cf729bdcf)

4. Reducing Image Resolution Using Block Averaging 
Replace non-overlapping blocks (3×3, 5×5, 7×7) with their average pixel value.
Result:
![Q4](https://github.com/user-attachments/assets/658372f6-4fa8-454a-a4cc-dc43a5c0eaae)

Conclusion 
This assignment successfully implemented four fundamental image processing techniques: 
intensity reduction, spatial averaging, rotation, and resolution reduction. The results 
demonstrate how each operation affects image quality and structure. All output images are 
included in the results folder, and the complete code is available in the GitHub repository. 
These exercises provide valuable hands-on experience with core computer vision concepts.

