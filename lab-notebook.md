# Lab Notebook

## Day 1 - 10 October 2026
**What I did:** Trained my first AI model in Google Colab on the Flowers102 dataset, using MobileNetV3-small with a free T4 GPU.

**Results (accuracy after each epoch):**
- Epoch 1: 22.4%
- Epoch 2: 49.4%
- Epoch 3: 70.6%
- Epoch 4: 77.4%
- Epoch 5: 78.7%

**What fine-tuning means (my own words):**
(Write one sentence here. Example: I took a model that already knows how to look at images and trained it a little more so it can do my new task.)

**What I noticed:**
Accuracy rose fast at first, then slowed down after epoch 4.

**Next experiment:**
Try 10 epochs, or change the learning rate, and compare.
## Day 2 - 11 October 2026

## Augmentation experiment
Changed: added stronger augmentation to EfficientNet-B0.
Best result: accuracy 73.5%, melanoma sensitivity 61.4%, balanced 73.9%.
Baseline: accuracy 78.4%, melanoma sensitivity 72.9%, balanced 76.6%.
Conclusion: no improvement at 8 epochs. It may need more epochs.
