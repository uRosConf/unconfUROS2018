Price Kaleidoscope Hackathon - uRos 2018
================

Price Kaleidoscope
------------------

The end goal of this Hackathon is to embed into a shiny web application an interactive kaleidoscope that displays historical information on the contribution of prices of the products of the basket of goods and services of a particular country or set of countries to the overall Consumer Price Index (CPI) of this particular country or set of countries. The price contribution to the CPI is commonly defined by official statistical agencies as "the price weight".

As stated by Paul Murrell of the university of Auckland, the price kaleidoscope is fundamentally a Voronoi Treemap, with the size of different regions reflecting the percentage contribution of different price categories to the overall CPI.

The main features of the kaleidoscope are:

-   users will be able to display the price weights for different periods of time,

-   users will be able to view specific information on price weights when hovering over the different items of the kaleidoscope and

-   users will be able to download a customized kaleidoscope.

The price kaleidoscope will provide users a quick overview of the weights and price trends of the individual goods and services classes, as well as detailed information on the price trends in certain fields.

An example of the price kaleidoscope project that has already been implemented using JavaScript can be found at the Federal Statistical Office of Germany (Destatis) [website](https://service.destatis.de/Voronoi/PriceKaleidoscope.svg).

Another additions to the shiny application are:

-   to have other types of price visualization that help to analyze the evolution of prices of a given country (timeline, barcharts, scatterplots, piecharts, etc.),

-   to have a calculator that calculates and plots a personalized price index calculator,

-   to have a button that scrapes the latest data on the price weights of a specific country and that populates the price kaleidoscope with the most updated data.

More information on how to implement a price kaleidoscope can be found on Paul Murrell's [website](https://www.stat.auckland.ac.nz/~paul/Reports/pricekaleidoscope/pricekaleidoscope.html).

![alt text](images/destatis.png)
