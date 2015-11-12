#Objective (research question)
Compare and analyze the differences in two different sources radiation measurements from the vicinity of the Fukushima nuclear incident

#Motivation
There have been allegations that the Japanese government was intentionally underreporting the dose rates of their radiation measurements. We can compare the difference between government data and independently collected data to see if these allegations have any merit.

#Data to be collected
Government radiation measurements from MEXT (Japanese Government Agency). Downloaded from IAEA website
Measurements from independent "pro-data" project Safecast. Full data set downloaded from Safecast.org
* Sidenote: Safecast also has an API that can be queried

#Tasks
1. Collect and clean data (by Oct 12)
  * removing faulty measurements
  * converting measurement values to standardized units
  * converting measurement times to standardized datetimes
  * upload data into a mongodb database for easier analysis and querying
2. Investigate ways to display map and data information via processing/R (by Oct 12)
3. Compare data from two sources
  * identify and compare measured dose rates "similar measurements" that are close to each other in time and space
  * determine important/interesting/significant findings to be presented (by late Oct)
4. Visualize each dataset
5. Visualize differences in datasets

