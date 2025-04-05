code folder contains jupyter notebooks used to train and evaluate models.
  main.ipynb contains main code needed to read and process data, as well as run and evaluate all models; and contains results for EN-CoF and baseline, and data figures.
  versus_time.ipynb shows code used to evaluate accuracy dependency on the testing month and forecasting further into the future.
  model.ipynb is a seperate notebook for each model, with grid searches and results from each.
  utils.ipynb has several functions used during development.
  
figures folder contains all figures used in paper, and others.
  countries.pdf contains the images referenced in paper, that compare raw counts to average counts and expected to forecasted for each country.
  
COVID-19-geographic-disbtribution-worldwide-2020-12-11.csv is data from ECDC used in paper. Data must be grouped by country, and within that each row must be sorted in ascending order by date.
