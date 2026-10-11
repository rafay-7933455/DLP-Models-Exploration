# CIFAR-10 Robust Classification — Starter

## Files
- `CIFAR10_SectionB_Starter.ipynb`: Section B notebook scaffold.
- `README.md`: setup and reproduction guidance.
- `INSTRUCTIONS.md`: ordered checklist.

## Install
Python 3.10 or 3.11 recommended.

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

python -m pip install --upgrade pip
pip install torch torchvision numpy matplotlib scikit-learn notebook
jupyter notebook
```

Open `CIFAR10_SectionB_Starter.ipynb` and run cells in order.

## Data and reproducibility
The notebook downloads CIFAR-10 via `torchvision.datasets.CIFAR10`, chooses 50 training images per class with seed 42, and creates a class-balanced split of 400 training and 100 validation images. Exact indices are saved in `outputs/data_split_indices.npz`.

Clean test images are held separately. Do not use either test set for hyperparameter selection. The instructor must provide the exact shifted-test corruption pipeline, including the hidden corruption, before final evaluation. Do not guess it.

## Before submission
1. Complete all TODOs, including augmentation and three-seed ablations.
2. Verify trainable parameters are at most 1,000,000.
3. Report mean ± standard deviation across three seeds.
4. Add class-wise accuracy, normalized confusion matrix, and eight real misclassified examples.
5. Run the entire notebook and save outputs.
6. Add the one-page Word summary and repository link as required by the course.
7. Report only measured results; this is not a completed experiment.

The assignment says AI is prohibited. Follow your instructor's rules and independently understand and complete this scaffold.
