# Time Series Analysis using InfluxDB, AWS IoT, and AWS Greengrass
### (IoT + Weather + Twitter + Machine Learning + InfluxDB + Grafana)

***

## Introduction
- It is to find the optimal exercise timing with less particulate matter(PM) in Seoul (South Korea)
- This system automatically sends weather and [particulate matter(PM)](https://www.epa.gov/pm-pollution) data to the Twitter and the [Line messenger](https://en.wikipedia.org/wiki/Line_(software)). (six times per a day).
- We analyze time series of collecting weather and [particulate matter(PM)](https://www.epa.gov/pm-pollution) data.
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
* Node-RED Flows
![00_Node-RED.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/00_Node-RED.png)
* Twitter Bot For Seoul Weather([@aniotmaker](https://twitter.com/aniotmaker))
![01_Weather_Twitter.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/01_Weather_Twitter.png)
![02_Twitter_bot.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/02_Twitter_bot.png)
* [Particulate Matter(PM)](https://www.epa.gov/pm-pollution) Data Analytics on Grafana
![03_DustDATA.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/03_DustDATA.png)
* AWS CloudWatch on Grafana
![04_AWS_CloudWatch.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/04_AWS_CloudWatch.png)
* Line Bot
![05_LineBots.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/05_LineBots.png)
* Tableu Analytics
![06_TableuAnalytics.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/06_TableuAnalytics.png)
* Jupyter Web Notebook
[Jupyter Web Notebook](https://nbviewer.jupyter.org/github/leehaesung/seoul_weather_twitter_Analysis/blob/master/01_files/SeoulWeather_pm2p5c_csv.ipynb)

![07_Analytics.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/07_Analytics.png)

---

## References

* [Getting started with InfluxDB](https://docs.influxdata.com/influxdb/v1.7/introduction/getting-started)
* [Node-RED nodes to save and query data from an influxdb time series database](https://flows.nodered.org/node/node-red-contrib-influxdb)
* [Grafana Lab](https://grafana.com/)
* [My Keynote(SlideShare)](https://www.slideshare.net/StephenHaesungLee/aws-iot-aws-greengrass-for-time-series-analysis-english-ver)
* [OpenWeather API](https://openweathermap.org/)
* [Get started with Tableau](https://www.tableau.com/learn/get-started)
* [What Is AWS IoT Greengrass?](https://docs.aws.amazon.com/greengrass/latest/developerguide/what-is-gg.html)
* [Designing MQTT Topics
for AWS IoT Core](https://d1.awsstatic.com/whitepapers/Designing_MQTT_Topics_for_AWS_IoT_Core.pdf)
* [Using Node-RED Library to Wire Telemetry Data from IoT Devices to the Cloud](https://labs.eleks.com/2019/01/node-red-library-iot-cloud.html)
* [Using AWS IoT Analytics to Prepare Data for QuickSight Time-Series Visualizations](https://aws.amazon.com/blogs/iot/using-aws-iot-analytics-to-prepare-data-for-quicksight-time-series-visualizations/)
* [AWS Documentation](https://docs.aws.amazon.com/index.html)
* [AWS 기반 지속 가능한 데이터 분석 플랫폼 구축하기 - 소성운, 지그재그 :: AWS Summit Seoul 2019](https://www.slideshare.net/awskorea/aws-aws-summit-seoul-2019-141290115)
* [AWS 기반 지속 가능한 데이터 분석하기](https://github.com/awskrug/datascience-group/tree/master/workshop-sustainable_data_analysis)
* [Spark Streaming: IoT with Amazon Kinesis and Visualizing with Qubole Notebooks](https://www.qubole.com/blog/spark-streaming-iot-amazon-kinesis-visualizing-qubole-notebooks/)
* [궁금한 이야기 Y - 그들이 AWS 위에서 데이터 파이프라인을 운영하는 법](https://docs.google.com/presentation/d/1_v-f5B67v-hcmEbltLEfjSS5MKKctztdAGZzEHs2DPM/edit?usp=sharing)

---
![QR Code](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/QRcode_aniotmaker.png)
