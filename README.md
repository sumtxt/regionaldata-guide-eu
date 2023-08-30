# A Guide to Regional Data in Europe

The main source for Europe-wide regional data is EUROSTAT's [Regional Database](https://ec.europa.eu/eurostat/web/regions/data/database) which relies on the NUTS nomenclature to reference regional units across the continent. As boundaries of regional units change over time, the NUTS nomenclature changes over time. A useful introduction appears on the [EUROSTAT website](https://ec.europa.eu/eurostat/web/nuts/background). An overview of available data tables on the [NUTS3](./files/eurostat_nuts3_tables_avail.csv) and [NUTS2](./files/eurostat_nuts3_tables_avail.csv) level (compiled in June 2022).

Other useful data sources include:  

- [EUROSTAT NUTS Shapefiles](https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/administrative-units-statistical-units/nuts) (NUTS-3 2006-2021)
- [European NUTS-Level Election Database (EU-NED)](https://eu-ned.com/) (various years, NUTS-3 2016)
- [ARDECO Database](https://www.camecon.com/european-regional-data/) Various demographic and economic indicators (1980-2022, NUTS-3 2016-2021)
- [ESPON 2006](https://www.espon.eu/tools-maps/espon-2006-tools-database-public-files) Various demographic and economic indicators (around 2006, NUTS-3 1999-2003)
- [QoG EU Regional Dataset](https://www.gu.se/en/quality-government/qog-data/data-downloads/eu-regional-dataset) Various demographic and economic indicators, as well as quality of government and corruption risk indicators (1990-2020, NUTS-2 only)
- [Rosés-Wolf GDP Database](https://www.wiwi.hu-berlin.de/de/professuren/vwl/wg/roses-wolf-database-on-regional-gdp) (1900-2015, NUTS-2 only)
- [Meteorological Indicators](https://data.mendeley.com/datasets/sf9x4h5jfk) (1989-2018, NUTS-3 2016)
- [Facebook's Social Connectedness Index](https://dataforgood.facebook.com/dfg/docs/methodology-social-connectedness-index) (Oct 2021, NUTS-3 2016-21)
- [The Nordic Statistics database](https://www.nordicstatistics.org/): Collection of comparative Nordic statistics. 

Software: 

* [R package "eurostat"](https://cran.r-project.org/web/packages/eurostat/index.html): Tools to download data from the Eurostat database together with search and manipulation utilities.
* [R package "regions"](https://cran.r-project.org/web/packages/regions/regions.pdf): Validating sub-national statistical typologies, re-coding across standard typologies of sub-national statistics, and making valid aggregate level imputation, re-aggregation, re-weighting and projection down to lower hierarchical levels to create meaningful data panels and time series. 
