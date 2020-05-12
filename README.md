# Face Generation

In this project, you'll define and train a DCGAN on a dataset of faces. Your goal is to get a generator network to generate new images of faces that look as realistic as possible!

The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.


## 1. Installation

[Download](https://www.anaconda.com/products/individual) Anaconda


**Install** [Anaconda](https://docs.anaconda.com/anaconda/install/) on your machine. Detailed instructions:

## 2. Create and Activate the Environment

Please go though this [doc](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) before you creating an environment.
After that create a environment using following command

```
conda create --name deep-learning
```

Then activate the environment using following command

```
activate deep-learning
```

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

**Now, you can create a local version of the project**

1. Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
```
git clone https://github.com/iKhushPatel/Generate-Faces.git
cd Generate-Faces
```

2. Install PyTorch and torchvision; this should install the latest version of PyTorch.
	
	- __Linux__ or __Mac__: 
	```
	conda install pytorch torchvision -c pytorch 
	```
	- __Windows__: 
	```
	conda install pytorch -c pytorch
	pip install torchvision
	```

3. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

4. That's it!, Now run the project using following command, check you default browser and open dlnd_face_generation.ipynb file

```
jupyter notebook
```

## 3. Output
Generate new faces using Generative Adversarial Networks (GANs).  
The model is trained on the CelebFaces Attributes Dataset (CelebA):
![Image of Training Set](https://github.com/iKhushPatel/Generate-Faces/blob/master/assets/processed_face_data.png)

It generates new human faces that look like this:  
![Image of Generated Faces](https://github.com/iKhushPatel/Generate-Faces/blob/master/assets/Generated_faces2.png)
