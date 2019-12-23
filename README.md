# UFOs_pdouglass

## Project Description
* The purpose of this page is to import unorganized array data from an external javascript file of UFO sitings and arrange the data into table form. 
* Table data can be viewed as is, but user has the option to input selection criteria to filter data table to a bespoke view. User may filter on date, location and physical attribute of UFO. 

## Challenges
* At first blush, this seems like a very straightforward assignment. Setting up the filters and updated HTML page are routine with some refactoring of the  filtering loops to allow for resetting the filter without refreshing the page. 
* The challenge for me has been understanding how to loop through the filtering function by calling within a separate function as I'm unclear on how to pass what into the function parans. 
* Separately, I was hoping to be able to have the filter update as I tabbed through a selection box but could not find documentation to explain that step though that seems secondary to the filtering evocation within a separate function. 

## Other Considerations
* Next steps would be create a more broad date criteria (e.g. between dates, recurring dates, etc.)
* Code should be modified to consider capitalization of state abbreviations or if a user types in an entire state name rather than two-letter abbreviation. 
