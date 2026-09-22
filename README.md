# Exploration-of-Dataset-Bias-In-Image-Classification-using-ConvNext-tiny
This research project investigates dataset bias and dataset-specific visual cues in image classification. A ConvNeXt-Tiny model pretrained on ImageNet-1K is fine-tuned to classify images according to their dataset of origin across four datasets: ArTaxOr, Insects Image Dataset, iNaturalist Regular Data, and iNaturalist Research Data.

The project compares different fine-tuning and regularization strategies and evaluates model performance using validation loss, test accuracy, confusion matrices, and per-dataset recall. Additional analyses using RGB colour histograms and Grad-CAM are performed to investigate whether the model relies on dataset-specific visual characteristics.

Key Components
ConvNeXt-Tiny with ImageNet-1K pretraining
End-to-end fine-tuning with AdamW
Dataset-balanced train/validation/test splits
Data augmentation and ImageNet normalization
Comparison of end-to-end and head-only training
Regularization experiments using dropout and weight decay
Confusion matrix and per-class evaluation
RGB colour histogram analysis
Grad-CAM-based model interpretability
Reproducible experiments using fixed random seeds

Technologies: Python, PyTorch, Torchvision, PyTorch Lightning, TorchMetrics, NumPy, Pandas, Matplotlib, Grad-CAM.
