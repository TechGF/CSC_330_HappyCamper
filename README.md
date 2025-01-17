# Happy Camper

Laura Kaplan, Victoria Jaczynski, Gary Feng

Happy Camper is an Java application that help user to locate campsites based on geo/weather datasets and user preferences.<br>
### Features:
- Filtering campsites by a preferred minimum and maximum distance from your current location
- Setting preferred rain type (raining or not raining)
- Setting preferred temperature range

## About the data and results:
***DATE RANGE: Must be between 06/01/20 and 06/08/20***<br>
User's initial zip code should be a New York state zip code.
Not all dates have good weather. The weather on 06/01/20 and 06/02/20 is particularly cold and rainy.
More campsites available at ranges over 100 miles from NYC.

## How to run:
With GUI: Happy Camper should be run from the HappyCamperView class in order to interract with the GUI.<br>
Without GUI: Functionality without the GUI should be tested from the PersonalizedResult class.<br>
Testing Classes: Most classes are set up with their own commented-out main method for individual class testing.<br>
	
	There are 3 file paths which need to be adjusted to the user's specific file-path. They are located in the classes:
		- Weather
		- Campsite
		- ZipCodeDatabase
		
## Video Walkthrough:
<img src='http://g.recordit.co/WIvfRQTGG5.gif'><br>

## Realism Note:
Some campsite names associated with multiple zip codes due to the way we combined our datasets. 
This issue would not be present with more accurate datasets.
