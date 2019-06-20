# Arctic-vs-Antarctic-Sea-Ice-Extent-Over-Time
A visual comparison of Arctic vs Antarctic Sea Ice Extent

In the accompanying jupyter notebook, Arctic and Antarctic sea ice extent over time is explored to determine if the Antarctic is also experiencing a decrease (as observed in the Arctic). 

Sea ice extent data was sourced online (see jupyter notebook for links) and imported into the notebook. The data for both regions was interrogated to ensure that records matched, before creating a dataframe containing the Year, Month and regional sea ice extents. A place holder for Day was added to the dataframe to enable the generation of a date-time value in the dataframe. (Note: Count was used as a data check). 

The resulting dataframe was used to determine the max and min recorded sea ice extents per year for each region; and a new min / max dataframe created.

After an initial exploration, a final plot was generated showing:

•	monthly mean sea ice extent over time for the Arctic and Antarctic

•	the summer (hence min) sea ice extent over time for each region

•	the winter (hence max) sea ice extent over time for each region

Although the Arctic region showed a clear decrease in both the summer and winter sea ice extent, data for the Antarctic region suggests the summer sea ice extent has changed very little whilst the winter maximum appears to have increased slightly. Note: the way the data was analysed accounted for seasonal differences between the northern and southern hemispheres.
