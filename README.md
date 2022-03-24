## About

This repo works as an API. 
You can GET thumbnails (icons, all 120x120) for most of B3 (Brazil's stock exchange) assets (stocks/bdrs/etfs/fiis...) 

``` 
GET https://github.com/monneda/B3-Assets-Images/blob/main/imgs/{{ticker}}.png
```

You can also GET logos (varying widths and heights) for stocks traded on B3 (no logos for bdrs/etfs/fiis yet)

``` 
GET https://github.com/monneda/B3-Assets-Images/blob/main/imgs/logos/{{base_ticker}}.png
```

Note that for logos you have to query by `base_ticker` (without numbers), and for icons you can do both with or without numbers


#### Images file size reduction
To reduce file size (and standardize dimensions to 120x120) we used [Optimize-Images CLI](https://github.com/victordomingos/optimize-images)
