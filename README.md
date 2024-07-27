# **Neural Network Model with Keras**
This repository contains a neural network model implementation using the Keras deep learning library. The code includes various layers and functionalities for building, training, and evaluating neural network models.
# **Requirements**
1.Python 2.7  

2.Keras 2.3.1  

3.TensorFlow 1.15.0  

4.NumPy 1.16.6  

5.Pandas 0.25.3  

6.Matplotlib 3.1.0  

7.Scikit-learn 0.18  

8.Tqdm 4.63.0  

9.Jupyter 0.7.1  

# **Installation**
## Clone the repository:
sh  

Execute the following command  

git clone [https://github.com/lore-ys/livegmv.git](https://github.com/lore-ys/livegmv.git)  

cd ./livegmv  

## Install the required packages:
sh  

Execute the following command  

pip install -r requirements.txt  

# **Usage**
## Start the jupyter server and run the code
sh  

jupyter notebook  

Select the corresponding algorithm, such as salenet.ipynb, open the file and click Run All. The   
model will load the data and perform training and evaluation.  

## Suppressing Warnings and Setting Up Environment
The code starts by suppressing warnings and setting the environment to use a specific GPU:  

python  

import warnings  

import os  

warnings.filterwarnings("ignore")  

os.environ["CUDA_VISIBLE_DEVICES"] = "0"  

# **Repo structure**
| models               | salenet and baseline             |
| :------------------- | :------------------------------- |
| **requirements.txt** | **python packages requirements** |
| **utils**            | **components**                   |
# **Notes**
This code includes some commented out parts (e.g., # from attention_keras import Attention).   

Make sure to install any additional packages if you intend to use those parts.  

Modify the model architecture and parameters as needed for your specific use case.  

Ensure that the GPU configuration (os.environ["CUDA_VISIBLE_DEVICES"]) matches your setup.  
