<p align="center">
</p>

<h1> Data Feed Visual of Stocks </h1> 
<b> This project allows you to both visualize and analyze share price data of different stocks. </b>
</p>
<p align="center"> 
	<b><a href="#overview">Task Overview</a></b>
	|
	<b><a href="#Demo">Demo of Program</a></b>
	| 
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	<b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/EbtbrgmwKbgqcXyGt" target="_blank">Link to Module 3</a></b>	
</p>

<h2 id="overview"> Overview </h2>

<p> This project utilizes JP Morgan's Perspective Visualization open source code to generate a chart that displays the data feed in a clear and visually appealing manner for traders to monitor this trading strategy. </p>

<p> Features: </p>
<ol>
	<li> Track and display the ratio between the two stock prices. </li>
	<li> Show the historical upper and lower bounds of the stocks' ratio.</li>
	<li> Show 'alerts'  whenever these bounds are crossed by the ratio, which a trader can use to determine to sell a stock if it is increasing in price or to buy a stock if the prices are lower than normal. </li>
	<li>Trigger 'alerts' on the graph whenever the bounds are crossed by the calculated ratio in a specific time period</li>
	
</ol>

<h2 id="Demo" > Program Demo </h2>
<a href= "Graphics/Server:Client.pdf" >





<h2 id="installation" >Setup / Installation</h2>
<p>In order to get the server and client application code working on your machine, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m3_v3.pdf">follow the setup here</a></p>

<p><b>Note</b>:This is the version of the JPM 3 exercise that uses Python 3. The Python 2.7 version is in <a href="https://github.com/insidesherpa/JPMC-tech-task-3">this other repo</a></p>

<h2>How to Run</h2>
<p>Similar to Task 2, start the data feed server by running the python server</p>
<p>Make sure your terminal / command line is in the repository first before doing any of this.</p>
<p>If you are using Windows, make sure to run your terminal/command prompt as administrator.</p>

<code>python datafeed/server3.py</code>

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install && npm start</code> to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have `npm` (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.

<h2>Known Issues</h2>
Some users seem to be having trouble with the unzipped version of the node_modules back up for windows. 
This is the alternative unzipped version:
https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz

Note: You may need to (hard) refresh the link to the public gdrive to see all of the files/folders e.g. @jpmorganchase/perspective as it takes gdrive a bit to load them for you.

<h2>How to fix the code to meet the objectives</h2>
<p>To make the changes necessary to complete the objectives of this task, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m3_v2.pdf">follow this guide</a>.</p>

