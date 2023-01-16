# Network-Assignment
This module assigns shipments and parcel trips to the road networks

## Introduction

The Network assignemnt module is a static traffic assignment developed to assign trip matrices generated from parcel and shipment scheduling modules to the road networks.the result of this model is the intensities on road networks where the number of truck passing each link can be validated with actual truck counts.

## Installation

## Execution

### Examples

```
python3 __module_TRAF__.py \
    Label Input Output \
    skimTijd_new_REF.mtx \
    skimAfstand_new_REF.mtx \
    nodes_v5.shp \
    Zones_v6.shp \
    SEGS2020.csv \
    links_v5.shp \
    SupCoordinatesID.csv \
    Cost_VehType_2016.csv \
    Cost_Sourcing_2016.csv \
    CarryingCapacity.csv \
    EmissieFactoren_BUITENWEG_LEEG.csv \
    EmissieFactoren_BUITENWEG_VOL.csv \
    EmissieFactoren_SNELWEG_LEEG.csv \
    EmissieFactoren_SNELWEG_VOL.csv \
    EmissieFactoren_STAD_LEEG.csv \
    EmissieFactoren_STAD_VOL.csv
```