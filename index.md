# 🧩Data Around Corona 🦠

Tackling Corona and its downstream consequences requires data. Trusted data. As researchers and developers are building the next generation of solutions to help us maneuver this crisis and come out stronger as a global society, we have put together a starting point for resources that provide data and insight into the numbers. We are starting with a focus on direct access to data about case numbers and will be expanding this more broadly into related areas (e.g. services data). While many more sites are out there providing information, we are specifically focused on those who provide scalable building blocks to challenges tackled right now.

Our focus is on providing easy tools to access and combine data and APIs across various platforms and sources. To overcome this crisis, we need collaboration beyond the traditional silos in society.

We can help integrate reliable data. Help us get there. It is urgent to collaborate - to bring solutions at scale. You can add more data via bit.ly/covid-data, a Github project is coming up. Later this week, we are going to publish the APIs easily accessible for researchers and developers to use.

If you want to stay in the loop or want full access leave your email below or drop me a quick note with subject “Covid-19 Push” to christian@xapix.io

The overview below is structured as follows:
- List of key data sources for case numbers
- For top resources for Corona cases with detailed access information
- Starting list of additional resources for broader related datasets
- Scrapers / automation tools / untrusted sites
- Ongoing projects

## List of key data sources for case numbers

- World Health Organization (WHO): https://www.who.int/
- DXY.cn. Pneumonia. 2020. http://3g.dxy.cn/newh5/view/pneumonia.
- BNO News: https://bnonews.com/index.php/2020/02/the-latest-coronavirus-cases/
- National Health Commission of the People’s Republic of China (NHC): http://www.nhc.gov.cn/xcs/yqtb/list_gzbd.shtml
- China CDC (CCDC): http://weekly.chinacdc.cn/news/TrackingtheEpidemic.htm
- Hong Kong Department of Health: https://www.chp.gov.hk/en/features/102465.html
- Macau Government: https://www.ssm.gov.mo/portal/
- Taiwan CDC: https://sites.google.com/cdc.gov.tw/2019ncov/taiwan?authuser=0
- US CDC: https://www.cdc.gov/coronavirus/2019-ncov/index.html
- Government of Canada: https://www.canada.ca/en/public-health/services/diseases/coronavirus.html
- Australia Government Department of Health: https://www.health.gov.au/news/coronavirus-update-at-a-glance
- European Centre for Disease Prevention and Control (ECDC): https://www.ecdc.europa.eu/en/geographical-distribution-2019-ncov-cases
- Ministry of Health Singapore (MOH): https://www.moh.gov.sg/covid-19
- Italy Ministry of Health: http://www.salute.gov.it/nuovocoronavirus
- Germany Robert Koch Institute https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Fallzahlen.html

## For top resources for Corona cases with detailed access information

### Available Data

#### 1. John Hopkins

Name: Daily Cases, Deaths, Recovered<br/>
Source: John Hopkins<br/>
Retrieved through: https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_daily_reports/03-16-2020.csv<br/>
Available Data (insert data table)<br/>
Quality of Data:
- Coverage: Global
- Update mechanism: Once daily
- Data type: csv
- Way data is provided: Aggregation across country sources
- Notes: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data

| Province/State | Country/Region | Last Update         | Confirmed | Deaths | Recovered | Latitude | Longitude |
|----------------|----------------|---------------------|-----------|--------|-----------|----------|-----------|
| Hubei          | China          | 2020-03-16T14:38:45 | 67798     | 3099   | 55142     | 30.9756  | 112.2707  |


#### 2. Europe
Name: Daily Cases, Deaths<br/>
Source: European Center for Disease Protection<br/>
Retrieved through: https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide<br/>
Available Data (insert data table)<br/>
Quality of Data:
- Coverage: Global
- Update mechanism: Once daily
- Way data is provided: Original source
- Notes: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data


| DateRep | Day | Month | Year | Cases | Deaths | Countries and territories | GeoId |
|---------|-----|-------|------|-------|--------|---------------------------|-------|
| 3/17/20 | 17  | 3     | 2020 | 5     | 0      | Afghanistan               | AF    |


#### 3. DXY China
Name: diagnosed, cumulative, death, cured by region<br/>
Source: NCOV DXY (Chinese online community for physicians)<br/>
Retrieved through: https://ncov.dxy.cn/ncovh5/view/pneumonia<br/>
Available Data (insert data table)<br/>
Quality of Data:<br/>
Coverage: ?<br/>
Update mechanism: ?<br/>
Way data is provided: Original source<br/>
Notes:<br/>

#### 4. Tencent
Name: cum diagnosed, confirmed diagnoses, cum cured, cum death, existing severe, overseas input<br/>
Source: Tencent<br/>
Retrieved through: https://news.qq.com/zt2020/page/feiyan.htm#/<br/>
Available Data (insert data table)<br/>
Quality of Data:<br/>
Coverage: ?<br/>
Update mechanism: ?<br/>
Way data is provided: ???<br/>
Notes:<br/>

#### 5. WHO
Name: cum diagnosed, confirmed diagnoses, cum cured, cum death, existing severe, overseas input<br/>
Source: WHO<br/>
Retrieved through: https://services.arcgis.com/5T5nSi527N4F7luB/arcgis/rest/services/COVID_19_HistoricCasesByCountry(pt)View/FeatureServer/0/query?f=json&where=1%3D1&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=OBJECTID%2CNewCase%2CDateOfDataEntry&orderByFields=DateOfDataEntry%20asc&resultOffset=2000&resultRecordCount=2000&cacheHint=true<br/>
Available Data (insert data table)<br/>
Quality of Data:<br/>
Coverage: ?<br/>
Update mechanism: ?<br/>
Way data is provided: json<br/>
Notes: showcase https://experience.arcgis.com/experience/685d0ace521648f8a5beeeee1b9125cd<br/>
