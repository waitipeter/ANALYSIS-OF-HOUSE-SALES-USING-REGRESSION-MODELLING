
# HOUSE SALES PREDICTION IN KING COUNTY USING REGRESSION MODELLING
    Project Overview 
For this project, I used regression modeling to analyze house sales in a northwestern county.

Assignment


	Business Problem: A real estate Agency need to provide prospective home sellers with guidance on how to improve the value of their home prior to listing, including the predicted increase in value expected based on improvements to particular features.



	Business Question: What features of their home can prospective home sellers change or improve to increase the value of their home, and by amount could this increase be specific to certain features?



## Requirements
This project requires that;

Your Jupyter Notebook should demonstrate an iterative approach to modeling. This means that you begin with a basic model, evaluate it, and then provide justification for and proceed to a new model. After you finish refining your models, you should provide 1-3 paragraphs discussing your final model - this should include interpreting at least 3 important parameter estimates or statistics.

Based on the results of your models, your notebook and presentation should discuss at least two features that have strong relationships with housing prices.

Your deliverables should explicitly address each step of the data science process. Refer to the Data Science Process lesson (https://github.com/learn-co-curriculum/dsc-data-science-processes.) from Topic 19 for more information about process models you can use.


## Requirements
This project requires that;

Your Jupyter Notebook should demonstrate an iterative approach to modeling. This means that you begin with a basic model, evaluate it, and then provide justification for and proceed to a new model. After you finish refining your models, you should provide 1-3 paragraphs discussing your final model - this should include interpreting at least 3 important parameter estimates or statistics.

Based on the results of your models, your notebook and presentation should discuss at least two features that have strong relationships with housing prices.

Your deliverables should explicitly address each step of the data science process. Refer to the Data Science Process lesson (https://github.com/learn-co-curriculum/dsc-data-science-processes.) from Topic 19 for more information about process models you can use.


## Data used
This project uses the King County House Sales dataset because Emerald City Realtors and its prospective homesellers are all based in King County. The dataset includes all data of single-family home sales from 2014-2015. The dataset itself can be found in kc_house_data.csv in the data folder of this GitHub repository along with the descriptions of the features, found in column_names.md Further information about the features can be found on the King County Assessor Website https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r

             Column Names in the csv file and their descriptions.
    date - Date house was sold.
    price - Sale price (prediction target)
    bedrooms - Number of bedrooms
    bathrooms - Number of bathrooms
    sqft_living - Square footage of living space in the home
    sqft_lot - Square footage of the lot
    floors - Number of floors (levels) in house
    waterfront - Whether the house is on a waterfront
    view - Quality of view from house
    condition - How good the overall condition of the house is.
    grade - Overall grade of the house. 
    sqft_above - Square footage of house apart from basement
    sqft_basement - Square footage of the basement
    yr_built - Year when house was built
    yr_renovated - Year when house was renovated
    
## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Data science process lesson](https://github.com/learn-co-curriculum/dsc-data-science-processes)
 - [king County Assessor website](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r)
 - [Univariate and Bivariate Analysis using Seaborn](https://shecancode.io/blog/univariate-and-bivariate-analysis-usingseaborn)


## Authors

- [@waitipeter](https://github.com/waitipeter)


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Installation

Install plotly with

```bash
  pip install plotly
```
    
## Configuration
Install plotly with

```bash
  def configure_plotly_browser_state():
  import IPython
  display(IPython.core.display.HTML('''
        <script src="/static/components/requirejs/require.js"></script>
        <script>
          requirejs.config({
            paths: {
              base: '/static/base',
              plotly: 'https://cdn.plot.ly/plotly-1.5.1.min.js?noext',
            },
          });
        </script>
        '''))
```
## Documentation

[Documentation](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r)

https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r

## Feedback

If you have any feedback, please reach out to us at waitipeter97@gmail.com


## 🚀 About Me
I'm a Data science student at Moringa school...


## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?

Data understanding.

Data cleaning

Data modelling using regression models

Researching.

Data Analysis
## Run Locally

Clone the project

```bash
  git clone https://github.com/waitipeter/ANALYSIS-OF-HOUSE-SALES-USING-REGRESSION-MODELLING.git
```

Go to the project directory

```bash
  cd ANALYSIS-OF-HOUSE-SALES-USING-REGRESSION-MODELLING
```

Install dependencies

```bash
  Nothing to install
```

Start the server

```bash
 source activate env
```

