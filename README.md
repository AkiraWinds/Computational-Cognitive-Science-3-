# Eye-Tracking Study on Text Format Impact on Attention, Cognitive Load, and Task Performance in Website Design

## Overview
This project explores the effects of text format on user attention, cognitive load, and task performance using **eye-tracking technology**. The study analyzes how **uppercase vs. title case text** affects usability and cognitive effort in web interfaces.

We used **Linear Mixed-Effects (LMM) models** to evaluate eye-tracking and behavioral data, providing insights for **web design and usability optimization**.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Repository Structure](#repository-structure)
- [License](#license)
- [Contributors](#contributors)

## Features
- **Eye-Tracking Data Analysis**: Uses Tobii X120 and Tobii Studio Pro 3.4.8
- **Cognitive Load Evaluation**: Measured using NASA-TLX questionnaire
- **Behavioral Metrics**: Task accuracy, fixation duration, and number of fixations
- **LMM Statistical Analysis**: Evaluates the impact of text format on usability
- **Interactive Website Simulation**: Modeled after real-world e-commerce interfaces

## Installation
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python Libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn statsmodels

## Usage

1. **Run Data Processing & Analysis**
   - Open `processing15.ipynb` in Jupyter Notebook.
   - Execute the steps to analyze eye-tracking and behavioral data.

2. **Modify & Extend the Study**
   - Update experimental data in `data/`
   - Adjust statistical analysis in `analysis/`

3. **Visualize Results**
   - Generate fixation maps and cognitive load analysis using provided scripts.

## Dataset

The dataset consists of:
- **Eye-tracking data**: Fixation points, saccades, time-to-fixation.
- **Task performance data**: User interaction logs, accuracy rates.
- **Cognitive load responses**: NASA-TLX questionnaire results.

## Methodology

- **Participants**: 23 individuals with varied linguistic backgrounds.
- **Eye-Tracking Equipment**: Tobii X120 with **AOI-based** data collection.
- **Task Levels**: Easy, Medium, Hard.
- **Statistical Analysis**: Linear Mixed-Effects Model (LMM).

## Results

- **Uppercase text captures attention more effectively** but **increases cognitive load**.
- **Title case improves task performance** and **reduces errors**.
- **No significant impact of language background** on eye-tracking metrics.


## License
This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

## Contributors
- **Yan Zhang (ljv310)**
- **Lingshan Lu (ptb818)**

