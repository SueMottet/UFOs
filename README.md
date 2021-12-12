# UFO Sitings web page with dynamic content using JavaScript
## Overview
Using JavaScript and HTML, this analysis creates a dynamic web page to use for researching UFO sitings.

### Analyis details:
1. A grid of UFO sitings data is presented via Bootstrap components.
2. JavaScript functions are written to create list elements for filtering the data, capturing text entered on change of entry points, and refreshing the grid on the web page filtering based on the filter criteria.

#### Software: JavaScript (ES6+), Bootstrap

## Results
 The web page provides the ability to search the UFO sitings dataset of 2010 sitings by proving the ability to filter and refilter the data by city, state, country, and shape. The data is filterable by any combination of these parameters. The filtered search results are presented in a table grid on the web page. If you clear out a column, a user will need to click enter (keyboard) to get the table grid to refresh again removing the cleared filter data.

 Here is a snapshot of the web page showing the overall web page setup:

  ![full page image](/resources/fullPage.png)
 
### Single-select filtering:
A user can filter just by one of the options. 

For example Date:

 ![date image](/resources/Date.png)

### Multi-select filtering
A user can also filter by combinations of the filter options.

For example Date and City:

 ![date city image](/resources/dateCity.png)

 Or Date, City and Shape:

 ![date city shape image](/resources/dateCityShape.png)

## Summary
The UFO sitings web page works well with the provided data. This dataset is however static and will require refreshing to stay current. The web page would be more useful over all if it provided a way for a user to refresh the page and get more/new data.

## References:
JavaScript - Double Equals vs. Triple Equals: https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a
