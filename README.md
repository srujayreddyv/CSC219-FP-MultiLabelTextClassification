# Multi Label Text Classification Using BERT

## Project Overview
This project aims at enhancing multi-label text classification using Transformer architectures. The focal point of this project is the BERT (Bidirectional Encoder Representations from Transformers) model. Our primary objective is to effectively capture label dependencies in multi-label text classification, an aspect often overlooked by traditional models.

### Key Features:
- Implementation of a range of models including classical ML, BiLSTM, CNN, MAGNET, and BERT.
- Specialized adaptation of the BERT model for multi-label classification.
- Extensive evaluation of model performance on the "Toxic Comment" dataset.

## Dataset
We utilized the "Toxic Comment Classification Challenge" dataset, which encompasses labels like Toxic, Severe Toxic, Obscene, Threat, Insult, and Identity Hate. This dataset is particularly suited for testing our model's capability in handling nuanced and complex label interdependencies.

## Methodology
- **Classical Machine Learning Models**: We began with traditional approaches in the initial implementation phase.
- **Deep Learning Models**: Progressing to more advanced models like BiLSTM, CNN, and MAGNET.
- **BERT Model**: We adapted BERT for multi-label classification, which included specialized preprocessing and evaluation methods.

## Results
The BERT model exhibited remarkable performance, surpassing other models with a high micro-average F1 score, lower hamming loss, and better accuracy. This demonstrates its capability in handling complex multi-label classification tasks.

## Future Work
We plan to explore using BERT with Graph Attention Networks for multi label text classification task.

## Acknowledgements
We thank the contributors of the "Toxic Comment Classification Challenge" dataset and acknowledge the use of various open-source libraries and resources that made this project possible.
