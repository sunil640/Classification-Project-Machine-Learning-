Hello Everyone,

About data:-

The Sloan Digital Sky Survey or SDSS is a multi-spectral image map using at Apache Point Observatory in New Mexico. It is the most detailed three-dimensional map of the universe ever made, with multi-color images of one third of the sky, and spectra for more than three million astronomical objects.
Data used in this project are results from a query which joins two tables: PhotoObj, which contains photometric data, and SpecObj, which contains spectral data. Data is retrieved from SkyServer SQL Search.


Goals & Target:-

Here in the project I'm trying to do the classification of different star, galaxies, quasars on sky-server data set, with the help of different machine learning classification model & EDA, preprocessing, & visualization of data is also done, where ever needed in this project. KNN model & Logistic regression are giving maximum accuracy.

Libraries used - Python,Pandas,Numpy,Sklearn,Seaborn,Matplotlib etc.

Model Used - DecisionTreeClassifier,RandomForestClassifier,KNeighborsClassifier,LogisticRegression etc.

Evalutaion - classification_report, confusion_matrix,accuracy_score etc.

Steps involved to acchive target:-

1. imported of all required libraries & models.

2. loaded data set(photometric data).

3. EDA & Precocessing done using Numpy and Pandas for feature selection and handling the missing or null values

4. highly correlated fetures are droped,for taking only uniques and important fetures for model creation.

5. Visualization of data done using diffrent plot like- Box plot,Bar plot,scatter plot etc.

6. Data set are seprated in two for training the model and testing the model perfomace.

7. Diffrent classification models are trained on training data set perfomace of all those model checked on testing dataset.

8. Some models performed very well and hyperparamters of model tunned for acciveing maximum accuracy.

9. Evaluation of all models cheked using evaluation metrix, accuracy_score,classification report.
