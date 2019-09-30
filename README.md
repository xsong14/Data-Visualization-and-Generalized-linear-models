# Data-Visualization-and-Generalized-linear-models
This project have various perspective of analysis. The two main analytics tools used are data visualizations and logistic regression analysis
## Visualizations
The dataset behind the visualizations reflects reported incidents of crime (with the exception of
murders where data exists for each victim) that occurred in the City of Chicago from 2001 to
2018. Data is extracted from the Chicago Police Department's Citizen Law Enforcement
Analysis and Reporting system. The data set contains mainly descriptive variables from initial
police reports of crimes in Chicago, no numerical data existed in the dataset. A count of the
number of records for the categorical variables was primarily used for quantitative visualization.

However, the true and false variables were transformed to binary numerical values in order to
visualize the dataset. The records can be based on unverified preliminary information supplied
to the Police Department by the reporting parties. The preliminary crime classifications may be
changed at a later date based upon additional investigation and there is always the possibility
of mechanical or human error.
I joined shape files provided by the Chicago government to map crime location data to police
districts for a more granular visualization purpose. I used both police district, and city street
shapefiles.
## Logistic Regression Models
This project was an investigation of the relationship between the rate of violent crime and the related factors.  
Using the same data for visualizations which contains incidents of crime since 2001 made available by the city of Chicago, I implemented a logistic regression predictive model to determine what kinds of factors influences violent crime occurrences.
I used the primary crime type to determine if it was a violent crime. The next step was to move forward with a logistic regression model, since the dependent variable is dichotomous. Additionally, I needed to create other binary variables to define some qualitative variables, such as the arrest variable or defining the type of crime as a binary variable. 

I explored several model selection methods like forward selection, backwards selection, and stepwise, to identify the parameters for the model. Since I chose a logistic regression model, I had to make sure none of the independent variables displayed any multicollinearity issues or had any outliers. I determined goodness of fit by examining a likelihood ratio test which will compare the log likelihood of my fitted model to the log likelihood for a similar model.
Once I’ve determined the goodness of fit, as well as removed any parameters causing multicollinearity, and identified influential points and outliers, I'm able to fit a final model and draw conclusions, and find the predicted probability value and confidence interval on dependent variables.
