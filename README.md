# Code for the Interpolated Discretized (ID) Embedding

Ofir Pele, Alexey Kurbatsky\
Contact: ofirpele@gmail.com\
Version: 1, August 2016

This directory contains the source code for computing the Interpolated Discretized (ID) embedding.

Please cite this paper if you use this code:\ 
 Interpolated Discretized Embedding of Single Vectors and Vector Pairs for Classification, Metric Learning and Distance Approximation\
 Ofir Pele, Yakir Ben-Aliz\ 
 arXiv 2016

bibTex:

@article{Pele-arXiv2016d,\
  title={Interpolated Discretized Embedding of Single Vectors and Vector Pairs for Classification, Metric Learning and Distance Approximation},\
  author = {Ofir Pele and Yakir Ben-Aliz},\
  journal={arXiv},\
  year={2016}\
}

The ID was also implemented in parallel to my work by Google in the Tensorflow Lattice library.\
They also implemented monotone constraints and hypercube interpolation.\
They did not implement metric learning.\
Eitam Kav-Venaki implemented metric learning example using ID here: https://github.com/idemb/idemb

# Easy startup
See IDdemo.cpp

# Compiling (the folder contains compiled binaries, thus you might not have to compile)
In a linux shell:
```bash
make
```
