## Awesome-free-things
Welcome to my repository, where i upload multiple free stuff, that are usually hidden deep in the internet, find what you need!

Some might require an api key, so make sure to include it.

The list doesnt include not so generous weather apis (but i still included those that are atleast worth trying, yet not so generous), the list might also not have free trials whatsoever. But if a category has free trials, i shall let you know in the description

# Weather forecasts and data
This included alot of good apis, so make sure to check them out, took me a good while to find few good ones.

| # | API / Service | Free Limit | Key Required? | Forecast | Historical Data | Coverage | Commercial OK? | Specialty / Notes |
|---|---|---|---|---|---|---|---|---|
| 1 | [Open-Meteo](https://open-meteo.com/) | 10K/day (Unlimited if self-hosted) | NO | 16 days | From 1940 (ERA5) | Global | CC BY 4.0 (non-commercial on free tier) | Self-host via Docker for truly unlimited; 30+ models |
| 2 | [NWS weather.gov](https://www.weather.gov/documentation/services-web-api) | Unlimited | NO | Yes | Limited | US Only | Yes | Official US govt; just add a User-Agent header |
| 3 | [NASA POWER](https://power.larc.nasa.gov/) | Unlimited | NO | Limited | Multi-decade | Global | Yes | Solar radiation, agricultural, climate data |
| 4 | [WMO WWIS](https://worldweather.wmo.int/) | Unlimited | NO | Yes | No | Global | Yes | Direct UN/govt source; raw JSON by city ID |
| 5 | [DWD Open Data](https://opendata.dwd.de/) | Unlimited | NO | Yes | Yes | Germany/EU | Yes | FTP-style server; raw ICON-D2 at 2.2km resolution |
| 6 | [BrightSky](https://brightsky.dev/) | Unlimited | NO | Yes | Yes | Germany | Yes | Clean REST wrapper for DWD; open source |
| 7 | [WeatherUnlocked](https://developer.weatherunlocked.com/) | 60K/day | YES | 7 days | Yes | Global | Non-commercial | Most underrated high-limit free API |
| 8 | [OpenWeatherMap](https://openweathermap.org/price) | 1M/month (60/min) | YES | 3-hour | Yes | Global | Limited | Watch endpoints — One Call API 4.0 has diff limits |
| 9 | [WeatherAPI.com](https://www.weatherapi.com/) | 1M/month | YES | 3 days | Yes | Global | Limited | Includes air quality + astronomy on free tier |
| 10 | [Weatherstack](https://weatherstack.com/) | 1M/month | YES | Yes | Multi-year | Global | Limited | Good for multi-year historical lookups |
| 11 | [WorldWeatherOnline](https://www.worldweatheronline.com/developer/) | Generous/day | YES | 15 days | Yes | Global | Limited | 15-day hourly forecast; UV index; JSON + XML |
| 12 | [Tomorrow.io](https://www.tomorrow.io/weather-api/) | Limited/day | YES | Yes | 20 years | Global | Non-commercial | 60+ data layers; AI/ML post-processed |
| 13 | [Visual Crossing](https://www.visualcrossing.com/weather-api) | 1K/day | YES | Yes | Yes | Global | Limited | Pay $0.0001/call after free limit |
| 14 | [Meteosource](https://www.meteosource.com/) | 400/day | YES | Yes | Yes | Global | Non-commercial | AI/ML bias-corrected model output |
| 15 | [Copernicus CDS](https://cds.climate.copernicus.eu/) | Unlimited (TB scale) | YES (free) | Seasonal (6mo) | ERA5 from 1940 | Global | Yes | EU-managed; GRIB/NetCDF; use `cdsapi` Python lib |
| 16 | [ECMWF Open Data](https://www.ecmwf.int/en/forecasts/datasets/open-data) | Free subset | YES (free) | HRES + ENS | Limited | Global | CC BY 4.0 | Gold-standard "European Model" open subset |
| 17 | [AWS Open Data (NOAA)](https://registry.opendata.aws/noaa-gfs-pds/) | Unlimited (S3 egress free) | NO | Yes | Yes | Global | Yes | Pull NEXRAD Level II radar or GFS directly from S3 |
| 18 | [Meteostat](https://meteostat.net/en/docs) | Generous (Python lib) | YES (free) | Limited | From ~1950s | Global | Limited | Python lib bypasses API limits for bulk historical |
| 19 | [MET Norway / Yr.no API](https://api.met.no/) | Generous | YES (free) | Yes | No | Global (best Arctic) | Limited | Backend for many pro apps; very accurate Arctic data |
| 20 | [Meteo-France MeteoNet](https://meteofrance.github.io/meteonet/) | Unlimited (dataset) | NO | No | 3-year snapshot | France | Yes | ML/AI training dataset; radar + satellite + stations |
| 21 | [Synoptic Open Access](https://synopticdata.com/open-access) | Free (academic) | YES (free) | No | Yes | Global | Academic only | 100K+ stations; QC-filtered data; students/researchers |
| 22 | [EUMETSAT Data Store](https://data.eumetsat.int/) | Free | YES (free) | No | Yes | Global/EU | Yes | Raw Meteosat + Sentinel-3 satellite imagery |
| 23 | [Space Weather Portal (LASP)](https://lasp.colorado.edu/space-weather-portal/) | Unlimited | NO | Yes | Yes | Space/Solar | Yes | Solar flares, geomagnetic storms; LaTiS API stream |
| 24 | [RainViewer API](https://www.rainviewer.com/api.html) | Free | NO | Radar only | Short-term | Global | Yes | Free global radar tile server; build your own rain map |
| 25 | [Blitzortung.org](https://www.blitzortung.org/) | Free | NO | No | Limited | Global | Yes | Community lightning network; real-time ms-latency strikes |
| 26 | [AVWX.rest](https://avwx.rest/) | Free tier | YES (free) | TAF (aviation) | No | Global | Limited | Parses METAR + TAF into clean JSON, aviation-focused |
| 27 | [RAMMB SLIDER](https://rammb-slider.cira.colostate.edu/) | Free | NO | Satellite viz only | Limited | Global | Yes | Uncompressed GOES-16/18 imagery, 1-min intervals |
| 28 | [Tropical Tidbits](https://www.tropicaltidbits.com/) | Free | NO | Yes | No | Tropics/Global | Yes | Hurricane tracking and deep model analysis tool |
| 29 | [Pivotal Weather](https://www.pivotalweather.com/model.php) | Free | NO | Yes (model viz) | No | Global | Yes | Good forecaster tool with GFS, ECMWF, HRRR, NAM imagery |
| 30 | [BUFKIT](https://training.weather.gov/wdtd/tools/BUFKIT/) | Free | NO | Yes (profiles) | No | US | Yes | Skew-T diagrams; NWS pro tool for atmospheric profiling |

---

