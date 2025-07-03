# Investigating key ML Algo Models! 🚀

Hi there! Welcome to my reference playground where I've been tinkering with **key machine learning algorithms**. This repo is my sandbox, a collection of experiments, prototypes, and half-baked ideas as I dive into the deep end of AI and ML. Each model here is a stepping stone toward building something awesome. I’m learning as I go, so expect some messy code and works in progress!

---

## The ML Algo Lineup :chart_with_upwards_trend:

Here’s the grand table of my algorithmic escapades, complete with what they’re used for and my personal commentary on their status. Buckle up—it’s a rollercoaster!

| **Algo #** | **Model Name**          | **Used For**                              | **Status**                  |
|------------|--------------------------|-------------------------------------------|---------------------------------------------|
| 1          | Linear Regression        | Predicting continuous values (e.g., house prices) | Done |
| 2          | Logistic Regression      | Binary classification (e.g., spam vs. not spam) | Done |
| 3          | Decision Trees           | Classification and regression tasks       | Done |
| 4          | Random Forest            | Ensemble classification/regression        | Done |
| 5          | Support Vector Machines  | Complex classification (e.g., image labels) | Done |
| 6          | K-Nearest Neighbors      | Pattern recognition (e.g., recommendation) | Done |
| 7          | K-Means Clustering       | Unsupervised grouping (e.g., customer segments) | Done |
| 8          | Principal Component Analysis | Dimensionality reduction              | Done |
| 9          | Gradient Boosting        | Boosted prediction (e.g., ranking models) | Done |
| 10         | Neural Networks          | General-purpose learning (e.g., digits)   | Done |
| 11         | Convolutional Neural Nets| Image processing (e.g., object detection) | Done |
| 12         | Recurrent Neural Nets    | Sequence data (e.g., time series)         | Done |
| 13         | Long Short-Term Memory   | Long-term sequence modeling               | Done |
| 14         | Autoencoders             | Anomaly detection and data compression    | Done |
| 15         | Generative Adversarial Nets | Synthetic data generation              | Done |
| 16         | Reinforcement Learning   | Decision-making (e.g., game AI)           | Done |
| 17         | Bayesian Networks        | Probabilistic inference                   | Done |
| 18         | Gaussian Mixture Models  | Clustering with soft assignments          | Done |
| 19         | Stable Diffusion         | Image generation from text prompts        | Work in progress - Investigating as too slow on my PC |
| 20         | Large Language Model     | Text generation (e.g., financial advice)  | Work in progress - Investigating significant overfitting and then plateauing on the training |

---

## What’s Cooking? :cooking:

- **Progress**: Most models (1–18) are in a "done" state, meaning they’re functional prototypes I’ve played with and learned from. Models 19 and 20 are my current obsessions—still under the microscope!
- **Challenges**: 
  - **Stable Diffusion (19)**: It’s a beast for image generation, but my PC struggles under the load. I’m digging into optimizations to make it run smoother.
  - **LLM (20)**: This text-generating champ is overfitting like crazy and then hitting a validation accuracy wall (around 0.28). I’m tweaking regularization, data, and architecture changes!
- **Next Steps**: I’m planning to refine these models, add more data where possible, and maybe even deploy a few as proof-of-concepts. 

---

## How to Dive In :diving_mask:

1. **Clone the Repo**: Grab it with `git clone <repo-url>` (you’ll need to imagine the URL for now—let me know if you want to set one up!).
2. **Set Up Environment**: Use Python 3.12 with dependencies like TensorFlow, NLTK, and Hugging Face datasets. Check the `requirements.txt` (coming soon!) for the full list.
3. **Run the Notebooks**: Each model has its own Jupyter notebook (e.g., `20_llm_large_language_model.ipynb`)—fire them up and tweak away!
4. **Experiment**: Mess with hyperparameters, datasets, or architectures. Break something? Awesome! that’s how we learn!

---

🚀