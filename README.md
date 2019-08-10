# Time Series Analysis using InfluxDB, AWS IoT, and AWS Greengrass
### (IoT + Weather + Twitter + Machine Learning + InfluxDB + Grafana)

***

## Introduction
- It is to find the optimal exercise timing with less fine dust in Seoul (South Korea)
- This system automatically sends weather and fine dust data to the Twitter and the [Line messenger](https://en.wikipedia.org/wiki/Line_(software)). (six times per a day).
- We analyze time series of collecting weather and fine dust data.
- Real Demo: [https://twitter.com/aniotmaker](https://twitter.com/aniotmaker)
- Keynote: [SlideShare @Nongshim Engineering](https://www.slideshare.net/StephenHaesungLee/aws-iot-aws-greengrass-for-time-series-analysis-english-ver)

This time, we will query AWS Athena for real-time collected data through AWS-IoT core & Greegrass.
In addition, BI verifies the results with AWS QuickSight, Tableau Analytics, and Apache Zeppline visualizations.

---

## Architecture
![SeoulWeatherArchitecture.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/SeoulWeatherArchitecture.png)

![IoT_Sensors_with_JSON_Format](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/IoT_Sensors_with_JSON_Format.png)


---

## Implementations
![00_Node-RED.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/00_Node-RED.png)
![01_Weather_Twitter.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/01_Weather_Twitter.png)
![02_Twitter_bot.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/02_Twitter_bot.png)
![03_DustDATA.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/03_DustDATA.png)
![04_AWS_CloudWatch.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/04_AWS_CloudWatch.png)
![05_LineBots.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/05_LineBots.png)
![06_TableuAnalytics.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/06_TableuAnalytics.png)
![07_Analytics.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/07_Analytics.png)

---

## Jupyter Web Notebook
 * [Jupyter Web Notebook](https://nbviewer.jupyter.org/github/leehaesung/seoul_weather_twitter_Analysis/blob/master/01_files/SeoulWeather_pm2p5c_csv.ipynb)

---

## References

* [Getting started with InfluxDB](https://docs.influxdata.com/influxdb/v1.7/introduction/getting-started)

* [Node-RED nodes to save and query data from an influxdb time series database](https://flows.nodered.org/node/node-red-contrib-influxdb)

* [Grafana Lab](https://grafana.com/)

* [My Keynote(SlideShare)](https://www.slideshare.net/StephenHaesungLee/aws-iot-aws-greengrass-for-time-series-analysis-english-ver)

* [OpenWeather API](https://openweathermap.org/)

* [Get started with Tableau](https://www.tableau.com/learn/get-started)


