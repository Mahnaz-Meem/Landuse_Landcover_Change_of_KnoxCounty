# Landuse and Land Cover Change of Knox County, Tennessee
- 📊 Geography Project
- 🗓 Date: 12 December 2023
- 👩🏽‍💻 Created by: Mahnaz Sarker Meem 👋🏼
- [Slides](https://www.canva.com/design/DAF2aLm3qyk/n-IPDU7sTY5LrmfAVzE7Ag/edit?utm_content=DAF2aLm3qyk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

![Timelapse](Visualization/timelapse.gif)

## Table of Contents
- [About](#about)
- [Technologies used](#technologies-used)
- [Process](#process)
- [Data](#dataset)
- [Visualization](#visualization)
- [Slides](#slides)


## About
Analyzing land use and land cover in specific locations like Knox County, Tennessee, is important to make important decisions for policy, understanding the growth and environmental impacts. I am using the NLCD data from 2001, 2004, 2006, 2008, 2011, 2016, 2019, and 2021. The USGS, in partnership with several federal agencies, developed and released NLCD products in two-to-three-year intervals between 2001 and 2021. These products provide spatially explicit, multi-temporal, consistent, and reliable information on the Nation’s land use and land cover change.


## Technologies used
* Python (Geemap, pandas, numpy, matplotlib)
* Canva
* Google Colab
* Microsoft Office

## Process
* Github and Trello: Created a Github repo and trello board for sharing and keeping the project organized and safe.
* SQL: Used MySQL for answering  some business question.
* EDA: Assessed the dataset for cleaning and explored them using Sweetviz, Seaborn, Matplotlib and ArcGIS pro.
* Data cleaning and wrangling: Used date of building, sold and renovation to consider the age and renovation. Considered duplicated houses and dropped them keeping the latest one and dropped the one house with 33 bathrooms because it did not make sense considering the other given features.
* Preprocessing: Normalized the data using Standard Scaler. Used Grid Search CV to identify the best parameters for models.
* Machine Learning: Trained automated machine learning models and corresponding R2 for them. The models are: Linear Regression, SGD model, K Neighbours Regressor, Decision Tree Regressor, and Random Forest Regressor. Based on the R2 of the train and test sets "Random Forest Regressor" has been chosen for the final prediction.
* Streamlit: Used stremlit app to give price prediction for any given feature values.
* Canva: Used Canva for presentation preparation.

## Data
- The data is available [here](https://developers.google.com/earth-engine/datasets/catalog/USGS_NLCD_RELEASES_2021_REL_NLCD)

## Visualization
The special visualizations are depicted in the slides.

Please click on the link to open, visualize and interact with the Google Colab. You need to copy the notebook in your own google drive.

[Link](https://colab.research.google.com/drive/1AGVE9OjMVWLqlxJ5G2PoGolDbeNRdYUp?usp=sharing)


## Slides
Please click on the link to visualize the Canva presentation.
[Link](https://www.canva.com/design/DAF2aLm3qyk/n-IPDU7sTY5LrmfAVzE7Ag/edit?utm_content=DAF2aLm3qyk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)