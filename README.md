# SpaceY Landing Prediction of Falcon 9_Project 
### Graduation Project of DEPI Initiative

SpaceX Falcon-9 Success Landing Prediction SpaceX has gained worldwide attention for a series of historic milestones. It is the only private company ever to return a spacecraft from low-earth orbit, which it first accomplished in December 2010. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars whereas other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

# Summary of methodologies
###### > Data Collection using SpaceX API
###### > Data Collection with Web Scraping
###### > Data Wrangling
###### > Exploratory Data Analysis using SQL
###### > EDA DataViz Using Python Pandas and Matplotlib
###### > Launch Sites Analysis with Folium-Interactive Visual Analytics and Plotly Dash
###### > Machine Learning Landing Prediction

# Summary of all results
###### > Exploratory Data Analysis results
###### > Interactive Visual Analytics and Dashboards 
###### > Predictive Analysis 

<img src="https://user-images.githubusercontent.com/84391594/152703941-8c1b3e93-7358-4274-8c7d-b152d3132814.png" alt="Header"/> 

# Applied Data Science Capstone

 <img src="https://images.squarespace-cdn.com/content/v1/54cbd36ae4b0cc1bb3fd8657/1439483297772-V55HNN2QDOD6UA1OHTSH/elon_spacex-e1419882308278.png" alt="SpaceX to Boldly Attempt Falcon 9 Rocket Landing — Colorado Business  Roundtable (COBRT)"/> 


## 📄 Summary
This capstone project will ultimately **predict if the Space X Falcon 9 first stage will land successfully**. 

The full report can be found [here](https://shorturl.at/vB028).

### Context and Business Understanding
- SpaceX launches Falcon 9 rockets at a cost of around $62m. This is considerably cheaper than other providers (which usually cost upwards of $165m), and much of the savings are because SpaceX can land, and then re-use the first stage of the rocket. 

- If we can make predictions on whether the first stage will land, we can determine the cost of a launch, and use this information to assess whether or not an alternate company should bid against SpaceX for a rocket launch.

## 📑 Main Topics 
This project follows these steps:
1. `Data Collection`
    - Making GET requests to the SpaceX REST API
    - Web Scraping
    
2. `Data Wrangling` 
    - Using the `.fillna()` method to remove NaN values
    - Using the `.value_counts()` method to determine the following:
        - Number of launches on each site
        - Number and occurrence of each orbit
        - Number and occurrence of mission outcome per orbit type
    - Creating a landing outcome label that shows the following:
        - 0 when the booster did not land successfully
        - 1 when the booster did land successfully

3. `Exploratory Data Analysis`
    - Using SQL queries to manipulate and evaluate the SpaceX dataset
    - Using Pandas and Matplotlib to visualize relationships between variables, and determine patterns

4. `Interactive Visual Analytics`
    - Geospatial analytics using Folium
    - Creating an interactive dashboard using Plotly Dash

5. `Predictive Analysis` (`Classification`)
    - Using Scikit-Learn to:
        - Pre-process (standardize) the data
        - Split the data into training and testing data using train_test_split
        - Train different classification models
        - Find hyperparameters using GridSearchCV
    - Plotting confusion matrices for each classification model
    - Assessing the accuracy of each classification model

 



## 🔑 Key Skills Learned/Used 
- Using data science methodologies to define and formulate a real-world business problem
- Using data analysis and data visualisation to load a dataset, clean it, and find out interesting insights from it
- Interactive dashboard development with Plotly Dash
- Interactive map development using Folium
- Using machine learning to build a predictive model to help a business function more efficiently
- Structuring and building a data-findings report

## 🏆 Certificates 
To verify the certificates, click the images to follow the links.

<p align="middle">
  <a href="https://coursera.org/share/1c59367a176b10961e2688d8c87f99c5"><img src="https://github.com/PramodRawat157/IBM_APPLIED_DATA_SCIENCE_CAPSTONE_PROJECT-/assets/110245477/02c9060d-7703-4d6a-9619-a4caae779e01" height="420"></a>
  <a href="https://www.credly.com/badges/d3357542-e250-46dd-80f7-924df239cfe4/public_url"><img src="https://github.com/PramodRawat157/IBM_APPLIED_DATA_SCIENCE_CAPSTONE_PROJECT-/assets/110245477/990e31c9-39ce-47dc-ac38-a6f677d844f5" height="420"></a>
</p>
