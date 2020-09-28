# UFOs

## Overview of Project
The goal of this assignment is to use HTML, CSS, and Javascript to create an interactive webpage with user submitted sightings of UFO's. Since there is a lot of sightings listed our we provide the user some search tools to filter the data.

### Results of Mission to Mars
On the first filter we can see the view of the webpage has narrowed down to 2 items vs the huge list that would normally be available to scroll through:
![filter_city](https://raw.githubusercontent.com/si1ver1/UFOs/master/static/images/filter_city.png) 
From there if the user wishes they can filter it even further (for example if they still had a list of items left). Here we filter out the shapes:
![filter_shape](https://raw.githubusercontent.com/si1ver1/UFOs/master/static/images/filter_shape.png)

### Summary
There are a couple drawbacks to our current setup. The first is if we filter the data and then remove our filter we do not see the additional data come back. To do so we need to refresh the page. The second issue is that the user may not know what search terms are available without looking through the data.

Two recommendations we have to solve both of the above issues:

* We can adjust so code so that is checks the filters and updates the results when the user removes any fields.
* Instead of search filters would could use a dropdown menu for some of the options which the user can use to select from. This way it is both easier for the user to know what is available and won't misspell any search items.# UFOs
