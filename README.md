# Mouse Learning Trajectories in the IBL Visual Discrimination Task

This repository contains the analysis code for my junior paper "Modeling Individual Learning Trajectories in a Standardized Visual Discrimination Task: Psychometric Evaluation of Session-by-Session Behavior in the IBL Protocol".

## Overview

This project analyzes session-by-session learning trajectories from four mice trained on the International Brain Laboratory (IBL) visual discrimination task. Using a session-level proficiency detection algorithm aligned with the IBL's Level 1a criteria, we track progress across four behavioral dimensions:
- Trial count
- Performance accuracy on high-contrast stimuli
- Contrast exposure
- Psychometric model parameters

## Data

This analysis uses the IBL mouse dataset from December 2019. Due to size constraints, the data is not included in this repository. To reproduce the analysis:

1. Download the dataset from [https://ndownloader.figshare.com/files/21623715](https://ndownloader.figshare.com/files/21623715)
2. Extract the ZIP file to the `data/` directory
3. Run the notebook which will process the data into the required format

## Setup and Installation

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/IBL-mouse-learning-trajectories.git
cd IBL-mouse-learning-trajectories

# Create a virtual environment (optional but recommended)
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt
