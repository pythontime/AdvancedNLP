![GitHub](https://img.shields.io/github/license/DataForScience/AdvancedNLP)
[![Twitter @data4sci](https://img.shields.io/twitter/follow/data4sci)](https://twitter.com/intent/follow?screen_name=data4sci)
![GitHub top language](https://img.shields.io/github/languages/top/DataForScience/AdvancedNLP)
![GitHub repo size](https://img.shields.io/github/repo-size/DataForScience/AdvancedNLP)
![GitHub last commit](https://img.shields.io/github/last-commit/DataForScience/AdvancedNLP)

[![Data For Science Substack](https://img.shields.io/badge/Data_For_Science_Substack-Subscribe-blue)](https://data4sci.substack.com/)
[![Data Science Briefing](https://img.shields.io/badge/Data_Science_Briefing-Subscribe-blue)](https://data4science.ck.page/a63d4cc8d9)

# NLP with PyTorch

### Code and slides to accompany the online series of webinars: https://data4sci.com/nlp-with-pytorch by Data For Science.

Natural Language lies at the heart of current developments in Artificial Intelligence, User Interaction, and Information Processing. The combination of unprecedented corpora of written text provided by social media and the massification of computational power has led to increased interest in the development of modern NLP tools based on state-of-the-art Deep Learning tools.

In this course, participants are introduced to the fundamental concepts and algorithms used for Natural Language Processing (NLP) through an in-depth exploration of different examples built using the PyTorch framework for deep learning. Applications to real datasets will be explored in detail.

## Schedule
### 1. Foundations of NLP
- One-Hot Encoding
- TF/IDF and Stemming
- Stopwords
- N-grams
- Working with Word Embeddings

### 2. Neural Networks with PyTorch
- PyTorch review
- Activation Functions
- Loss Functions
- Training procedures
- Network Architectures

### 3. Text classification
- Feed Forward Networks
- Convolutional Neural Networks
- Applications

### 4. Word Embeddings
- Motivations
- Skip-gram and Continuous Bag of words
- Transfer Learning

### 5. Sequence Modeling
- Recurrent Network Networks
- Gated Recurrent Unit
- Long-Short Term Memory
- Encoder-Decoder Models
- Text Generation

<!-- Slides: https://data4sci.com/landing/advanced-nlp -->

## Author

<table border="0">
 <tr>
        <td>
          <img src="data/bgoncalves.png" alt="Bruno Gonçalves" width="150" height="150" style="border-radius: 50%; object-fit: cover;">
        </td>
        <td>
          <h2>Bruno Gonçalves</h2>
          <h3>Data For Science, Inc.</h3>
          <p>
                        Web: <a href="http://www.data4sci.com/">www.data4sci.com</a><br>
                        Twitter/X: <a href="https://twitter.com/bgoncalves">@bgoncalves</a><br>
                        LinkedIn: <a href="https://www.linkedin.com/in/bmtgoncalves/">@bmtgoncalves</a><br>
                        Email: <a href="info@data4sci.com">info@data4sci.com</a><br>
                        Schedule a Call: <a href="https://data4sci.com/call">https://data4sci.com/call</a>
          </p>
        </td>
 </tr>
</table>


## Getting Started

### Prerequisites
- Python 3.10 or higher (up to 3.13)
- macOS, Linux, or Windows

### Installation

#### Option 1: Using uv (Recommended)

[uv](https://github.com/astral-sh/uv) is a fast Python package installer and resolver. If you don't have it installed:

```bash
# Install uv
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Then clone and setup the repository:

```bash
# Clone the repository
git clone https://github.com/DataForScience/AdvancedNLP.git
cd AdvancedNLP

# Install dependencies
uv sync

# Run Jupyter
uv run jupyter notebook
```

#### Option 2: Using pip and venv

```bash
# Clone the repository
git clone https://github.com/DataForScience/AdvancedNLP.git
cd AdvancedNLP

# Create virtual environment
python -m venv .venv

# Activate virtual environment
# On macOS/Linux:
source .venv/bin/activate
# On Windows:
.venv\Scripts\activate

# Install dependencies
pip install -e .

# Run Jupyter
jupyter notebook
```

### Hardware Acceleration

This project supports hardware acceleration for faster training:
- **Apple Silicon (M1/M2/M3)**: Automatically uses MPS (Metal Performance Shaders) backend
- **NVIDIA GPUs**: Automatically uses CUDA if available
- **CPU**: Falls back to CPU if no GPU is available

### Running the Notebooks

Once Jupyter is running, open any of the numbered notebooks:
1. Foundations of NLP.ipynb
2. Neural Networks with PyTorch.ipynb
3. Text Classification.ipynb
4. Word Embeddings.ipynb
5. Sequence Modeling.ipynb