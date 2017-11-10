# cat_recognition_dnn
Cat image recognition implementing 4 layer deep neural network only using numpy

<ul>
<li>Training set: 209 pictures (64 by 64 pixels) of cat images.</li>
<li>Test set: 50 pictures (64 by 64 pixels) of cat images.</li>
</ul>

<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32639503-3b420966-c5ff-11e7-9b5a-8f4ee7bb2d8b.jpg" width="500"></p>

We implement a <b>4 layers deep neural network</b> just using numpy. Notice images resolution is lowered to 64 x 64 pixels before putting into the network. 
<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32612759-0a432efe-c5a4-11e7-8d77-917f73f09cbf.png" width="500"></p>

### cat_dnn_model.py
<ul>
<li>Train the model</li>
<li>Record parameters in a pickle file</li>
</ul>

### cat_recognizer.py
<ul>
<li>Load trained model parameters from pickle file </li>
<li>Run chosen image into the network providing prediction </li>
</ul>

### dnn_app_utils.py
<ul>
<li>Contain supporting fuctions for cat_dnn_model.py and cat_recognizer.py</li>
</ul>

<br/>

<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32639095-2610a414-c5fd-11e7-9a3d-836ba5cde141.PNG" width="500"></p>
