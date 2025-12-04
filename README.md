# Company_electricity
Hypothesis: Weather conditions affect to Nordpool Spot electric prices in Finland?

Study what kind of relationship weather conditions have with electricity prices in Finland.

Use electric prices data given (fmi_weather_and_price.csv) or you can use other sources to get Nordpool Spot in Finland. "fmi_weather_and_price" dataset is showing hourly electricity prices and mean temperature and wind-speed values in Finland.

For weather data you can use given dataset or seek weather data from other sources such as NCEI https://www.ncei.noaa.gov/support/access-data-service-api-user-documentation or from Finnish Meterological Institute https://www.ilmatieteenlaitos.fi/havaintojen-lataus.

Tips:

- If you use other data sources than given dataset, consider location from where weather data is measured. (Finland, Scandinavia area etc.)
- Spot-prices are estimated one day before, need to shift data? 
- You might need to split data into smaller pieces to study correlation, so ignoring data with high variation due to some disturbances
- Weather conditions which might affect to prices such as, temperature, wind speed, amount of rain...
- Some global events and other energy sources affect to prices. Data for these are not needed but you can discuss these also how these might affect.
- For the reporting tool, you can use Streamlit with CSC server, Streamlit server or some other cloud hosting service. You can use some other cloud based reporting tools such as PowerBi, Google Looker etc. what you prefer.

Expected output:
- Online report with figures showing used data in analysis, descriptive statistics and different correlations between these
- Using other source for data than provided file as extra information, (for example other weather data, data of electricity consumption etc.) 
- Try to find some regression model between weather variables and price,
- Create URL of your report 
