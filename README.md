# 2020 Homework 1

1. Write a shell script called `count_fires.sh` which does all of the following.
   * Download a comma delimited datasets from data.gov file which are listing of fires in several decades. (hint use `curl`)
     * [1990s](https://gis.data.cnra.ca.gov/datasets/653647b20bc74480b335e31d6d81a52f_4.csv) https://catalog.data.gov/dataset/1990s-b2103
     * [2000s](https://gis.data.cnra.ca.gov/datasets/653647b20bc74480b335e31d6d81a52f_12.csv) - https://catalog.data.gov/dataset/2000s
     * [2010s](https://gis.data.cnra.ca.gov/datasets/653647b20bc74480b335e31d6d81a52f_11.csv) - https://catalog.data.gov/dataset/2010s
   * Print out the number of fires for each decade (hint use `wc`)
   * Print out the number of fires in each year (hint use `cut` and `uniq`)
   * Print out the largest fire (hint use `sort`) - use the `GIS_ACRES` column
   * Print out the total acerage burned in each year.
