# Iowa Housing Condition Mapping

Spatial analysis and cartography for the Iowa State University Data Science for the Public Good program, AI Housing team, May to July 2023.

**Problem.** Four small Iowa communities, Ogden, Grundy Center, New Hampton, and Independence, needed a housing condition inventory to support local planning. No existing spatial dataset described the condition of individual properties.

**Data.** Field collected address records paired with condition ratings for roof, siding, and other exterior characteristics. Addresses were geocoded to latitude and longitude using the Google Geocoding API.

**Tools.** R with ggmap for geocoding, Quarto for documentation and publishing, Tableau Public for thematic mapping and dashboards.

**Map output.** Thematic point maps of roof and siding condition for New Hampton and Ogden, published as interactive Tableau dashboards with a categorical color scheme for condition class.

## What is in this repository

A documented methodology written during the internship, covering the full workflow from address cleaning through geocoding in R to final cartographic output. Published as a Quarto site.

**Live site:** 1angelinaevans.github.io/iowa-housing-condition-mapping/

## Note on data privacy

The underlying dataset contains property level address and condition information and is not published here. Screenshots and dashboards in this repository show condition classes and geographic patterns only, without identifying individual properties.
