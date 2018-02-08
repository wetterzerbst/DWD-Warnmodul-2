# DWD-Warnmodul-2
show weather alerts from Deutscher Wetterdienst    
[Demo](https://dj0001.github.io/DWD-Warnmodul-2/)

removed jquery (use json), add icons, update marker and map, location request, add satlayer    
needs Leaflet

*Read this in other languages: [Deutsch](README.de.md)*

## API

add filter querystringparameter ?EC_GROUP e.g. ?Frost    
Demo https://dj0001.github.io/DWD-Warnmodul-2/?Frost    

add Notification querystringparameter ?warnlevel e.g. ?2 (?5 no-notification)    
Demo https://dj0001.github.io/DWD-Warnmodul-2/?2 for ≥ Moderate

add city querystringparameter ?ort=<city> e.g. ?ort=Augsburg    
Demo https://dj0001.github.io/DWD-Warnmodul-2/?ort=Augsburg    

## Changelog
26.01. add Notification    
26.01. add Geocode (click on search icon)    
27.01. add legend ⌄    
29.01. add parameter ort    
30.01. without global variables    
31.01. add parameter ?0 no-geolocation, ?1 watch-geo

## License
Copyright © warndata, <a href="https://dwd.de">DWD<img src="https://www.dwd.de/SiteGlobals/StyleBundles/Bilder/favicon.ico?__blob=normal" alt="DWD" /></a>    

Copyright © 2018, dj0001    
[BSD 2-Clause](https://opensource.org/licenses/BSD-2-Clause)
