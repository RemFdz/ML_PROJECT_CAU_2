# Machine learning project class Chung Ang

# Reproducibility Notes

This project was developed and tested in a Kaggle Notebook environment.  
To reproduce the results, follow the instructions below.

## Environment
- Platform: **Kaggle Notebook**
- Hardware: **Two Tesla T4 GPUs**
- Internet: **Disabled**
- Python dependencies: default Kaggle environment (TensorFlow, PyTorch, scikit-learn, transformers)

## Data and Models

All external models are loaded from Kaggle datasets.  
Ensure the dataset is attached to the notebook before execution.
(Competition environment)

## Randomness and Seeds
To ensure consistent results across runs:

- Use `random_state=42` for all train/validation splits  
- Use `random_state=42` for all scikit-learn models  
- NumPy and TensorFlow seeds are also set to `42` where applicable

## Execution Steps
1. Open the Kaggle Notebook in Kaggle.  
2. Attach the required dataset (use the competition environment).  
3. Run all cells in order.
4. No internet access is required or used.
