# Research Methodology

## 1. Study Design

This project uses an applied geospatial research approach to investigate how spatial data, remote sensing and participatory environmental observations can support coastal environmental governance and spatial decision-making in Epe Local Government Area, Lagos State, Nigeria.

The project is exploratory and will develop through documented stages of data acquisition, quality assessment, spatial analysis and interpretation.

## 2. Study Area

The study area is Epe Local Government Area, Lagos State, Nigeria. The research will consider the relationship between settlements, waterways, waterbodies, fisheries-related activities and relevant coastal environmental governance concerns.

The official administrative boundary will be validated before it is used to clip datasets or calculate spatial statistics.

## 3. Data Acquisition

Potential data sources include:

- Administrative boundaries from GRID3 or another suitable authoritative source.
- Waterway and waterbody datasets from documented geospatial services.
- Fisheries and aquaculture candidate locations compiled from published research, government materials, OpenStreetMap and other documented sources.
- Sentinel-2 satellite imagery for suitable environmental indicators.
- Global Fishing Watch data, subject to access, coverage and suitability checks.
- Participatory environmental observations where collection, consent and data-quality procedures permit.

Each dataset will have a documented source, acquisition date where available, coordinate reference system, intended use and known limitations.

## 4. Data Quality and Validation

Spatial data will be checked for:

- Coordinate validity and completeness.
- Geometry validity.
- Coordinate reference system consistency.
- Duplicate records.
- Positional uncertainty.
- Source reliability and date.
- Suitability for the intended analytical scale.

Candidate locations will be classified by evidence and verification status. The existence of coordinates alone will not be treated as proof that a location is correct or currently active.

## 5. Spatial Processing

Python geospatial libraries will be used for data inspection, transformation, spatial joins, clipping, quality checks and reproducible processing where appropriate.

GeoPandas, Shapely and PyProj may support vector operations. Rasterio and other suitable tools may support raster processing.

The selected projected coordinate reference system will be documented and checked for suitability for the study location and analytical purpose.

## 6. Remote Sensing

Sentinel-2 imagery may be assessed for suitable indicators, including water extent, vegetation-related indices and land-cover or shoreline change where the available imagery and methods support defensible analysis.

Cloud cover, image dates, spatial resolution, atmospheric conditions and classification uncertainty will be documented.

Satellite-derived indicators will not automatically be interpreted as direct measurements of pollution. Environmental interpretations will require appropriate evidence and validation.

## 7. Fisheries and Fishing Activity

The candidate inventory will distinguish fish markets, landing sites, jetties, aquaculture facilities and other relevant locations.

Global Fishing Watch data will be evaluated for coverage and suitability. AIS-derived vessel activity cannot be assumed to represent all artisanal fishing activity or all fishing locations in Epe.

## 8. Participatory Observations

Community observations may be incorporated where they can be collected and documented responsibly. Relevant metadata may include observation date, approximate location, observation category, source and verification status.

Sensitive personal information and location data that could create risks for contributors will not be published without appropriate safeguards.

## 9. Mapping and Outputs

Maps will include appropriate titles, legends, scale information, data sources, dates and coordinate reference information where relevant.

Planned outputs include spatial datasets, reproducible notebooks, maps, tables, an interactive map or dashboard, and a research brief.

## 10. Limitations

The completeness, currency and positional accuracy of secondary data may vary. Some locations may require field verification. Satellite imagery and vessel activity data have specific observational limitations.

All findings will distinguish observed data, analytical results, interpretations and recommendations.

## 11. Reproducibility

Processing steps, assumptions, data sources and software dependencies will be documented. Public repository contents will be reviewed to prevent disclosure of credentials, sensitive information or data that cannot appropriately be redistributed.

## 12. Current Status

This methodology describes the planned and developing workflow. It does not imply that all datasets have been validated or that satellite analysis, vessel activity analysis or field verification has been completed.
