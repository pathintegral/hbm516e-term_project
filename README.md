# HBM516E - Term Project

## Introduction

This project aims to visualize CNN outputs by using Paraview. 5 of ImageNet classes are used. Each class has 5 examples, also. Those classes:

- tiger_cat
- tabby_cat
- sport_car
- doberman
- rotweiller

## Folder Structure

- outputs-resized-single-filter: ResNet-50 outputs of 25 examples.
- netcdf: NetCDF files of 25 examples.
- images: Images of 25 examples.
- animations: Paraview animations of 5 examples, 1 from each class.
- states: Saved states during visualizations.
- create_nc.ipynb: Takes ResNet-50 outputs and generate NetCDF files.
