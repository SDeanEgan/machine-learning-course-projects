# Machine Learning Course Projects


### Project 1: Obesity Dataset Classification Exploration

This first project attempts to explore and understand Machine Learning classification techniques using a multiclass dataset. A number of machine learning concepts are discussed, and a variety of classification models are used and analyzed. The goal of the project has been to maximize the performance of a variety of classifiers from sklearn. These are: Decision Trees, Random Forests, Gradient Boosted Trees, SVM, and KNN. The project also sought to learn the hyperparameter tuning tool GridsearchCV, feature selection, and evaluation metrics or model scoring.

  - Original Source: [Sinop University Obesity Dataset from Kaggle](https://www.kaggle.com/datasets/suleymansulak/obesity-dataset)
  - License details: [Creative Commons CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

The Sinop University Obesity Dataset was collected as a research project by Nigmet Koklu and Süleyman Alpaslan Sulak. The authors conducted an online survey in order to collect the observations available in the dataset with the intention of analyzing it through machine learning techniques. They have provided a single table in a Microsoft Excel format. This is provided directly under `data/Obesity_Dataset.xlsx` thanks to the CC BY-NC-SA 4.0 license included on kaggle.

### Project 2: Titanic Dataset Unsupervised Methods Exploration

The second project is for unsupervised Machine Learning techniques using a dataset, sourced from kaggle, which collects information about passengers aboard the RMS Titanic ocean liner. A number of machine learning concepts are discussed. This includes the use of matrix factorization techniques for transforming the data and multiple clustering models, as well as methods of analysing clustering performance. The goal has been to develop multiple representations of the dataset and to interpret clustering behavior changes via those transformations using visual analysis, clustering metrics, and ground truth. Transformation methods include Singular Value Decomposition, and Nonnegative Matrix Factorization dimension reductions. Clustering methods will include Heirarchical (agglomerative), K-means, Gaussian Mixture, and Spectral Clustering models. A pipeline is constructed to streamline the process of hyperparameter selection and results analysis.

  - Original Source: [The Complete Titanic Dataset from Kaggle](https://www.kaggle.com/datasets/vinicius150987/titanic3)

To access The Complete Titanic Dataset visit the above kaggle link, where it has been provided by Vinicius Barbosa Paiva. A direct copy was left out of the repository as license is not provided. Running any code cells of the notebook will require downloading the `titanic.xls` file and storing it in the respective `data` folder.

### Project 3: Image Classification Exploration Through Neural Networks

The third project builds neural networks for image classification using the CIFAR-10 dataset, provided through the University of Toronto. Some time is spent examining image preprocessing and discussing effective methods to perform this. Afterward, the project describes the two major network types chosen; namely, the Convolutional Neural Network and the Vision Transformer. The Hyperband tuner from the keras tuner package is used to perform hyperparameter search, and some experiences from the project's results and inter-model performance is explored.

  - Original Source: [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)

The CIFAR-10 dataset is a well known image dataset of sixty thousand 32 x 32 color images containing ten different classes. Originating from the Canadian Institute for Advanced Research (CIFAR) it was introduced by Alex Krizhevsky and other CIFAR collaborators in 2009. To use the code yourself [the python specific version can be downloaded and unpacked into the `data` directory for the project](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz). 
