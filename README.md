Please visit the link to view the visualization https://satgobi-g.github.io/Satgobi-g.io/Index.html
# Creating 3d Data Visualization- D3 Scatter Plot by using A-Frame

### Introduction

An all-purpose data visualization component for the [AFrame](https://aframe.io/) WebVR Framework.

### Integrating D3 Visualization
You must also include a link the [D3](https://d3js.org/) JavaScript data visualization framework.

```html
<head>
  <title>3D Visualization</title>
  <script src="https://aframe.io/releases/0.5.0/aframe.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/4.4.1/d3.min.js"></script>
  <script src="https://cdn.rawgit.com/zcanter/aframe-scatterplot/master/dist/a-scatterplot.min.js"></script>
</head>
### Data Formatting

Datasets should be formatted as follows:

```javascript
[
 {
  "Product": "Honda City",
  "Qnty": 10,
  "Sales": 7,
  "City": "Chennai"
 },
 {
  "Product": "Honda City",
  "Qnty": 7,
  "Sales": "5",
  "City": "Coimbatore"
 },
 ]
```

