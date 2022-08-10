# Multivariate-LSTM-Home-Index

<p> <i>Bushra Islam, Ha Bui, Geeta Apodaca, Ramya Venkatesan, Karthigalakshmi Ramasamy, Elizabeth Hall, and Ewa Godlewska </i></p>
<p>This Project is a part of DataScience4All Women's Summit 2022, sponsored by Correlation One. We analyzed the impact of different socio-economic factors on housing prices during the Covid-19 pandemic, and forecasted two years of average US housing prices (2022-2024) in reaction to the FED's housing market correction plan.  </p>

<H2><b>Background </b></H2>

<p>The project aims to answer three questions: </p>
<ol type="1">
  <li>Can we accurately model the increase in house prices during Covid-19?</li>
  <li>How does work from home and millennials entering the housing market affect house prices?</li>
  <li>What will house prices look like in the next two years?</li>
</ol>  

<H2> Data </H2>

<p>The data covers the period of January 2005 – May 2022. </p>

 <ol type="1">
  <li>Housing Data - Zillow Research (Zillow Home Value Index, Rental Price)</li>
  <li>FRED Economic Data (Mortgage Rate, Mortgage-to-Income Rate, Interest Rate, Inflation Rate, Housing Starts)</li>
  <li>Havard JCHS https://www.jchs.harvard.edu/stte-nations-housing-2022 (work-from-home rate)</li>
</ol> 

<H2><b> Contents </b>  </H2>
<ul>
  <li><b> Data: </b> 
  <ul>
  <li> Raw: Contains a folder of the raw data used in the Data Wrangling notebook. Some datasets were directly pulled from the FED with "pandas_datareader", and are not included in the folder.</li>
  <li> Processed: The raw datasets were merged together in the Data Wrangling notebook, and subsetted to the 2005-2022 years used in the analysis <i> housing_data_for_eda.csv. </i> We fill in missing values during EDA to prepare for modeling <i> housing_data_for_modeling.csv. </i> Exogenous variables forecasted out for 30 months and with the FED's correction plan initatied are in <i> forecast30observation_sensitivity_new.csv. </i> Forecasted housing prices for 2022-2024 with and without the FED's correction plan are in <i>final_forecast.csv.</i> </li> </ul>
  <li> <b> Notebooks:</b> Contains jupyter notebooks of Data Wrangling, Exploratory Data Analysis, Modeling, & Forecasting </li>
</ul>

<H2>Poster  </H2>
      
![Team # 5 Datafolio Draft (4)](https://user-images.githubusercontent.com/45531187/183999889-eb34a44f-ddcf-4426-831f-d3ba45410020.jpg)

