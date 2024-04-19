# AyurvedBot
# Model Training README

## Objective
The objective of this document is to outline the training details for seven different instances of a model trained on an Ayurvedic dataset. Each instance varies in certain hyperparameters, resulting in distinct training processes and outcomes.

## Model Instances

### 1. FIRST Instance
- **Hyperparameters:**
  - Batch Size: 16
  - Block Size: 32
  - Max Iterations: 7000
  - Evaluation Interval: 100
  - Learning Rate: 1e3
  - Device: CUDA (if available), CPU otherwise
  - Evaluation Iterations: 200
  - Embedding Size (n_embd): 264
  - Number of Attention Heads (n_head): 4
  - Number of Layers (n_layer): 2
  - Dropout: 0.2
- **Length of Dataset in Characters:** 90480
- **Result:** 
  - 1.730338 M parameters
  - Training and validation loss values recorded at various steps

#### Generated Text Sample:
```
vata is deferls change exceive excetics staged. Diet is dities stage, the relation of balance, and not discopting and that they wide or moder in un our health the norrmaction

Ayurveda stages. Balances an

```

### 2. SECOND Instance
- **Hyperparameters:**
  - Batch Size: 16
  - Block Size: 32
  - Max Iterations: 7000
  - Evaluation Interval: 100
  - Learning Rate: 1e3
  - Device: CUDA (if available), CPU otherwise
  - Evaluation Iterations: 200
  - Embedding Size (n_embd): 300
  - Number of Attention Heads (n_head): 4
  - Number of Layers (n_layer): 2
  - Dropout: 0.2
- **Length of Dataset in Characters:** 90480
- **Result:** 
  - 2.225482 M parameters
  - Training and validation loss values recorded at various steps

#### Generated Text Sample:
```
vata individuals them. Pro1ries a long if nature. If thie stages structural. Ayurvedic helps to partienge of the body, cracter fear, and corredless, what hate, start. Then ama, stark and relation. Regus a
```

### 3. THIRD Instance
- **Hyperparameters:**
  - Batch Size: 16
  - Block Size: 32
  - Max Iterations: 7000
  - Evaluation Interval: 100
  - Learning Rate: 1e3
  - Device: CUDA (if available), CPU otherwise
  - Evaluation Iterations: 200
  - Embedding Size (n_embd): 300
  - Number of Attention Heads (n_head): 4
  - Number of Layers (n_layer): 2
  - Dropout: 0.2
- **Length of Dataset in Characters:** 78626
- **Result:** 
  - 2.225482 M parameters
  - Training and validation loss values recorded at various steps

#### Generated Text Sample:
```
vata ind deevelopmedt. From it basic enternad considereded and emotions. Your maind leading.

NOTEM NFEggramental For mental warder you. Balance of a has healthy happiness twater to reecondlession, relt a

```

### 4. FOURTH Instance
- **Hyperparameters:**
  - Batch Size: 16
  - Block Size: 32
  - Max Iterations: 7000
  - Evaluation Interval: 100
  - Learning Rate: 1e3
  - Device: CUDA (if available), CPU otherwise
  - Evaluation Iterations: 200
  - Embedding Size (n_embd): 300
  - Number of Attention Heads (n_head): 4
  - Number of Layers (n_layer): 2
  - Dropout: 0.2
- **Length of Dataset in Characters:** 33398
- **Result:** 
  - 2.223078 M parameters
  - Training and validation loss values recorded at various steps

#### Generated Text Sample:
```
vata is one of cold foods and ination. If your health.
- Life Elements

Ayurvedic and freshly trained conlue hashest are so spreaks will or dry inciple, it speak qupces in the other constitution accor sth

```

### 5. FIFTH Instance
- **Hyperparameters:**
  - Batch Size: 16
  - Block Size: 32
  - Max Iterations: 5000
  - Evaluation Interval: 100
  - Learning Rate: 1e3
  - Device: CUDA (if available), CPU otherwise
  - Evaluation Iterations: 300
  - Embedding Size (n_embd): 264
  - Number of Attention Heads (n_head): 2
  - Number of Layers (n_layer): 4
  - Dropout: 0.2
- **Length of Dataset in Characters:** 33398
- **Result:** 
  - 3.406206 M parameters
  - Training and validation loss values recorded at various steps

#### Generated Text

 Sample:
```
vatas cold foods foody, with prep remedies interruptes the primport of the characterimation a sthese from but dosha their character of the doshas are also king a regulate to mae more other aggravates vata
```

### 6. SIXTH Instance
- **Hyperparameters:**
  - Batch Size: 32
  - Block Size: 64
  - Max Iterations: 2000
  - Evaluation Interval: 100
  - Learning Rate: 1e3
  - Device: CUDA (if available), CPU otherwise
  - Evaluation Iterations: 200
  - Embedding Size (n_embd): 64
  - Number of Attention Heads (n_head): 4
  - Number of Layers (n_layer): 2
  - Dropout: 0.0
- **Length of Dataset in Characters:** 24870
- **Result:** 
  - 0.423499 M parameters
  - Training and validation loss values recorded at various steps

#### Generated Text Sample:
```
vata can of beth which accurater in lack the variable qualititive Speace, and veince your life—time. Dreflmenew in all they weater gable are ember.
Themparent, and everthron

Condittly, Andyperactives and

```

### 7. SEVENTH Instance
- **Hyperparameters:**
  - Batch Size: 16
  - Block Size: 32
  - Max Iterations: 5000
  - Evaluation Interval: 100
  - Learning Rate: 1e3
  - Device: CUDA (if available), CPU otherwise
  - Evaluation Iterations: 300
  - Embedding Size (n_embd): 264
  - Number of Attention Heads (n_head): 2
  - Number of Layers (n_layer): 2
  - Dropout: 0.2
- **Length of Dataset in Characters:** 24870
- **Result:** 
  - 3.404619 M parameters
  - Training and validation loss values recorded at various steps

#### Generated Text Sample:
```
vata differwe are they ofterwe will ou traks under affect on and kaphagenic. And the person maintaining this proportion various walk quickly and the vata and practical. It is the last phouge to jort of ph
```

## Conclusion
So in conclusion, after doing the seven different instances of a model by changing the hyperparameters and length of the dataset the seven itration is the best.

## Learnings

1)	Iterations show that importance of hyperparameters while traing a model. Varying parameters like batch size, block size, learning rate, embedding size, number of attention heads, number of layers, and dropout rate led to different outcomes.
2)	Adjusting the length of the dataset used for training also had an impact on the model's performance.
3)	Even though we have some numbers to show how the training went, like loss values, they don't tell us everything about how understandable, relevant, or accurate the text is.
4)	Finding the best setup for a task involves some experimenting. You need to balance how much computing power you use, how long it takes to train, and how well the model performs. Sometimes, even if you have access to powerful computers, you might not get coherent results due to limitations in computing power.

