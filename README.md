```markdown
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
  ```

### Clone the Repository
```bash
git clone https://github.com/AkiraWinds/Computational-Cognitive-Science-3-.git
cd Computational-Cognitive-Science-3-
```

## Usage
1. **Run Data Processing & Analysis**  
   Open the Jupyter notebook and execute the steps in `processing15.ipynb` to analyze the eye-tracking dataset.

2. **Modify & Extend the Study**  
   - Update experimental data in `data/`
   - Adjust statistical analysis in `analysis/`

3. **Visualize Results**  
   Use the provided Python scripts to generate fixation maps and cognitive load analysis charts.

## Dataset
The dataset consists of:
- **Eye-tracking data**: Fixation points, saccades, and time-to-fixation values
- **Task performance data**: User interaction logs, accuracy rates
- **Post-task cognitive load responses**: NASA-TLX scores from participants

## Methodology
- **Experiment Setup**: Conducted with **23 participants** in a controlled lab environment.
- **Eye-Tracking Hardware**: Tobii X120 with **calibrated AOIs (Areas of Interest)**.
- **Task Complexity Levels**: Easy, Medium, Hard.
- **Statistical Analysis**: LMM models were used to evaluate the impact of text formatting.

## Results
- **Uppercase text captures attention better** in complex tasks but **increases cognitive load**.
- **Title case improves task performance** and reduces errors across all difficulty levels.
- **No significant effect of language background** on eye-tracking metrics.

## Repository Structure
```
📦 Computational-Cognitive-Science-3-
 ┣ 📂 data/               # Raw and processed eye-tracking datasets
 ┣ 📂 analysis/           # Statistical models and analysis scripts
 ┣ 📂 results/            # Visualizations and output reports
 ┣ 📜 processing15.ipynb  # Jupyter Notebook for data analysis
 ┣ 📜 README.md           # Project documentation
 ┗ 📜 LICENSE             # Open-source license (if applicable)
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributors
- **Yan Zhang (ljv310)**
- **Lingshan Lu (ptb818)**
```
