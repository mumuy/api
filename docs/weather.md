### 腾讯接口
天气（各城市排行）
``` javascript
http://weather.gtimg.cn/aqi/cityrank.json
```
城市ID
``` javascript
http://mat1.gtimg.com/weather/index2014/wtData_v2.js
```
获取城市天气（javascript）
``` javascript
http://weather.gtimg.cn/city/01010101.js
//http://weather.gtimg.cn/city/{城市ID}.js
```
获取城市天气（jsonp）
``` javascript
http://weather.gtimg.cn/aqi/01010508.json
//http://weather.gtimg.cn/aqi/{城市ID}.json
```

调用方法（参考）
``` javascript
http://mat1.gtimg.com/weather/index2014/wtEvent_v2.js
```
搜索方法（参考）
``` javascript
http://mat1.gtimg.com/weather/index2014/searchEvent_v3.js?v3
```


###etouch接口
通过城市名字获得天气数据（json）
``` javascript
http://wthrcdn.etouch.cn/weather_mini?city=北京市
```
通过城市ID获得天气数据（json）
``` javascript
http://wthrcdn.etouch.cn/weather_mini?citykey=101010100
```
通过城市名字获得天气数据（xml）
``` javascript
http://wthrcdn.etouch.cn/WeatherApi?city=北京市
```
通过城市ID获得天气数据（xml）
``` javascript
http://wthrcdn.etouch.cn/WeatherApi?citykey=101010100
```