## PROJECT TITLE:
***

CUSTOMER CHURN PREDICTION FOR SYRIATEL


## DESCRIPTION:
***
SyriaTel, a telecommunications company, is facing a challenge with customers switching to competitors, resulting in revenue loss. The company seeks to tackle the issue of revenue loss by creating a model to predict customer churn. By analyzing the customer data, it will help the company gain insights and take action ,ultimately reducing the churn rate and improving business performance.

I did correlation to assess the relationship between the features and plotted a heatmap to visualize their relationships.

In the jupyter notebook file, an exploratory data analysis was conducted on the features , (logistic regression models & Decision Trees models) were plotted to  to be able to come up with concrete business recommendations.

I also found answers to my business problem and came up with areas for future improvement for the business.



## TOOLS AND TECHNOLOGIES USED:
***
#Data Analysis
 pandas 
 numpy 

# Data visualization
 seaborn 
 matplotlib

# Downloading images
IPython.display
# checks for multicollinearity
from statsmodels.stats.outliers_influence import variance_inflation_factor
# Modeling
from scipy import stats
from sklearn.preprocessing import LabelEncoder, StandardScaler, OneHotEncoder
from sklearn.model_selection import train_test_split
from sklearn.metrics import classification_report , confusion_matrix,accuracy_score,recall_score,ConfusionMatrixDisplay,roc_curve,roc_auc_score 
from sklearn.tree import DecisionTreeClassifier
from imblearn.over_sampling  import SMOTE
from sklearn.ensemble import RandomForestClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import GridSearchCV, StratifiedKFold,RandomizedSearchCV
from sklearn.compose import ColumnTransformer
from statsmodels.tools.tools import add_constant
from sklearn.pipeline import Pipeline



## DATASETS:
***

In this repo there is a CSV file (churn_analysis) that contains the data used in this project.



## ADDITIONAL RESOURCES

In this repo there are some additional images that have been used in the notebook.

## REPORT PDF:
***

There is also a report in the repo that is focused on the business problem.




