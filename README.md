# SimpleNeuralNetworks

Neural Network implementations in TensorFlow : 
<br /><br />
1) Fashion MNIST Dataset : <br />
Classify images of clothing. There are 10 types of clothing items.<br />
Training data consists of 60,000 images (grayscale).<br />
CNN is also implemented for the same task. <br />
CNN architecture : Two layers of Conv2D and Max Pooling followed by Dense Layer with Softmax activation.<br />

2) CNN to classify imaages of dogs and cats.<br/>
The images are of different sizes and are colored pictures, hence ImageGenerator class is used.<br/>
Data Augmentation is also done with rotation, flipping and zooming.<br/>
Visualization of training and validation accuracy and loss is also done.<br/>

3) Multi Class Image Classification on CIFAR 10.<br />
50,000 images belonging to 10 classes classified using PyTorch.<br/>
Model Description : LeNet Model with ReLU activation and MaxPooling.<br/>
Loss function : Cross Entropy and Optimizer : SGD<br/>

4) Transfer Learning for Image Classification.<br />
Task : Binary Image Classification on colored pictures.<br/>
Inception V3 model with pre-trained layers.<br/>
Adam Optimizer with Binary Crossentropy loss function.<br/>

5) Exploratory Data Analysis on Titanic dataset.<br/>
Task : Predicting whether a passenger will survive on Titanic or not.<br/>
Data Visualization of input features using Seaborn and Matplotlib.<br/>
Comparision of various ML algorithms and their performance on validation sets.<br/>


