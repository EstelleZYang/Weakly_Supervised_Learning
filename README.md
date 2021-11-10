# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2021

+ Team Group7
+ Team members
	+ Jing Lu (jl5886)
	+ Yuming Tu(yt2748)
	+ Wang, Ziyi (zw2732)
	+ Zhang, Zhuohan (zz2751)
	+ Zhao, Yang (yz4115)

+ Project summary: In this project, we will carry out model evaluation and selection for predictive analytics on an imbalanced image data. As data scientists, we often need to evaluate different modeling/analysis strategies and decide what is the best. Such decisions need to be supported by sound evidence in the form of model assessment, validation and comparison. In addition, we also need to communicate our decision and supporting evidence clearly and convincingly in an accessible fashion. We will be dealing with a classification problem, where the training labels are not perfect. This is a common phenomenon in data science. Getting accurate ground true labels can be costly and time-consuming. Sometimes, it is even impossible. The weakly supervised learning is a subject that addresses the issue with imperfect labels. In particular, we are going to train a predictive model where label noises exist.
	
**Contribution statement**: 
 ***Yuming Tu***: data loading and model 1 construction. ***Zhuohan Zhang***: Implemented Model1 and Model 2 and tuned both models.  Contributed to Main.pdf. ***Jing Lu***: Implemented model 1 and Help other debugs and explain the details of model 1. Build model 2 and optimize parameters and data sets. The model 2 final performance is not good. we chose Zhuohan model 2.***Yang Zhao*** participated in the implement of model 2, literature review and group discussions. ***Ziyi Wang***:help develop and run model I for noisy label and develop data pipeline for building models on Google Colab, increasing the upload and model speed. Research and propose ideas for label correction model, facilitating teammates to implement code. All team members approve our work presented in this GitHub repository including this contributions statement. 

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
