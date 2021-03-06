##### When working on your data science project, consider the following guidelines as best practices.

### Part One

<details>
  <summary><strong>Proposal Requirements :notebook:</strong></summary>

> 1. Project Name: Title for your project 
> 2. Problem Statement: What are you trying to solve?
> 2. Data science Hypothesis(es)/solutions considering: One or multiple angles to consider solving this problem with data science  
> 3. Data sets to be used: Share the links and files, .csvs, .js, .xlsx, .txt, website URLs
> 4. Data dictionaries to describe the data types you're using: write these out in markdown as tables  
> 5. Potential business cases relative to project: how would this help businesses out to make money or save money or improve accuracy or make better products
> 6. Potential stakeholders who would find this interesting: who would be your ideal customer or client for this?
> 7. Potential places to share your results post project (client, world, website, blog)

**Deliverables:**
> 1. To be pushed to github
> 2. To be submitted as a markdown readme.md file in your project-final repository
</details>


### Part Two
<details>
  <summary><strong>EDA Guidelines :bar_chart:</strong></summary>

> 1. To create a Jupyter .ipynb notebook for data analysis 
> 2. Import your data or data files and to save as dataframes 
> 3. Examine your data, columns and rows and rename and adjust indexing and encoding as appropriate 
> 4. Clean null and blank values, and consider to drop rows, as well as to manipulate data and adjust data types as appropriate, including dates and time, or setting appropriate indices. Adjusting specific values and replacing strings and characters for the data wrangling process.  
> 5. Explore analysis with graphing and visualizations with matplotlib and seaborn and alternative visualization packages (Plotly, bokeh, altair, vincent)
> 6. Perform additional analysis by creating new columns for calculations, including aggregator functions, counts and groupbys.
> 7. Encode categorical variables with a variety of techniques through logical conditions, mapping, applying, where clauses, dummy variables, and one hot encoding 
> 8. Re-run calculations, including crosstabs or pivots, and new graphs to see results 
> 9. Create correlation matrices, pairplots, scatterplot matrices, and heatmaps to determine which attributes should be features for your models and which attributes should not 
> 10. Identify the response variables(s) that you would want to predict/classify/interpret with data science 
> 11. Perform additional feature engineering as necessary, including Min/Max, Normalizaton, Scaling, and additional Pipeline changes that may be beneficial or helpful when you run machine learning 
> 12. Merge or concatenate datasets if you have not already, based on common keys or unique items for more in-depth analysis 
> 13. Add commenting and markdown throughout the jupyter notebook to explain the interpretation of your results or to comment on code that may not be human readable, and help you recall for you what you are referencing.  
> 14. To create a markdown .md milestone report that shows and explains the results of what you have accomplished to date in this part of your course project. Consider also creating a .pdf or .pptx to display initial results, aha moments, or findings that would be novel or fascinating for your final presentations. 
</details>

### Part Three
<details>
  <summary><strong>Machine Learning Guidelines :computer:</strong></summary>
  
> 0. Create a brand new Jupyter notebook, where you run the latest DataFrame or .csv files(s) that you have previously saved from your exploratory data analysis notebook. 
> 1. After you have completed the exploratory data analysis section of your project, start revisiting your hypothesis(es) on ideas that you would like to either predict (regression) or classify (classifier).  > 2. Have you identified a specific column or multiple columns that could be treated as response or target variables to predict/classify?
> 3. If not, consider performing additional exploratory analysis that helps you pinpoint a potential working hypothesis to test results against. You could consider clustering as an addition to exploratory data analysis as a preparation for machine learning.
> 4. Consider for your machine learning what parts of your feature engineering have been completed, or need to additionally be completed through Pipeline operations such as Normalize, Scaler, Min/Max, etc. 
> 5. As a result of correlation matrices, heatmaps, and visualizations, consider which features may be relevant to support the model that you are building. 
> 6. Consider what machine learning models could be effective for your newly discovered hypothesis (linear regression, logistic regression, KNearest Neighbors, Clustering (http://scikit-learn.org/stable/modules/clustering.html), Decision Tree, Random Forest, Time Series Analysis, Neural Networks, Support Vector Machines,  dimensionality reduction with PCA).  Once you have determined models to consider, be sure to import their packages into Python.
> 7. Consider what tuning parameters you may want to optimize for your model, including regularization (Lasso, ridge, ElasticNet), and additional parameters relevant to each model.
> 8.  Be sure to include a train_test_split, and then consider a KFolds or Cross Validations to offer stratified results that limit the interpretation of outliers for your dataset.
> 9. If you still have many outliers, consider how to remove them or optimize for them with categories.  How could you adjust your categories, or thresholds to improve performance for what you are testing for your hypothesis? Depending on how your model error performs, you may want to consider to change or adjust other features in your model.  You may want to consider to add or remove features, and measure the feature importance when running models. 
> 10.  Consider a Grid Search or Random Search to better optimize your models. 
> 11.  Share metrics on each model that is run, such as error and accuracy, confusion matrices, and the ROC/AUC scores.  Other models have additional metrics, that you can consider to share.  You can set up metrics and running models in defined functions for further automation of your project. 
> 12. Compare your metrics against the base case or null case for accuracy, which ideally is compared to your majority class, or a median/mean representation for your target/response variable.  How well does your model perform?
> 13. Provide markdown explaining the interpretation relevant to your business case after running models.  Also, share comments to explain what you are doing, for your interpretation and then reproducibility of your code. 
> 14.  If you are running Time Series Analysis, you will want to consider additional model capabilities such as rolling and moving averages with the dateTime package and pandas.
> 15.  If you are working on Natural Language processing, you will want to consider python packages such as Spacy, NLTK, TextBlob.
> 16. If you are scraping additional data, consider python packages such as Selenium and BeautifulSoup4.
> 17.  For your project, your presentation will showcase the best 3-5 models.  However, it is fine if you have inefficient models that do not perform well, for practice, so keep these in your main modeling Jupyter notebook as a reference. 
</details>

## Licenses
License

[![CC-4.0-by-nc-nd](https://licensebuttons.net/l/by-nc-nd/3.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

To the extent possible under law, [David Yakobovitch](http://davidyakobovitch.com/) has licensed this work under Creative Commons, 4.0-NC-ND.  This [license](https://creativecommons.org/licenses/by-nc-nd/4.0/) is the most restrictive of Creative Commons six main licenses, only allowing others to download your works and share them with others as long as they credit the author, but they can’t change them in any way or use them commercially.
