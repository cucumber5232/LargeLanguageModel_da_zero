# Large Language Model da Zero 

Un percorso didattico per costruire un Large Language Model partendo dalle fondamenta matematiche fino all'architettura Transformer completa.

## Obiettivo

Questo progetto documenta il mio percorso di apprendimento nella costruzione di un LLM da zero, seguendo la teoria matematica e implementando ogni componente in Python/PyTorch.

## Progressi

- [x] Fondamenti matematici (vettori, matrici, softmax)
- [x] Bigram Language Model
- [ ] Attention Mechanism (Q, K, V)
- [ ] Multi-Head Attention
- [ ] Transformer Block completo
- [ ] Training loop
- [ ] Generazione di testo

## Setup

```bash
# 1. Clona la repository
git clone https://github.com/TUO_USERNAME/LargeLanguageModel_da_zero
cd LargeLanguageModel_da_zero

# 2. Crea l'ambiente virtuale
python -m venv cuda

# 3. Attiva l'ambiente
cuda\Scripts\activate       # Windows
# source cuda/bin/activate  # Mac/Linux

# 4. Installa le dipendenze
pip install -r requirements.txt

# 5. Avvia Jupyter
cd notebooks
jupyter notebook
```

## Notebook


##  Concetti Teorici Chiave

- **Bigram Model**: predizione del token successivo basata su probabilità condizionale
- **Self-Attention**: meccanismo che permette al modello di "guardare" tutti i token precedenti
- **Q, K, V (Query, Key, Value)**: le tre proiezioni fondamentali dell'attention
- **Softmax**: normalizzazione delle probabilità di attenzione
- **Multi-Head Attention**: esecuzione parallela di più meccanismi di attention

##  Risorse

- **Paper**: [Attention is All You Need](https://arxiv.org/abs/1706.03762) (Vaswani et al., 2017)
- **Tutorial**: [[Nome/link del tutorial che stai seguendo]](https://www.youtube.com/watch?v=yAcWnfsZhzo)
