# UFO_Challenge

## Overview

The purpose of this analysis is to use HTML and Javascript to filter through a table filled with UFO data sightings, allowing users to better refine their searches and populate the UFO sighting table data with customized information. 


## Results

In order to perform a search for one field such as the date, enter the exact date in order to filter the UFO sighting data and press "Filter Table":
![UFODataFilter1](https://github.com/tylerfallon/UFO_Challenge/blob/main/static/images/ufo2date.png?raw=true)

Entering text into multiple search fields allows the data to be further refined:
![UFODataFilter3](https://github.com/tylerfallon/UFO_Challenge/blob/main/static/images/ufo3multi.png?raw=true)

You can enter text into all of the fields at once in order to perform a fully-refined search using all of the data inputted for matching:
![UFODataFilter4](https://github.com/tylerfallon/UFO_Challenge/blob/main/static/images/ufo4all.png?raw=true)


In order to clear the filters and populate the table with all of the data again after performing a search, clear the form. It will show gray sample text that says "1/10/2010", but this can simply be ignored, as it does not cause a filtered search to occur. Pressing "Filter Table" will remove all filters and repopulate the complete data in the table, as shown below:
![UFODataFilter2](https://github.com/tylerfallon/UFO_Challenge/blob/main/static/images/ufo1empty.png?raw=true)


## Summary

### Drawbacks 

There are a few drawbacks withg this webpage. One of the primary issues is that data must be searched for exactly, and even a small typo or modification in the way data is typed into the field, such as adding a "0" to the date field (01/09/2010 vs 1/9/2010) will cause issues with the search results. 

### Recommendations 

There are a few recommendations that could vastly improve the user experience on this webpage. First, the search fields should not be case sensitive and should allow for similar or near-exact versions of the same types of searches, as mentioned above in the Drawbacks section of this README. This improvement would allow users to more reliably obtain filtered data. In addition, users should be able to search for text in the "Comments" section that will allow for different types of sightings to be searched for based on descriptions of each UFO sighting. 
