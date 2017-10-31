# Social Force Model in C++

The *social force model* was originally introduced by [Helbing and Molnár (1995)](https://doi.org/10.1103/PhysRevE.51.4282), and is one of the microscopic technique in crowd simulation. It presents an idea that the agents’ internal motivation to perform certain movements affects their motion. Throughout the years, many improvements were made to the original model. One of the latest improvement was made by [Moussaïd *et al.* (2009)](https://doi.org/10.1098/rspb.2009.0405). In their research, the model parameters were calibrated to match the results of the experiment they have conducted on the real-world crowd. The *Social Force Model in C++* project  is created based on this research.

## Getting Started

This project consists of three header files and four source files. *Core.cpp* is used to setup the scene and display the position of all agents and obstacle walls, while the remaining header and source files are used to store the characteristics of agents and obstacle walls, and perform calculations.

### Prerequisites

This project requires the following libraries.
- [C++ Port of the *vecmath* Package](https://github.com/egonw/vecmath)
- [Open Graphics Library (OpenGL)](https://www.opengl.org/)

This project also requires users to use compilers that support C++ 11.

## Authors

- Fawwaz Mohd Nasir
- Shamsul Mohamad
