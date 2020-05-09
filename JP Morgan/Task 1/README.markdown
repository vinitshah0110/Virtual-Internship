<br>
<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
<img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpm+gitub+.png"></a>
</p>

<p align="center"> 
	<b><a href="#task">Task Overview</a></b>
	|
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	<b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/gtAhtcvke9AFCzqME" target="_blank">Link to Module 1</a></b>		
	| 
	<b><a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience">JP Morgan Chase & Co Software Engineering Virtual Experience</a></b>
</p>

<h1> Introduction</h1> 
<b> Experience Technology at JP Morgan Chase & Co</b>
<p>Try out what real work is like in the technology team at JP Morgan Chase & Co. Fast track to the tech team with your work.</p>

<h2 id="task"> Module 1 Task Overview </h2>
<p>Interface with a stock price data feed and set up your system for analysis of the data</p>
<p> <b>Aim:</b> You’ve been asked to assist with some development to add a chart to a trader’s dashboard allowing them to better identify under/over-valued stocks.
<br>
The trader would like to be able to monitor two historically correlated stocks and be able to visualize when the correlation between the two weakens (i.e. one stock moves proportionally more than the historical correlation would imply). This could indicate a potential trade strategy to simultaneously buy the relatively underperforming stock and sell the relatively outperforming stock. Assuming the two prices subsequently converge, the trade should be profitable.</p>

<ol>
	<li>Set up your system by downloading the necessary repository, files, tools and dependencies</li>
	<li>You'll have to make the modifications in getDataPoint, getRation and main method for compute the right stock price.</li>
	<li>Once you have applied changes in the client application, you now have to ensure you cover them in enough unit tests in bonus task</li>
	<li>Generate a patch file of the changes you made</li>
	
</ol>

<h2 id="installation" >Set up / Installation</h2>

<p>In order to get the server and client application code working on your machine, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m1_v6.pdf">follow the setup here</a></p>
<p><b>Note:</b>This is the Python 3 version of the JPM 1 exercise. The Python 2.7 version is in <a href="https://github.com/insidesherpa/JPMC-tech-task-1">this other repo</a></p>

<h2>How to Run</h2>
To start the server, run

	python server3.py

this will create random market called 'test.csv' in your working directory if one does not already exist.

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip yet, you can install it from: https://pip.pypa.io/en/stable/installing/

To start the example client, run:

	python client3.py

To test the example client, run:
	python client_test.py

<h2>How to request from the server using curl</h2>
<!--See also [client.py](https://github.com/texodus/exchange_simulator/blob/master/client.py)-->
Query:

	$ curl 'http://localhost:8080/query?id=1'
	{"id": "1", "top_ask": {"price": 129.18, "size": 70}, "timestamp": "2016-08-06 12:32:11.821574", "top_bid": {"price": 128.79, "size": 61}}

<h2>How to fix the code to meet objectives</h2>
<p>To make the changes necessary to complete the objectives of this task, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m1_v4a.pdf">follow this guide</a>.</p>
<p>Bonus Task <br>
The bonus task is completely optional and servers as a bonus. This task involves adding tests to the methods in the client application so that developers are more confident these methods work as expected with different inputs given to them.
<a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/client_test_m1_v1a.pdf">A link to a guide on how to do this</a></p>

<h2>Submitting Changes</h2>
<p>Please upload a git patch file as the submission to this task <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/create_patch_file_v3a.pdf">To generate a patch file, follow the guide</a></p>
