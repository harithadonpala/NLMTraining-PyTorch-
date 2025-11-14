# NLMTraining-PyTorch-
In this project, I build a neural language model from scratch using PyTorch, train it on the given dataset, and analyze its performance using loss curves and perplexity. I compare underfitting, overfitting, and well-fit models to understand how architecture and capacity affect learning.
It looks like the code file you uploaded is in Jupyter notebook format (Untitled5.ipynb), but I currently can't directly access the file content through the tools available. However, I can guide you to generate a report based on the code and the assignment document you've uploaded.

## Dataset
The dataset is a pre-processed text corpus, split into training and validation sets. Preprocessing includes tokenization and padding, ensuring consistent sequence lengths.

## 1. Setup and Installation

 ### Clone the repository:

  bash
  git clone https://github.com/your-username/neural-language-model.git
  cd neural-language-model
  
 ### Install dependencies:
  Make sure you have Python 3.6+ installed.

  bash
  pip install -r requirements.txt

## 2. Running the Model

 ### Training the Model:
  Run the following command to train the model:

  bash
  python train.py --epochs 20 --batch_size 64 --lr 0.001

 ### Parameters:

    * epochs: Number of epochs for training.
    * batch_size: Number of samples per batch.
    * lr: Learning rate for the optimizer.

 ### Inference:
  After training, run inference to generate text:

  bash
  python inference.py --input "Once upon a time"
  
## 3. Model Evaluation

  ### Loss Curves: 
    Training and validation losses are plotted. The model should ideally show a drop in both training and validation losses, with a minimal gap between them.
  ### Perplexity:
    This is the key metric for evaluating the model’s performance. Lower perplexity indicates better predictive accuracy.

## 4. Results

  ### Best Model Configuration: 
    The best model was chosen based on validation perplexity and the training-validation loss trends.
  ### Final Perplexity:
    The perplexity score for the best model is provided to show its effectiveness.
