# Project: Can you recognize the emotion from an image of a face? 
<img src="figs/CE.jpg" alt="Compound Emotions" width="500"/>
(Image source: https://www.pnas.org/content/111/15/E1454)

### [Full Project Description](doc/project3_desc.md)

Term: Fall 2020

+ Team 5
+ Team members
	+ Han, Xiangning xh2443@columbia.edu
	+ Liang, Rui rl2886@columbia.edu
	+ Segal, Yotam ys3114@columbia.edu
	+ Sun, Xiaoli xs2338@columbia.edu
	+ Wang, Shuyuan sw3449@columbia.edu
	+ Zhang, Xinyi xz2862@columbia.edu

+ Project summary: In this project, we created a classification engine for facial emotion recognition. We tested various models including: baseline Baseline Model (GBT), XGBoost, Random Forest, SVM, NN, CNN, VGG16（Transfer Learning), logistic (starter code), PCA+LDA and KNN. 

We decided that NN preforms best, even though we expected CNN to be the most appropriate model. Finally, we were able to improve the baseline model’s performance in all parameters (accuracy, AUC).


| Model      |Accuracy| Weighted Accuracy |  AUC    |Train Time|Test time| Link|
| ----------- | ----------- | ------    |------|------|------|------|
| Baseline Model (GBT)      | 0.78|0.70       |  0.79   |7.13 s|0.02 s| [GBT](https://github.com/TZstatsADS/Fall2020-Project3-group5/blob/master/doc/baseline_model_tuned.ipynb)|
| XGBoost   | 0.81|0.72       |  0.83|37.21 s |0.06 s |[XGBoost](https://github.com/TZstatsADS/Fall2020-Project3-group5/blob/master/doc/XGBoost_tuned_2.ipynb)|
| Random Forest | 0.80|0.58 | 0.81 |8.38 s |0.23 s |[Random Forest](https://github.com/TZstatsADS/Fall2020-Project3-group5/blob/master/doc/random_forest.ipynb) |
| SVM |0.66|0.71 |0.79|51.37 s |7.87 s |[SVM](https://github.com/TZstatsADS/Fall2020-Project3-group5/blob/master/doc/SVM.ipynb)|
|Neural Networks|0.81|0.73 | 0.83|110.419 s|0.3 s| [NN](https://github.com/TZstatsADS/Fall2020-Project3-group5/blob/master/doc/Neural_Network_train.ipynb)|
|CNN|0.52| 0.52 | 0.51 |278 s |25 s |[CNN](https://github.com/TZstatsADS/Fall2020-Project3-group5/blob/master/doc/CNN.ipynb)|
|KNN |0.76|0.50|0.51|73.33 s|15.2 s|[KNN](https://github.com/TZstatsADS/Fall2020-Project3-group5/blob/master/doc/KNN.ipynb)
|LDA|0.70|0.53|0.68|20.34 s|0.14 s|[LDA](https://github.com/TZstatsADS/Fall2020-Project3-group5/blob/master/doc/LDA%20with%20PCA.ipynb)
|LDA with PCA|0.72|0.59|0.8|0.02 s|0.02 s|[LDA with PCA](https://github.com/TZstatsADS/Fall2020-Project3-group5/blob/master/doc/LDA%20with%20PCA.ipynb)


	
**Contribution statement**: All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
