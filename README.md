# ETA DETECTION 

![DeveloperPrince](https://developerprince.herokuapp.com/static/assets/images/logo.png)

This is a machine learning project of being able to predict ETA for logistic services .
Take note the Dataset is taken from [zindi](zindi.africa) from a closed competition.

## Contributor

[DeveloperPrince](developerprince.co.zw)

## Requirements

    1. Python 3.7
    2. pip
    3. Virtualenv(python package)

## Warning 

Please make sure you use python version 3.6 or 3.7 because python 3.8 due to the introduction of new features and rendering other features depracted some libraries are not supported in python 3.8, as python is still young,  being released on th 14th of October 2019. We shall work tirelessly with team to see that we update our project to support for python 3.8.

## Setup & Inference

1. Create Virtual environment.

on Unix based System
```bash
    python3 -m venv env
```

or on Win32

```bash

    py -m venv env

```

2. Switch to Virtual environment

on Unix based System
```bash

    source env/bin/activate

```

or Win32 

```bash

    .\env\Scripts\activate

```
4. Python Install packages from requirements.txt

```bash 
    pip install -r requirements.txt
```

3. Change KERAS_BACKEND to either tensorflow if you your CPU supports AVX otherwise Shift to theano for leagcy CPU's 

on Unix Based System
```bash

    export KERAS_BACKEND=theano        

```

on Windows Based System
```bash

    set KERAS_BACKEND=theano

```
3. Create a Model

```bash

    python3 train.py

```

4. Infer Model

Coming Soon 

Enjoy
