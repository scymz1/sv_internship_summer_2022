In the first half of last week, we introduced

* the current site
* the history of the project (Dr. Domingues' visit)
* the dataset
* the API
* pre-existing demo use cases for consuming the API
	* Nishant Satpathy's jupyter notebooks
	* JCM's plotly dashboards
* some underlying technologies the project is using
	* we installed docker desktop on our laptops and stood up the api on our localhosts
	* we set up git cli
	* we established ci/cd pipelines btw git and heroku

In the second half of last week, we turned to

* react components
* decomposing Xinna Pan's code
* experimenting with other react components

Effectively, in our examination of already existing react code, we drew a basic sketch of how a react app might functionally consume API data and render the necessary interfaces. As we start week 2, I want to take a step back and have us consider the problem methodologically --> *how do we want to go about building the apps*

I want us to form teams to explore a few different paths we can take:



* Visualization
	* Plotly (Zhihao & Jiran)
		* For interactive graphing
		* For toolbar/dashboard components
	* D3.js
		* interactive visualizations
		* see observable.com for some of their toolbar components
* Non-viz UI
	* Bootstrap (Lize & Minghao)
	* MUI (Alison & Gaoyuan)
	* umi (Haoyu)
	* Prime Faces (Zewen & Jiacheng)
* Requests
	* Axios (Jiasheng)

Here are the components we need:

* rangeslider
* autocomplete dropdown text search
* nested menus
* tables and cards
* assume the visualizations will be generated in plotly or d3.js (so ask whether your framework can interact well with either or both of those)
* anything else?

We will therefore break off into teams to:

* Choose a base framework (e.g., Xinna's, mui, plotly dash)
* Examine its suitability with respect to the above needs (e.g., rangeslider, autocomplete, plotly/d3 interoperability)
* Build one of the above components using API data to demonstrate your argument about whether this framework is suitable or not
* And push it to heroku :)


Note: If we have time, we may want to update our local builds, now that the remote has been updated (and for practice as another update will come in the next week or so).

Umi
(Reference: https://umijs.org/docs)
What is this?
Umi is a scalable enterprise-class front-end application framework, based on routing, and supports both configuration routing and convention routing to ensure complete routing function experience. 
It is also complemented with a complete life cycle plug-in system, covering every use case from source code to build products, and supports many function extensions and business requirements.

What is it good for?
It supports for routing and configuration.
It enables various components within the functionality of antd.
(Reference: https://ant.design/docs/react/introduce)

How can we use it?
Create umi project:
(Reference: https://v2.umijs.org/guide/create-umi-app.html#create-umi-project)
	npm create-umi myapp
	cd my app
	npm install
	npm start
Components:
	Slider:
		https://ant.design/components/slider/
	DropDown:
		https://ant.design/components/dropdown/
	AutoComplete:
		https://ant.design/components/auto-complete/
	TreeSelection:
		https://ant.design/components/tree/

Do I want to?
No, I prefer MUI and Prime Faces, which are more widely used and due to following reasons.

Shortcoming:
Cannot use when you:
* Require a browser support for IE 8 or lower
* Need to support React < 16.8
* Need to use a different routing scheme
* Require a lot of webpack customization