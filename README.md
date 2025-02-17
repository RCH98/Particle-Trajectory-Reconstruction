# Particle-Trajectory-Reconstruction


Developed a machine learning model to predict particle trajectories in Resistive Silicon Detectors (RSD).

## Overview

This repository contains the tools, data preprocessing steps, and machine learning models required to predict the trajectories of particles in Resistive Silicon Detectors. The project primarily utilizes Jupyter Notebooks to explore, analyze, and model experimental data, making it a resourceful starting point for anyone interested in particle tracking and machine learning applications in high-energy physics.

## Project Structure

```
├── data/
│   ├── raw/             # Raw input datasets
│   └── processed/       # Processed and cleaned data ready for modeling
├── notebooks/
│   ├── data_preprocessing.ipynb  # Notebook for data cleaning and preprocessing
│   ├── model_training.ipynb      # Notebook detailing model creation and training
│   └── evaluation.ipynb          # Notebook for model evaluation and analysis
├── docs/
│   └── additional_notes.md       # Supplementary project documentation
└── README.md                     # This file
```

## Getting Started

### Prerequisites

- [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) (recommended for managing dependencies)
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/RCH98/Particle-Trajectory-Reconstruction.git
   cd Particle-Trajectory-Reconstruction
   ```

2. **Create a Conda Environment**

   ```bash
   conda create -n particle_env python=3.8
   conda activate particle_env
   ```

3. **Install Dependencies**

   If a `requirements.txt` file is provided, run:

   ```bash
   pip install -r requirements.txt
   ```

   Otherwise, manually install the primary libraries:

   ```bash
   pip install numpy pandas scikit-learn matplotlib jupyter
   ```

### Running the Notebooks

Launch the Jupyter Notebook interface:

```bash
jupyter notebook
```

Then, open the notebooks located in the `notebooks/` directory to explore data preprocessing, model training, and evaluation workflows.

## Usage

- **Data Preprocessing:** Use the `data_preprocessing.ipynb` notebook to clean and transform raw experimental data.
- **Model Training:** The `model_training.ipynb` notebook contains code to build, train, and validate the machine learning model.
- **Evaluation:** Evaluate model performance and visualize results using the `evaluation.ipynb` notebook.

Feel free to modify the notebooks or integrate additional data sources to further improve the model's performance.

## Contributions

Contributions and feedback are welcome! Please fork the repository and submit a pull request with your proposed changes. Major changes or improvements should be accompanied by additional discussion in the form of an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the research community in particle physics for their continuous contributions.
- A special thanks to [GitHub](https://github.com) for providing an excellent platform for collaboration.
- Recognition to all contributors who helped make this project possible.

Happy Modeling!
