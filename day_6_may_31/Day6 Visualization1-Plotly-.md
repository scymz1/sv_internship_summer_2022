
# Visualization1-Plotly 
> Date: May/31/2022
> Group: Zhihao Wan & Jiran Yang
- Jiran Yang: Implement the `React-Plotly` and `pie-charts` finish 3 instances.
- Zhihao Wan: Draw `Plotly` with the `fetch` API data on React Application 


### What is the Plotly?
we use `React-Plotly` package(library) to draw the plotly and the `fetch` module to get the data that plotly need. 



[link: React-plotly](https://plotly.com/javascript/react/)
[link: Plotly.js](https://plotly.com/javascript/)


### What is it good for?
- The plotly.js is with over 40 chart types, including 3D charts, statistical graphs, and SVG maps.
- The API fetch is successful, and it could be the prototype of fetching `Voyages` API stuff.



### How can we use it?
**Plotly**
```javaScript
npm install plotly.js-dist

or 

yarn install plotly.js-dist
```

**Plotly-React**
```javaScript
npm install react-plotly.js plotly.js
```

For the examples(Bar charts, Pie charts, Filled-area-plots)

[Bar charts](https://plotly.com/javascript/bar-charts/)
<br>
[Pie charts](https://plotly.com/javascript/pie-charts/)
<br>
[Filled-area-plots](https://plotly.com/javascript/filled-area-plots/)

![charts](plotly%20charts.png)



### Do I want it?
Yes, but we still need to figure out one issue, which we still could not get the `Voyages` API data (This issue is same as Jason's `Request`) 

it is the `CORS` proble: 
![cors](CORS%20problem.jpeg)


### Shrtcoming (What we fail to finish right now):
1. CORS problem.
2. cannot find a way to create UI like nested menus using plotly.js 
3. cannot find any example using plotly to do the slider in js, the use of slider in plotly mostly is changing the chart's color or range.



### Upcoming Task List:
    1. Transform the Dash Core Components to React useable components

