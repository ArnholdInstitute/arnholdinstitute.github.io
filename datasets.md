---
layout: page
title: Datasets
subtitle: Datasets disseminated by the Arnhold Institute
---

## [National Drinking Water Database](https://github.com/ArnholdInstitute/National-Drinking-Water)

The [Environmental Working Group](http://www.ewg.org) publishes [data about drinking water contamination](http://www.ewg.org/tap-water/).  We've scraped this data and put it into a relational database.  The results can be found on our [Github page](https://github.com/ArnholdInstitute/National-Drinking-Water)

<div class="row" style="display: flex; justify-content: center; align-items: center">
	<a class="btn btn-primary" href="https://data.world/arnholdinst/drinking-water-contaminations">
		Download Data
	</a>
</div>

## [Copernicus Emergency Mapping Data](https://github.com/ArnholdInstitute/Copernicus-Mapping-DB)

The [Copernicus](http://emergency.copernicus.eu/mapping/ems/emergency-management-service-mapping) mapping project seeks to provide a datasource for disaster recovery.  

> The Copernicus EMS Mapping addresses, with a worldwide coverage, a wide range of emergency situations resulting from natural or man-made disasters. The satellite imagery is used as a main datasource about disasters. It covers in particular:

The data is released on their website, but is split up by disaster and region.  This makes for a large number of datasets to work with and is also in an inconvinient projection.

We've aggregated all of this data and loaded it into a convienient PostgreSQL dump.  This allows for expressive Geo-Spatial queries over the data.

<div class="row" style="display: flex; justify-content: center; align-items: center">
	<a class="btn btn-primary" target="_blank" href="https://data.world/arnholdinst/copernicus-emergency-mapping-data">
		Download Data
	</a>
</div>

## [Ocean Eddies](https://github.com/jfaghm/OceanEddies)

Mesoscale ocean eddies transport heat, salt, energy, and nutrients across the World Oceans. As a result, accurately identifying and tracking such phenomena are crucial for understanding future marine and terrestrial ecosystems and their sustainability. We have built a suite of algorithms to automatically identify and track ocean eddies on a global scale. We report the most comprehensive set of eddy statistics publicly available and open to oceanographers to explore and analyze.

The data has been released in multiple forms including an SQL (Postgres) dump and CSV

<div class="row" style="display: flex; justify-content: center; align-items: center">
	<a class="btn btn-primary" target="_blank" href="https://data.world/arnholdinst/ocean-eddies">
		Download Data
	</a>
</div>