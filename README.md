### Project Title

**Author**

#### Executive summary



#### Rationale
Why should anyone care about this question?

A good model will help reduce the dependency on physically testing EVs and bring the expected information closer to design time. So manufacturers can test and validate different features in the design phase compared to building prototypes and testing physically. 

#### Research Question
What are you trying to answer?
Predicting EPA ranges of Electric cars based on features and data that impacts the range (battery size, drag coefficient, size of the car etc.)
A good model will help reduce the dependency on physically testing EVs and bring the expected information closer to design time. So manufacturers can test and validate different features in the design phase compared to building prototypes and testing physically. 

#### Data Sources

[First data source](https://afdc.energy.gov/vehicles/search/results?view_mode=grid&search_field=vehicle&search_dir=desc&per_page=8&current=true&ajax_count=18&fuel_id=41&category_id=27,25,29,9&all_manufacturers=y) for EV info.
Remainder of the information can be obtained through each manufacturers press releases and specification info.

#### Methodology
What methods are you using to answer the question?
I had originally thought of using Logistic Regression, KNN Classifierer, DecisionTree Classifier and SVM but those are all classifiers so had to pivot to using models that work with range of numbers like Linear Regression, SVR, Decision Tree Regressor, KNN Regressor. 

#### Results
What did your research find?
Based on the tested models Decision Tree Regressor seems to yield the best results. Using GridSearchCV the best hyperparameters are n_neighbors=  3, p = 1, weights = distance. Using the hyperparameters we can predict the EPA ranges of EVs with the provided features.

#### Next steps
What suggestions do you have for next steps?

#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information