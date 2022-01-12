# Problem Statement 
The Prostate Cancer Classification task simply asks for a predictive model which, given the data, successfully suggests if a particular case is cancerous or not. An effective model can help speed up the process of cancer detection and can help provide almost accurate preliminary results.

## Dataset

The dataset used is the [Prostate Cancer Classification](https://www.kaggle.com/sajidsaifi/prostate-cancer) from (Kaggle). This is the dataset of 100 patients to implement the machine learning algorithm and thereby interpreting results. The data set consists of 100 observations and 10 variables (out of which 8 numeric variables and a categorical variable and an ID):

0. Id
1. Radius
2. Texture
3. Perimeter
4. Area
5. Smoothness
6. Compactness
7. diagnosis_result
8. Symmetry
9. Fractal dimension

The class labels are:
<br>

**1. M:** Malicious. May be cancerous.
<br>
**2. B:** Benign. May not be cancerous.


## Models Used

**1. K Nearest Neighbours:** This model is most useful in data which can be linearly separated. It simply finds the "K nearest neighbours" and uses the hoghest class occurence as the final class preidction.

**2. Support Vector Classifier:** This model is also very useful when the data is linearly separable. Although, SVMs are capable of projecting the data into greater dimensions to find out better patterns.

**3. Decision Tree Classifier:** This model identifies the most informative attribute at every level and uses it to make a tree. The final tree can then be used as a simple if-else statement to identify the final prediction.

## Future Work
1. We can perform Hyperparameter Tuning on the models used to find out how much the accuracy can be improved.
2. We can try using Neural Networks.
3. We can perform regression instead of classification to get the probabilities. Once we have them, we can set a threshold suggesting the classes more appropriately.
