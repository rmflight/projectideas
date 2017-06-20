# Accident Density

This analysis would be to compare the number of accidents along different sections
of roadway to see if there are areas with higher than expected accidents.

## Motivation

I live in Kentucky, and there is a section of I-64 between Lexington and Louisville
that I feel has a higher than expected number of accidents. However, I would like
to see if my hunch is true using some sort of statistical analysis.

## Data

* [Kentucky collision reports](http://crashinformationky.org/KCAP/Public/Downloads.aspx):
Probably the most useful, as it includes **all** collision reports in KY, not just
fatalities.

* [NHTS FARS data](ftp://ftp.nhtsa.dot.gov/fars/)

* [Transtats](https://www.transtats.bts.gov/Databases.asp?Subject_ID=1&Subject_DESC=Safety&Mode_ID2=3)

## How?

Need to work out how to get contiguous roadway coordinates into `R`, and then
map the collisions onto it, and then analyze density in a rolling window along
the roadway.
