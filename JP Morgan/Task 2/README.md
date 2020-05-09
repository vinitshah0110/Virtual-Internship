<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
<img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpmc+github+img.png">
	</a>
</p>

<p align="center"> 
	<b><a href="#task">Task Overview</a></b>
	|
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	<b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/88AisH7iuw3L5N5ig" target="_blank">Link to Module 2</a></b>

<h2 id="task">Here is the background information on your task</h2>
<p>Typically, traders monitor stock prices and trading strategies by having data displayed visually on their screens in chart form. Often these charts will be accompanied by alerts that notify users when certain events occur or when preset price thresholds are hit.
JPMorgan Chase created the Perspective tool over many years to allows users to present and manipulate data feeds visually in web applications.<br>
Perspective provides a set of flexible data transforms, such as pivots, filters, and aggregations. It utilizes bleeding-edge browser technology such as Web Assembly and Apache Arrow and is unmatched in browser performance. It is engineered for reliability and production-vetted on the JPMorgan Chase trading floor and is now available to the development community as Open Source. If you want to explore that, a link is provided in the resources section. </p>

<h2>Purpose</h2>
<p>The objective of this task will be for you to fix the client-side web application so that it displays a graph that automatically updates as it gets data from the server application (see Before and After images below) Currently, the web application only gets data every time you click on the 'Start Streaming Data' button and does not aggregate duplicated data.</p>

<ol>
<li>Set up your system by downloading the necessary files, tools and dependencies.</li>
<li>Fix the broken typescript files in repository to make the web application output correctly</li>
<li>Generate a patch file of the changes you made.</li>	
</ol>

<h2 id="installation">Set Up</h2>
<p>Before you can tackle any software or development task you need to set up your development environment. Your development environment refers to your system having all the required software installed to modify the code, as well as getting the code of the project itself onto your computer. <br>
<a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m2_v8.pdf">To do this we've created a simple PDF guide on how to get your environment set up</a></p>


<h2>How to Run</h2>

<p>Similar to Task 1, start the data feed server by running the python server.</p> 
<p>Make sure your terminal / command line is in the repository first before doing any of this.</p>
<p>If you are using Windows, make sure to run your terminal/command prompt as administrator.</p>

<code> python datafeed/server3.py </code>

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install && npm start</code> to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have `npm` (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.


<h2>How to fix the code to meet the objectives</h2>
<p>To make the changes necessary to complete the objectives of this task, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m2_v2.pdf">follow this guide</a>.</p>

<h2>Submitting Changes</h2>
<p>Once you've done this, please submit the patch file as your task deliverable <br>
<a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/create_patch_file_v3a.pdf">To generate a patch file, follow the guide</a></p>
