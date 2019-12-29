# Human-Activity-Recognition-Using-Accelerometer-Data

Here we gathered the accelerometer data that tells about the human activity based on there values.

Types of activity gathered:

1. Walking       137375
2. Jogging       129392
3. Upstairs       35137
4. Downstairs     33358
5. Sitting         4599
6. Standing        3555

We gathered the human activities and here we gona classify the activity based on there each values. Each activity data was gathered in the way of 3 dimensional (X, Y, Z). 

Here we have a raw text need to preprocces the data to the format which Fit to the Neural network. so we aligned and named the label column based on the activity


WHY CNN?
   why not CNN, CNN works well with the image datas and here we have a input in 3 dim so i think to try with CNN model and works well and got good results.
   
CNN-
1. Conv layer- divide the data into multiple small parts
2. Relu layer- negative pixel to zero
3. pooling layer- down sampling
4. Fully connected layer- recognize and classify the data and labels 

Basically, here we classified the human activity based on accelerometers datas using CNN.
