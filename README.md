# Assignment-2--Reinforcement-Learning-Programming---CSCN-8020

This project implements and analyzes Reinforcement Learning (RL) algorithms using the OpenAI Gymnasium environment. The focus is on training and evaluating an agent to perform tasks under different learning and exploration parameters.

Project Overview

Implementing a reinforcement learning model (e.g., Q-Learning or Monte Carlo methods)

Training the model in the Taxi-v3 environment from Gymnasium

Evaluating learning performance using average reward, number of steps, and training stability

Visualizing training performance through plots

Repository Structure
RF Assignment 2.ipynb – Main Jupyter Notebook with full implementation
assignment2_utils.py – Utility functions (simulation, metrics, plotting)
requirements.txt – Python dependencies
.gitignore – Ignored files and directories
README.md – Project documentation

Installation
Step 1: Clone the Repository
git clone https://github.com/yourusername/RL-Assignment2.git

cd RL-Assignment2

Step 2: Create and Activate Virtual Environment
python -m venv venv
source venv/bin/activate (On Windows: venv\Scripts\activate)

Step 3: Install Dependencies
pip install -r requirements.txt

Running the Notebook
Launch Jupyter Notebook or JupyterLab and open the file:
jupyter notebook "RF Assignment 2.ipynb"
Then run all cells sequentially to reproduce results and plots.

Output and Results
The notebook produces metrics and visualizations for:

Average Reward per Episode

Average Steps per Episode

Impact of Learning Rate (α) and Exploration Factor (ε)

Plots and results are automatically displayed within the notebook.

Insights

Higher learning rate (α) accelerates convergence but can increase variability.

Lower exploration factor (ε) helps refine policy but risks local optima.

The optimal configuration (based on your results): α = 0.2, ε = 0.1 produced higher average reward and reduced steps.

Author
Name: Kumari Nikitha Singh
