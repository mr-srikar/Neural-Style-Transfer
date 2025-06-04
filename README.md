# 🎨 Neural Style Transfer — TensorFlow Implementation

This project showcases **Neural Style Transfer**, a deep learning technique that blends the content of one image with the artistic style of another. The result is a unique, stylized image.

## 🧠 Technologies Used
- **TensorFlow** and **TensorFlow Hub**
- **OpenCV** and **Matplotlib**
- Implemented in **Jupyter Notebook**

## 📌 Model
Uses [`arbitrary-image-stylization-v1-256`](https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2), a TensorFlow Hub model for fast and high-quality style transfer between arbitrary images.

## 🚧 Features
- Load and preprocess **content** and **style** images
- Apply **style transfer** using the model
- Save the **stylized output**
- Utility functions for:
  - Resizing images
  - Displaying results
  - Converting tensors to image format

## 🔄 Customization
- Swap in your own content/style images with ease
- Stylized outputs are saved to the `images/` directory

## 🚀 Potential Extensions
- Add interactive image sliders
- Enable batch processing
- Integrate with web frameworks like **Streamlit** or **Flask**

---

> 💡 This project is a great starting point for exploring **pre-trained computer vision models** and building creative AI tools with **TensorFlow Hub**.
