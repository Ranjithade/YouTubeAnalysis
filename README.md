# YouTube Analysis using Python Web Scraping

Project Overview:

Web Scraping has its major value in data mining and data visualization field. This project involves scraping data from YouTube using web scraping techniques and analyzing the collected data to gain insights into video trends, engagement metrics, and channel statistics.

I started by first creating an YouTube API Key which will be our credential to access youtube data. 
Once the API Key is generated, I have used this API key to access different youtube data. I.e. walking through the documentation given by google to use youtube API. I have used this different sections in the documentation to access different data we need to build this project. 

Then I started writing the python code to build this project. I have used Jupyter Notebook to write my python code.  I have then installed all the required python packages. So we will install "google-api-python-client" (which is the google python package required to access youtube api data), we will also install pandas and seaborn. 

Once everything is set and required packages are installed, I have started writing the code in Jupyter Notebook. 
First, I have extracted channel details from youtube. I.e. extracting details such as youtube channel name, total no of subscribers, total views and total number of videos posted by each channel. I have gathered these details for few Data Analyst/Data Scientist kind of channel and then compare these channel data with each other. For visualisation, I had to see who has the highest subscriber and who gets the most views and the total number of videos posted by these channels. I have loaded all of this data into a pandas dataframe and then analyzed it. I have also generated some basic visualization using this data so we can easily compare these multiple channels.

Then, I built a logic to extract video details from a particular channel.I extracted details such as video title, total views each video has got, total number of likes and Published date for each videos. I have extracted these details for all of the videos posted by a particular channel. I have then analyzed this data by loading it into a pandas dataframe. At the end I have created some simple visualization using Seaborn python library.

I am fetching the details of 5 most popular youtube channels of Data Analysis. 

1.The PyCoach	

2.freeCodeCamp.org	

3.Simplilearn

4.Tiff In Tech	

5.GeeksforGeeks


Steps to follow:

1. Generating API Key
	- Google Developer Console
		-Create an account 
		-Create Project
		- Enable the APIs and Services and Select Youtube Data API V3 and Enable it.
		- Go to Credentials, Create API key
2. Youtube API Documentation 
	-Developers.google.com (Youtube Data API)
	- Use Refernces to access different data from the youtube
3. Json Formater to validate the output that we get from the code we execute.

Other libraries to support our python code.

1.googleapiclient.discovery: pip install google-api-python-client

2.pandas: pip install pandas

3.seaborn: pip install seaborn

4.matplotlib: pip install matplotlib

Features:

Web Scraping: Collecting YouTube video data, including titles, views, likes and Published Date.
Data Analysis: Explore trends, patterns, and correlations within the collected YouTube data.
Visualization: Create visualizations to represent key insights.

Technologies Used:

Python

Pandas for data manipulation

Matplotlib and Seaborn for data visualization

Jupyter Notebooks for analysis
