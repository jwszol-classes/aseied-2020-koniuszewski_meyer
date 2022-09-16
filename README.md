
# Gdańsk University of Technology project ASEiED

## Contributors
- Jakub Koniuszewski
- Michał Meyer

## Description of the problem (Task 3)
Analyze the data containing information on the differentiation of the height of the terrain
by selecting the groups of areas with the highest growth (the continent of North and South America). 
The height increase at a given location should be measured with at least 10 measurement points.
Find 6 groups of areas relative to the average value of the height increase. Please put the detected areas on the map.

## Used technologies
Purpose of the project was learn about processing and analyzing vast amounts of data using cloud technologies. 
We have used Amazon EMR (Elastic MapReduce) which is a cloud big data platform for running large-scale distributed
data processing jobs. EMR features include easy provisioning, managed scaling, and reconfiguring of computing clusters.
Regarding additional technologies beside EMR (EMR 5.36.0), we have defined software configuration requirements (Hadoop 2.10.1, JupyterEnterpriseGateway 2.1.0, Spark 2.4.8, Livy 0.7.1) while provisioning the cluster.

## Given terrain data
From Amazon Simple Storage Service (Amazon S3) we can download a global dataset providing bare-earth terrain heights.
The data is split to tiles with different zoom values and is available in different formats