# SimpleNeuralNetworks

Neural Network implementations in TensorFlow : 
<br /><br />
1) Fashion MNIST Dataset : <br />
Classify images of clothing. There are 10 types of clothing items.<br />
Training data consists of 60,000 images (grayscale).<br />
CNN is also implemented for the same task. <br />
CNN architecture : Two layers of Conv2D and Max Pooling followed by Fully Connected Layer and Softmax Layer.<br />

2) CNN to classify imaages of dogs and cats.<br/>
The images are of different sizes and are colored pictures, hence ImageGenerator class is used.<br/>
Data Augmentation is also done with rotation, flipping and zooming.<br/>
Visualization of training and validation accuracy and loss is also done.<br/>

3) Multi Class Image Classification on CIFAR 10.<br />
50,000 images belonging to 10 classes classified using PyTorch.<br/>
Model Description : LeNet Model with ReLU activation and MaxPooling.<br/>
Loss function : Cross Entropy and Optimizer : SGD<br/>
