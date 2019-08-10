# Time series analysis using InfluxDB, AWS IoT, and AWS Greengrass
### (IoT + Weather + Twitter + Machine Learning + InfluxDB(TSDB)

***

## Introduction
- It is to find the optimal exercise timing with less fine dust.
- This system automatically sends weather and fine dust data to tweeters and line messengers.
- We analyze time series of collected weather and fine dust data.
- [https://twitter.com/aniotmaker](https://twitter.com/aniotmaker)
- [SlideShare @Nongshim Engineering](https://www.slideshare.net/StephenHaesungLee/aws-iot-aws-greengrass-for-time-series-analysis-english-ver)

This time, we will query AWS Athena for real-time collected data through AWS-IoT core & Greegrass.
In addition, BI verifies the results with AWS QuickSight, Tableau Analytics, and Apache Zeppline visualizations.

---

## Jupyter Web Notebook
 * [Jupyter Web Notebook](https://nbviewer.jupyter.org/github/leehaesung/seoul_weather_twitter_Analysis/blob/master/01_files/SeoulWeather_pm2p5c_csv.ipynb)

---

## Architecture
![SeoulWeatherArchitecture.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/SeoulWeatherArchitecture.png)

---

![IoT_Sensors_with_JSON_Format](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/IoT_Sensors_with_JSON_Format.png)

---

## References
![Node-RED nodes to save and query data from an influxdb time series database](https://flows.nodered.org/node/node-red-contrib-influxdb)

![Grafana Lab](https://grafana.com/)

