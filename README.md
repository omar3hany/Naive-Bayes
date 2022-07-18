[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6533689&assignment_repo_type=AssignmentRepo)
# csen1022-assignment
Template for the jupyter notebook to use in order to submit CSEN1022 assignments

## Folder Structure
```
Data
├── test
│   └── airplane (1000 images)
│   └── automobile (1000 images)
│   └── frog (1000 images)
└── train
    └── airplane (5000 images)
    └── automobile (5000 images)
    └── frog (5000 images)
Assignment.ipynb ── This is the only file that you need to work on and submit
```

## Prerequisites
This repository requires that you have:-
* [Python3+](https://www.python.org/downloads/)
* [Numpy](https://numpy.org/install/)
* [Matplotlib](https://matplotlib.org/users/installing.html)
* [OpenCV](https://pypi.org/project/opencv-python/)
* [Jupyter Notebook](https://jupyter.org/install)

### Installation of Prerequisites
#### Easy way (More HD space, less hassle)
Install [Anaconda](https://www.anaconda.com/products/individual) then just run Jupyter.

#### Hard way (Less HD space, more hassle)
Install [Python3+](https://www.python.org/downloads/) 

Make sure Python and pip are added to environment variables
![Python](https://bitsilla.com/wiki/lib/exe/fetch.php?w=600&tok=5a7732&media=images:py_setting_win.png)

From your Linux, Mac, or Windows terminal, verify that both are installed correctly.
```sh
$ python --version
$ pip --version
```

Using the same terminal install numpy, matplotlib, pillow and notebook
```sh
$ pip install numpy matplotlib pillow notebook
```

#### Alternative way (Cloud but you have to upload the data)
Create a New Notebook from here
[Google Colab](https://colab.research.google.com)

Upload the Data.zip folder
```
from google.colab import files
uploaded = files.upload()
```

Extract the zipped folder into the cloud
```
!unzip [foldername].zip
```

## How To Run
From your terminal, run this command then navigate to the Assignment.ipynb file
```
jupyter notebook
```

## License
BSD 3-Clause "New" or "Revised" License











