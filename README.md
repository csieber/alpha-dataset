# alpha-dataset

This repository contains the supplemental material to the paper *Keep Calm and Don't Switch: About the Relationship Between Switches and Quality in HAS* ([[paper]](https://mediatum.ub.tum.de/doc/1415867/1415867.pdf)).
In the paper we evaluate the relationship between average video quality and switching frequency for HTTP-based video streaming.

## Files

The following files are provided in the dataset:

| File                   | Description                         | Example Notebook                           |
|------------------------|-------------------------------------|--------------------------------------------|
| data/database.csv.gz   | Optimization result                 | [results.ipynb](notebooks/results.ipynb)   |
| data/traffictraces.csv | Mobile goodput trace                | [trace.ipynb](notebooks/trace.ipynb)       |
| data/videos/*          | Segment sizes of the videos         | [segments.ipynb](notebooks/segments.ipynb) |

## Citation

If you use the provided material, please cite the following paper:

*Keep Calm and Don't Switch: About the Relationship Between Switches and Quality in HAS*, Christian Moldovan, Korbinian Hagn, Christian Sieber, Wolfgang Kellerer, Tobias Hoßfeld, pubished at the Modeling Communication Networks workshop at the International Teletraffic Congress (ITC 2017), September, 2017, Genoa, Italy.
