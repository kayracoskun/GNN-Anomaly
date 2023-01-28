# GNN-Anomaly
Anomaly Detection using Graph Neural Networks


## Related Works
### 1) Article

User Preference-aware Fake News Detection article is the original work done. 

UPFD in PyTorch Geometric is also taken from this work.

*Article*: https://arxiv.org/pdf/2104.12259.pdf

*Github*: https://github.com/safe-graph/GNN-FakeNews 

Four node features are used:
    - Profile: 10-dimensional Twitter user profile attributes.
    - Sapcy: 300-dimensional Twitter user historical tweets encoded by spaCy word2vec encoder.
    - Bert: 768-dimensional Twitter user historical tweets encoded by bert-as-service.
    - Content: 310-dimensional spaCy (300-dimensional) + profile (10-dimensional)

### 2) Original Code

The original code is taken from the below Colab notebook and Youtube video.

*Colab Notebook*: https://colab.research.google.com/drive/1ZVZdehPPod6o4sF64QZa8I3NoSOH8MmC?usp=sharing

*Youtube Video*: https://youtube.com/watch?v=QAIVFr24FrA 

### 3) Fake News Profile

Original code changed for using profile attributes for node features.

### 4) Fake News Spacy

Original code changed for using spacy embeddings for node features.

### 5) Fake News Bert

Original code changed for using bert embeddings for node features.

### 6) Fake News Content

Original code changed for using content for node features.

The highest accuracy was found in using content as node features.


