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

```
python -m src.networkassignment.__main__ -vvv \
    --env .env \
    sample-data/input/skimTijd_new_REF.mtx \
    sample-data/input/skimAfstand_new_REF.mtx \
    sample-data/input/nodes_v5.zip \
    sample-data/input/Zones_v6.zip \
    sample-data/input/SEGS2020.csv \
    sample-data/input/links_v5.zip \
    sample-data/input/SupCoordinatesID.csv \
    sample-data/input/Cost_VehType_2016.csv \
    sample-data/input/Cost_Sourcing_2016.csv \
    sample-data/input/CarryingCapacity.csv \
    sample-data/input/EmissieFactoren_BUITENWEG_LEEG.csv \
    sample-data/input/EmissieFactoren_BUITENWEG_VOL.csv \
    sample-data/input/EmissieFactoren_SNELWEG_LEEG.csv \
    sample-data/input/EmissieFactoren_SNELWEG_VOL.csv \
    sample-data/input/EmissieFactoren_STAD_LEEG.csv \
    sample-data/input/EmissieFactoren_STAD_VOL.csv \
    sample-data/input/logistic_segment.txt \
    sample-data/input/vehicle_type.txt \
    sample-data/input/emission_type.txt \
    sample-data/output/
```