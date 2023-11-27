# AI_Fashion_Recommendation_System

# Project Setup

## Install Anaconda and set the default python version from the below configurations

conda create -n py37 python =3.7

conda activate py37

conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0

conda install -c conda-forge cudatoolkit=10.1 cudnn=7.6

python -m pip install --upgrade tensorflow=2.3.1

### Check whether the CUDA and CUDNN are available for use.
import tensorflow as tf

print(tf.version.VERSION)

tf.config.list_physical_devices('GPU')

tf.test.is_gpu_available()

### Download the data set from the link below
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset

And configure the folders accordingly

![image](https://github.com/Dpaace/AI_Fashion_Recommendation_System/assets/63782923/2f711853-56ee-4085-909d-fdb1db4f3a75)

### Run the code and train the data, which will generate two files like below
![image](https://github.com/Dpaace/AI_Fashion_Recommendation_System/assets/63782923/f2d0f9c5-6519-4a44-8077-5992712f5eb3)

And your final project overview will be like this:

![image](https://github.com/Dpaace/AI_Fashion_Recommendation_System/assets/63782923/8a8eae98-a806-46c7-b6aa-08f913798f29)

### Then goto main.py file and run the code "streamlit run main.py" in the terminal which will open a webpage running the final product.
