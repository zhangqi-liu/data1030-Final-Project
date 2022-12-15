# data1030-Final-Project

Briefly described, the dataset utilized considers work-related measures concerning
staff who leave the service, and our target of this project is to understand the overall
situation of employee attrition and distinguish the reasons behind it. Furthermore,
prediction of whether an employee will leave could then be made based on his
information.

Starting with Exploratory Data Analysis, variables with zero variance, null and
duplicate values were checked to do a preliminary data processing. At the same
time, Univariate and bivariate analysis were conducted to help us gain primary insight
of the data. We then detected high correlations to tackle the multicollinearity
problem.

Finally, our optimal model was determined based F1 score as the
metrics,  Gradien Bossting has highest F1-score (58%). We then
identified some more significant factors like monthly income, age, and overtime that
affect people’s decision on attrition, and according to these results, a clearer picture
of the reasons behind attrition was gained, and further discussion like strategic plans
for companies were made.


Python 3.9.12

Package Verison:
_py-xgboost-mutex         2.0                       cpu_0    conda-forge

matplotlib                3.5.2           py310h2ec42d9_1    conda-forge

pandas                    1.4.2           py310h3099161_2    conda-forge

pip                       22.2.2             pyhd8ed1ab_0    conda-forge

plotly                    5.8.0              pyhd8ed1ab_1    conda-forge

pure_eval                 0.2.2              pyhd8ed1ab_0    conda-forge

py-xgboost                1.5.1           cpu_py310h22f808f_2    conda-forge

python                    3.10.5          hdaaf3db_0_cpython    conda-forge

scikit-learn              1.1.1           py310hfc06b38_0    conda-forge

scipy                     1.9.1           py310h240c617_0    conda-forge

seaborn                   0.12.0                   pypi_0    pypi

shap                      0.41.0                   pypi_0    pypi

xgboost                   1.5.1           cpu_py310hce1aae2_2    conda-forge


