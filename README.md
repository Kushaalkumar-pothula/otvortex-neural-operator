# FNO Orszag-Tang Vortex Test
A Fourier Neural Operator based Orszag-Tang Vortex test. The core C++ solver is used to generate the simulationsm,
and a Python/PyTorch pipeline is developed for training and running the neural operator. This project trains an FNO to learn the solution operator for this problem, enabling fast emulation of the MHD dynamics without solving the PDEs from scratch at each timestep.

![Test Run](assets/testrun.gif)

## Requirements
 
- Python 3.8+
- PyTorch, NumPy
- C++17 compiler

