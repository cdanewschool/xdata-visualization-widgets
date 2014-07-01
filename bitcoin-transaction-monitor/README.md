Bitcoin Transaction Monitor
===========================
The Bitcoin Transaction Monitor was created by the [Parson's Institute for Information Mapping](http://piim.newschool.edu/) as part of the DARPA XDATA program to demonstrate the type of stand-alone visualization widget that might compliment a composite dashboard display for a decision-maker/analyst. 

The widget leverages an open API to reveal aspects of the Bitcoin ecosystem, an emerging force in the new financial landscape and potential breeding ground for money laundering, arbitrage, and other types of financial abuse. Using this tool or one like it, it is envisioned that analysts interested in illicit use of the cryptocurrency could spot suspicious trends and clusters of trading activity that might require further investigation. By visualizing self-reported data, the widget also has the potential to flag erroneous reporting to regulators when compared with similar readouts of the same data collected internally or through alternative means.

The monitor uses websockets to visualize real-time transactions in [D3](http://d3js.org), as reported by the blockchain.info's [Websocket API](http://blockchain.info/api/api_websocket). Similar to the monitor featured on [bitcoinmonitor.com](http://bitcoinmonitor.com/) (on which it is heavily based), transactions are shown in blue, trades in red, and newly-minted blocks in yellow. 

Running
-------
To run the Bitcoin Transaction Monitor:

- `cd` to the root directory
- `bower install` to install the project dependencies

Then, simply pull up the index.html file over localhost to view.

Modification
------------
The explorer is built using D3 and Javascript, so anyone with working knowledge of these tools/languages should be able to modify the widget as needed.