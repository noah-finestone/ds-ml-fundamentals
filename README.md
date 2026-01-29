# ds-ml-fundamentals
Data Science and Machine Learning Fundamentals

Following "Machine Learning with PyTorch and Scikit-Learn" by Sebastian Raschka

## Project Structure
```
├── ch01-intro/          # Chapter 1: Introduction to ML
├── ch02-training/       # Chapter 2: Training ML algorithms
├── ch03-classification/ # Chapter 3: Classification
├── data/                # Datasets
│   ├── raw/            # Original data
│   └── processed/      # Cleaned/processed data
├── models/             # Saved model files
├── figures/            # Plots and visualizations
└── src/                # Reusable Python utilities
```

## Setup

**Environment:** `ml-pytorch`

### Option 1: Create from environment file (recommended)
```bash
conda env create -f environment.yml
conda activate ml-pytorch
```

### Option 2: Manual setup
```bash
conda create -n ml-pytorch python=3.10 -y
conda activate ml-pytorch
conda install pytorch torchvision -c pytorch -y
conda install numpy scipy pandas matplotlib scikit-learn jupyter -y
```

### Verify installation
```bash
python -c "import torch, numpy, scipy, pandas, matplotlib, sklearn; print('All packages installed successfully!')"
```

### List installed packages
```bash
# List all packages in environment
conda list

# List only explicitly installed packages
conda env export --from-history

# Search for specific package
conda list | grep numpy
```
