CS598 Final Project - Molecular Property Prediction
-
Traditional drug discovery takes long time (usually 5 to 10 years) and spends billion dollars on it, and there are four drug discovery task under drug discoery[1]:
* Molecular Property Prediction:
  molecule and the ouput is predict the drug's properties.

* Drug Reposition:
  input is drug molecules and proteins, DL model will predict the affinity score.

* Drug-Drug Interaction:
  input is two different drugs and we want to utilize DL model to predict the interactions between them. Experts will test differenct drug-drug before the drug to release.

* De Novo Design:
  reverse of Molecular Property Prediction.

Deep learning usually can help the first two tasks: Molecular Property Prediction and Drug Reposition. Because there are some limitations (such as time ) for the final project, we will only focus on one task: Molecular Property Prediction.

We develop Molecular Property Prediction by a Generative Adversarial Networks (GAN).

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
    │     ├── qm8.csv                               # qm8 dataset
    │     └── qm9.csv                               # qm9 dataset
    │
    ├── log                                         # train model log
    │     ├── 2021041710                            
    │     ├── 2021041712                       
    │     ├── 2021041715                                  
    │     ├── 2021041719_63                             
    │     ├── 2021041723_40                         
    │     ├── 2021041807_52                         
    │     ├── 2021041907_58                   
    │     └── 2021041909_38                        
    │
    ├─ GAN19.ipynb                                  # !!!Paper demo model, check this one!!!
    ├─ GAN20_bigdataset.ipynb                       # The model training by big data
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
[1] Vivian Hu  Project Topic B: Deep learning in Drug Discovery  https://piazza.com/class/kjyow0m1rkd7mf?cid=522
