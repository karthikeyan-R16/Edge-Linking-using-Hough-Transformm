# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image
![image](https://github.com/user-attachments/assets/282572cb-a2d6-4c09-a657-3562d67bbb7d)

![image](https://github.com/user-attachments/assets/9bbc7a26-9a6a-47d0-8a49-43670ee17423)

### Canny Edge detector output
![image](https://github.com/user-attachments/assets/ee649307-2d59-4014-987b-3f14d4406bec)

### Display the result of Hough transform
![image](https://github.com/user-attachments/assets/dd6f6ce0-c370-4073-a7bd-8ccca8cbddf1)

## Result

Thus we have successfully detected lines by using Hough Transform

