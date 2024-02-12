<h1>AROS (Auto Reporing Obstacle System)</h1>
<p>

Building a model to detect the road's obstacles like potholes and rocks using SSD MobilenetV2.

But first we are expreminting with Tensorflow Object detection API to understand it more
so we can apply it for obstacle detection, we firstly tryed to train and run our model to detect sign language
with four classes (ThumbsUp, ThumbsDown, ThankYou, LiveLong) we got decent accuracy with this model with only 32 training images.

So far good right. I wish soo, when we switched for more realiastic dataset for road obstacle called <a href='https://arxiv.org/abs/2209.08538'>Road Damage Dataset 2022</a>,
with only 10k images for road in India only, we trained with 8K images and 2K for validation, our model training loss function was stuck at 0.50, with random values and unstable learning curve, The main questions we got now is what is the best aproach for road object detection and is Tensorflow Object detection API is the right choice for training, and does the dataset good with our need.

Thank in advance.
</p>
