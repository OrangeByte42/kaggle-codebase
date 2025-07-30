# 1.1

Basic Info:
- Dataset Processing: simple spliting (20% test, 80% train);
- Model Architecture: MLP (331-2048-ReLU-Dropout(0.2)-1);
- Loss Function: MSE;
- Optimizer: Adam;
- Training Details: fixed hyper-parameters (no tricks);
- Evaluation Metrics: RMSE;

## Added

- v1.1.1 MLP implementation;

## Fixed

- v1.1.1 Resolved an issue where pandas converted None to NA automatically when reading .csv, preventing feature loss due to mixed None and NA values.
- v1.1.1 Align data and model weight types (deal with mismatch error);


