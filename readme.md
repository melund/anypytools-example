# AnyPyTools Example

This repository contains an example project using AnyPyTools, a toolkit for working with the AnyBody Modeling System in Python.

 The project demonstrates how to run a toy model with different configurations and input paramters. How to export the results to a pandas dataframe and plot the data. 


 ## Getting Started

### Prerequisites

- The AnyBody Modeling System version 8.

- The [pixi package manager](https://pixi.sh) to get the necessary Python liberaries. Pixi can be installed from powershell with the following command:
 
   ``` 
   iwr -useb https://pixi.sh/install.ps1 | iex
   ```

- Prerelease version of the Python extension for Visual Studio Code. This will ensure that VS Code Jupyter will automatically find the pixi python enviornment.

### Installation

- Clone the repository to your local machine:

- Run the following command to create the environment.

  ```
  pixi install
  ```

  The python environment is now created under /.pixi/envs/default


### Running the Example

- Open the "Example.ipynb" in Jupyter lab or Visual Studio Code and run the cells to see the results.


