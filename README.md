CS598 Final Project - Molecular Property Prediction
-
   Drug discovery could take a lengthy process that usually takes more than 5 years, and it is costly as well with billions of dollars on bills [1]. There are a few research tasks under drug discovery, the first one is molecular property prediction task which the input is a drug molecule and the output is the drug’s properties. The second task is drug reposition with the input of drug proteins and molecules, and deep learning (DL) model predicts the affinity score, and the third task is drug-drug interaction with the input of different drugs and we want to predict the interactions between two drugs by deep learning. The lab will test drug-drug. The fourth one is de novo design which is the reversion of molecular property prediction [2].

System Structure
-
    .
    ├── archive                                     # Old version models
    │     ├── GAN1.ipynb
    │     ├── GAN2.ipynb
    │     ├── GAN3.ipynb
    │     ├── GAN4.ipynb
    │     ├── GAN5.ipynb
    │     ├── GAN6.ipynb
    │     ├── GAN7_nlp.ipnyb
    │     ├── GAN8.ipynb
    │     ├── GAN10.ipynb
    │     ├── GAN11_good.ipynb
    │     ├── GAN12Good.ipynb
    │     ├── GAN13.ipynb
    │     ├── GAN14.ipynb
    │     ├── GAN15.ipynb
    │     ├── GAN15Pending_labelupdate.ipynb
    │     ├── GAN16_nopass.ipynb
    │     ├── GAN17.ipynb
    │     ├── GAN18.ipynb
    │     ├── GAN18_good.ipynb
    │     ├── GAN19.ipynb
    │     ├── GAN20_bigdataset.ipynb
    │     └── GAN20b_bigdataset.ipynb                         
    │
    ├── dataset                                     # dataset folder
    │     └── qm9.csv                               # qm9 dataset
    │
    │
    ├─ GAN19_Baseline.ipynb                         # GAN19 Baseline model by qm9 dataset
    ├─ GAN19_Model1.ipynb                           # GAN19 model 1 by qm9 dataset
    ├─ GAN19_Model2.ipynb                           # GAN19 model 2 by qm9 dataset
    ├─ GAN19_Model3.ipynb                           # GAN19 model 3 by qm9 dataset
    ├─ GAN19_Model4.ipynb                           # GAN19 model 4 by qm9 dataset
    ├─ GAN19_Model5.ipynb                           # GAN19 model 5 by qm9 dataset
    ├─ GAN19_Model6.ipynb                           # GAN19 model 6 by qm9 dataset
    ├─ GAN19_Model7.ipynb                           # GAN19 model 7 by qm9 dataset
    ├─ GAN19_Model8.ipynb                           # GAN19 model 8 by qm9 dataset
    ├─ LICENSE                                      # project license file
    └─ README.md                                    # this file

Version
-
1.0.0.0

Team Member
-
Zhouning Ma

NetID
-
ZM11

License
-
Apache License

Reference
-
[1] J. Li, R. Topaloglu and S. Ghosh, "Quantum Generative Models for Small Molecule," p. 1, 2021. 
[2] Vivian Hu  Project Topic B: Deep learning in Drug Discovery  https://piazza.com/class/kjyow0m1rkd7mf?cid=522
