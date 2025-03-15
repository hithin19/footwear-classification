# Footwear Classification using Transfer Learning

## Overview
This project implements a deep learning-based **footwear classification** system using **transfer learning**. The model is trained on footwear images and deployed as a **Flask web application** for real-time predictions.

## Features
- **Transfer Learning:** Utilizes pre-trained models (**ResNet152V2, DenseNet201, NASNetMobile, InceptionResNetV2**).
- **Image Processing:** Uses OpenCV and ImageDataGenerator for **normalization, augmentation (rescaling, zooming, shifting)**.
- **Flask Web App:** Accepts user-uploaded images or image URLs for classification.
- **Evaluation Metrics:** Displays **accuracy, confusion matrix**, and other performance measures.

## Tech Stack
- **Python** (TensorFlow, Keras, OpenCV, NumPy, Flask)
- **Deep Learning Models:** Pre-trained architectures fine-tuned for classification




## Results & Conclusion
- **InceptionResNetV2** achieved the best performance among tested models.
- Transfer learning proved effective for accurate and efficient footwear classification.
- Future improvements include **hyperparameter tuning, ensemble methods, real-time deployment**, and **dataset expansion**.

## Future Work
- Optimize hyperparameters for better accuracy.
- Implement real-time deployment with TensorFlow Lite/JS.
- Expand dataset with more footwear categories.
- Explore architectures like **EfficientNet and Xception** for improved performance.

## Contributing
Feel free to **fork** this repository, create feature branches, and submit **pull requests** for improvements!

## License
This project is licensed under the **MIT License**.

---
Made with ❤️ by **[Hithin]**
