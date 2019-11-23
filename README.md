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
