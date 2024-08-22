# Project Title

`Leveraging machine learning to identify subgroups of misclassified patients in the emergency department – a multi-center proof-of-concept study`

## Description

The aim of this study was to identify clinical features most strongly associated with triage misclassification using a machine learning classification model to capture non-linear relationships.

## Project Strucutre
```
├── notebooks/
│   ├── Bergen_UnderTriage.ipynb  # notebook feauture engeneering + classification + interpretability with SHAP , Bergen Triage data 
│   ├── Trondheim_UnderTriage.ipynb  # notebook feauture engeneering + classification + interpretability with SHAP , Trondhein Triage data
├── util/
   ├── functions.py   # Helper functions.
├── data/ # available upon request.
│
├── requirements.txt                  # List of Python dependencies required for the project
├── README.md                         # Project overview and instructions (this file)
├── LICENSE                           # License for the project
└── .gitignore                        # Specifies files and directories to be ignored by git
```

## Installation

Follow these steps:

1. **Clone the repo**

`git clone https://github.com/mounirHai/triage.git`

`cd SynthCAMH`

2. **Create a Conda environment**

`conda create --name myenv --file requirements.txt`

3. **Activate the Conda Environment**

`conda activate myenv`

4. **Install Dependencies/Requirments**
