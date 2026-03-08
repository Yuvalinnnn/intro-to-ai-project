# Intro to AI – Final Project (Supervised Learning)

Final project for the *Introduction to Artificial Intelligence* course.

**Author:** Yuval Yerushmali


## Project Overview

The project includes:
1. Regression (Auto MPG)
2. Classical classification (CIFAR-10)
3. Neural networks with PyTorch (CIFAR-10)
+ Optional bonus: regression with PyTorch



## Repository Contents

- `Part1_Regression_AutoMPG.ipynb`  
  Regression on Auto MPG (linear / polynomial / KNN + optimization behavior).

- `Part2_Classification_CIFAR10.ipynb`  
  Classical models on CIFAR-10 (Logistic Regression, SVM, KNN) with hyperparameter tuning.

- `Part3_NeuralNetwork_PyTorch.ipynb`  
  PyTorch neural network on CIFAR-10 (including the BetterNet architecture).

- `Bonus_Regression_PyTorch.ipynb` *(optional)*  
  PyTorch regression model on Auto MPG.

- `Intro_to_AI___Final_Project.pdf`  
  Final report (results + discussion).



## Setup

### 1) Create a virtual environment (recommended)

**macOS / Linux**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Windows (PowerShell)**
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

### 2) Install dependencies

```bash
pip install -r requirements
```


## Data

- **Auto MPG**: loaded inside the notebook (internet access required).
- **CIFAR-10**:
  - In `Part3`, the dataset is downloaded automatically via `torchvision` on first run.
  - In `Part2`, the notebook handles downloading/extraction (see notes inside the notebook).



## How to Run

Open Jupyter and run notebooks from top to bottom:

```bash
jupyter notebook
```

Recommended order:
1. `Part1_Regression_AutoMPG.ipynb`
2. `Part2_Classification_CIFAR10.ipynb`
3. `Part3_NeuralNetwork_PyTorch.ipynb`
4. `Bonus_Regression_PyTorch.ipynb` (optional)



## Notes

- Notebooks should be run from top to bottom.
- For submission, I saved the notebooks with outputs.


## Submission

- Report: `Intro_to_AI___Final_Project.pdf`
- Code: this GitHub repository
