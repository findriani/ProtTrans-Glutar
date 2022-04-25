# ProtTrans-Glutar

This GitHub repository contains all the materials for paper titled "ProtTrans-Glutar: Incorporating Features from Pre-trained Transformer-Based Models for Predicting Glutarylation Sites", Fatma Indriani, Kunti Robiatul Mahmudah, Bedy Purnama, Kenji Satou.

Dataset folder includes all features extracted using various encoding methods experimented in the paper, separated into train and test dataset:
- amino acid encoding (AAC)
- enhanced amino acid encoding (EAAC)
- Composition/Distribution/Transition (CTD) encoding
- pseudo-amino acid composition (PAAC)
- amphiphilic pseudo-amino acid composition (APAAC)
- ProtBert
- ProtBert-BFD
- ProtT5-XL-UniRef50
- ProtT5-XL-BFD
- ProtAlbert
- ProtXLNet

Code folder includes:
- Jupyter notebook demo to use our pretrained model for classification https://github.com/findriani/ProtTrans-Glutar/blob/main/codes/ProtTrans-Glutar.ipynb
- pretrained model using whole dataset: ProtTrans-Glutar.full.model
- pretrained model using only training data: ProtTrans-Glutar.train.model
