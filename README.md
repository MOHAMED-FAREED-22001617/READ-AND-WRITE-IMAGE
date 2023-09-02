# READ AND WRITE AN IMAGE
## AIM
To write a python program using OpenCV to do the following image manipulations.
i) Read, display, and write an image.
ii) Access the rows and columns in an image.
iii) Cut and paste a small portion of the image.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Choose an image and save it as a filename.jpg
### Step2:
Use imread(filename, flags) to read the file.
### Step3:
Use imshow(window_name, image) to display the image.
### Step4:
Use imwrite(filename, image) to write the image.
### Step5:
End the program and close the output image windows.
## Program:
### Developed By:MOHAMED FAREED F
### Register Number:212222230082
i) #To Read,display the image
```
import cv2
color_img=cv2.imread('sayonora.jpg',1)
cv2.imshow('212222230082',color_img)
cv2.waitKey(0)
  

```
ii) #To write the image
```
import cv2
color_img=cv2.imread('sayonora.jpg',1)
w=cv2.imwrite('4.png',color_img)
cv2.imshow('212222230082'color_img)
cv2.waitKey(0)



```
iii) #Find the shape of the Image
```
import cv2
import random
color_img=cv2.imread('sayonora.jpg',1)
print(color_img.shape)



```
iv) #To access rows and columns

```

import cv2
import random
color_img=cv2.imread('sayonora.jpg',1)
for i in range(100):
    for j in range(color_img.shape[1]):
        color_img[i][j]=[random.randint(0,255),random.randint(0,255),random.randint(0,255)]
cv2.imshow('212222230082',color_img)
cv2.waitKey(0)

```
v) #To cut and paste portion of image
```

import cv2
color_image=cv2.imread('sayonora.jpg',1)
tag=color_image[300:400,300:400]
color_image[50:150,50:150]=tag
cv2.imshow('212222230082',color_image)
cv2.waitKey(0)


```

## Output:

### i) Read and display the image

![image](https://github.com/MOHAMED-FAREED-22001617/READ-AND-WRITE-IMAGE/assets/121412904/6daed37a-acbe-4510-b95f-ce08f3e2e63c)


### ii)Write the image
![image](https://github.com/MOHAMED-FAREED-22001617/READ-AND-WRITE-IMAGE/assets/121412904/ddf712dd-e2fa-4028-aa37-534f602c97fe)

### iii)Shape of the Image

![image](https://github.com/MOHAMED-FAREED-22001617/READ-AND-WRITE-IMAGE/assets/121412904/0d4fb166-cf15-42c1-991d-c5ab83a3cabb)


### iv)Access rows and columns
![image](https://github.com/MOHAMED-FAREED-22001617/READ-AND-WRITE-IMAGE/assets/121412904/19a0aaf2-22ac-40d7-bee0-4d7e53f564db)

### v)Cut and paste portion of image
![image](https://github.com/MOHAMED-FAREED-22001617/READ-AND-WRITE-IMAGE/assets/121412904/e38fc3c1-af0e-4f1c-913e-7ac10af6ff3e)


## Result:
Thus the images are read, displayed, and written successfully using the python program.
