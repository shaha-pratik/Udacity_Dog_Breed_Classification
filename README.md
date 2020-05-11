# Udacity_Dog_Breed_Classification
This project is a part of deep learning nanodegree program at [Udacity](https://www.udacity.com/course/deep-learning-nanodegree--nd101).

## Project Overview

In this Part firstly we have deteceted dog and human faces with different algorithm. Then using transfer learning CNN has been trained to detect the breed of the dog.

Then output has been display as 

```
breed_name = predict_breed_transfer(img)
if dog_detector(img):
	print("Hello Dog, Your breed: " + breed_name)
else human_detector(img):
	print("Hello Human, You resember to " + breed_name + "of dog")
else:
	print("Neither human nor dog")
```

## Project Instruction

1. Clone the repository

```
git clone https://github.com/shaha-pratik/Udacity_Dog_Breed_Classification.git
```
2. Install Anaconda or miniconda

This step is not mandatory but it will really good to understand and manage the environment in conda. Anaconda is available for Windows, Mac OS X, and Linux. You can find the installers at https://www.anaconda.com/download/ and the installation instructions [here](https://docs.anaconda.com/anaconda/install/).

After that you can open the anaconda prompt and create the virtual environment name `dog_breed_classification` and activate as follow:

```
conda create --name dog_breed_classification python=3.6
conda activate dog_breed_classification
```

For conda cheat-sheet can be found [here](https://docs.conda.io/projects/conda/en/latest/user-guide/cheatsheet.html)

3. Install [PyTorch](https://pytorch.org/) and [torchvision](https://pytorch.org/docs/stable/torchvision/index.html) as below

* Linux or Mac:
```
pip3 install torch===1.3.1 torchvision===0.4.2 -f https://download.pytorch.org/whl/torch_stable.html
```

4. After that to install [jupyter](https://jupyter.org/). The jupyter notebook is a web application that allows you to combine explanatory text, math equations, code, and visualizations all in one easily sharable document.
```
conda install jupyter matplotlib opencv=3.4.1 numpy tqdm pillow
```

5. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`. The 'dogImages/' folder should contain 133 folders, each corresponding to a different dog breed.

6. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz). Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.


7. Go to terminal and type
```
jupyter dog_app.ipynb
```
