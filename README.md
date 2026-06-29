## Awesome-free-things
Welcome to my repository, where i upload multiple free stuff, that are usually hidden deep in the internet, find what you need! If you want something to be added, like a category or anything, make an suggestion in the discussion.

Some might require an api key, so make sure to include it.

The list doesnt include not so generous weather apis (but i still included those that are atleast worth trying, yet not so generous), the list might also not have free trials whatsoever. But if a category has free trials, i shall let you know in the description

# Navigation 
Suggested for navigation (originally for TomTom)

| # | API / Service | Free Limit | Key Required? | Card Required? | Category | Commercial OK? | Specialty / Notes |
|---|---|---|---|---|---|---|---|
| 1 | [TomTom](https://developer.tomtom.com/) | 50K tiles/day + 2,500 non-tile/day | YES | NO | Routing + Geocoding + Traffic | Yes | 5 req/sec limit; commercial OK even on free plan |
| 2 | [HERE Maps](https://www.here.com/get-started) | 250K transactions/month | YES | NO | Routing + Geocoding + Traffic + Transit | Yes | Most generous monthly volume of any commercial nav API, scales to 10M before enterprise |
| 3 | [Mapbox](https://www.mapbox.com/) | 100K directions/month + 100K geocoding/month + 50K map loads/month | YES | NO | Routing + Geocoding + Maps + EV Routing | Yes | Each API has separate free bucket; EV routing available, beware of Search Box keystroke billing |
| 4 | [OpenRouteService](https://openrouteservice.org/) | 2,500/day (all endpoints combined), 40K/month, 40 concurrent | YES | NO | Routing + Geocoding + Isochrones + Matrix + POI + Elevation | Yes | Best all-in-one single key, fully open source |
| 5 | [Geoapify](https://www.geoapify.com/) | 3K/day + 90K matrix elements/month | YES | NO | Routing + Geocoding + Isochrones + POI + Map Tiles | Limited | All-in-one on one key, 90K matrix elements/month is 9x more than Google |
| 6 | [LocationIQ](https://locationiq.com/) | 5K/day | YES | NO | Routing + Geocoding | Limited | OSM-powered, global coverage |
| 7 | [Stadia Maps](https://stadiamaps.com/) | Perpetual free dev plan | YES | NO (never) | Routing (Valhalla) + Map Tiles + Geocoding | Yes | No credit card ever required, hosts Valhalla + map tiles + geocoding |
| 8 | [MapQuest](https://developer.mapquest.com/) | 15K/month | YES | NO | Routing + Geocoding | Limited | OSM-based. forgotten but still alive and free |
| 9 | [FreeRoute](https://api.maps.freeroute.org/) | Free tier (exact requires sign-up) | YES | NO | Routing + Geocoding + Map Tiles | Yes | Drop-in replacement for Google Maps or Mapbox, same SDK shape, 240+ countries |
| 10 | [GraphHopper](https://www.graphhopper.com/) | Credit-based (non-commercial and not recommended tho) | YES | NO | Routing + Geocoding + Isochrones + Map Matching | Non-commercial | 45+ turn instruction languages; GTFS public transit routing supported |
| 11 | [Trimble Maps](https://developer.trimblemaps.com/) | Free tier (must register) | YES | NO | Routing (Truck-specific) | Limited | Only free truck-specific routing API; height, weight, hazmat restrictions |
| 12 | [MapTiler Cloud](https://www.maptiler.com/cloud/) | 100K req/month + 5K sessions/month + 100MB hosting | YES | NO | Maps + Tiles + Geocoding + Routing | Non-commercial on free | Pauses (not charges) when limit hits, includes custom data hosting |
| 13 | [Jawg Maps](https://www.jawg.io/) | 25K map views/month | YES | NO | Map Tiles + Geocoding + Routing + Elevation | Limited | GDPR-compliant by design, strong choice for EU projects |
| 14 | [Protomaps](https://protomaps.com/) | 1M/month (soft cap) | YES | NO | Map Tiles only | GitHub Sponsor for commercial | Anti-SaaS design, near-$0 if self-hosted on Cloudflare R2 or S3 |
| 15 | [Nominatim (OSM)](https://nominatim.org/) | 1 req/sec (public instance) | NO | NO | Geocoding + Reverse Geocoding | Attribution (ODbL) | Keyless, OSM-powered, public instance only for low traffic so dont abuse it |
| 16 | [OpenCage](https://opencagedata.com/) | 2,500/day, 1 req/sec | YES | NO | Geocoding + Reverse Geocoding | Limited (testing only) | GDPR-compliant and with 40+ SDKs permissive storage terms |
| 17 | [Geocodio](https://www.geocod.io/) | 2,500/day | YES | NO (never) | Geocoding + Reverse (US + Canada only) | Limited | All features free including batch + Census data appends, US + Canada only |
| 18 | [CSV2GEO](https://csv2geo.com/) | 3,000/day | YES | NO | Geocoding + Address Validation + Batch | Limited | 18 endpoints on one key; batch + validation + autocomplete + cross-street lookup |
| 19 | [Photon (Komoot)](https://photon.komoot.io/) | Fair-use (no hard cap; throttled at scale) | NO | NO | Geocoding + Autocomplete | Attribution (ODbL) | Keyless, autocomplete-optimized; hosted by Komoot |
| 20 | [Photon (GraphHopper hosted)](https://graphhopper.com/) | 2,500/day | YES | NO | Geocoding | Non-commercial | GraphHopper-managed Photon instance; more reliable than Komoot public instance |
| 21 | [Geocode Earth](https://geocode.earth/) | 1,000/day, 10 req/sec | YES | NO | Geocoding + Autocomplete + Reverse | Yes | Results can be stored permanently, built by original Pelias/Mapzen team |
| 22 | [US Census Geocoder](https://geocoding.geo.census.gov/) | Unlimited | NO | NO | Geocoding + Batch (US only) | Yes | Official US govt, batch geocoding; US addresses only |
| 23 | [Apple MapKit JS](https://maps-api.apple.com/) | 250K map views/day + 25K service calls/day | YES (Apple Dev acct) | NO | Maps + Geocoding + Directions | Yes | Apple Maps quality data, massively underused by developers |
| 24 | [Maps.co](https://geocode.maps.co/) | 25K requests (demo tier) | NO | NO | Geocoding | Limited | Dead simple REST + JSON. good for demos and prototyping ig |
| 25 | [what3words](https://what3words.com/public-api) | Free tier (sign up to confirm) | YES | NO | Geocoding (3-word address system) | Limited | Converts coordinates to/from 3-word addresses, used by emergency services worldwide |
| 26 | [BigDataCloud](https://www.bigdatacloud.com/) | Unlimited | NO | NO | Reverse Geocoding only | Yes | Keyless; no signup, no rate limits, zero friction |
| 27 | [DAWA Geocoder](https://dawadocs.dataforsyningen.dk/) | Unlimited | NO | NO | Geocoding (Denmark only) | Yes | Danish government official address database |
| 28 | [BAN (Base Adresse Nationale)](https://adresse.data.gouv.fr/api-doc/adresse) | Unlimited | NO | NO | Geocoding (France only) | Yes | French national address database and government-backed |
| 29 | [Geoclient API (NYC)](https://api.nyc.gov/geoclient/v2/) | Unlimited | YES (free NYC dev acct) | NO | Geocoding (NYC only) | Yes | Official NYC geocoder, authoritative for New York City addresses |
| 30 | [IPinfo.io](https://ipinfo.io/) | 50K/month | YES | NO | IP Geolocation | Limited | Most generous IP geolocation free tier yet in this list, HTTPS on free tier |
| 31 | [IPGeolocation.io](https://ipgeolocation.io/) | 30K/month | YES | NO | IP Geolocation | Limited | Includes proxy detection + ASN + currency on free tier |
| 32 | [ipapi.co](https://ipapi.co/) | 1K/day | NO | NO | IP Geolocation | Limited | Keyless, field-specific queries to reduce payload size |
| 33 | [ip-api.com](http://ip-api.com/) | 45 req/min | NO | NO | IP Geolocation | Non-commercial only | Keyless, no HTTPS on free tier; non-commercial only |
| 34 | [FreeIPAPI](https://freeipapi.com/) | 60 req/min | NO | NO | IP Geolocation | Yes | Keyless + commercial OK, batch up to 50 IPs per request |
| 35 | [USPS Web Tools](https://www.usps.com/business/web-tools-apis/) | Unlimited | YES (free) | NO | Address Validation (US only) | Yes | Official USPS source, authoritative for US delivery points |
| 36 | [ZipCodeStack](https://zipcodestack.com/) | 100/day | YES | NO | Postal Code Validation + Distance | Limited | Distance calculation between two zip codes in one call |
| 37 | [Smarty](https://www.smarty.com/) | 250/month | YES | NO | Address Validation (US + 240+ countries) | Limited | No card required; US + international address validation |
| 38 | [HERE Public Transit API](https://www.here.com/docs/bundle/public-transit-api-developer-guide/) | 250K/month (shared HERE quota) | YES | NO | Transit Routing + Departures + Station Search | Yes | Hidden within HERE free tier, bus/train/metro routing globally |
| 39 | [MTA API (NYC)](https://api.mta.info/) | Unlimited | NO | NO | Real-time Transit (NYC) | Yes | Official NYC transit; subway, bus, LIRR, Metro-North; GTFS-Realtime |
| 40 | [CTA API (Chicago)](https://www.transitchicago.com/developers/) | Unlimited | YES (free) | NO | Real-time Transit (Chicago) | Yes | Bus Tracker + Train Tracker + Customer Alerts API |
| 41 | [Entur (Norway)](https://api.entur.io/) | Unlimited (fair use) | NO | NO | All Transit Modes (Norway) | Yes (NLOD license) | All of Norway's public transport in one GraphQL API, buses, trains, ferries, trams |
| 42 | [iRail (Belgium)](https://api.irail.be/) | Unlimited | NO | NO | Rail Transit (Belgium) | Yes (Creative Commons) | Belgian rail real-time data, open source |
| 43 | [OC Transpo (Ottawa)](https://www.octranspo.com/en/plan-your-trip/travel-tools/developers/) | Unlimited | YES (free) | NO | Transit (Ottawa, Canada) | Yes | Bus + transit, next departure by stop, station, name, or number |
| 44 | [Transitland](https://www.transit.land/) | 6 req/sec; 1K routing/month | YES (free) | NO | Global GTFS + GTFS-Realtime + Routing | Non-commercial | Largest GTFS aggregator on earth, historical feed archive, 99+ countries |
| 45 | [MBTA V3 API (Boston)](https://www.mbta.com/developers/v3-api) | 1,000 req/min | YES (free) | NO | Real-time Transit (Boston) | Yes (MassDOT license) | Subway, bus, commuter rail, ferry and JSON:API format |
| 46 | [NPS GTFS](https://www.nps.gov/subjects/developer/gtfs.htm) | Unlimited | NO | NO | Transit (US National Parks) | Yes | Shuttle systems inside US National Parks, Yosemite, Grand Canyon, Zion |
| 47 | [Mobility Database](https://mobilitydatabase.org/) | Unlimited (open catalog) | YES (free) | NO | Global GTFS + GTFS-Realtime Catalog | Depends on feed | 6,000+ feeds in 99+ countries, every transit agency's data in one place |
| 48 | [Walk Score Transit API](https://www.walkscore.com/professional/public-transit-api.php) | Free (request access) | YES (free) | NO | Transit Score + Stop Data | Limited (branding req) | Only API giving walkability + transit score per address |
| 49 | [511 SF Bay](https://511.org/open-data/) | 1 req/min (60 req/hour) | YES (free) | NO | Transit (SF Bay Area) | Yes | All SF Bay Area agencies in one API, GTFS + GTFS-Realtime |
| 50 | [Malaysia Open API](https://api.data.gov.my/) | Unlimited | NO | NO | Transit (Malaysia) | Yes | KTMB + Prasarana (LRT, MRT, monorail, bus); GTFS-Realtime |
| 51 | [OneBusAway](https://onebusaway.org/) | Unlimited | YES (free per deployment) | NO | Transit (Multiple US Cities) | Yes (Apache license) | Seattle, Tampa, DC and more; GTFS-Realtime vehicle positions + alerts |
| 52 | [GBFS Feeds](https://gbfs.org/) | Unlimited (no key by spec) | NO | NO | Bike Share + Scooter + Micromobility | Varies per operator | 1,000+ systems in 45+ countries like Lime, Bird, Citi Bike all publish free feeds |
| 53 | [CityBikes API](https://api.citybik.es/v2/) | Unlimited | NO | NO | Aggregated Bike Share | Yes | Aggregates hundreds of GBFS systems into one unified keyless REST API |
| 54 | [Open Topo Data](https://www.opentopodata.org/) | 1K/day, 1 req/sec, 100 locations/req | NO | NO | Elevation | Yes | Compatible with Google Maps Elevation API, multiple datasets for ML Training |
| 55 | [Open-Elevation](https://open-elevation.com/) | 1K/month hosted | NO | NO | Elevation | Yes (GPLv2) | Open-source Google Elevation API alternative, global coverage |
| 56 | [AISstream.io](https://aisstream.io/) | Free WebSocket stream | YES | NO | Maritime + Vessel Tracking | Limited | Real-time WebSocket stream of global vessel positions |
| 57 | [AISHub](https://www.aishub.net/) | Free (contribution-based for full access) | YES | NO | Maritime + Vessel Tracking | Limited | AIS data sharing network, contribute receiver for full access |
| 58 | [TimeZoneDB](https://timezonedb.com/) | Unlimited (1 req/sec) | YES | NO | Timezone | Non-commercial only | Unlimited queries but 1 req/sec rate limit, non-commercial only on free |
| 59 | [TimeAPI.io](https://timeapi.io/) | Unlimited | NO | NO | Timezone + Current Time | Yes | Keyless and returns UTC offset, DST status, local time for any IANA timezone |
| 60 | [Overpass API (OSM)](https://overpass-api.de/) | Fair use (no hard cap) | NO | NO | POI + OSM Data Query | Attribution (ODbL) | Query any OSM data like roads, amenities, buildings, stops for any area on Earth |
| 61 | [GeoDB Cities](https://rapidapi.com/wirefreethought/api/geodb-cities/) | 86,400/day | YES | NO | City + Region Data | Limited | City population, location, timezone, currency, country info |

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






