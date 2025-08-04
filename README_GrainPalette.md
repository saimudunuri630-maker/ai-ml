
# GrainPalette - Rice Type Classification Using Deep Learning

GrainPalette is a machine learning project designed to classify different types of rice grains using deep learning and transfer learning techniques. This project aims to help farmers, agricultural researchers, and home gardeners quickly identify rice varieties from images.

---

## 🚀 Features

- Classifies 5 rice types using image data
- Built with Convolutional Neural Networks (CNN) and MobileNetV2
- User-friendly input (upload an image and get prediction)
- Model training with data augmentation and evaluation
- High potential for mobile/web deployment using Gradio or Streamlit

---

## 🖥️ System Requirements

- Windows 8 or later
- Two web browsers installed (e.g., Chrome, Firefox)
- Internet bandwidth of at least 30 Mbps
- Google Colab or Jupyter Notebook environment

---

## 📂 Dataset Structure

The dataset directory should follow this structure:

```
rice_dataset/
├── Basmati/
├── Jasmine/
├── Arborio/
├── Black_Rice/
└── Brown_Rice/
```

Each subfolder should contain labeled images of rice grains of the corresponding variety.

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2 (pre-trained on ImageNet)
- Google Colab
- Matplotlib (for plotting results)

---

## 📈 Model Training

- **Image Size:** 224x224
- **Batch Size:** 32
- **Epochs:** 10
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy

---

## 📤 Output

- Trained model saved as `rice_type_classifier.h5`
- Accuracy and validation accuracy plots
- Console output for each training epoch

---

## 📌 Use Case Scenarios

- **Farmers:** Crop planning and variety selection
- **Researchers:** Quick classification during field trials
- **Gardeners:** Educational tool for identifying rice seeds

---

## 📚 Future Enhancements

- Add more rice types and a larger dataset
- Fine-tune MobileNetV2 for better performance
- Deploy as an interactive web/mobile app
- Multi-language support for rural farmers

---

## 📄 License

Open source for educational and research use.

---

## 🙏 Acknowledgments

- TensorFlow and Keras community
- ImageNet and rice dataset providers
