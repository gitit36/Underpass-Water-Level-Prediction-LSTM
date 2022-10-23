# Underpass Water Level Prediction (LSTM)
Woojangchun Underpass location:   https://www.google.com/maps/place/%EC%9A%B0%EC%9E%A5%EC%B6%98%EC%A7%80%ED%95%98%EC%B0%A8%EB%8F%84/@35.2151336,129.0723631,15z/data=!4m2!3m1!1s0x0:0xbdc1958dec0e586a?sa=X&ved=2ahUKEwjsgYWmo_b6AhXIQPUHHaqZCkMQ_BJ6BAhOEAU 
  
Woojangchun underpass is located in Busan, South Korea. Flooding of the underpass has been a chronic problem during the rainy season in summers. 
This project is to accurately predict the water level of the underpass from June to August to help better prepare for and prevent damage.
  
Apart from the Woojangchun water level data acquired from a govenrment entity, various weather metadata of districts in Busan city such as *Suyoung-gu*, *Dongnae-gu Oncheon-2-dong*, *Dongnae-gu Oncheon-3-dong*, *Nakdong River Estuary Bank*, *Gupo bridge* have been collected using Open APIs like [Water Resource Management Information System](http://www.wamis.go.kr:8080/wamisweb/rf/w3.do#) and [Korea Meteorological Administration](https://data.kma.go.kr/data/rmt/rmtList.do?code=400&pgmNo=570).  
  
Relevant weather metadata include the following:
1. rainfall (1 hour ~ 6 hour forecast)
2. water level
3. rain type (1 hour ~ 6 hour forecast)
4. temperature (1 hour ~ 6 hour forecast)
5. North/South wind substance (1 hour ~ 6 hour forecast)
6. East/West wind substance
7. wind speed (1 hour ~ 6 hour forecast)
8. wind direction
9. sky's overcast (1 hour ~ 6 hour forecast)
10. thunderbold and lightening
11. relative humidity
12. total cloud cover
13. sea level pressure
14. accumulated snow
15. solar irradiance
16. dew point

hi
