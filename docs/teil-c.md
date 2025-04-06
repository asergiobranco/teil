TEIL C Library
==============

The C Library is available to download at: [https://github.com/asergiobranco/teil-c/releases](https://github.com/asergiobranco/teil-c/releases).

## Available ML Algorithms

| Algorithm               | Task           | Documentation |
|:------------------------|:--------------:|:-------------:|
| Decision Tree           | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#decision-tree) |
| Decision Tree           | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#decision-tree) |
| Multi-Layer Percepton   | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#multi-layer-percepton) |
| Multi-Layer Percepton   | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#multi-layer-percepton) |
| SVM (Linear)            | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (Linear)            | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (RBF)               | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (RBF)               | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (Polynomial)        | Classification | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| SVM (Polynomial)        | Regression     | [readthedocs](https://teil.readthedocs.io/en/latest/ebis/#support-vector-machines) |
| PCA                     | Dimensionality Reduction / Decomposition | []() |
| Gaussian Naive Bayes    | Classification | []() |
| Multinomial Naive Bayes | Classification | []() |


 
## Compile the Code

One approach, if you are uing GCC, is to use the following command to compile your code and add TEIL

`gcc -I /path/to/src *.c /path/to/teil.a -o main -lm`

## Docker 

We provide an official Docker image to easily compile any model. To pull the image please use the following command:

`docker pull asergiobranco/teil-gcc`

This will pull the compiling image (note that the python package is not included in this). 

Once downloaded, one can run the container with:

`docker run -it -v ./:/workspace asergiobranco/teil-gcc`

This will open the bash, which allows your to compile the model using the command:

`root:/workspace$ gcc *.c -o main -lm -lteil`


## Useful Links

|               | URL  |
|:-------------:|:----:|
| Download      | [https://github.com/asergiobranco/teil-c/releases](https://github.com/asergiobranco/teil-c/releases) |
| Github        | [https://github.com/asergiobranco/teil-c](https://github.com/asergiobranco/teil-c)  |
| Documentation | [https://teil.readthedocs.io](https://teil.readthedocs.io) 
| Issues        | |