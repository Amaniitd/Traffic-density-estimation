# Traffic-density-estimation
Traffic density estimation using OpenCV functions.
  - Subtask1: Camera angle correction and frame cropping.
    - Converting colored image into gray image.
    - Camera angle correction using Homography.
    - Cropping of the image.
    > to compile the code include opencv in library (refer Makefile) and give your image as first argument in the compiled code.
    > Or just run the make file that will compile and store the output in a file named "hello" now type ./hello {location of image} and press enter.
    > A black and white image will pop on the screen.
    > Now select 4 points for the alignment by right mouse click on the image (left-top => left-bottom => right.bottom => right.top ).
    > Two new image will pop up, One is aligned image and another is aligned + cropped. 
