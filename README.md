# Dog-Breed-Image-Classification-Using-CNNs-and-Transfer-Learning-In-Pytorch
This Project is all about building a Deep Learning Pipeline to process the real world , user supplied Images.Given an Image of a dog the algorithm will Identify an Estimate of the canine’s breed.If supplied an image of a human, the code will identify the resembling dog breed.

The CNN model which was built from scratch achieved a Test Accuracy of 16% with a Limited Dataset and also a Dataset that was imbalanced (This is even difficult for the Humans to correctly identify the Breed of the Dog). Applying Data Augmentation and Batch Normalization Could have helped the Model Performance a Little More.

The Model Achieved a Test Accuracy of 76% by Training with a Pre-Trained VGG16 Model, The Test Accuracy can be improved with the help of using other states of the art Pre-trained models such as ResNet and Inception Networks.

Along with exploring state-of-the-art CNN models for classification, This Project helped me to make important design decisions about the user experience for the app.

### Datasets

[Dogs Dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) Unzip the folder and place it in this project’s home directory, at the location /dog_images.

[Humans Dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) Unzip the folder and place it in this project’s home directory, at the location /lfw.

The task of assigning breed to dogs from images is considered exceptionally challenging. To see why, consider that even a human would have trouble distinguishing between a Brittany and a Welsh Springer Spaniel.
It is not difficult to find other dog breed pairs with minimal inter-class variation (for instance, Curly-Coated Retrievers and American Water Spaniels).Likewise, recall that labradors come in yellow, chocolate, and black. Your vision-based algorithm will have to conquer this high intra-class variation to determine how to classify all of these different shades as the same breed. The random chance presents an exceptionally low bar: setting aside the fact that the classes are slightly imabalanced, a random guess will provide a correct answer roughly 1 in 133 times, which corresponds to an accuracy of less than 1%.

### Results
The Model acheived a Test accuracy of 19% when Trained Using a Convolutional Neural Network From Scratch , Using Data Augmentation and Batch Normalization Techniques with Much Deeper Architrecture Can help to improve the model performance

The Model acheived a Test Accuracy of 78% when Trained using a Pre-Trained VGG16 Model for 30 epochs, The Performance of the model can be improved using othet pre-trained models such as RESNET and Inception Networks.

![plot](C:/Users/aakom/Downloads/sample_dog_output.png)

### Softwares and Libraries
[Python 3](https://www.python.org/downloads/)

[Numpy](https://pypi.org/project/numpy/)

[Pandas](https://pypi.org/project/pandas/)

[Matplotlib](https://pypi.org/project/matplotlib/)

[Jupyter Notebook](https://jupyter.org/install)

[OpenCV](https://opencv.org/)



















