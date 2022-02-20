# Zillow_Rent_Analysis
Analyzing historical rent prices

Analyzing Zillow's NYC Rent Index
This project took much longer than expected. So much future work I want to do with this data.</br></br>
I found this data while strolling around the Kaggle datasets. Someone uploaded Zillow Rent Index data from 2014 until 2021 June.</br>
Per the Zillow website, the Zillow Rent Index is the following:</br></br>
The Zillow Rent Index (ZRI) is a dollar-valued index intended to capture typical market rent for a given segment (IE, multifamily or single-family units) and/or geography (IE for a given ZIP code, city, county, state or metro) by leveraging Rent Zestimates.</br></br>
Data can be found here: https://www.kaggle.com/haydenvenable/zillow-observed-rent-index-jan-2014-june-2021</br></br>
This dataset was 1744 rows by 94 columns. Out of those rows, there were 95 zip codes for NYC. These 95 zip codes I analyzed because I was curious how COVID affected rent prices.
Below you will see all the NYC zip codes plotted. The X-Axis is just the range of months from 2014 until June 2021. Additionally at the very end, I made some LSTM (Long-Short Term Memory) neural net predictions of the next 10 months of data based on the historical data. It is not perfect by any means, but definitely well worth the practice. I did these predictions for the top 5 ranked zip codes that Zillow had for "most urbanized".</br></br>
A couple of observations I found:</br></br>
Alot of the high rent zip codes took the largest fall.</br>
Alot of the high rent ones that fell followed the same reverse "J" curve which showed an immediate rebound in rent price. This might indicate that demand is still there for that zip code but price had to match demand.</br>
There are zip codes with lower rents. Some fell, some stayed stable and there were even some where the rent was trending upward!</br>
There may be gaps in the graphs, this is due to the lack of data for that specific row/column value which I filled with a zero.</br></br></br>

See below plots:</br></br></br>
![tessssssssssstttt](https://user-images.githubusercontent.com/62908910/154826073-abb4ff82-70e7-41b5-b80d-fca466039557.jpeg)
</br>

So many dips! But also so many are trending upwards! Notice the reverse "J" spikes in price.</br></br>

LSTM (Long-Short Term Memory) Neural Net Model Predictions:</br></br>
![zip1](https://user-images.githubusercontent.com/62908910/154826088-58d59267-a68f-43c7-b775-74110dafc795.PNG)
</br></br>![zip2](https://user-images.githubusercontent.com/62908910/154826090-84975e46-93af-4902-83f9-8a8299a3bf4e.PNG)
</br></br>![zip3](https://user-images.githubusercontent.com/62908910/154826095-6b921108-da67-428e-8508-b387c4c98363.PNG)
</br></br>
![zip4](https://user-images.githubusercontent.com/62908910/154826101-dc69b75e-224a-415d-8f35-c7b189b2aebe.PNG)
</br></br>
![zip5](https://user-images.githubusercontent.com/62908910/154826105-a2834223-87b6-49d2-862f-7e49048487fd.PNG)

</br></br>
Also here are the LSTM model predictions for the following top rated zip codes in NYC per Zillow. You will see the prediction as the little orange line at the right side of the graph. These LSTM models are rudimentary and the predictions should be taken with a grain of salt.</br></br>
Future work:</br>
Where do I begin with the future work? I want to use Facebook Prophet's powerful prediction software on this data. I want to use more refined neural nets. I want to train a neural net on all the data at once and not on just a single row's data. I want to create a more robust model that will give me even more refined predictions. I want to make a subplot of all 95 zip codes with all 95 of them having predicted values rather than manually training a model each time. I want more dang colors in these graphs!</br>
And, last but not least….I want to compare the LSTM's neural net's predictions versus the latest Zillow Rent Index data.</br></br>
Closing thoughts:</br></br>
Resources were limited, but progress was satisfactory. There is much more that I want to try and do if I had more time. Sometimes I have to respect the deadline for my own sanity.
