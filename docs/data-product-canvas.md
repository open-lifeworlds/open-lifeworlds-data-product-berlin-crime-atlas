
# Data Product Canvas - Berlin LOR Crime Atlas

## Metadata

* owner: Open Lifeworlds
* description: Data products providing Berlin crime data on different LOR hierarchy levels
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas
* license: CC-BY 4.0
* updated: 2025-11-09

## Input Ports

### berlin-lor-geodata

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/refs/heads/main/data-product-manifest.yml

### berlin-crime-atlas-source-aligned

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-crime-atlas-source-aligned/refs/heads/main/data-product-manifest.yml

## Transformation Steps

* [Data extractor](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/extract/data_extractor.py) extracts data from inout ports
* [Data blender](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/transform/data_blender.py) blends csv data into geojson files

## Output Ports

### berlin-crime-atlas-geojson
name: Berlin Crime Atlas Geojson
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/tree/main/data/03-gold/berlin-crime-atlas-geojson
* license: CC-BY 4.0
* updated: 2025-11-09

**Files**

* [berlin-crime-atlas-2012-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2012-00-city.geojson)
* [berlin-crime-atlas-2012-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2012-00-district-regions.geojson)
* [berlin-crime-atlas-2012-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2012-00-districts.geojson)
* [berlin-crime-atlas-2012-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2012-00-forecast-areas.geojson)
* [berlin-crime-atlas-2013-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2013-00-city.geojson)
* [berlin-crime-atlas-2013-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2013-00-district-regions.geojson)
* [berlin-crime-atlas-2013-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2013-00-districts.geojson)
* [berlin-crime-atlas-2013-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2013-00-forecast-areas.geojson)
* [berlin-crime-atlas-2014-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2014-00-city.geojson)
* [berlin-crime-atlas-2014-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2014-00-district-regions.geojson)
* [berlin-crime-atlas-2014-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2014-00-districts.geojson)
* [berlin-crime-atlas-2014-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2014-00-forecast-areas.geojson)
* [berlin-crime-atlas-2015-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2015-00-city.geojson)
* [berlin-crime-atlas-2015-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2015-00-district-regions.geojson)
* [berlin-crime-atlas-2015-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2015-00-districts.geojson)
* [berlin-crime-atlas-2015-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2015-00-forecast-areas.geojson)
* [berlin-crime-atlas-2016-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2016-00-city.geojson)
* [berlin-crime-atlas-2016-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2016-00-district-regions.geojson)
* [berlin-crime-atlas-2016-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2016-00-districts.geojson)
* [berlin-crime-atlas-2016-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2016-00-forecast-areas.geojson)
* [berlin-crime-atlas-2017-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2017-00-city.geojson)
* [berlin-crime-atlas-2017-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2017-00-district-regions.geojson)
* [berlin-crime-atlas-2017-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2017-00-districts.geojson)
* [berlin-crime-atlas-2017-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2017-00-forecast-areas.geojson)
* [berlin-crime-atlas-2018-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2018-00-city.geojson)
* [berlin-crime-atlas-2018-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2018-00-district-regions.geojson)
* [berlin-crime-atlas-2018-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2018-00-districts.geojson)
* [berlin-crime-atlas-2018-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2018-00-forecast-areas.geojson)
* [berlin-crime-atlas-2019-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2019-00-city.geojson)
* [berlin-crime-atlas-2019-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2019-00-district-regions.geojson)
* [berlin-crime-atlas-2019-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2019-00-districts.geojson)
* [berlin-crime-atlas-2019-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2019-00-forecast-areas.geojson)
* [berlin-crime-atlas-2020-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2020-00-city.geojson)
* [berlin-crime-atlas-2020-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2020-00-district-regions.geojson)
* [berlin-crime-atlas-2020-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2020-00-districts.geojson)
* [berlin-crime-atlas-2020-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2020-00-forecast-areas.geojson)
* [berlin-crime-atlas-2021-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2021-00-city.geojson)
* [berlin-crime-atlas-2021-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2021-00-district-regions.geojson)
* [berlin-crime-atlas-2021-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2021-00-districts.geojson)
* [berlin-crime-atlas-2021-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2021-00-forecast-areas.geojson)
* [berlin-crime-atlas-2022-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2022-00-city.geojson)
* [berlin-crime-atlas-2022-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2022-00-district-regions.geojson)
* [berlin-crime-atlas-2022-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2022-00-districts.geojson)
* [berlin-crime-atlas-2022-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2022-00-forecast-areas.geojson)
* [berlin-crime-atlas-2023-00-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2023-00-city.geojson)
* [berlin-crime-atlas-2023-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2023-00-district-regions.geojson)
* [berlin-crime-atlas-2023-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2023-00-districts.geojson)
* [berlin-crime-atlas-2023-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-geojson/berlin-crime-atlas-2023-00-forecast-areas.geojson)


### berlin-crime-atlas-statistics
name: Berlin Crime Atlas Statistics
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/tree/main/data/03-gold/berlin-crime-atlas-statistics
* license: CC-BY 4.0
* updated: 2025-11-09

**Files**

* [berlin-crime-atlas-statistics.json](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-crime-atlas/refs/heads/main/data/03-gold/berlin-crime-atlas-statistics/berlin-crime-atlas-statistics.json)


## Observability

### Quality metrics

 * name: geojson_property_completeness
 * description: The percentage of geojson features that have all necessary properties

| Name | Value |
| --- | --- |
| berlin-crime-atlas-2012-00-city.geojson | 100 |
| berlin-crime-atlas-2012-00-districts.geojson | 100 |
| berlin-crime-atlas-2012-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2012-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2013-00-city.geojson | 100 |
| berlin-crime-atlas-2013-00-districts.geojson | 100 |
| berlin-crime-atlas-2013-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2013-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2014-00-city.geojson | 100 |
| berlin-crime-atlas-2014-00-districts.geojson | 100 |
| berlin-crime-atlas-2014-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2014-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2015-00-city.geojson | 100 |
| berlin-crime-atlas-2015-00-districts.geojson | 100 |
| berlin-crime-atlas-2015-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2015-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2016-00-city.geojson | 100 |
| berlin-crime-atlas-2016-00-districts.geojson | 100 |
| berlin-crime-atlas-2016-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2016-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2017-00-city.geojson | 100 |
| berlin-crime-atlas-2017-00-districts.geojson | 100 |
| berlin-crime-atlas-2017-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2017-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2018-00-city.geojson | 100 |
| berlin-crime-atlas-2018-00-districts.geojson | 100 |
| berlin-crime-atlas-2018-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2018-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2019-00-city.geojson | 100 |
| berlin-crime-atlas-2019-00-districts.geojson | 100 |
| berlin-crime-atlas-2019-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2019-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2020-00-city.geojson | 100 |
| berlin-crime-atlas-2020-00-districts.geojson | 100 |
| berlin-crime-atlas-2020-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2020-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2021-00-city.geojson | 100 |
| berlin-crime-atlas-2021-00-districts.geojson | 100 |
| berlin-crime-atlas-2021-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2021-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2022-00-city.geojson | 100 |
| berlin-crime-atlas-2022-00-districts.geojson | 100 |
| berlin-crime-atlas-2022-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2022-00-district-regions.geojson | 100 |
| berlin-crime-atlas-2023-00-city.geojson | 100 |
| berlin-crime-atlas-2023-00-districts.geojson | 100 |
| berlin-crime-atlas-2023-00-forecast-areas.geojson | 100 |
| berlin-crime-atlas-2023-00-district-regions.geojson | 100 |


## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

consumer-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).