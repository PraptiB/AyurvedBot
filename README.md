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
According to three dose? Undertannelst to mained day influences with V, feeling and threealing use that will thoughts and selunctioning of your seestantly help vata, the core complical inthan of or the sunal enech, whult and the joints, your mores diet, self-regulause plents
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
vata is deferls change exceive excetics staged. Diet is dities stage, the relation of balance, and not discopting and that they wide or moder in un our health the norrmaction
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
vata individuals them. Pro1ries a long if nature. If thie stages structural. Ayurvedic helps to partienge of the body, cracter fear, and corredless, what hate, start. Then ama, stark and relation. Regus a
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
vata is the underlying causing the bodientify to change in certain behavior, because it is this air elements. The appropra"
```

### 6. SIXTH Instance
- **Hyperparameters:**
  - Batch Size: 16
  - Block Size: 32
  - Max Iterations: 5000
  - Evaluation Interval: 100
  - Learning Rate: 1e3
  - Device: CUDA (if available), CPU otherwise
  - Evaluation Iterations: 300
  - Embedding Size (n_embd): 256
  - Number of Attention Heads (n_head): 4
  - Number of Layers (n_layer): 2
  - Dropout: 0.1
- **Length of Dataset in Characters:** 33398
- **Result:** 
  - 2.048098 M parameters
  - Training and validation loss values recorded at various steps

#### Generated Text Sample:
```
vata in the body is one of the moon and the body and they are change by the fire element, which is called kapha, and they are the body. The body and the body and the body and the body and the body and the body
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
  - Embedding Size (n_embd): 300
  - Number of Attention Heads (n_head): 2
  - Number of Layers (n_layer): 2
  - Dropout: 0.1
- **Length of Dataset in Characters:** 33398
- **Result:** 
  - 2.057142 M parameters
  - Training and validation loss values recorded at various steps

#### Generated Text Sample:
```
vata is a person who is the body and the body is the body and the body is the body and the body is the body and the body is the body and the body is the body and the body is the body and the body is the body
```

## Conclusion
The seven instances of the model trained on the Ayurvedic dataset showcase variations in hyperparameters, resulting in models with different numbers of parameters and performances. Further fine-tuning and experimentation may be necessary to optimize performance for specific tasks.
