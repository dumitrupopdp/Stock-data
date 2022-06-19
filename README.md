# Stock data

The purpose for this project is to take financial from publicly traded companies, using data from public websites in order to create a stock dashboard in Power BI.

The main sources of data are https://finance.yahoo.com/  and https://www.marketbeat.com/ in order to get information regarding companies from the Dividend Kings list. A list of companies that have distributed dividends for a long period of time, without interruptions. 

To be able to use data from these sites, I choose the “Web” connector provided by Power BI. Since you can use only one link, you could import data for only one company. Because I wanted data from multiple companies, and didn’t want to import all of them manually, I used parameters in combination with the URL. This combination made possible to change just one part of the link that was particular to each company. 

The final product is to write a list of company tickers (the label of a listed company on the stock market) that I want to get imported and Power BI would do the rest.

After the data was imported, there was a need for cleaning and transforming the data to be usable for visualizations.

On the report page there are multiple tools to help the user to choose the date wanted for analysis, which, individual or
group of companies will be analyzed and what are their respective dividend yield. 

All of this can be seen in the "Stock data.pbix" file.
