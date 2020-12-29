# Data Feed Visual of Stocks
This project allows you to both visualize and analyze share price data of different stocks.

## Overview
his project utilizes JP Morgan's Perspective Visualization open source code to generate a chart that displays the data feed in a clear and visually appealing manner for traders to monitor this trading strategy.
Features:
- Track and display the ratio between the two stock prices.
- Show the historical upper and lower bounds of the stocks' ratio.
- Show 'alerts'  whenever these bounds are crossed by the ratio, which a trader can use to determine to sell a stock if it is increasing in price or to buy a stock if the prices are lower than normal.
- Trigger 'alerts' on the graph whenever the bounds are crossed by the calculated ratio in a specific time period

## Demo
![A test image](Graphics/Server-Client.png)

## Installation
In order to get the server and client application code working on your machine, [follow the setup here]("https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m3_v3.pdf").

**Note:** This is the version of the JPM 3 exercise that uses Python 3. The Python 2.7 version is in [this other repo]("https://github.com/insidesherpa/JPMC-tech-task-3").

## How to Run
Similar to Task 2, start the data feed server by running the python server.

Make sure your terminal / command line is in the repository first before doing any of this.

If you are using Windows, make sure to run your terminal/command prompt as administrator.














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

