>> Pre-requisites
    Make sure you have installed python http-server(https://docs.python.org/3/library/http.server.html) 
    or http-server (https://www.npmjs.com/package/http-server)

>> File Structure
    .
    ├── index.html                             Index file that runs on http-server
    ├── README.md                              
    └── source_files                           Folder for holding all source files
        ├── cleanedData.xlsx
        ├── d3.min.js                          Working with a minified d3 js (1.3)
        ├── data_covid.json                    Cleaned dataset transformed to json format for easy consumption
        ├── newDeathsFortnightData.csv
        ├── owid-covid-data.xlsx               Original dataset
        ├── process.ipynb                      Jupyter Notebook for cleaning (drafts)
        ├── reset.css                          Resetting CSS for older browser support
        ├── script.js                          JS Script for defining Charts and other functions
        └── style.css                          CSS Style Sheet

>> Running The Visualization

#   Open a terminal instance (on Linux or iOS) or command line (on Windows)
#   Run python http.server or http-server with the root folder
#   An example of http-server run
$   http-server -o -c 0
#   The above command will open the visualization in a new broswer window with cache time period as 0 

>> Interactivity
    ~ Slider Control - The slider controls the passage of time
    ~ Detail View Functionality - Hovering above a sector will tell the estimated number of deaths
    ~ Hovering on Legends highlights the parts of the hovered country
    
