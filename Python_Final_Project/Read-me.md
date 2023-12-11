Read-me

Project description 

	The purpose of this project is to legally scrape data using python coding on the most streamed songs on Spotify since its release date from the Wikipedia website: https://en.wikipedia.org/wiki/List_of_Spotify_streaming_records  along with other software(s).  The data extracted from the website will be processed and stored in SQLite before placing it on a website where the user can view, update and delete the data. 

Requirements

	To achieve this project, the requirements provided below must be accomplished: 
		1.	Data collection
			a.	The data has to be scraped legally from https://en.wikipedia.org/wiki/List_of_Spotify_streaming_records   by using the Beautiful Soup software. It involves collecting 100 observations with the following columns:
				i.	Rank
				ii.	Song
				iii.	Artist(s)
				iv.	Streams
				v.	Release date
		2.	Data Processing
			a.	The data collected from the website has to be cleaned for readability. It includes converting the values with three decimal places into two decimal places in the Streams column and removing hyphens from the song titles.
		3.	Database
			a.	The adjusted data is stored in the SQLite database as one table with the table named “spotify.database.db” using the recommended software SQLite3.
		4.	Website
			a.	The website is created using the software: Flask, SQLAlchemy, where the user can interact with the data. The website will have basic information showing the user how to use the site. The site will have the following.
				i.	About page on how to use the site 
				ii.	Metadata on the variables and source of the data extraction
				iii.	The user should be able to do the following on the website.
					1.	Search for an artist by their song title and able to see the result.
					2.	Update the database by reallocating the row up or down with the corresponding song.
					
		5.	Repository Structure
			a.	The coding files related to this project should be in a single GitHub repository, containing the following:
				i.	  – Python_Project_WebScraping_Spotify.ipynb
				ii.	   – Spotify_data_processing.ipynb
				iii.	   – SpotifyStreamingRecords_database.ipynb
				iv.	   – Spotify_Top_100.ipynb
				v.	   - Readme.md
				vi.	   - requirements.txt
				vii.	- Group_project.html
Usage
	1.	Save the GitHub repository onto your computer.
	2.	Install python software into your system.
	3.	Open the jupyter notebook and execute the commands by selecting the run button 
		a.	Data collection and pre-processing by opening the below files:
			i.	Python_Project_WebScraping_Spotify.ipynb
			ii.	Spotify_data_processing.ipynb
		b.	Converting the process data into database format by opening below:
			i.	SpotifyStreamingRecords_database.ipynb
		c.	Open the below file to start the website
			i.	Spotify_Top_100.ipynb

Submission
	This project will be submitted by uploading the link to the GitHub repository with all the related codes.
	



