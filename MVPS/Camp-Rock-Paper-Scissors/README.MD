## Rock-Paper-Scissors Project

The goal of this project is to train a neural network to recognize different hand gestures in the game of rock-paper-scissors. The students are encouraged to create their own data for this project and use it for training and performance assessment.

The project is structured as follows:

- **colab_setup**: Files to connect to Colab (requires internet connection and a Google email account). Skip this if you are running the files locally.

- **data_prep**: Folder contains Jupyter Notebooks that allow students to create their own data using a computer webcam and process data for a model-ready dataset.  
  - Templates for cleaning and validating student pictures and pre-made datasets.
  - Training and testing pre-made datasets (_rps.zip_, _rps_test.zip_, and _rps-20240619T044016Z-001.zip_).
  - Utility functions (_dlutils.py_, _kerutils.py_).

- **model_init**: First run templates.
  - Initial student model run (_2024_project_template.ipynb_).
  - Weight initialization example.
  - Neural Network example with CIFAR10 data.

- **model_tune**: Second run templates.

- **rps**: Example "rps" folder contains Jupyter Notebooks that allow students to create their own data using a computer webcam and process data for a model-ready dataset.  
  - This folder is created from the data prep templates.
  - Training and testing pre-made datasets (_rps.zip_, _rps_60.zip_, and _rps_360.zip_) are used for comparing data quality before model tuning.

The project is aimed to be covered in 4 half-day modules:
- **Data Collection**: 1 module.
- **Model fitting and presentation prep**: 2 modules.
- **Students present their results**: 1 module.

Each module is accompanied by a short lecture covering the necessary theoretical background of the task. For lecture materials, please refer to [Session Materials/Tutorials](https://github.com/RudyMartin/dsai-2024/tree/main/MVPS/Session-Materials/Tutorials) folder.

