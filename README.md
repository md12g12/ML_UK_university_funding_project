# ML_UK_university_funding_project
Small machine learning project using UK University League table results to predict the level of funding received from UKRI body (UK Research and Innovate).

The project is split into two parts, the data extraction and cleaning, and the machine learning using Scikit-Learn to fit a model to the data.

The data is sourced from The Complete University Guide (https://www.thecompleteuniversityguide.co.uk/league-tables/rankings?tabletype=full-table&sortby=student-staff-ratio) and the UKRI transparency reports (https://www.ukri.org/about-us/what-we-do/financial-data/). This data was downloaded on 12/05/2022 and may change in the URL's linked. As such the final dataframe (after data cleaning) is saved in this repository before being used for modelling.


ML_UK_university_funding.ipynb          - Machine learning on the datasets juypter notebook. 

University_funding_data_cleaning.ipynb  - Data download and cleaning juypter notebook.

funding_ML_df.csv.csv                   - Dataframe with the universities scores as well as their total UKRI grants for the year 2022.
