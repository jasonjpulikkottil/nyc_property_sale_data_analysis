# NYC property sale data analysis
<p>
	<br />
	Models Used:
</p>
<p>
	1. Linear regression
	<br />
	Linear regression analysis predicts the value of one variable depending on the value of another.
	<br />
	The variable you wish to forecast is referred to as the dependent variable.
	<br />
	The variable you are using to forecast the value of the other variable is known as the independent variable.
</p>
<p>
	Results:
	<br />
	MSE: 0.26797398321223115
	<br />
	RMSE: 0.5176620357069187
	<br />
	R-square 0.45458337550857975
</p>
<p>
	2. Lasso regression
	<br />
	Lasso is a linear regression variant in which the model is penalised for the sum of absolute weight values.
	<br />
	As a result, the absolute values of weight will be lowered, and many will be zeros.
</p>
<p>
	Results:
	<br />
	MAE: 0.41064756068144653
	<br />
	MSE: 0.3577337239138058
	<br />
	RMSE: 0.5981084549760234
	<br />
	R-square 0.27189230154001
</p>
<p>
	3. Ridge regression
	<br />
	Ridge regression is a technique for estimating the coefficients of multiple-regression models where the variables are linearly independent but strongly linked.
	<br />
	It has been applied in a variety of domains such as econometrics, chemistry, and engineering.
</p>
<p>
	Results:
	<br />
	MAE: 0.338012270339426
	<br />
	MSE: 0.2679617375113761
	<br />
	RMSE: 0.5176502076802212
	<br />
	R-square 0.45460829960286997
</p>
<p>
	4. Elastic net regression
	<br />
	The elastic net is a regularised regression approach in statistics that linearly integrates the L1 and L2 penalties of the lasso and ridge methods for fitting linear or logistic regression models.
</p>
<p>
	Results:
	<br />
	MAE: 0.40879575916630645
	<br />
	MSE: 0.35543034925971345
	<br />
	RMSE: 0.5961797960847998
	<br />
	R-square 0.27658043884988903
</p>
<p>
	5. XGBoost regression
	<br />
	Extreme Gradient Boosting (XGBoost) is a scalable, distributed gradient-boosted decision tree (GBDT) machine learning framework.
	<br />
	It is the top machine learning package for regression, classification, and ranking tasks, and it supports parallel tree boosting.
</p>
<p>
	Results:
	<br />
	MAE: 0.2956385433985124
	<br />
	MSE: 0.20136431082607506
	<br />
	RMSE: 0.4487363489021979
	<br />
	R-square 0.5901563226874251
</p>
<p>
	6. LGBM regression
	<br />
	Light GBM is a high-performance gradient boosting framework based on the decision tree technique that may be used for ranking, classification, and a variety of other machine learning applications.
	<br />
	It splits the tree leaf-wise with the greatest fit since it is based on decision tree algorithms, unlike other boosting methods split the tree depth-wise or level-wise rather than leaf-wise.
	<br />
	So, while growing on the same leaf in Light GBM, the leaf-wise approach may minimise more loss than the level-wise technique, resulting in significantly superior accuracy than any of the existing.
	<br />
	boosting algorithms can seldom accomplish.
	<br />
	<br />
	Results:
	<br />
	MAE: 0.29492443887358166
	<br />
	MSE: 0.20390782497660231
	<br />
	RMSE: 0.45156154063051285
	<br />
	R-square 0.5849794212371525
	<br />
	<br />
	7. MLP regression
	<br />
	MLP The regressor trains iteratively because the partial derivatives of the loss function with respect to the model parameters are computed at each time step to update the parameters.
	<br />
	A regularisation component that decreases model parameters to prevent overfitting may also be introduced to the loss function.
	<br />
	<br />
	Results:
	<br />
	MAE: 0.40116117647733074
	<br />
	MSE: 0.33666917766568866
	<br />
	RMSE: 0.5802320033104764
	<br />
	R-square 0.3147656938498612
</p>
<p>
	8. KNN regression
	<br />
	KNN regression is a non-parametric approach that approximates the relationship between independent variables and continuous outcomes by averaging data in the same neighbourhood.
	<br />
	<br />
	Results:
	<br />
	MAE: 0.32470589409378403
	<br />
	MSE: 0.2376743073414717
	<br />
	RMSE: 0.4875185199984424
	<br />
	R-square 0.5162533433857429
</p>
<p>
	9. Decision tree regression
	<br />
	Decision tree uses a tree structure to develop regression or classification models.
	<br />
	It progressively divides a dataset into smaller and smaller sections while also developing an associated decision tree.
	<br />
	The end result is a tree containing leaf nodes and decision nodes.
	<br />
	<br />
	Results:
	<br />
	MAE: 0.3981848247374902
	<br />
	MSE: 0.36513100418452077
	<br />
	RMSE: 0.6042607087876232
	<br />
	R-square 0.2568363636937042
</p>
<p>
	Also Variables of importance is plotted.
</p>
