# ECE8803_Term_Proj

To work with this project, navigate to the src folder and explore the two IPython notebooks. Each notebook caontains the classifiers training, testing and evaluation. 

To run the code segments locally, a copy of the Prime_DF data is required. This can be downloaded and store outside the repository and the path to these images can be set in the notebook.

## GMM

The Gausian Mixture Models are directly after the data loader and eploration portion of the gmm_nb_Project_ECE8803.ipynb Notebook. Each GMM test set uses a featureset calculated directly before training. The testing and prediction occurs directly after training and is followed by analysis. 

## NB

The Naive Bayes classifiers are at the end of the gmm_nb_Project_ECE8803.ipynb file. These classifiers use the same data from the GMM, so they were not recalculated. Similar testing analysis occurs for this portion of the Notebook as in the GMM portion.

## SVM

The SVM classifiers are after the dataloader and data processing in SVM.ipynb. Since each SVM training take a lot of time, train and test can't be done at he same time. We save the model after trainin and load i back in next pace-ice working session. The testing and prediction occurs directly after training and is followed by analysis.

## ResNet18

The ResNet18 classifiers are after the dataloader and data processing in ResNet18.ipynb. The testing and prediction occurs directly after training and is followed by analysis. 