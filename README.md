# ML_Lane_Detection
ML_Lane_Detection uses inception v3 as a backbone with our original twist to fit the selected data. The model 
is trained to identify where the lane is with a set of image data with its corresponding "labels", which are 
a set of image data with color coded region of where the lane is. The output of this machine learning model 
is an image that serve as a mask of the original lane data. After superimposing the output image (detected 
lane), we're able to see where the lane is with the difference in color. 

These files (Regression and Classification) serve as a training for simple machine learning models
Regression: Process the image into core components, reproduce them with the characteristics. 
Classification: Identify the number from the input. 
