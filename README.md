# Yolov4_Darknet-Google_Colab



_Please Download 'weight' file Seperately to avoid error_   
_make "yolo" folder in your gdrive first and put all the files before you run ipynb file_

### custom.names
 + names of classes we trained
### custom.data
 + path for .names file
### yolov4-custom.cfg
 + set img size to 64x64 and modified to fit our class number
### yolov4-custom_last.weights
 + weights file we trained in custom
### image.c
 + modified to save labeled images


## Yolov4.ipynb
_Darknet Codes for Colab_

  + Get Yolov4
    + git clone from https://github.com/AlexeyAB/darknet and follow official instructions
  + Get Weight and Files
    + mount goolge drive and copy our custom files
    + make result_img dir for saving cropped images
  + Auto Exe
    + put arguments in code to make it convenient to execute darknet with original weights
  + Test
    + execute darknet with our custom weights
