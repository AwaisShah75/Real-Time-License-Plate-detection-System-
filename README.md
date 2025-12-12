# Tensorflow REAL TIME LICENSE PLATE Detection Walkthrough



## Steps
<br />
<b>Step 1.</b> Clone this repository: https://github.com/nicknochnack/TFODCourse
<br/><br/>
<b>Step 2.</b> Create a new virtual environment 
<pre>
python -m venv anprsys
.\anprsys\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 4.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=anprsys
</pre>
<br/>
<b>Step 5.</b> Collect images using the Notebook 1. Image Collection.ipynb</a> - ensure you change the kernel to the virtual environment as shown below
<br/>
<b>Step 6.</b> Manually divide collected images into two folders train and test. So now all folders and annotations should be split between the following two folders. <br/>
\TFODCourse\Tensorflow\workspace\images\train<br />
\TFODCourse\Tensorflow\workspace\images\test
<br/><br/>
<b>Step 7.</b> Begin training process by opening main file.ipynb</a>, this notebook will walk you through installing Tensorflow Object Detection, making detections, saving and exporting your model. 
<br /><br/>
<b>Step 8.</b> During this process the Notebook will install Tensorflow Object Detection. You should ideally receive a notification indicating that the API has installed successfully at Step 8 with the last line stating OK.  
If not, resolve installation errors by referring to the <a href="https://github.com/nicknochnack/TFODCourse/blob/main/README.md">Error Guide.md</a> in this folder.
<br /> <br/>
<b>Step 9.</b> Once you get to step 6. Train the model, inside of the notebook, you may choose to train the model from within the notebook. I have noticed however that training inside of a separate terminal on a Windows machine you're able to display live loss metrics. 
 

