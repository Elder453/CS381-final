# CPSC 381 Final Project

## Team Members
- Elon Abergel
- Raja Moreno
- Daphne Raskin
- Elder Veliz

## Project Overview
This project is a continuation and adaptation of existing research into modular arithmetic using one-layer transformer models. Originally focused on modular addition as studied by Nanda et al. (2023), our project extends these findings to modular subtraction. This extension is performed with an eye toward mechanistic interpretability, which is a method that seeks to provide deeper insights into the inner workings of machine learning models.

## Setup Instructions

### Prerequisites
- Access to the Yale McCleary High-Performance Computing (HPC) facility or a compatible environment.
- Python 3.x and Jupyter Notebook installed.

## Hardware Requirements

### GPU Requirement
This project requires the execution environment to have a GPU with CUDA support to handle computations involving high-precision 64-bit floating-point data types (float64). Running the computations on a GPU ensures that the operations are performed efficiently and within feasible time frames.

### Compatibility Note
**Apple Silicon Limitation**: Please note that this project is **not compatible** with Apple Silicon (MPS) due to its requirements for high-precision computations that are not currently supported on that architecture. Users attempting to run this project on devices with Apple Silicon may encounter failures or incorrect computations.

### Running the Notebook
1. **Download Main Notebook**:
   Ensure you have the project notebook by downloading `subtraction_grok.ipynb` directly.


2. **Install Dependencies**:
   Install the required Python libraries mentioned in `requirements.txt`. This step is partly hardcoded into the initial notebook setup.

   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Notebook**:
   Open `subtraction_grok.ipynb` using Jupyter Notebook.

   ```bash
   jupyter notebook subtraction_grok.ipynb
   ```

4. **Run the Notebook**:
   Execute the notebook cells sequentially to view the implementation, minor discussion, and results.

### Plotting Issues
The notebook employs Plotly for visualizations, which might not render correctly in some environments like Google Colab. For convenience, a PDF with all the outputs and plots has been provided in case there are rendering issues on your platform.

## Acknowledgements
This project is heavily based on the work and code presented in the paper:
- Nanda, N., Chan, L., Lieberum, T., Smith, J., & Steinhardt, J. (2023). "Progress measures for grokking via mechanistic interpretability." arXiv preprint arXiv:2301.05217. Available at: https://arxiv.org/abs/2301.05217

The insights provided by Nanda et al. have been instrumental in guiding our adaptation of the techniques to modular subtraction, and we gratefully acknowledge their influence on our work.

## Contact Information
For any queries related to the project, please contact:
- Elder Veliz: [elder.veliz@yale.edu]