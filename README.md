# Automatic-Number-Plate-Detection-System
## Description:
Using OpenCV and YOLOv4 model to detect number plate text of vehicles. This project can be used for multiple applications like traffic management, 
collection of toll and smart parking etc.
### Method - 1 using OpenCV:
* Import and install dependencies
* Read image, convert to greyscale and denoise the image
* Apply dilation filter and find the edges for localization
* Find contours and apply the mask to extract plate
* Use EasyOCR and read text
### Method - 2 using pre-trained YOLOv4 model:
* Import and install dependencies
* Collecting car images with license plate data
* Loading a pre-trained YOLOv4 model 
* Detect the number plate
* Use EasyOCR and read text


