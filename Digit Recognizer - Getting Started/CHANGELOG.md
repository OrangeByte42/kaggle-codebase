# 1.1

Basic Info:
- Dataset Processing: simple spliting (20% test, 80% train);
- Model Architecture: MLP;
- Loss Function: MSE;
- Optimizer: SGD;
- Training Details: fixed hyper-parameters (no tricks);

## Added

- v1.1.1 MLP implementation;

## Fixed

- v1.1.1 Data standardization (non-standardization causes gradient explosions);
- v1.1.1 Align data and model weight types (deal with mismatch error);



















