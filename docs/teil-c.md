TEIL C Library
==============

The C Library is available to download at: 

## Compile the Code

## Docker 

We provide an official Docker image to easily compile any model. To pull the image please use the following command:

`docker pull asergiobranco/teil-gcc`

This will pull the compiling image (note that the python package is not included in this). 

Once downloaded, one can run the container with:

`docker run -it -v ./:/workspace asergiobranco/teil-gcc`

This will open the bash, which allows your to compile the model using the command:

`root:/workspace$ gcc ª.c -o main -lm -lteil`


## Useful Links

|               | URL  |
|:-------------:|:----:|
| Download      | http://github.com/realeases/ |
| Github        | |
| Documentation | |
| Issues        | |