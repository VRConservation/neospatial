---
title: Lidar
subject: Article
subtitle: Using lidar point clouds to analyze and visualize forest structure
short_title: Lidar
authors:
  - name: Vance Russell
    affiliations:
      - 3point.xyz
    email: vance@3point.xyz
license: CC-BY-4.0
keywords: data, geospatial, open-science
abstract: |
  We introduce Lidar
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

# Lidar

```{code} python
# import libraries
import whitebox
import whitebox_workflows as wbw
import geemap
import rioxarray as rxr
import rasterio
import earthpy as et
import earthpy.plot as ep
import matplotlib.pyplot as plt
import geopandas as gpd
from rasterio.plot import plotting_extent
```

```{code} python
# instantiate whitebox tools
wbt = whitebox.WhiteboxTools()
```

