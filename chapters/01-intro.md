---
title: Neospatial data approaches 🧙
subject: 
subtitle: New approaches to solving real world problems using spatial data
short_title: 1. Neospatial
authors:
  - name: Vance Russell
    affiliations:
      - 3point.xyz
    email: vance@3point.xyz
license: CC-BY-4.0
keywords: data, geospatial, foss
abstract: |
  Neospatial is concept of solving real world problems using cloud native geospatial workflows and open source software.
kernelspec:
  name: python3
  display_name: Python 3
exports:
  - format: docx
  - format: pdf
    template: volcanica
    article_type: Report
# downloads:
#   - id: neospatial.pdf
#     title: neospatial intro   
---

# Neospatial 🛰️ 🌐 ☁️

## Background

## Audience

## Chapters
The book contains the following chapters

1. **Introduction**. An introduction to the concept of neospatial.
2. **CNG**. Cloud-native geospatial concepts and applications.
3. **Optimization**. Mathematical algorithms for optimizing variables for forest health and conservation.
4. **Machine Learning**. Machine learning algorithms for land use land cover change integrated with remote sensing applictaions.
5. **AI**. Practical, useful, and accurate uses of AI in geospatial and cloud-native applications.
6. **Lidar**. Lidar collection and processing workflows using open source tools and python packages.
7. **Drones**. Using drones to collect local to landscape multispectral imagery.

## Map demo
Land, carbon, and biodiversity data for supply chain impact calculations are part of reducing negative drivers of land conversion [https://doi.org/10.1101/2023.11.01.565036]. Using data from Source Cooperative rendered through Leafmap, we demonstrate how quickly you can upload, analyze, and visualize cloud-native geospatial data at large scale.

```{code-cell} python
# import dependencies
import leafmap.foliumap as leafmap
import os

# add data from deforestation carbon emissions (source.coop land, carbon, bd data)
deforest_hum_cog = 'https://data.source.coop/vizzuality/lg-land-carbon-data/deforest_by_human_lu_50km_1000m_cog.tif

# initialize map
m = leafmap.Map(center=[40, -100], zoom=4)
m
```

## Takeaways


## Resources
