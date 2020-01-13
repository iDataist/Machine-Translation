# Machine Translation
I built a deep neural network that functions as part of an end-to-end machine translation pipeline. The pipeline accepts English text as input and return the French translation.

## Setup

Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/iDataist/Machine-Translation

cd machine_translation
```

Create (and activate) a new environment with Python 3.5 and the numpy package.
```
conda create --name machine-translation python=3.5 numpy
source activate machine-translation
```

Install/Update TensorFlow.
```
pip install tensorflow==1.1 -U
```

Install/Update Keras.
```
pip install keras -U
```

Switch Keras backend to TensorFlow.
```
KERAS_BACKEND=tensorflow python -c "from keras import backend"
```

Start Jupyter:
```
jupyter notebook --no-browser
```
