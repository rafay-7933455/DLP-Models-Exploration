# Instructions

1. Install Python 3.10/3.11 and the dependencies in README.md.
2. Open `CIFAR10_SectionB_Starter.ipynb` in Jupyter and run cells in order.
3. Confirm the split contains 400 training and 100 validation images, with 40/10 per class.
4. Run the baseline and inspect the loss and accuracy curves.
5. Implement the augmentation configurations marked TODO; apply them on the fly to training data only.
6. Complete the ablation loop for seeds 17, 42, and 123. Start a fresh model for every run.
7. Use validation data only for hyperparameter selection and checkpoint selection.
8. Obtain the exact hidden corruption and shifted-test setup from the instructor; do not invent it.
9. After model selection is frozen, evaluate clean and shifted test sets once.
10. Add class-wise accuracy, a normalized confusion matrix, eight misclassified images, and optional TTA results.
11. Ensure every plot has a title and labeled axes; include legends where appropriate.
12. Save the notebook with outputs visible and include measured results only.
13. Write the one-page Word summary with final score, selected configuration, and the most helpful change.
14. Push the notebook, README, and necessary reproduction files to GitHub. Do not upload the CIFAR-10 dataset unless instructed.
