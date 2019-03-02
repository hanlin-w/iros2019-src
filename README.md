

# CPL-Sync

**CPL-Sync** is a *certifiably correct* algorithm which solves planar pose graph optimization (PGO) using the complex number representation efficiently.

A detailed description of the algorithm and its implementation can be found in our [paper](http://www.google.com)


# In this repository
This repository features 2 algorithms
- SE-Sync, proposed by Rosen, etc. It is a *certifiably correct* algorithm for performing *synchronization over the special Euclidean group*: estimate the values of a set of unknown *poses* (positions and orientations in Euclidean space) given noisy measurements of a subset of their pairwise relative transforms.

- Cartan-Sync, our contribution, a novel RTR based algorithm which solves planar pose graph optimization (PGO).

The performance comparison of  SE-Sync and CPL-Sync is shown as follows:

![enter image description here](https://drive.google.com/file/d/1LnVXoD6Bb7F4bM0qBDQmUFRS8r5Ry04K/view?usp=sharing)

# Getting started


## Dependencies
In order to compile the library, the installation of following libraries is required:

- [Suitesparse](http://faculty.cse.tamu.edu/davis/suitesparse.html)

- [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page)

- [Spectra](https://spectralib.org/)

- [Optimization](https://github.com/david-m-rosen/Optimization)


## Building CPL-Sync library

On most unix-like systems, the library can be downloaded and compiled using following commands:
>git clone 

>cd CPL-Sync

> mkdir build

> cd build

> cmake  -DCMAKE_BUILD_TYPE=Release .\.

> make 


## Usage of example 




