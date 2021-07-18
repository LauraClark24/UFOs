# UFOs

## Overview
This project is less geared towards manipulating numbers to understand nuance about the data and instead is all about presenting the data such that it is simple to read and easy to filter on any of multiple criteria. As such, there is less analysis as seen in previous projects, and this analysis will be more about the look and ease of filtering as intended. 
## Results
The way to sort results is optimal if it acts as a newcomer expects it to, and I believe that is a relatively accurate for our site. After a brief glance, you should see that the input boxes have the same names as the columns, thereby indicating that, to sort a specific column, you should go to the box with the same label. 

![Screenshot1](https://user-images.githubusercontent.com/83182353/126084934-5fd89d5e-e6ab-4c92-ba25-827bc88b2588.png)

Typing into the input box is the only course of action that should make sense, and it is the correct decision, followed up with hitting the enter key, a natural move to indicate a complete input.

![Screenshot2](https://user-images.githubusercontent.com/83182353/126084937-e1dc5cf1-9463-4ce6-a2b1-add259808a64.png)

At this point, the webpage will redraw the table with an appropriately filtered list.

![Screenshot3](https://user-images.githubusercontent.com/83182353/126084940-77ec6cf0-671a-4bd5-8a67-4aadfbc9e4cf.png)

It is optional to give another input, same process as before, in a new field, and further sort the table or change the input in a field to get a different subset of the data. 

![Screenshot4](https://user-images.githubusercontent.com/83182353/126084941-6025dd42-905c-455e-ac40-22de24c7d22e.png)

## Summary
 The filter may act as expected on the surface, but there are some limitations. Any misspelling will fail to return the desired results, while on the programing side, capital letters that aren’t included in the data set will also throw off the results. This can be fixed most simply by ensuring input will be changed to lower case before being compared, but at that point, the data to be filtered should also be entirely lower case when compared, just to ensure no problems like the one we are trying to avoid are created if someone decides to add more data to this set. From a visibility standpoint, the solid dark isn’t a great choice for the list. It would be beneficial to find a second color that matches the existing dark scheme but is different from the current background and make every other row of our table this secondary color instead, making it easier to read across each row. Although these are not the only improvements, these would be simple, beneficial improvements. 
