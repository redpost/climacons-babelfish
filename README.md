climacons-babelfish
===================

JSON hashes to convert various weather icons into [@adamwhitcroft's](https://twitter.com/adamwhitcroft) much prettier Climacons.

[Download Climacons here](http://adamwhitcroft.com/climacons/)


## NOAA

We're keeping an updated list of icon matches in a Google Doc here, request sharing access to contribute:
* [NOAA images to Climacons Conversion Table](https://docs.google.com/a/theredpost.com/spreadsheets/d/1VGStbCok1r1oyWz76ZZao3DAE5R2bF1tL_sbjWB-XXI/edit#gid=0)

NOAA images are complex, with maritime, day/night and several special weather events that Climacons doesn't include (and very rarely occur). We attempted to make a complete list of NOAA images from these sources; there is seemingly not a single comprehensive list anywhere. I'm sure we missed some. Also, if you have a better suggestion for what to use for the Wave icon, we're all ears!
* [NOAA Element List and Suggested Icons](http://w1.weather.gov/xml/current_obs/weather.php)
* [Forecast At-A-Glance Icons](http://www.crh.noaa.gov/riw/?n=forecast_icons)
* [Index of /weather/images/fcicons](http://www.nws.noaa.gov/weather/images/fcicons/)
* [Weather icons .zip file](http://w1.weather.gov/images/fcicons/Weather%20Icons.zip)

NOAA suggested changing their icon system in 2006, but decided against it in 2007, [public comments here](http://www.nws.noaa.gov/icon_comments/).

We'd love to add other JSON hashes in this project, there is no standard. Eventually, a nice Javascript library or Ruby gem to translate between them all would be awesome:
* [Yahoo! Weather icons](http://developer.yahoo.com/weather/#codes)
* [Forecast.io animations](http://blog.forecast.io/skycons-unobtrustive-animated-weather-icons/)

NOAA's API documentation is [here](http://graphical.weather.gov/xml/). NOAA Ruby gem (which we use) [here](https://github.com/outoftime/noaa).
