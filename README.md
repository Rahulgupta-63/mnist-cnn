# MNIST CNN

Digit classifier using a Convolutional Neural Network in PyTorch. Trained on the MNIST dataset (70,000 handwritten digit images).

## Result

99.10% test accuracy after 5 epochs.

## Model

- 2 Conv2d layers + MaxPooling
- Fully connected output layer
- Adam optimizer, CrossEntropyLoss

## Run

```bash
pip install torch torchvision
```

Open `mnist.ipynb` and run all cells. Dataset downloads automatically via torchvision.

## Limitations

- No test-time augmentation or regularization tuning — standard baseline CNN, not optimized further
- Fixed 5 epochs, no early stopping
