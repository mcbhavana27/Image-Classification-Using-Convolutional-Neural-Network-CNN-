# Image-Classification-Using-Convolutional-Neural-Network-CNN-


## Dataset

 CIFAR-10 dataset was developed along with the CIFAR-100 dataset by researchers at the CIFAR institute.

The dataset is comprised of 60,000 32×32 pixel color photographs of objects from 10 classes, such as frogs, birds, cats, ships, etc. The class labels and their standard associated integer values are listed below.

    0: airplane
    1: automobile
    2: bird
    3: cat
    4: deer
    5: dog
    6: frog
    7: horse
    8: ship
    9: truck

These are very small images, much smaller than a typical photograph, and the dataset was intended for computer vision research.

![image](https://user-images.githubusercontent.com/58338319/134147237-ef794ab2-d451-4b7d-adec-7920e2314172.png)

## Define Model

Next, we need a way to a neural network model.

The define_model() function below will define and return this model and can be filled-in or replaced for a given model configuration that we wish to evaluate later.
	
# define cnn model
def define_model():
	model = Sequential()
	# ...
	return model
  
 ## Evaluate Model

After the model is defined, we need to fit and evaluate it.

