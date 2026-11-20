# Mixed Corruption-Based Data Augmentation for Traffic Sign Recognition

ARTI 502 course project. Team: Reena Aloraini, Maria Aljafri, Wala Almukhtar, Rawan Alzaid, Dima Alrahal, Sara Alsahli. 



**Pipeline description:** compares Clean, Gaussian-noise, Gaussian-blur and Mixed (noise or blur) training augmentation on GTSRB (43 classes) for a custom CNN and a pretrained MobileNetV2, and tests all eight models on the same test images under clean, noisy and blurred conditions.

**Contents**
- notebooks/: the full experiment (run top to bottom, GPU recommended; designed for Google Colab)
- results/: figures, CSV tables and training histories
- checkpoints/: best model of each run
- requirements.txt: dependencies (the dataset downloads automatically)

**Note:** one training seed per configuration; corruption severities are proposed settings, not a benchmark.
