* Business Case Assessment

You have already conducted a business case assessment, so you can also use that information to build your project README file.

    What are the business requirements?
        The client is interested in discovering how house attributes correlate with sale prices. Therefore, the client expects data visualizations of the correlated variables against the sale price.
        The client is interested in predicting the house sale prices from her 4 inherited houses, and any other house in Ames, Iowa.
    Is there any business requirement that can be answered with conventional data analysis?
        Yes, we can use conventional data analysis to investigate how house attributes are correlated with the sale prices.
    Does the client need a dashboard or an API endpoint?
        The client needs a dashboard
    What does the client consider as a successful project outcome?
        A study showing the most relevant variables correlated to sale price.
        Also, a capability to predict the sale price for the 4 inherited houses, as well as any other house in Ames, Iowa.
    Can you break down the project into Epics and User Stories?
        Information gathering and data collection.
        Data visualization, cleaning, and preparation.
        Model training, optimization and validation.
        Dashboard planning, designing, and development.
        Dashboard deployment and release.
    Ethical or Privacy concerns?
        No. The client found a public dataset.
    Does the data suggest a particular model?
        The data suggests a regressor where the target is the sale price.
    What are the model's inputs and intended outputs?
        The inputs are house attribute information and the output is the predicted sale price.
    What are the criteria for the performance goal of the predictions?
        We agreed with the client an R2 score of at least 0.75 on the train set as well as on the test set.
    How will the client benefit?
        The client will maximize the sales price for the inherited properties.

Project Considerations

In case you want to use a spreadsheet to list your variables for the data-cleaning and feature-engineering steps, you may download the template in this link. This file will not be assessed and it will not be as part of your final grade; it is just an auxiliary file you can use in your workflow.

In this file, you should list the names of the variables.
Business Requirement 1

    You may perform a correlation and/or PPS study to investigate the most relevant variables correlated to the sale price.
    You have to visualize these variables against the sale price, so you can summarize the insights.

Business Requirement 2

    You may deliver an ML system that is capable of reliably predicting the summed sales price of the 4 inherited houses.
    You may use either conventional ML or Neural Networks to map the relationships between the features and the target.
    You may consider changing the ML task from Regression to Classification if you find a valid rationale for that.
    In case you are modelling using conventional ML, with packages like scikit-learn for example, you may conduct an extensive hyperparameter optimization for a given algorithm. You can refer back to the Scikit-learn lesson, Unit Notebook 6: Cross-Validation Search Part 2. At the end of the notebook, you will find a list of hyperparameter options and values to start with, for the family of algorithms we covered in the course.

Dashboard Expectations

Your dashboard should contain:

    A project summary page, showing the project dataset summary and the client's requirements.
    A page listing your findings related to which features have the strongest correlation to the house sale price.
    A page displaying the 4 houses' attributes and their respective predicted sale price. It should display a message informing the summed predicted price for all 4 inherited houses. You should add interactive input widgets that allow a user to provide real-time house data to predict the sale price.
    A page indicating your project hypothesis(es) and how you validated it across the project.
    A technical page displaying your model performance. If you deployed an ML pipeline, you have to display your pipeline steps.

    
