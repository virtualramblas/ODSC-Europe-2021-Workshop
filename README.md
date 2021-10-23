# ODSC-Europe-2021-Workshop
This repository hosts the [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) notebooks used for my [workshop](https://odsc.com/speakers/adversarial-attacks-and-defence-in-computer-vision-101/) at the ODSC 2021 Europe on June 9th at 10:15 BST.    
![ODSC Logo](https://opendatascience.com/wp-content/uploads/2021/01/odsceutop.png)  
### Instructions
In order to use the provided notebooks you need to have a Google account to login to the Colab free environment. Clone this repo, then upload to Colab the notebook(s) you need to play with. Each notebook contains reference to which runtime (CPU, GPU or TPU) is recommended for it. The reference programming language is Python 3. The framework used for Deep Learning is [TensorFlow](https://www.tensorflow.org/) 2.x and its [Keras](https://keras.io/) high-level API.  
#### Module 1
- *FGSM on InceptionV3.ipynb*: creating adversarial examples using FGSM (Fast Gradient Sign Method). The attack is performed to an Inception V3 model trained on ImageNet.  
#### Modules 2/3
- *Basic Iterative Adversarial Attack on InceptionV3.ipynb*: creating adversarial examples using a basic iterative method (BIM). The attack is performed to an Inception V3 model trained on ImageNet.  
- *GRADIO app to compare CNN models.ipynb*: a [Gradio](https://www.gradio.app/) interface to compare multiple CNN models performance in image classification tasks (legit images or adversarial samples).  
- *Adversarial Training.ipynb*: Adversarial Training on a DenseNet201 model trained on the CIFAR-10 data set. Adversarial attacks and training are performed through the Open Source [ART](https://adversarial-robustness-toolbox.org/) (Adversarial Robustness Toolbox) Python library. The pre-trained model can be downloaded from [here](https://drive.google.com/file/d/1AL8mIW1VqxVZC0F3oONoGbQnqLvF4x1f/view?usp=sharing). It would be available in that location until November 14th 2021. It would be then removed and a fifth notebook to train it would be provided in this repo.  
