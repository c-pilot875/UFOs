# UFOs

## Search Sightings

Code ref: `HTML`, `JavaScript`, `3d.`

### 1. Overview of Analysis

The purpose of this analysis was to create a webpage using `HTML` and `JavaScript` that displays collected data of UFO sightings and generate a series of filters users could manipulate to obtain specific data points.

![UFO_webpage](https://user-images.githubusercontent.com/115188500/213293576-41fb612f-39ef-44f0-ac22-80c184cee076.png)

### Results
## Dev 1: Filter UFO sightings on multiple criteria
file reference: index.html, app.js, data.js
### How to use the filters
Users can filter through the data by entering values in either filter: Date, City, State, County, or Shape. When users enter a value, they can press the enter key or click out of the filter box to generate the filtered data. 

![UFO_filters](https://user-images.githubusercontent.com/115188500/213293646-1d2db4e0-a861-406f-8a1f-8ff4a72015e3.png)

### Example
For example, if a user would like to see all UFO sightings in Ohio, they would use the State filter and enter "oh". 

![UFO_filter_oh](https://user-images.githubusercontent.com/115188500/213293666-70ace901-86e4-4803-a7ac-c9a3153d87f0.png)

## Dev 2: Analysis Summary

### Drawbacks of the current webpage search function
* One limitation to this search function is that users will need to know what parameters to search for along with entering the values correctly without spaces, upper cases, or special characters. Entering values the filter will not recognize will not return any results.

### Recommendatioins for further development
* Write the filter to recognize values with different text characteristics (such as Upper Case)
* Include a button for users to press once their filter values are entered (so it is more obvious)
* Include a counter for the returned results
* Include a "No results found" message when entered value criteria is not met.





