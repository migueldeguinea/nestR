Updated preprint available: https://www.biorxiv.org/content/10.1101/562025v2

# nestR

## Overview

The nestR package includes functions to (1) identify nesting locations along bird movement trajectories obtained from GPS tracking data and (2) estimate the outcome of nesting attempts based on patterns of nest revisitation. The package includes functions to run the analysis as well as interactive exploratory tools and data processing and custom plotting functions. The package comes with three example datasets, each containing GPS trajectories for 2 individual-years of the following species: wood storks (*Mycteria americana*), lesser kestrel (*Falco naumanni*), and Mediterranean gull (*Ichthyaetus melanocephalus*). 

## Installation Instructions

To install the current version of nestR:
  
`remotes::install_github("picardis/nestR", build_opts = "")`

## Contribution Instructions

Contributions are welcome through [Issues](https://github.com/picardis/nestR/issues).

## Resources

Functions in nestR implement an approach first described in our manuscript: "A data-driven method to locate nest sites and estimate reproductive outcome from avian telemetry data". The manuscript is currently available as a preprint at the following link: https://www.biorxiv.org/content/10.1101/562025v2

For details on package features and example applications, check out the nestR vignette:

`vignette("nestR")`

## Data Sources

The wood stork data was provided by P. Frederick and R. R. Borkhataria at the University of Florida, USA.
The lesser kestrel data was provided by Jacopo G. Cecere at the Italian Institute for Environmental Research and Protection, Italy and Diego Rubolini at the University of Milan, Italy. 
The Mediterranean gull data was provided by Jacopo G. Cecere, Lorenzo Serra, and Simone Pirrello at the Italian Institute for Environmental Research and Protection, Italy.
