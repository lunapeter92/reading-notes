# Day 12 Notes
Notes taken from https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/
 ## Chart.js
  - Chart.js is a Javascript plugin that uses the canvas element to easily draw charts/graphs unto the page. 
  - Charts are useful for showing data on a webpage, while allowing the user to read the data quickly and easily. 
  
  ### Setup
   - The first step to setup Chart.js on your webpage is to download the Chart.min.js file and load it into the directory that you will be working out of. 
   - You then need to import the script, `<script src="Chart.min.js"></script>`.
  
  ### Setting up Line Chart: 
   `<canvas id="chart" width="600" height="600"></canvas>`
   - The next step is to target the canvas element with `document.getElementById('chart')`.
   `new Chart(buyers).Line(buyerData);`
   
  ### Setting up Pie Chart:
    `<canvas id="chart" width="600" height="600"></canvas>`
   - The next step is to target the canvas element with `document.getElementById('chart')`.
   `new Chart(buyers).Pie(pieData, pieOptions);`
   
  ### Creating Data: 
   - The data that will be used in charts will be contained within a data Object. 
