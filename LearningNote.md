# To generate data file use below command. #

## Yahoo Finance ##

```
cd C:\Users\raj.champaneriya\Source\Repos\Lean\ToolBox\bin\Debug 
QuantConnect.ToolBox.exe --app=YahooDownloader --tickers=RELIANCE.NS --resolution=Daily --from-date=20190913-00:00:00 
```

## NSE ##
```
cd C:\Users\raj.champaneriya\Source\Repos\Lean\ToolBox\bin\Debug 

QuantConnect.ToolBox.exe --app=nsemarketdataconverter --source-dir=C:\Users\raj.champaneriya\Desktop\nse --destination-dir=C:\Users\raj.champaneriya\Desktop\nse\out
```

# Algorithm #

```
Refer BasicTemplateIntrinioEconomicData for usage of basic indicators. 
Candle stick patters are also kind of indicators.

```

# To setup NSE analysis

```
Add  entry for NSE to C:\Users\raj.champaneriya\Source\Repos\Lean\Data\market-hours\market-hours-database.json



```