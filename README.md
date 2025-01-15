# A SHAP-based method for Propaganda Detection
A Transformer-based model for propaganda detection from texts.

Replication for the paper:

### Micaela Bangerter, Giuseppe Fenza, Mariacristina Gallo, Vincenzo Loia, Alberto Volpe, Carmen De Maio, and Claudio Stanzione. 2023. Unisa at SemEval-2023 Task 3: A SHAP-based method for Propaganda Detection. In Proceedings of the 17th International Workshop on Semantic Evaluation (SemEval-2023), pages 885–891, Toronto, Canada. Association for Computational Linguistics.

avaialble at: 

https://aclanthology.org/2023.semeval-1.122/

contacts: 

gfenza at unisa dot it

# Description

The model is a Transformer network based on a DistilBERT pre-trained model. The pre-trained model is fine-tuned on the SemEval 2023 Task 3 training dataset for the propaganda detection task.
Hyperparameters :

Batch size = 16; Learning rate = 2e-5; AdamW optimizer; Epochs = 4.

Accuracy = 90 % on SemEval 2023 test set.

The model is avaialable on Huggingface: https://huggingface.co/IDA-SERICS/PropagandaDetection

# Acknowledgements

This work was partially supported by project SERICS (PE00000014) under the MUR National Recovery and Resilience Plan funded by the European Union - NextGenerationEU.
