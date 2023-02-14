# Number_recognition
Program that can recognize handwritten multi-digit numbers.  

To perform this, i followed the following steps:  
-Given an image of multi-digits numbers, I find the contours of the image thanks to traditionnal computer vision techniques.  
-I perform a DBSCAN clustering to detect wether the differetn digits are from the same number or not.  
-Thanks to a CNN trained on NIST dataset (more noise than MNIST), i classify each digit.  
-At last, I reconstruct the numbers.  

You may find in this repository:   
-A jupyter notebook performing this.  
-The weights of the neural network.  
-An example of handwritten numbers to test the program.  

Issues:  
-Difficulty to recognize ones.
