<h1 align="center">🧠 Deep Learning Journey</h1>

<p align="center">
  A hands-on collection of deep learning notebooks, from a single perceptron to CNNs, transfer learning and RNNs.<br>
  Built in Google Colab with <b>NumPy, PyTorch and TensorFlow/Keras</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
</p>

---

## 📌 About

I'm a third-year B.Tech student in AI & Data Science at **IIITDM Kurnool**. This repo is my learning log for deep learning: I implement the core ideas **from scratch first**, then rebuild them with PyTorch and Keras to see what the frameworks do for me.

The notebooks are numbered in the order I learned them, so you can read the repo top to bottom as a roadmap.

## 🗺️ Learning Roadmap

### 1️⃣ Foundations: from scratch
| # | Notebook | What it covers |
|---|---|---|
| 01 | [Perceptron Trick](notebooks/01_perceptron_trick.ipynb) | Perceptron learning rule and decision boundaries |
| 02 | [Backpropagation from Scratch](notebooks/02_backpropagation_from_scratch.ipynb) | Forward and backward pass implemented manually |
| 03 | [Backprop for Classification](notebooks/03_backpropagation_classification_from_scratch.ipynb) | Extending backprop to a classification problem |
| 04 | [Backprop using Keras](notebooks/04_backpropagation_using_keras.ipynb) | Same network rebuilt with Keras for comparison |
| 05 | [Mini-Batch Gradient Descent](notebooks/05_mini_batch_gradient_descent.ipynb) | Batch vs mini-batch vs stochastic updates |

### 2️⃣ PyTorch Basics
| # | Notebook | What it covers |
|---|---|---|
| 06 | [Tensors in PyTorch](notebooks/06_tensors_in_pytorch.ipynb) | Tensor creation, operations and shapes |
| 07 | [Autograd](notebooks/07_autograd.ipynb) | Automatic differentiation and gradients |
| 08 | [Dataset & DataLoader](notebooks/08_dataset_dataloader_demo.ipynb) | Custom datasets and batching |
| 09 | [ANN on Fashion-MNIST](notebooks/09_ann_pytorch_fashion_mnist.ipynb) | Training an ANN end to end in PyTorch |

### 3️⃣ Neural Networks & CNNs with Keras
| # | Notebook | What it covers |
|---|---|---|
| 10 | [MNIST Classification](notebooks/10_mnist_classification.ipynb) | Handwritten digit recognition |
| 11 | [NN Pipeline](notebooks/11_nn_pipeline.ipynb) | Structuring preprocessing and training as a pipeline |
| 12 | [Keras Functional API](notebooks/12_keras_functional_api.ipynb) | Multi-input and non-sequential models |
| 13 | [LeNet-5 Architecture](notebooks/13_lenet5_architecture.ipynb) | Classic CNN architecture |
| 14 | [Data Augmentation](notebooks/14_data_augmentation.ipynb) | Reducing overfitting with augmented images |
| 15 | [Cats vs Dogs CNN](notebooks/15_cats_vs_dogs_cnn.ipynb) | Binary image classification with a CNN |
| 16 | [Transfer Learning: Feature Extraction](notebooks/16_transfer_learning_feature_extraction.ipynb) | Using pretrained models as feature extractors |

### 4️⃣ Sequence & Text Models
| # | Notebook | What it covers |
|---|---|---|
| 17 | [Keras Padding Demo](notebooks/17_keras_padding_demo.ipynb) | Preparing variable-length sequences |
| 18 | [SimpleRNN with Embeddings](notebooks/18_simple_rnn_embeddings.ipynb) | Integer encoding, embeddings and a SimpleRNN |

### 5️⃣ Applied Projects
| # | Notebook | What it covers |
|---|---|---|
| 19 | [UTK Face](notebooks/19_utk_face.ipynb) | Face-attribute prediction on the UTKFace dataset |
| 20 | [Indian Sign Language Classifier](notebooks/20_indian_sign_language_classifier.ipynb) | Gesture classification, the basis of my SignBridge project |

## ▶️ Run the Notebooks

Every notebook runs in Google Colab. Open any file on GitHub and click **Open in Colab**, or use this link pattern:

```
https://colab.research.google.com/github/DD-bit001/deep-learning-journey/blob/main/notebooks/<notebook-name>.ipynb
```

To run locally:

```bash
git clone https://github.com/DD-bit001/deep-learning-journey.git
cd deep-learning-journey
pip install numpy pandas matplotlib scikit-learn torch torchvision tensorflow jupyter
jupyter notebook
```

Datasets (MNIST, Fashion-MNIST, Cats vs Dogs, UTKFace) are downloaded inside the notebooks or loaded from their public sources, so large data files are not stored in this repo.

## 📂 Structure

```
deep-learning-journey/
├── notebooks/        # numbered notebooks, in learning order
├── .gitignore
└── README.md
```

## 🎯 What I Learned

- How neurons, loss functions and backpropagation work under the hood
- The difference between writing training loops by hand (PyTorch) and using high-level APIs (Keras)
- Why augmentation and transfer learning matter on small datasets
- How embeddings and RNNs handle text and sequences

## 🔜 Next Up

- [ ] CNN architectures: VGG, ResNet
- [ ] LSTM / GRU and attention
- [ ] Transformers and fine-tuning
- [ ] Deploying a trained model as an API

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-dilnawaz-ahmad-b4637732a)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DD-bit001)

⭐ If this helped you, consider starring the repo.
