Cat vs Dog Classification 🐱🐶

Used Transfer Learning with MobileNetV2 (pre-trained on ImageNet).

Froze all base layers to retain pre-trained weights.

Added custom output layers (Dense, Dropout, Sigmoid) for binary classification.

Trained only the new layers → faster training & good accuracy.
