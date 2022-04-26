# Real-Time-Face-Mask-Detection

This is a real time face mask detection project. I have created my own dataset and  trained a model using transfer learning on **ssd_mobilenet_v2_fpnlite_320x320_coco17_tpu-8** 
# Dataset
I wrote up a script using python to collect the images using **[opencv](https://opencv.org/)** library - **[capture.ipynb](https://github.com/chiragdeep01/Real-Time-Face-Mask-Detection/blob/master/Tensorflow/workspace/images/capture.ipynb)**

After that I again used **[opencv](https://opencv.org/)** library to convert these images to grayscale - **[convert_to_grayscale.ipynb](https://github.com/chiragdeep01/Real-Time-Face-Mask-Detection/blob/master/Tensorflow/workspace/images/convert_to_grayscale.ipynb)** 

Then i used **[labelImg](https://github.com/tzutalin/labelImg)** which is a great graphical image annotation tool. You should definitely check it out.  
<img src="https://github.com/chiragdeep01/Real-Time-Face-Mask-Detection/blob/master/readme_ss/2.png" width="700" height="400" />  
# Training  
For training i used transfer learning on **ssd_mobilenet_v2_fpnlite_320x320_coco17_tpu-8**  

I got the model from **[TensorFlow 2 Detection Model Zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md#tensorflow-2-detection-model-zoo)** and trained it using tensorflow object detection api.  

You can check out their **[Documentation](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/)** and their github **[repository](https://github.com/tensorflow/models)**  

<img src="https://github.com/chiragdeep01/Real-Time-Face-Mask-Detection/blob/master/readme_ss/Untitled.png" width="700" height="400" />  

# Tuning  
At first the performance was not good so i tried different things such as:  

- Training on different models.  
- Changing the number of iterations.
- The thing that most helped was implementing changes to the dataset.  

https://github.com/chiragdeep01/Real-Time-Face-Mask-Detection/blob/master/readme_ss/20220426185032_8PV5kzgJ.mp4






