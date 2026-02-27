# Fundus Image Analysis

## Overview
This project focuses on the analysis of fundus images for the detection and localization of optic disc centers and blood vessels. The workflow includes data preprocessing, image segmentation, and result visualization. The project is structured to facilitate experimentation and reproducibility using Jupyter Notebooks.

## Directory Structure
```
Assignment_2/
├── Data/
│   ├── data.csv
│   ├── optic_disc_centres.csv
│   ├── Blood vessels/
│   └── Fundus image/
├── Data_OG/
│   ├── optic_disc_centres.csv
│   ├── Blood vessels/
│   └── Fundus image/
├── Output/
│   ├── data.csv
│   ├── Center/
│   ├── Closing/
│   └── Threshold/
├── Output2/
│   └── data.csv
├── Output3/
│   └── data.csv
├── main.ipynb
├── main copy.ipynb
├── assignment 2.drawio
├── output1.txt
└── Assignment-2.pdf
```

## Getting Started
1. Clone the repository.
2. Install the required Python packages (see below).
3. Open and run the Jupyter Notebooks for step-by-step analysis.

## Requirements
- Python 3.x
- Jupyter Notebook
- Common libraries: numpy, pandas, matplotlib, opencv-python, scikit-image

Install dependencies with:
```
pip install numpy pandas matplotlib opencv-python scikit-image
```

## Usage
- Place your fundus images and related data in the `Data/` directory.
- Run the notebooks (e.g., `main.ipynb`) to process images and generate outputs.
- Results will be saved in the `Output/`, `Output2/`, and `Output3/` directories.

## Files
- `main.ipynb`, etc.: Jupyter Notebooks for analysis and experimentation.
- `assignment 2.drawio`: Diagram(s) related to the workflow or results.
- `Assignment-2.pdf`: Assignment instructions and details.

## Notes
- The `.gitignore` file excludes outputs, checkpoints, and environment files from version control.
- For more details, refer to the assignment PDF.

## License
This project is for academic use only.
