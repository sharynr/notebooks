# notebooks
Refer to the <a href="LICENSE" target="_blank">LICENSE</a> for information about the license under which this code is made available.

This repository includes Spark notebooks for working with Cloudant data.

<strong><a href="Import-to-Cloudant.ipynb" target="_blank">Import to Cloudant</a></strong>: This notebook is intended for Python 2 with Spark 2.0. It uses SparkSession to load a CSV file stored in Bluemix object storage into a dataframe, filters that data, then writes the filtered data to a previoulsy created Cloudant database. This example notebook loads a CSV file containing Child Care providers in Massachusetts downloaded from https://data.mass.gov/Education/Program-list-for-Child-Care-Search-1-15-2015/cb6m-ccic
