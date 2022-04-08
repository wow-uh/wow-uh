---
title: National map of median bed-material sediment particle size
summary: Map of D50 over the contiguous US in a vector format that corresponds to approximately 2.7 million river segments.
tags:
- Data
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: 'Image credit: [**HyRiver**](https://hyriver.readthedocs.io/en/latest/notebooks/rem.html)'
#   focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://github.com/E3SM-Project/E3SM
url_code: "https://doi.org/10.5281/zenodo.4921987"
url_pdf: "https://doi.org/10.1029/2020WR029343"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Bed-material sediment particle size data, particularly the median sediment particle size (D50), are critical for understanding and modeling riverine sediment transport. However, sediment particle size observations are primarily available at individual sites. Large-scale modeling and assessment of riverine sediment transport are limited by the lack of continuous regional maps of bed-material sediment particle size. We hence present a map of D50 over the contiguous US in a vector format that corresponds to approximately 2.7 million river segments (i.e., flowlines) in the National Hydrography Dataset Plus (NHDPlus) dataset. We develop the map in four steps: (1) collect and process the observed D50 data from 2577 U.S. Geological Survey stations or U.S. Army Corps of Engineers sampling locations; (2) collocate these data with the NHDPlus flowlines based on their geographic locations, resulting in 1691 flowlines with collocated D50 values; (3) develop a predictive model using the eXtreme Gradient Boosting (XGBoost) machine learning method based on the observed D50 data and the corresponding climate, hydrology, geology, and other attributes retrieved from the NHDPlus dataset; and (4) estimate the D50 values for flowlines without observations using the XGBoost predictive model. We expect this map to be useful for various purposes, such as research in large-scale river sediment transport using model- and data-driven approaches, teaching environmental and earth system sciences, planning, and managing floodplain zones, etc. The map is available at https://doi.org/10.5281/zenodo.4921987 (Li et al., 2021a).
