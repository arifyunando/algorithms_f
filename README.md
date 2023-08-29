# Introduction to Algorithms with Modern Fortran
> **Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, and Clifford Stein.** (2009). _Introduction to Algorithms, Third Edition (3rd. ed.)_. The MIT Press. Education.  

## Description
This repository contains implementation of various computer algorithms that is described in
Cormen, et al., "Introduction to Algorithms". The book covers sorting,
data structures, other important algorithms in computer science and commonly used as the reference
book for algorithm and data structure classes in the computer science major. Each folder contains
different topics and thus can be studied separately.

### About **Algorithms and Data Structures**
An algorithm functions as a systematic approach for solving problems or conducting computations, consisting of precise instructions that execute specific actions in a step-by-step manner within either hardware- or software-based routines. Its widespread use spans across all IT domains, encompassing mathematics, computer programming, and computer science, often representing a concise method to address recurring issues and serving as a blueprint for automated systems and data processing. Whether sorting numerical sets or orchestrating complex tasks like personalized social media content recommendations, algorithms typically initiate with initial inputs and explicit instructions, culminating in the execution of specific computations and the eventual production of an output.

On the other side, data structures are fundamental concepts that revolve around organizing and storing data in a way that optimizes retrieval, manipulation, and management of that data. Imagine them as the blueprints that determine how data is arranged and accessed within computer programs.

Data structures serve as the building blocks for designing efficient algorithms and software systems. They enable programmers to handle different types of data with varying levels of complexity, ensuring that the operations performed on the data are both effective and resource-efficient.

## Compiling and Running the Codes
This repository is arranged such that every folder has its own topic and `CMakeLists.txt` file for easy compilation with [CMake](https://cmake.org/). To install CMake 3.15, please run this following commands
```sh
sudo apt-add-repository 'deb https://apt.kitware.com/ubuntu/ bionic main'
sudo apt update
sudo apt upgrade
```

The code then can be compiled using GNU Fortran Compiler with this following commands.
```sh
sudo apt update 
sudo apt upgrade -y
sudo apt install -y build-essential 
cd <pathto>/<topic_folder>
mkdir build; cd build
cmake ..
make install
```

These commands will put the compiled binaries in a subfolder called bin which placed at `<project_parent>/<chapter>/<topic_folder>/build/run/` along with any input files that is needed for testing. 

## Table of Contents
1. [Sorting and Order Statistics]()
2. [Data Structures]()
3. [Advanced Design and Analysis Techniques]()
4. [Advanced Data Structures]()
5. [Graph Algorithms]()
6. [Selected Topics]()


## Disclaimers and Contribution
This is a simple study repository, thus the quality of the code is not the priority. Since it is basically a study log, contributions from third parties is not expected. Though, you are very welcome to fork this repository and give a GitHub star ⭐

## Author
**Arif Y. Sunanhadikusuma (Soen)** <br>
--- <br>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/arifyunando)
[![](https://img.shields.io/badge/Gmail-EA4335.svg?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:arifyunando@gmail.com)<br>
_Civil Engineering (S.T.)_ <br>
Department of Civil Engineering <br>
Parahyangan Catholic University, Indonesia  <br> 
--- <br>
_Geotechnical Engineering (M.Sc)_ <br>
Civiel Techniek en Geowetenschappen (CiTG) <br>
TU Delft, The Netherlands