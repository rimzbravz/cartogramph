## Synopsis

CartogramPH was developed as an alternative map visualization tool for anyone to use.
Read more about the project on stories.thinkingmachin.es/cartogramph

## Code Example

```javascript
var visID = "#vis"; //div containing the svg

var geoData = "/static/data/philippines-topo2.json"; //link to the map json source file

var thematicDataSource = "/static/data/philpopulation2015.csv"; //link to population data
var thematicColumn = "pop2015"; //thematic variable

var sequentialDataSource = "/static/data/philpoverty2015.csv"; //link to poverty data

var sequentialColumn = "poverty2015"; //variable you want to map

var mapcolor = "#ef4631";

var cartogram = new cartogramph(visID,geoData,thematicDataSource,thematicColumn,sequentialDataSource,sequentialColumn,mapcolor);
```

## Motivation

Making cartograms requires a lot of time, we want to make the process simpler.
Read more about the project on stories.thinkingmachin.es/cartogramph

## Installation

```javascript
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="http://d3js.org/topojson.v1.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/d3/3.5.6/d3.min.js" charset="utf-8"></script>
<script src="/cartogramph.js"></script>
```

Simply import JQuery, the D3 library, Topojson.js and the cartogramph.js files into your code.

## Contributors

Mika Aldaba - @hailmika

## License

This project is licensed under the terms of the MIT license.