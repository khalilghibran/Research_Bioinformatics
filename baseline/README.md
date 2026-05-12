# SMILES2VEC Refactored Code

This repository contains refactored code for various Deep Learning models applied to SMILES data. Each directory corresponds to a specific model architecture based on Bidirectional GRU (BiGRU) and other layers.

## Directory Structure

The project is organized into several main directories representing different combinations of neural network layers:

### 1. [Bi-gru/](./Bi-gru/)
Contains standard Bidirectional GRU models.
- **Subdirectories:**
  - `1_layer/`: Single-layer BiGRU architecture.
  - `2_layer/`: Two-layer BiGRU architecture.
  - `3_layer/`: Three-layer BiGRU architecture.

### 2. [Bi-gru+conv/](./Bi-gru+conv/)
Contains models combining BiGRU with Convolutional layers.
- **Subdirectories:**
  - `1_layer+conv/`
  - `2_layer+conv/`
  - `3_layer+conv/`

### 3. [Bi-gru+dense/](./Bi-gru+dense/)
Contains models combining BiGRU with Dense layers.
- **Subdirectories:**
  - `1_layer+dense/`
  - `2_layer+dense/`
  - `3_layer+dense/`

### 4. [Bi-gru+flatten/](./Bi-gru+flatten/)
Contains models combining BiGRU with Flatten layers.
- **Subdirectories:**
  - `1_layer+flatten/`
  - `2_layer+flatten/`
  - `3_layer+flatten/`

### 5. [Bi-gru+conv+dense/](./Bi-gru+conv+dense/)
Contains models combining BiGRU with Convolutional and Dense layers.
- **Subdirectories:**
  - `1_layer+conv+dense/`
  - `2_layer+conv+dense/`
  - `3_layer+conv+dense/`

### 6. [Bi-gru+conv+dense+flatten/](./Bi-gru+conv+dense+flatten/)
Contains complex models combining BiGRU with Convolutional, Dense, and Flatten layers.
- **Subdirectories:**
  - `1_layer+conv+dense+flatten/`
  - `2_layer+conv+dense+flatten/`
  - `3_layer+conv+dense+flatten/`

## Common File Structure within Folders

Inside each specific model folder (e.g., `1_layer/`), you will typically find:

- **Jupyter Notebook (`.ipynb`)**: The main code for defining, training, and evaluating the model.
- **`csv/`**: Stores training metrics and history (e.g., `_metrics.csv`, `_training_history.csv`).
- **`model/`**: Saved trained models (e.g., `.keras` files).
- **`image/`**: Generated plots such as accuracy/loss graphs and confusion matrices.
