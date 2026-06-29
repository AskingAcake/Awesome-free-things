## Awesome-free-things
Welcome to my repository, where i upload multiple free stuff, that are usually hidden deep in the internet, find what you need! If you want something to be added, like a category or anything, make an suggestion in the discussion.

Some might require an api key, so make sure to include it.

The list doesnt include not so generous weather apis (but i still included those that are atleast worth trying, yet not so generous), the list might also not have free trials whatsoever. But if a category has free trials, i shall let you know in the description

# Weather forecasts and data
This included alot of good apis, so make sure to check them out, took me a good while to find few good ones.

| # | API / Service | Free Limit | Key Required? | Forecast | Historical Data | Coverage | Fine with commercial use? | Specialty / Notes |
|---|---|---|---|---|---|---|---|---|
| 1 | [Open-Meteo](https://open-meteo.com/) | 10K/day, 5K/hr, 600/min (Unlimited if self-hosted) | NO | 16 days | From 1940 (ERA5) | Global | CC BY 4.0 (non-commercial on free tier) | Self-host via Docker for truly unlimited; 30+ models |
| 2 | [NWS weather.gov](https://www.weather.gov/documentation/services-web-api) | Unlimited (no published cap) | NO | Yes | Limited | US Only | Yes | Official US govt; just add a User-Agent header |
| 3 | [NASA POWER](https://power.larc.nasa.gov/) | Unlimited (no published cap) | NO | Limited | Multi-decade | Global | Yes | Solar radiation, agricultural, climate data |
| 4 | [WMO WWIS](https://worldweather.wmo.int/) | Unlimited (no published cap) | NO | Yes | No | Global | Yes | Direct UN/govt source and raw JSON by city ID |
| 5 | [DWD Open Data](https://opendata.dwd.de/) | Unlimited (no published cap) | NO | Yes | Yes | Germany/EU | Yes | FTP-style server, raw ICON-D2 at 2.2km resolution |
| 6 | [BrightSky](https://brightsky.dev/) | Unlimited (no published cap) | NO | Yes | Yes | Germany | Yes | Clean REST wrapper for DWD, open source |
| 7 | [WeatherUnlocked](https://developer.weatherunlocked.com/) | 60K/day | YES | 7 days | Yes | Global | Non-commercial | Best high-limit free API with good stuff|
| 8 | [OpenWeatherMap](https://openweathermap.org/price) | 1M/month, 60/min (Free Weather API path) 1K/day (One Call 3.0/4.0 path) | YES | 3-hour intervals | Yes | Global | Limited | Two separate product paths with different limits becareful do not mix |
| 9 | [WeatherAPI.com](https://www.weatherapi.com/) | 1M/month | YES | 3 days | Yes | Global | Limited | Includes air quality + astronomy + free map tiles on free tier |
| 10 | [Weatherstack](https://weatherstack.com/) | 100K/month, historical limited to 1 day back | YES | Yes | 1 day back only (free) | Global | Limited | Historical depth is severely limited on free tier |
| 11 | [WorldWeatherOnline](https://www.worldweatheronline.com/developer/) | 500/day | YES | 14 days | From July 2008 | Global | Limited | Includes marine tides + ski resort elevation forecasts |
| 12 | [Tomorrow.io](https://www.tomorrow.io/weather-api/) | 500/day (no weekly/monthly cap beyond daily) | YES | 14 days | Core params only on free | Global | Non-commercial | Pollen, lightning, air quality are paid only sadly ;-; |
| 13 | [Visual Crossing](https://www.visualcrossing.com/weather-api) | 1K/day | YES | Yes | 50+ years | Global | Limited | Multi-date in one call, Timeline LLX endpoint for IoT/mobile |
| 14 | [Meteosource](https://www.meteosource.com/) | 400/day | YES | Yes | Yes | Global | Non-commercial | AI/ML bias-corrected model output |
| 15 | [Copernicus CDS](https://cds.climate.copernicus.eu/) | Unlimited (TB scale) | YES (free) | Seasonal (6mo) | ERA5 from 1940 | Global | Yes | EU-managed; GRIB/NetCDF, use cdsapi Python lib, good for old historical storage ig |
| 16 | [ECMWF Open Data](https://www.ecmwf.int/en/forecasts/datasets/open-data) | Free subset (no published cap so) | YES (free) | HRES + ENS | Limited | Global | CC BY 4.0 | Gold-standard European Model open subset, check it out |
| 17 | [AWS Open Data / NOAA](https://registry.opendata.aws/noaa-gfs-pds/) | Unlimited (S3 egress free) | NO | Yes | Yes | Global | Yes | Pull NEXRAD Level II radar or GFS directly from S3 buckets |
| 18 | [Meteostat](https://meteostat.net/en/docs) | Generous (Python lib bypasses limits) | YES (free) | Limited | From ~1950s | Global | Limited | Python lib bypasses API limits for bulk historical pulls |
| 19 | [MET Norway / Yr.no](https://api.met.no/) | Unlimited (caching encouraged; no hard cap published) | NO | Yes | No | Global (best Arctic) | CC license | Backend for many pro apps as it has very accurate Arctic/Nordic data |
| 20 | [Meteo-France MeteoNet](https://meteofrance.github.io/meteonet/) | Unlimited (dataset) | NO | No | 3-year snapshot | France | Yes | ML/AI training dataset with radar + satellite + stations |
| 21 | [Synoptic Open Access](https://synopticdata.com/open-access) | Free (academic only; no published hard cap) | YES (free) | No | Yes | Global | Academic only | 100K+ stations, QC-filtered data for students/researchers |
| 22 | [EUMETSAT Data Store](https://data.eumetsat.int/) | Free (no published cap) | YES (free) | No | Yes | Global/EU | Yes | Raw Meteosat + Sentinel-3 satellite imagery |
| 23 | [Space Weather Portal (LASP)](https://lasp.colorado.edu/space-weather-portal/) | Unlimited (no published cap) | NO | Yes | Yes | Space/Solar | Yes | Solar flares, geomagnetic storms, LaTiS API stream |
| 24 | [RainViewer API](https://www.rainviewer.com/api.html) | Unlimited (no published cap) | NO | Radar only | Short-term | Global | Yes | Free global radar tile server, build your own rain map |
| 25 | [Blitzortung.org](https://www.blitzortung.org/) | Unlimited (no published cap) | NO | No | Limited | Global | Yes | Community lightning network; real-time ms-latency strikes |
| 26 | [AVWX.rest](https://avwx.rest/) | Free hobby tier; daily cap (resets 00:00Z); exact number not published | YES (free) | TAF  | No | Global | Limited | Basic METAR + TAF parsing free; other features require paid plan |
| 27 | [RAMMB SLIDER](https://rammb-slider.cira.colostate.edu/) | Unlimited (no published cap) | NO | Satellite viz only | Limited | Global | Yes | Uncompressed GOES-16/18 imagery, 1-min intervals, Colorado State Uni |
| 28 | [Tropical Tidbits](https://www.tropicaltidbits.com/) | Unlimited (no published cap) | NO | Yes | No | Tropics/Global | Yes | Hurricane tracking + deep model analysis, used by pro meteorologists |
| 29 | [Pivotal Weather](https://www.pivotalweather.com/model.php) | Unlimited (no published cap) | NO | Yes (model viz) | No | Global | Yes | Industry standard model viewer; GFS, ECMWF, HRRR, NAM imagery |
| 30 | [BUFKIT](https://training.weather.gov/wdtd/tools/BUFKIT/) | Unlimited (no published cap) | NO | Yes (profiles) | No | US | Yes | Skew-T diagrams; NWS pro tool for atmospheric profiling |
| 31 | [API-Ninjas Weather](https://api-ninjas.com/api/weather) | 10K/month | YES | 5 days (3hr intervals) | No | Global | Limited | Simple, clean, no fuss |
| 32 | [Meteoblue](https://www.meteoblue.com/en/weather-api) | 5K/year (~13/day) 1-year free then expires | YES | 14 days | 4 days back | Global | Non-commercial | 100+ variables; agro + solar packages; research-grade |
| 33 | [NOAA CDO](https://www.ncei.noaa.gov/cdo-web/) | 10K/day, 5/sec | YES (email token) | No | Global archive | Global | Yes | Separate from weather.gov; daily/monthly/yearly historical records |
| 34 | [Stormglass](https://stormglass.io/) | 10/day | YES | Yes | Yes | Global | Limited | Marine chemical composition, wave height, energy, soil — all params free |
| 35 | [Google Maps Platform](https://mapsplatform.google.com/maps-products/weather/) | Demo sandbox only (no card required) | YES (demo key) | Yes | No | Global | Demo only | AI-powered; includes Weather + Air Quality + Pollen + Solar APIs |
| 36 | [Xweather / AerisWeather](https://www.xweather.com/) | Free tier (exact limit not publicly published, must sign up to see ig) | YES | Yes | Yes | Global | Limited | Best free mapping + weather visualization layers |
| 37 | [Pirate Weather](https://pirateweather.net/) | 20K/month (667/day) | YES | Yes | 7 days back | Global | Limited | Drop-in Dark Sky replacement; same JSON format; open source |
| 38 | [Weatherbit](https://www.weatherbit.io/) | 50/day | YES | 7 days | Yes | Global | Non-commercial | 50,000+ station sources; includes AQ API on same platform |
| 39 | [Weather2020](https://weather2020.com/) | 1K/day | YES | Up to 1 year ahead | No | Global | Limited | LRC model; only free API with 1-year ahead long-range forecasts |
| 40 | [NOAA Tides and Currents](https://api.tidesandcurrents.noaa.gov/api/prod/) | Unlimited (no published cap) | NO | Yes | Yes | US Coastal | Yes | Buoy/tide/coastal data, completely separate from weather.gov |
| 41 | [AviationWeather NOAA](https://aviationweather.gov/data/api/) | Unlimited (no published cap) | NO | TAF (aviation) | METAR archive | Global | Yes | METARs, TAFs, PIREPs, SIGMETs, AIRMETs; direct from NOAA Aviation Center |
| 42 | [Farmonaut](https://farmonaut.com/api-development/) | Free tier (exact limit not publicly published, must sign up to see ig) | YES | Yes | 20 years | Global | Limited | Agri + NDVI + EVI + GDD + soil moisture + weather combo |
| 43 | [JMA](https://www.jma.go.jp/bosai/forecast/) | Unlimited (no published cap) | NO | Yes | No | Japan | Yes | Official Japan Met Agency, direct JSON, keyless, CORS-enabled |
| 44 | [BOM FTP](http://www.bom.gov.au/catalogue/data-feeds.shtml) | Unlimited (no published cap) | NO | Yes | Yes | Australia | Non-commercial | Anonymous FTP, XML/JSON forecasts + radar + satellite |
| 45 | [BOM Space Weather](https://sws-data.sws.bom.gov.au/) | Unlimited (no published cap) | YES (free) | Yes | Yes | Australia/Space | Yes | Australian Space Weather Forecasting Centre, aurora alerts |
| 46 | [UK Met Office DataHub](https://datahub.metoffice.gov.uk/) | Free tier (exact daily limit not publicly published, must sign up to see ig) | YES (free) | Yes | Yes (UK obs) | Global | Limited | had replaced old DataPoint API, and has 45K global forecast locations |
| 47 | [SILO / Australian Long Paddock](https://www.longpaddock.qld.gov.au/silo/) | Unlimited (email address required in query instead of key) | Kind of (email in query) | No | From 1889 | Australia | CC BY | Queensland govt, 0.05 degree resolution, longest free archive |
| 48 | [DPIRD](https://www.dpird.wa.gov.au/online-tools/apis/) | Free tier (exact limit not publicly published, must sign up to see ig) | YES (free) | Yes | Yes | Western Australia | Limited | WA agricultural weather station network, high-quality regional data |
| 49 | [weather.tsukumijima.net](https://weather.tsukumijima.net/) | Unlimited (0.5s minimum between requests) | NO | Yes | No | Japan | Unclear | Unofficial JMA scraper, clean JSON, almost zero English docs, so use a translator |
| 50 | [weather-au](https://github.com/tonyallan/weather-au) | Unlimited (no published cap and unofficial as of what i think) | NO | Yes | Yes | Australia | Non-commercial | Unofficial Python lib hitting BOM unpublished beta API endpoints |
| 51 | [SMHI Open Data](https://opendata.smhi.se/) | Unlimited (no published cap) | NO | Yes | Yes | Sweden/Nordic/Baltic | Yes | Swedish Met Institute, completely unknown outside Scandinavia |
| 52 | [FCOO Denmark](https://www.fcoo.dk/) | Unlimited (no published cap) | NO | Yes | Yes | North Sea/Baltic | Yes | Danish defence weather, precision marine data for North Sea routing |
| 53 | [CurrentUVIndex.com](https://currentuvindex.com/api) | 500/day per IP | NO | No | No | Global | CC BY 4.0 | UV only, keyless, IP-based rate limit |
| 54 | [UVIndexAPI.com](https://uvindexapi.com/) | 1K/day per IP | NO | No | No | Global | Yes | UV + NOAA data, keyless, commercial OK |
| 55 | [OpenUV.io](https://www.openuv.io/) | 50/day (free tier) | YES | No | No | Global | Limited | UV + ozone + skin type health recommendations |
| 56 | [Swellcloud](https://swellcloud.com/) | Free key (exact limit not publicly published; must sign up to see) | YES | Yes | No | Global | Limited | Surf/wave/marine specialist, 0.25 degree resolution |
| 57 | [AgroMonitoring](https://agromonitoring.com/) | Free tier (exact limit not publicly published; must sign up to see) | YES | Yes | Yes | Global | Limited | Soil + NDVI + satellite + weather combo for agriculture |
| 58 | [Meteomatics](https://www.meteomatics.com/en/weather-api/) | TRIAL ONLY, 14 days, 500 queries/day, 50/min, 10 parallel | YES | Yes | Yes | Global | Trial only | 1800+ parameters, widest parameter list of this list but not a true generous free tier sadly |

I added Meteromatics, tho it is trial only, it is still pretty informational, so i still have added it




