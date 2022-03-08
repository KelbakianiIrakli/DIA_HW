# DIA_HW2
This is homework for Document Image Analysis course.
I get images from the folder "images".
I implemented convolution function. In order to have the final image size equal to the size 
of the original picture, I added 2 rows and 2 columns filled with all zeros to the original image.
The convolution function creates a numpy array of all zeros. The size of the array is image size – kernel_size + 1 
(As after convolution is applied image size is reduced).  I multiply kernel 
with appropriate matrix and writing result to convolved images corresponding member. 

Irakli Kelbakiani
