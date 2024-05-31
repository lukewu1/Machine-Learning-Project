# Purpose
In late 2017, a lawsuit was filed against the office of Cook County Assessor Joseph Berrios for producing "[racially discriminatory assessments and taxes](https://www.chicagotribune.com/politics/ct-cook-county-board-assessor-berrios-met-20170718-story.html)." The lawsuit included claims that the assessor's office undervalued high-priced homes and overvalued low-priced homes, creating a visible divide along racial lines: Wealthy homeowners, who were typically white, [paid less in property taxes](https://fix8media-chicago.squarespace.com/bpnc-v-berrios-resource-page), whereas [working-class, non-white homeowners paid more](https://www.chicagotribune.com/news/breaking/ct-cook-county-assessor-berrios-sued-met-20171214-story.html).

In the case of the Cook County Assessor’s Office, Chief Data Officer Rob Ross states that fair property tax rates are contingent on whether property values are assessed accurately - that they’re valued at what they’re worth, relative to properties with similar characteristics. This implies that having a more accurate model results in fairer assessments. The goal of the property assessment process for the CCAO, then, is to be as accurate as possible. 

# Project Description
This is a machine learning model that predicts housing prices in Cook County, Illinois.

In the first part of the notebook, I performed some basic exploratory data analysis (EDA), laying out the thought process that lead to certain modeling decisions. Then, I added a few new features to the dataset, cleaning the data as well in the process.

In the next part of the notebook,  I fit a linear model to a few features of the housing data to predict housing prices. 
I also analyzed the error of the model and brainstormed ways to improve the model's performance. 
Finally, I delved deeper into the implications of predictive modeling 
within the Cook County Assessor's Office (CCAO) case study, especially because statistical modeling is how the CCAO valuates properties. Given the history of racial discrimination 
in housing policy and property taxation in Cook County, I also considered the impacts of my modeling results - thinking about what fairness might mean to property owners in Cook County.

