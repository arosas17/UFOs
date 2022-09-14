# UFOs

## Overview 
In the process of setting up a journalism article about UFO sights, data was received in a JavaScript file about current information on UFO sightings throughout the US and CA. Although the data file is not massive, there is enough data that it could be disorganized. In addition to the disorganization, the article will be publicly displayed online. Thus, in order to organize the data, a table was created in an html file to hold the data as well as filters for multiple categories to even further the organization.

## Results 

<img src="https://github.com/arosas17/UFOs/blob/main/static/images/webpage.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="700" height="400" />

The layout the wrbpage has a fairly simple layout. The filters added have been made to show to the left of table, with placeholders found within the input boxes. In order to use the the filters, all that needs to be done is to type into one, or multiple, of the boxes. The code ```d3.selectAll("input").on("change", updateFilters);``` is made to activte the updateFilters function upon any changes that occur within the "input" element. The table will then change after clicking out of the box or by pressing the enter key. Depending what the viewer whats to look at and filter out, the search boxes will direct them to the approprate category.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Before Filter is Activated**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **After Filter is Activated**<br>
<img src="https://github.com/arosas17/UFOs/blob/main/static/images/webpage_filtered_pre.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="400" height="200" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/arosas17/UFOs/blob/main/static/images/webpage_filtered_2.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="400" height="200" />

For example, a person wants to look at all the UFO sightings in Canada. They would go to the filters and input "ca" into the searchbox under the "Enter Country" text. That person would then activate the filter.

Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.
## Summary
Overall, the webpage operates as it should. The text is displayed properly, coloring is applied, and the table filters base on the input boxes on the left. One takeaway from this new design is that the removal of the search button, which may initially throw a person off. People are more accustom to using, or at least having, a button to search or filter something after typing in the search/filter terms. An example would be the Google homepage, there exists button that would allow a person to search. Other ways that it may be improved it to add in a method to sort the table. There are a few pieces of information that would be helpful to see in an ascending or descending order, particularly date and duration. Furthermore, the borders around the search criteria could be improved visually. The borders are much longer in length than the input boxes, so it can be visually enhanced by simply decreasing the length of the borders so that it fits more snugly around the search criteria.  

