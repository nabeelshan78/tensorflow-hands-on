# 🧠 TensorFlow Hands-On Projects

A hands-on repository showcasing real-world deep learning implementations using **TensorFlow** and **Keras**.

---

## 🔗 Table of Contents

- [Computer Vision Examples](#computer-vision-examples)
- [Exploring Convolutions](#exploring-convolutions)
- [Improving Accuracy Using Convolutions](#improving-accuracy-using-convolutions)
- [Improve MNIST with CNN](#improve-mnist-with-cnn)
- [Early Stopping & Callbacks](#early-stopping--callbacks)
- [Handling Complex Images](#handling-complex-images)
- [Visualizing Conv Layers](#visualizing-conv-layers)
- [Dataset Structure](#dataset-structure)
- [Image Assets](#image-assets)
- [Skills Demonstrated](#skills-demonstrated)
- [Setup & Installation](#setup--installation)
- [Future Work](#future-work)


---

## Computer Vision Examples

> [`computer_vision_ex.ipynb`](./computer_vision_ex.ipynb)

A foundational notebook where we:
- Load image datasets
- Preprocess and reshape tensors
- Use simple CNN architectures
- Apply training/validation testing

![Example Image](./images/horse.webp)

---

## Exploring Convolutions

> [`exploring_convolutions.ipynb`](./exploring_convolutions.ipynb)

Explore how convolutional filters behave with different kernel sizes and strides. This section visually demonstrates how features are extracted.

| Feature Map Visuals |
|---------------------|
| ![](./images/exploring_convolutions_01.png) |
| ![](./images/exploring_convolutions_03.png) |

---

## Improving Accuracy Using Convolutions

> [`improving_accuracy_using_convolutions.ipynb`](./improving_accuracy_using_convolutions.ipynb)

Train a CNN and compare its performance with traditional dense layers. Visualize convolutional filters and their effects on training.

![Conv Filter Visual](./images/improving_accuracy_using_convolutions_01_conv_visual.png)

---

## Improve MNIST with Convolutions

> [`Improve MNIST with Convolutions.ipynb`](./Improve%20MNIST%20with%20Convolutions.ipynb)

A deep dive into improving the performance of MNIST classification using convolutional layers. Step-by-step comparison with dense architectures.

---

## Callbacks & Early Stopping

> [`callbacks.ipynb`](./callbacks.ipynb)  
> [`early_stop_callbacks.ipynb`](./early_stop_callbacks.ipynb)

Understand and implement:
- Custom Callbacks
- Early stopping based on validation loss
- Learning rate schedules

---

## Handling Complex Images

> [`Handling Complex Images`](./Handling%20Complex%20Images/)

- Custom dataset with `happy 😃` and `sad 😢` faces
- Demonstrates binary classification using CNNs
- Real-world simulation of emotion detection


📷 Sample Images:
| Happy | Sad |
|-------|-----|
| ![](./Handling%20Complex%20Images/data/happy/happy1-00.png) | ![](./Handling%20Complex%20Images/data/sad/sad1-00.png) |

---

## Visualizing Conv Layers

> [`Visualizing Conv Layers`](./Visualizing%20Conv%20Layers/)

- Visualizes learned filters
- Helps debug training by seeing how CNNs perceive data

Results Chart:

![Chart](./Visualizing%20Conv%20Layers/results%20chart.png)

| Visualized Activations |
|------------------------|
| ![](./Visualizing%20Conv%20Layers/visual_1.png) |
| ![](./Visualizing%20Conv%20Layers/visual_2.png) |

---

## Dataset Structure

```bash
tensorflow-hands-on/
├── callbacks.ipynb
├── computer_vision_ex.ipynb
├── data/
│   └── mnist.npz
├── early_stop_callbacks.ipynb
├── exploring_convolutions.ipynb
├── Improve MNIST with Convolutions.ipynb
├── improving_accuracy_using_convolutions.ipynb
├── images/
│   └── *.png, *.webp
├── Handling Complex Images/
│   ├── notebook.ipynb
│   └── data/
│       ├── happy/
│       └── sad/
└── Visualizing Conv Layers/
    ├── notebook.ipynb
    └── visual_x.png
```

