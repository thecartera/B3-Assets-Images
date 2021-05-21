## About

This repo works as an API. 
You can GET thumbnails for most of B3 (Brazil's stock exchange) assets (stocks/bdrs/etfs/fiis...) 

``` 
GET https://github.com/monneda/B3-Assets-Images/blob/main/imgs/{{ticker}}.png
```


#### Images file size reduction
To reduce file size (and standardize dimensions to 120x120) we used [Optimize-Images CLI](https://github.com/victordomingos/optimize-images)
