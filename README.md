# 📝 Transformer for Machine Translation (English to Urdu)  

This project implements a **Transformer model** for **English-to-Urdu translation** using the **UMC005 Parallel Corpus**. The model is trained to translate English sentences into Urdu by leveraging the self-attention mechanism in Transformers.  

---

## 🚀 **Features**  
✔ Preprocesses the **UMC005 English-Urdu dataset**  
✔ Cleans and tokenizes English and Urdu text  
✔ Uses **Byte Pair Encoding (BPE)** or other tokenization techniques  
✔ Implements a **Transformer-based sequence-to-sequence model** from scratch  
✔ Trains the model with **multi-head attention, positional encoding, and feed-forward layers**  
✔ Tunes **hyperparameters** such as layers, attention heads, dropout, and batch size  
✔ Compares the performance with an **LSTM-based model** for machine translation  
✔ Evaluates the model using **BLEU Score & ROUGE Score**  
✔ Visualizes the **training & validation loss curves**  
✔ Implements **attention visualization** to analyze word alignments in translations  
✔ Deploys a **ChatGPT-like UI** where users can input English text and get Urdu translations  

---

## 🔧 **Requirements**  
- Python  
- TensorFlow/PyTorch  
- Numpy & Pandas  
- Matplotlib & Seaborn  
- Tokenization Library (e.g., SentencePiece for BPE)  

---

## 📊 **Results & Evaluation**  
- The model was trained and evaluated on the **UMC005 English-Urdu Parallel Corpus**  
- Translation performance was measured using:  
  ✔ **BLEU Score**  
  ✔ **ROUGE Score**  
- A comparative analysis was done between **Transformer and LSTM-based translation models**  
- Training and validation loss were plotted to observe model convergence  
