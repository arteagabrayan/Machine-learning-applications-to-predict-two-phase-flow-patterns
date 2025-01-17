# Machine learning applications to predict two-phase flow patterns

Recent advances in artificial intelligence with traditional machine learning algorithms and deep learning architectures solve complex classification problems. This work presents the performance of different artificial intelligence models to classify two-phase flow patterns, showing the best alternatives for this specific classification problem using two-phase flow regimes (liquid and gas) in pipes. Flow patterns are affected by physical variables such as superficial velocity, viscosity, density, and superficial tension. They also depend on the construction characteristics of the pipe, such as the angle of inclination and the diameter. We selected 12 databases (9,029 samples) to train and test machine learning models, considering these variables that influence the flow patterns. The primary dataset is Shoham (1982), containing 5,675 samples with six different flow patterns. An extensive set of metrics validated the results obtained. The most relevant characteristics for training the models using Shoham (1982) dataset are gas and liquid superficial velocities, angle of inclination, and diameter. Regarding the algorithms, the Extra Trees model classifies the flow patterns with the highest degree of fidelity, achieving an accuracy of 98.8%. 

## Folders

- **12 DB** In this folder, you will find all algorithms and implementations with the '12 DB' dataset. Please see the associated paper. 
- **Databases** This folder contain the databases files for Shoham and '12 DB' for 6, 5, and 3 classes.
- **FeatureSelection-DataDistribution-ROC_AUC_CI** This folder shows the feature selection process, data distribution, and ROC curves with the AUC, including the CI. 
- **Shoham** In this folder, you will find all algorithms and implementations with the Shoham (1982) dataset. Also, please see the associated paper. 

## Requirements
This repository requires the following libraries and frameworks:

- TensorFlow 
- Matplotlib
- Seaborn
- Scikit-learn
- Yellowbrick
- Bokeh
- NumPy
- Time
- Random
- OS
- XGBoost

This repository was developed in the Python 3 (3.8) programming language.

## Package installation

If you don't use google colab, We highly recommend to use and install Python packages within an Anaconda enviroment. To create, execute the command below:
```
conda create --name MPF python=3.8
```
So, activate it
```
conda activate MPF 
```
Packages installation
```
pip install ipykernel
```
and display of enviroment in jupyther
```
python -m ipykernel install --user --name MPF --display-name "MPF"
```
installed the framework
```
conda install tensorflow-gpu
```
Now, install the libraries.
```
conda install -c conda-forge matplotlib
```
```
conda install -c anaconda seaborn
```
```
conda install -c anaconda scikit-learn
```
```
conda install -c districtdatalabs yellowbrick
```
```
pip install imbalanced-learn
```
```
conda install -c bokeh bokeh
```
```
conda install -c conda-forge xgboost
```
## Execution
After installing all the Requirements, you must clone the repository using.
```
git clone https://github.com/BioAITeam/Machine-learning-applications-to-predict-two-phase-flow-patterns.git
```
If you will use colab, upload the cloned folder to drive, then open the folder and run the notebook of your choice.

if you are going to use your computer, install:
```
conda install jupyter 
```
Enter the cloned folder, then enter the folder and run the notebook of your choice.

## Note 
Before running the notebook, please verify that the file paths are correct.
