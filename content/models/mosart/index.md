---
title: Model for Scale Adaptive River Transport (MOSART)
summary: A new physically based runoff routing model applicable across local, regional, and global scales.
tags:
- Model
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
url_code: "https://github.com/E3SM-Project/E3SM"
url_pdf: "https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015MS000471"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

A new physically based runoff routing model, called the Model for Scale Adaptive River Transport (MOSART), has been developed to be applicable across local, regional, and global scales. Within each spatial unit, surface runoff is first routed across hillslopes and then discharged along with subsurface runoff into a “tributary subnetwork” before entering the main channel. The spatial units are thus linked via routing through the main channel network, which is constructed in a scale-consistent way across different spatial resolutions. All model parameters are physically based, and only a small subset requires calibration. MOSART has been applied to the Columbia River basin at ⅙°, ⅛°, ¼°, and ½° spatial resolutions and was evaluated using naturalized or observed streamflow at a number of gauge stations. MOSART is compared to two other routing models widely used with land surface models, the River Transport Model (RTM) in the Community Land Model (CLM) and the Lohmann routing model, included as a postprocessor in the Variable Infiltration Capacity (VIC) model package, yielding consistent performance at multiple resolutions. MOSART is further evaluated using the channel velocities derived from field measurements or a hydraulic model at various locations and is shown to be capable of producing the seasonal variation and magnitude of channel velocities reasonably well at different resolutions. Moreover, the impacts of spatial resolution on model simulations are systematically examined at local and regional scales. Finally, the limitations of MOSART and future directions for improvements are discussed.
