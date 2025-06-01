# Development-of-an-Illegal-Camera-Detection-Model-for-Mobile-Devices (with sPresto)
1. Data: 1,500 illegal camera images provided by the company
2. Model: Fcos(Fully Convolutional One-Stage Object Detection) and RetinaNet
3. Challenges: Small object detection, Limited datasets, model lightweighting in the field of computer vision.
4. (IoU 0.5) Recall: 95.1%, Precision: 90.4% / Inference Time: 731(ms)
5. Redesigning the FPN (Feature Pyramid Network) architecture and implementing reverse tracking of data distribution.
6. Managed the conversion process from PyTorch to ONNX to TensorFlow Lite and ultimately to Flutter, addressing challenges such as dimension mismatches and limitations in dynamic operation conversion; implemented custom post-processing logic in Flutter.
