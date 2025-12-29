# Koenigsberg_Bayes

## Overview

This project contains a Bayesian analysis of job satisfaction data from the General Social Survey (GSS). The analysis explores relationships between job satisfaction and various psychological and work-related variables using Python data science tools.

## What You'll Find Here

- **Data**: GSS survey data focusing on job satisfaction and related variables
- **Analysis**: Jupyter notebook with exploratory data analysis and visualizations
- **Tools**: Modern Python data science stack (Polars, Plotly, PyMC for Bayesian analysis)

## Installation Guide

**Judy: You have already installed this, so you can skip this section.**

### Step 1: Install Pixi Package Manager

Pixi is a modern package manager that handles all Python dependencies automatically.

Open Terminal **in the project directory** and run:
```bash
curl -fsSL https://pixi.sh/install.sh | bash
```

After installation, restart the Terminal.

### Step 3: Set Up the Environment

From within the **project directory**, run:
```bash
pixi install
```

This will automatically:
- Install Python and all required packages
- Set up the correct versions of all tools
- Create an isolated environment for this project

## Getting Started

### Running the Analysis

1. From within the **project directory**, run:
   **Start Jupyter Lab:**
   ```bash
   pixi run jupyter lab
   ```
   This will open a web browser with the Jupyter interface. THIS IS NOT CONNECTED TO ANY REMOTE SERVER, SO NOTHING IS BEING UPLOADED OR SENT ANYWHERE.

2. **Open the analysis notebook:**
   - Look for the little folder icon at the top of the column of icons on the left. Click on this icon to open the file browser.
   - In the file browser, click on `basic_bayes_analysis.ipynb`
   - This contains the ordinal regression model

3. **Run the analysis:**
   - Click "Run" → "Run All Cells" to execute the entire analysis
   - Or run cells one by one using Shift+Enter
