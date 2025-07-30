# Classifying swimming Styles from images: Butterfly or Backstroke or Breaststroke or Freestyle.

## Results & Analysis

| Model            | Test Accuracy |
|------------------|---------------|
| Baseline         | 60–70%        |
| ResNet18         | 64%–77%       |
| EfficientNetV2-S | 80%–96%       |

EfficientNetV2-S classified backstroke and butterfly perfectly, with (11/11) and (14/14), while most of the error is centered around freestyle and breaststroke. That is, 2 out of 18 true-freestyle frames were mistaken for breaststroke, and 3 out of 11 true-breaststroke frames were misclassified (two as backstroke and one as freestyle). 


