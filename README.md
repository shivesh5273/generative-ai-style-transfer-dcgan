# Generative AI Practice – Text, Style Transfer, and DCGAN

This project explores three pillars of generative AI: large language models, neural style transfer, and deep convolutional GANs (DCGAN), each applied in real-world settings to generate text and images.

---

## 🔍 Project Breakdown

### ✍️ 1. OpenAI Text Generation via API
- Prompted the model to generate a poem on a custom topic.
- Controlled output length and formatting via model parameters.
- Limited to 1–2 trials for comparison and observation.

### 🎨 2. Neural Style Transfer with Custom Inputs
- Modified and executed `neural_style_transfer.ipynb` with:
  - A new photo for content input (not Paris)
  - A different painting for style input (not Starry Night)
- Produced stylized images using TensorFlow's NST pipeline.
- Saved output to HTML and documented every intermediate step.

### 👗 3. DCGAN for Fashion MNIST
- Adapted `dcgan.ipynb` to generate clothing items instead of digits.
- Trained a DCGAN on Fashion MNIST with modified preprocessing.
- Generated and visualized 28x28 grayscale images after training.

---

## 📁 Files Included

- `openai-api-text-generation.html`
- `neural-style-transfer-custom-images.html`
- `dcgan-fashion-mnist-generation.html`
- `generative-ai-overview.docx`

---

## 🛠 Tools & Libraries

- OpenAI GPT-3.5 API  
- TensorFlow / Keras  
- Fashion MNIST  
- Matplotlib / PIL / Numpy  
- Google Colab / Jupyter

---

> Bridging language and vision generation through hands-on creative AI exploration.
