Kiva Field Partner Explorer
===========================
The Kiva Field Partner Explorer was created by the [Parson's Institute for Information Mapping](http://piim.newschool.edu/) as part of the DARPA XDATA program to demonstrate the type of stand-alone visualization widget that might compliment a composite dashboard display for a decision-maker/analyst. 

The widget leverages an open API to reveal aspects of the Kiva ecosystem, an emerging force in the new financial landscape and potential breeding ground for money laundering, arbitrage, and other types of financial abuse. 

Specifcally, the widget visualizes Kiva [Field Partner](http://www.kiva.org/partners) data (from their [GetPartners](http://build.kiva.org/api#GET*|partners) API method) as an interactive, zoomable radial pie-chart. By mapping said data against country information from Wikimedia's [country code list](https://github.com/wikimedia/limn-data/blob/master/geo/country-codes.json), the widget allows users to explore the various field partners and the countries in which their funded recipients reside. Additionally, by visualizing self-reported data, the widget has the potential to flag erroneous reporting to regulators when compared with similar readouts of the same data collected internally or through alternative means.

Looking at the visualization itself, the outermost ring represents lenders, the middle ring represents countries funded, and the innermost ring representsg the continents said countries belong to. Hovering over a lender highlights its other instances, indicating additional countries in which they have conducted lending activity. 

Running
-------
To install the Kiva Field Partner Explorer:

- `cd` to the root directory
- `bower install` to install the project dependencies

Then, simply pull up the index.html file over localhost to view.

Modification
------------
The explorer is built using D3 and Javascript, so anyone with working knowledge of these tools/languages should be able to modify the widget as needed.