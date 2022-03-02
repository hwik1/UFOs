# UFOs
Module 11 challenge prepared by Hannah Wikum - March 2022
___

## Resources
Data Source: data.js (provided)

Software: JavaScript, HTML, Visual Studio Code
___

## Overview
For this challenge, I used HTML and JavaScript to transfer data on UFO sightings onto a webpage that could be filtered based on a variety of criteria. The data included the date, location (city, state, country), shape, duration, and comments about various reported UFO sightings. Below is a sample from the data.js file, which includes one of my favorite observations.

_Sample of Data_

![Sample data](https://user-images.githubusercontent.com/93058069/156274497-a470df92-2f99-4a63-aa1d-3f5ef1f468a3.PNG)

Once the webpage was set up with title, text, images, and the data, I added filters on date, city, state, country, and shape so users could select any or all preferred search filters to limit the amount of sightings shown.
___

## Results
Once my coding was complete to build the webpage, it could be used for filtering. When you first open the webpage, you can see the title and a picture, a header, text paragraph with background on UFOs, and then the search criteria and full data table at the bottom. 

_Initial Webpage before Filtering_

![image](https://user-images.githubusercontent.com/93058069/156275609-19607ab4-c5e2-4828-af3b-0486480d1d65.png)

Since the full data table has too many entries to read or view at once, you can use one or more of the filters at left to narrow the results based on date, city, state, country, and shape. Each filter has an example of the text entry so the user knows the format to enter, as seen in the image below.

_Filter Options for Search_

![image](https://user-images.githubusercontent.com/93058069/156275869-df8e8935-96e8-45a5-aa39-2fc73a98e6e2.png)

In order to filter the table, you must enter at least one filter, but could add up to all five. Below is an example of the results for when I filtered for the state of Wisconsin by inputting "wi" in the "Enter a State" box and pressing "Enter." There were three UFO sightings reported in Wisconsin from our data, as you can see in the image below.

_Filtering by State_

![image](https://user-images.githubusercontent.com/93058069/156276409-4787c070-db22-4d25-9ca7-bb3e3391016d.png)

For another example, I tested filtering using two criteria for UFOs that were reported in the United States with a fireball shape. (There were more results than I expected!)

_Filter by Country and Shape_

![image](https://user-images.githubusercontent.com/93058069/156276879-00f59551-e24a-4906-ab1a-fade95a04a46.png)

To clear the filter, delete what you typed in the filter bar and press "Enter" or click into another one of entry boxes for the full table to show again.
___

## Summary
In summary, I created a webpage with information about UFO sightings, included a filterable table showing seven attributes about each sighting. Users can filter based on date, city, state, country, or shape to search for desired information. Although the webpage looks good and functions, there are a few drawbacks and things that could be added with further development.

### Drawback of Current Webpage
One of the major drawbacks of this webpage is the lack of instructions around filtering. You could add a filter for just one of the options or fill out multiple, but it doesn't specify what is required to use it. In addition, although default values are populated, it doesn't specify the format that must be used for each filter. A visitor could search for an existing state or country and not yield any results if they do not enter it correctly.

### Recommendations for Further Development
To improve the webpage, I recommend adding a dropdown menu for each filter instead of having open text fields. As mentioned above with the lack of clear instructions, visitors to the webpage won't necessarily know which dates or countries or shapes are an option. They might not understand that state needs to be entered as the two letter postal abbreviation instead of the full name (i.e. "ca" instead of "California"). A second enhancement would be to automatically narrow the state and country dropdown list based on which city was typed in to ensure the user selects a valid city/state/country combination. Finally, I would add the search button back to the page because the functionality makes it easier for visitors to the webpage to know how to filter.


