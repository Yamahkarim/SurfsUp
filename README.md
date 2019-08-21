# Surf's Up: A climate Application  
![surf.jpg](img/surf.jpg) 

## Objective  
Create a Flask API to provide climate data for Hawaii based on a given date range. 	

- SQLAlchemy was used to query the ORM using python 3. 

- The data was provided as a SQLlite file and used to perform a climate analysis detailing the percipatation and temperatures for the various weather stations in Hawaii. 

## Technologies 
- Python 3
- ORM Queries with SQLAlchemy 
- Flask 
- SQL 
- Pandas 
- Matplotlib
- JSON 

## Explore 
1.) Download install related technologies and dependencies 
	
- Python 3 
	*  Matplotlib 
	*  Pandas 
	*  Numpy 
	*  SQLAlchemy 
	*  Flask 
	*  Jupyter Notebook
	
- SQL
- Google Chrome (recommended) or Mozilla Firefox web browsers with related JSON beautification extentions: 

	* [Chrome](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en)

	* [Firefox](https://addons.mozilla.org/en-US/firefox/addon/basic-json-formatter/) 

2.) Clone Repo 

3.) Initialize Jupyter Notebook within the downloaded directory. 

4.) Open "FinalAnalysis.ipynb" and work through notebook to:

- Reflect tables into SQLAlchemy Object Relational Model (ORM)
- Perform the climate analysis
- Data visualizations resulting from the analysis are saved to the "Images" directory 

5.) Navigate to the repo in the CLI. Run the command: 
		
		Python app.py
		
6.) Open `http://localhost:5000` in either chrome (recommended) or firefox web browsers. 

7.) Paste the following routes to access application data:  
`http://localhost:5000/` for welcome page 
	
`http://localhost:5000/api/v1.0/precipitation` for a list of rain fall ordered by descending date
	
`http://localhost:5000/api/v1.0/stations` for a list of stations with corrersponding nate and elevation data
	
`http://localhost:5000/api/v1.0/tobs` for the temperature observation data
	
`http://localhost:5000/api/v1.0/<insert_start_date>` for climate data on a given start date. (Format: XXXX-XX-XX : Year-month-day)  

8.) To stop running the flask application run: 
`cntrl + c` and follow the prompt in the CLI. 