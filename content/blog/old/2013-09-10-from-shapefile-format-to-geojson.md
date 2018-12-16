---
title: From shapefile format to geojson
author: gaba
layout: post
date: 2013-09-10
url: /2013/09/10/from-shapefile-format-to-geojson/
categories:
  - data
tags:
  - data
  - GIS
  - tips
---
ogr2ogr is a very useful tool to convert data features between file formats. To convert input.shp to output.geojson:

> ogr2ogr -f geoJSON output.json input.shp

There are many operations that you can do in the middle like quering for only rows with specific attributes.
