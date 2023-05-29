# polynomialRegression
# In this data i only have two columns usefull, so I take as X "level columns" and as y "salary column"
# Then I import "LinearRegression" and train my model "lin_reg.fit(X,Y)"
# Now I import "PolynomialFeatures" and set parameter of my "regressor at 4", default is 2, its specifies the maximal degree
# Next I train and transform my X and when I chave my "polynomial features" i can use "linear regression" and get "Polynomial Regression"
# I have X as polynomial feature and y trained by Linear Regression, I put this two features to my "lin_reg_2.fit(X_poly, Y)" 
# Now I can check difference between "Linear Regression" and "Polynomial Regression" by plotting them
# So first I plot "Linear Regression" using "matplotlib", into my "plt.scatter" I put X, y and set color at red 
# Then into my "plt.plot" i put X and X predicted my "Linear Regression"
