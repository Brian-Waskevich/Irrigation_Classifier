### Irrigation Classifier

**Brian Waskevich**

#### Executive summary
Using basic observations of the weather, a classification model can be created to inform a farmer whether or not irrigation will be needed, or if natural rainfall will be sufficient.

#### Rationale
Artificial irrigation is a large expense for agriculture. By creating a model to classify whether irrigation is necessary, it can lower costs by reducing the amount of unnecessary irrigation, or even damages from over-irrigation.

#### Research Question
Create a precipitation prediction model that can inform a farmer if man-made irrigation will be necessary in a given time window.

#### Data Sources
https://www.ncei.noaa.gov/access/past-weather/ohare
Data is selected for O'Hare International Airport from October 9th, 1946 through June 22nd, 2025

#### Methodology
This problem will use classification algorithms to determine a binary classification of whether or not artificial irrigation is needed. Possible algorithms include Logistic Regression, KNN, SVM, Decision Trees, as well as ensemble models that combine multiple classifiers. Loss function will be Mean Squared Error.

#### Results
Based on initial findings, even with very basic classification models, they perform exceptionally well. A Logistic Regression classifier with default hyperparameters has an accuracy score of 98-100%, depending on the split of training and testing data.

#### Next steps
Next steps include cross-validating multiple different hyperparameter values to further optimize the classifier, as well as explore more sophisticated classification models. An ensemble model can be created to minimize any weaknesses of an individual model.

#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
Brian Waskevich - b.waskevich@gmail.com