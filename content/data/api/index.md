---
title: Data API
summary: Get data from the Green Deal Data Observatory via our API
tags:
- API
date: "2021-06-01T11:00:00Z"
lastmod: "2021-07-08T11:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

authors:
- daniel_antal
- botond_vitos

image:
  caption: 
  focal_point: Smart
  preview_only: true

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/GreenDealObs
- icon: linkedin
  icon_pack: fab
  name: Connect
  url: https://www.linkedin.com/company/78556699/
- icon: database
  icon_pack: fas
  name: API
  url: https://api.greendeal.dataobservatory.eu/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Our observatory has a new data API which allows access to our daily refreshing open data. You can access the API via [api.greendeal.dataobservatory.eu](http://api.greendeal.dataobservatory.eu/) 

All the data and the metadata are available as open data, without database use restrictions, under the [ODbL](https://opendatacommons.org/licenses/odbl/) license. However, the metadata contents are fully not finalized yet. We are currently working on a solution that applies the [FAIR Guiding Principles for scientific data management and stewardship](http://www.nature.com/articles/sdata201618), and fulfills the mandatory requirements of the Dublic Core metadata standards and at the same time the [mandatory requirements](https://support.datacite.org/docs/datacite-metadata-schema-v44-mandatory-properties), and most of the [recommended requirements](https://support.datacite.org/docs/datacite-metadata-schema-v44-recommended-and-optional-properties) of DataCite. 

## Data table {#data-table}

The indicator table contains the actual values, and the various estimated/imputed values of the indicator, clearly marking missing values, too.

{{< figure src="/media/img/observatory_screenshots/GDO_API_data_table.png" caption="[api.greendeal.dataobservatory.eu](https://api.greendeal.dataobservatory.eu/database/) data retrieval" numbered="true" >}}

You can get the data in [CSV](https://api.greendeal.dataobservatory.eu/database/data.csv?_size=max) or [json](https://api.greendeal.dataobservatory.eu/database/data.json) format, or write SQL queries. (Tutorials in SQL, R, Python will be posted shortly.)

## Descriptive metadata table {#metadata-table}

{{< figure src="/media/img/observatory_screenshots/GDO_API_metadata_table.png" 
caption="[api.greendeal.dataobservatory.eu](https://api.greendeal.dataobservatory.eu/database/metadata) descriptive metadata" numbered="true" >}}

For further reference, see [Descriptive Metadata](/data/metadata/#descriptive-metadata).

## Statistical Processing metadata table {#processing-table}


{{< figure src="/media/img/observatory_screenshots/GDO_API_codebook_table.png" caption="[api.greendeal.dataobservatory.eu](https://api.greendeal.dataobservatory.eu/database/codebook) processing metadata" numbered="true" >}}

For further reference, see [Administrative (Processing) Metadata ](/data/metadata/#processing-metadata)

## Authoritative Copies 

[Greendeal Data Observatory on Zenodo](https://zenodo.org/communities/greendeal_observatory/)
