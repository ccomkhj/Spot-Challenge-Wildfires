![](/images/wildfires-logo-github-v2.png)

# Call for Code Spot Challenge for Wildfires

## This is the notebook of participation challenge above.

### My team achieved the second best rank in the competition.
![](/images/outcome.png)

### Source code could be found in the main and main2 folder. (it has multiple versions)
## main: build model and explore data, main2: test with multiple model and data processing.

<a name="timeline"></a>
### Timeline

There will be four main contest stages  - the first three stages are for practice. The final stage is what the contestants will be measured on. Find more details and submission dates [here](http://ibm.biz/cfcsc-wildfires). For each stage the provided data will be improved, so check back here and make sure you use the right data from [here](https://github.com/Call-for-Code/Spot-Challenge-Wildfires/tree/main/data).

* Try the platform - Predict Feb 2020
* Predict Jan 2021 week 3 (Jan 16-22)
* Predict Jan 2021 week 4 (Jan 23-29)
* Predict Feb 2021 (Feb 1-28)

<a name="data"></a>
## The data

Data is provided as a [zip file](https://github.com/Call-for-Code/Spot-Challenge-Wildfires/tree/main/data) that contains the below files. **For each submission round a new zip file will be added, make sure you use the right one!**

The following data is provided as daily timeseries for the 9 regions:

* Historical wildfires
* Historical weather
* Historical weather forecasts
* Historical vegetation index
* Land classes (static throughout the contest)

Find details about the data sources and data processesing in these [slides](https://github.com/Call-for-Code/Spot-Challenge-Wildfires/blob/main/resources/wildfire-challenge-data-introduction.pdf) and the [data documentation](https://github.com/Call-for-Code/Spot-Challenge-Wildfires/blob/main/data/Readme_Docs_Wildfires-Datasets_2020-11.pdf). 

This [Jupyter notebook](https://github.com/Call-for-Code/Spot-Challenge-Wildfires/blob/main/notebooks/wildfire-data-introduction.ipynb) will you get started with loading and exploring the data. The data can be loaded directly from this repository into a notebook:

```python
!wget -N https://raw.githubusercontent.com/Call-for-Code/Spot-Challenge-Wildfires/main/data/Nov_10.zip
zip = zipfile.ZipFile("Nov_10.zip")
zip.extractall()
```

<a name="resources"></a>
## Further resources

* [Forecasting - principles and practice](https://otexts.com/fpp2/) - online textbook on forecasting
* [Prophet](https://facebook.github.io/prophet/) - forecasting toolbox from Facebook

