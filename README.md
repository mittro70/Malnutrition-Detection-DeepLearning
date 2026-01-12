# Malnutrition Detection using Deep Learning (YOLOv8, ResNet50, VGG16)
* **Objective**: developed an automated system to classify malnutrition in children using facial and full-body imagery to assist in low-resource medical diagnosis.
* **Tech Stack**: Python, TensorFlow/Keras, PyTorch (YOLOv8), OpenCV, Pandas.
* **Key Results**:
  * Achieved **95.70% Accuracy** using YOLOv8-cls on the test set.
  * Outperformed VGG16 (92%) and ResNet50 (94%) in inference speed and precision.
  * Implemented Transfer Learning and fine-tuning on ImageNet weights.
* **Methodology**: Utilised data augmentation, architectural-specific resizing, and callbacks (EarlyStopping, ReduceLROnPlateau) to optimise model convergence.
