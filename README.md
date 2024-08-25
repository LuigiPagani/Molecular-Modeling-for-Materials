
# Molecular Modeling for Materials

This repository contains various simulations and modeling techniques applied to molecular systems, specifically within the context of statistical physics and random processes. The included notebooks demonstrate the application of algorithms to study phase transitions, random walks, and other phenomena in materials science.

## Contents

### 1. IsingMC.ipynb
- **Description:** This notebook focuses on the simulation of the Ising model using various algorithms including the Metropolis-Hastings algorithm, Wolff algorithm, and Swendsen-Wang algorithm. It provides detailed theoretical background, mathematical formulations, and practical implementation in Python.
- **Key Features:**
  - Implementation of Metropolis-Hastings for simulating phase transitions.
  - Comparison with more advanced algorithms like Wolff and Swendsen-Wang.
  - Visualization of lattice configurations and temperature-dependent properties.
    
### 2. RandomWalk.ipynb
- **Description:** This notebook explores random walk models in 1D, including correlated random walks and random walks with boundary conditions. It also extends to simulations in 2D and 3D, illustrating concepts such as polymer chains, particles in glassy mediums, and quantum walks.
- **Key Features:**
  - Simulation of random walks in one, two, and three dimensions.
  - Analysis of correlated random walks and their implications in different physical systems.
  - Visualization of random walks under various boundary conditions and their impact on system behavior.

## Usage
To run the simulations provided in this repository:
1. Clone the repository: `git clone https://github.com/LuigiPagani/Molecular-Modeling-for-Materials.git`
2. Install the necessary Python packages:
   ```bash
   pip install numpy matplotlib scipy
   ```
3. Open the Jupyter notebooks (`.ipynb` files) in JupyterLab or Jupyter Notebook:
   ```bash
   jupyter notebook IsingMC.ipynb
   jupyter notebook RandomWalk.ipynb
   ```


## License
This repository is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Author
Luigi Pagani


