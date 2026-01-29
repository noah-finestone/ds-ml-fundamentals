# ds-ml-fundamentals
Data Science and Machine Learning Fundamentals

Following "Machine Learning with PyTorch and Scikit-Learn" by Sebastian Raschka

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
conda install numpy scipy pandas matplotlib scikit-learn jupyter -y
```

### Verify installation
```bash
python -c "import numpy, scipy, pandas, matplotlib, sklearn; print('All packages installed successfully!')"
```
