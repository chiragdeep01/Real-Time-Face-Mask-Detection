# Real-Time-Face-Mask-Detection

This is a real time face mask detection project. I have created my own dataset and  trained a model using transfer learning on ssd_mobilenet_v2_fpnlite_320x320_coco17_tpu-8 
# Dataset
I wrote up a script using python to collect the images using [opencv](https://opencv.org/) library - [capture.ipynb](https://github.com/chiragdeep01/Real-Time-Face-Mask-Detection/blob/master/Tensorflow/workspace/images/capture.ipynb)

After that I again used [opencv](https://opencv.org/) library to convert these images to grayscale - [convert_to_grayscale.ipynb](https://github.com/chiragdeep01/Real-Time-Face-Mask-Detection/blob/master/Tensorflow/workspace/images/convert_to_grayscale.ipynb)  

Then i used [labelImg](https://github.com/tzutalin/labelImg) which is a great graphical image annotation tool. You should definitely check it out.  
<img src="https://github.com/chiragdeep01/Real-Time-Face-Mask-Detection/blob/master/readme_ss/2.png" width="700" height="600" />


