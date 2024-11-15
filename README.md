# NLP_Assignment_2
---
The code for tokenizer can be found <a href = 'https://github.com/PreyumKr/nlp_assignment2/blob/main/Tokenizer_Training.ipynb'>here</a> and code for model training can be found <a href='https://github.com/PreyumKr/nlp_assignment2/blob/main/NLP_A2_2_large_5Epoch.ipynb'>here</a> and the inference can be found <a href='https://github.com/PreyumKr/nlp_assignment2/blob/main/inference.ipynb'>here</a>.
---
## **Task 1: Tokenizer Training** 
- Curated 5 different samples of around 300k rows and size of 2.2 GB.
  
- Tried different types of tokenizers like *SentencePieceBPETokenizer, BertWordPieceTokenizer, ByteLevelBPETokenizer* and because of the most promising result of sentence piece tokenizer on *Marathi* dataset, went ahead and trained our curated samples with sentence piece tokenizer.
  
- The fertility score calculated is as follows :
  
| Tokenizer    | Fertility Score      | Dataset Size |
|--------------|----------------------|--------------|
| tokenizer1   | 1.0343142615270633   | 2.2 GB       |
| tokenizer2   | 1.0342307120504148   | 2.2 GB       |
| tokenizer3   | 1.0341533059176373   | 2.2 GB       |
| tokenizer4   | 1.0341987666622845   | 2.2 GB       |
| tokenizer5   | 1.0341545345864116   | 2.2 GB       |

## **Task 2: Model Training** 
- Selected llama as the base model. Utilized Xavier Initialization to reduce the size of the model.
- Selected tokenizer 3 and tokenized the data
- Utilized wandb to train the model efficiently.
- Perplexity is calculated after every 0.1 epoch.
- Model inference can be found <a href = 'https://github.com/PreyumKr/nlp_assignment2/blob/main/inference.ipynb'> here. </a>








## ***Individual Contribution***

**Manish, Eshwar, and Isha** - Curated five different samples and trained SentencePieceBPETokenizer, BertWordPieceTokenizer, ByteLevelBPETokenizer and went ahead with Sentence Piece because of the best results. Calculated fertility score for all the samples. Tokenized the dataset. 

**Mukul and Preyum** - Selected Llama model and reduced parameters. Trained reduces llama model with the trained tokenizer. Calculated training loss after every 100 steps and perplexity after every 0.1 epochs. 



