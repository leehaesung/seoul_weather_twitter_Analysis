# Time series analysis using InfluxDB, AWS IoT, and AWS Greengrass
### (미세먼지로부터 우리의 건강을 지키자.)

***

## 개요
- AWS IoT Core, Greengrass 통해 미세먼지가 적은 시간의 운동타이밍을 찾는것입니다.
- 미세먼지데이터를 트위터와 라인에 전송합니다.
- 수집한 미세먼지데이터를 시계열 분석합니다.
- [https://twitter.com/aniotmaker](https://twitter.com/aniotmaker)
- [SlideShare @농심엔지니어링](https://www.slideshare.net/StephenHaesungLee/aws-iot-aws-greengrass-for-time-series-analysis-english-ver)

이번에는 AWS-IoT core & Greegrass 통해 실시간 수집데이타 대해서 AWS Athena로 쿼리하는 것을 확인한다.
또한, 결과에 대해 BI는 AWS QuickSight, Tableau Analytics, Apache Zeppline 시각화해서 확인한다.

---

## Jupyter Web Notebook
 * [Jupyter Web Notebook](https://nbviewer.jupyter.org/github/leehaesung/seoul_weather_twitter_Analysis/blob/master/01_files/SeoulWeather_pm2p5c_csv.ipynb)

---

## Architecture
![SeoulWeatherArchitecture.png](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/SeoulWeatherArchitecture.png)

---

![IoT_Sensors_with_JSON_Format](https://raw.githubusercontent.com/leehaesung/seoul_weather_twitter_Analysis/master/01_files/IoT_Sensors_with_JSON_Format.png)

