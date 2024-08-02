# 🔍 Training and Evaluating a Keypoint Detection Model using ResNet50 🔍

## 📊 Data
The data for this project is sourced from this [repository](https://github.com/yastrebksv/TennisCourtDetector).

## 🏛️ Model Architecture
The model employed is **ResNet50**, a deep residual network architecture. The final fully connected layer is customized to output **28 (14x2) keypoints**, tailored for this specific task.

## 🚀 Training

- **Loss Function**: Mean Squared Error (MSE) loss is utilized to gauge the difference between predicted and true keypoints.
- **Optimizer**: Adam optimizer is used to enhance model performance.

## 📈 Evaluation

- **Test Loss**: The average loss on the test set is calculated to assess model performance.
- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and true keypoints.

![History](./images/History.jpg)

## 🏷️ Tags
- 🤖 **Machine Learning**
- 🌟 **Deep Learning**
- 🖼️ **Computer Vision**
- 📍 **Keypoint Detection**
- 🧠 **ResNet50**
- 🔥 **PyTorch**
- 📉 **Mean Squared Error**

