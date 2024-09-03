# safeBeachBS

| <img "https://github.com/secchildo/safeBeachBS/blob/3448fe42432dc9c9503dca00fd09f91204abbdab/logo.png" width="35%"> |
|:--:| 


The Northwestern Black Sea (NWBS) have a wide range of beaches which are exposed to different wind wave conditions. In this sense, safeBeachBS is an application which helps to identify hazardous conditions at beaches. This application uses Marine Copernicus capabilities together with morphohydrodynamic model to identify unsafe conditions at  7 beaches of the NWBS:

- Ropotamo Beach (Bulgary)
- Kavatsite Beach(Bulgary)
- Burgas Beach (Bulgary)
- Sunny Beach (Bulgary)
- Modern Beach (Romenia)
- Sfântu Gheorghe Beach (Romenia)
- Moncastro Beach (Ukraine)

## Modelling Approach

XBeach (https://xbeach.readthedocs.io/en/latest/) is employed as a morphodynamical model capable to resolve the processes at nearshore scale. The results of XBeach model make it possible to identify strong currents and erosion in suficient details to prevant risks for the beach users. This model relay on Copernicus Marine Service, which provide data to force the model ina hourly interval. The specific dataset used are the Black Sea Physics Analysis and Forecast (https://data.marine.copernicus.eu/product/BLKSEA_ANALYSISFORECAST_PHY_007_001/description) and Black Sea Waves Analysis and Forecast (https://data.marine.copernicus.eu/product/BLKSEA_ANALYSISFORECAST_WAV_007_003/description).  


## Signaling safety

## Identifying hazards with safeBeachBS
