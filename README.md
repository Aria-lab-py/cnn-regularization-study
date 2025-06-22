# CNN Regularization Study

This project explores how data augmentation and label smoothing impact the generalization of a CNN trained on CIFAR-10.

## 🔍 Summary

We trained a compact convolutional neural network under four conditions:

1. Baseline (no augmentation, no smoothing)
2. Data Augmentation Only
3. Label Smoothing Only
4. Data Aug + Label Smoothing

| Experiment            | Validation Accuracy |
|-----------------------|---------------------|
| Baseline              | 84.55%              |
| Data Aug Only         | 85.89%              |
| Label Smoothing Only  | 85.62%              |
| Aug + Label Smoothing | **88.44%**          |

## 🖼️ Visualizations

### Training Curves
![Training Curves](paper/combined_training_curves.jpg)

### t-SNE Plots
- Data Aug Only  
  ![](paper/tsne_after_training_aug_only.png)

- Label Smoothing Only  
  ![](paper/tsne_after_training_ls_only.png)

- Aug + LS  
  ![](paper/tsne_after_training_aug_ls.png)

## 📂 Contents

| Folder     | Description                       |
|------------|-----------------------------------|
| `src/`     | Source code (model, trainer, etc) |
| `notebooks/` | Training experiments             |
| `results/` | Saved models and metrics          |
| `paper/`   | LaTeX source and final PDF         |

## 🧠 Author

**Aria Ahmadi** — High school researcher with a passion for deep learning.

