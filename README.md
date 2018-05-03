# Alaska-Trails-Capstone
This repository includes the files and code snippets we used to implement the Mapping Event Scheduler for Alaska-Trails. 

This includes files such as: 
  - Google Sheets
  - Embedded Code Blocks
  - Javascript
  - Google API functions
  
* Most of the Google API functions are found within the Google Sheets. Simply select a cell and view the functions used to see how things are done.
* There was a web scraper and an HTML generator implemented in Google Sheets. The test documents have been uploaded as well as the master copy of the file.
* The Master Copy only has functions implemented in the "Points" and "Add Event to Map" tabs.
* The web scraper was added to the "Add Event to Map" tab so that the user doesn't have to reenter data. It scrapes data from the appropriate EventBrite web page and adds the data to the correct fields in the Google Sheet.
* After the data is scraped, HTML is generated for the map GUI and added to the correct field in the "Points" tab.
* Once the Google Sheet has been saved in the Clients Google Drive it is then connected and run through the other GitHub repository and posts the new event almost instantaneously. 

The actual mapping software in run through another repository and can be found here:
https://github.com/AlaskaTrails/leaflet-maps-with-google-sheets

IMPORTANT NOTE: If you encounter an issue with opening the Google Sheet in excel the document may need to be opened in Google Sheets. 
To do this you can download the "Office Editing for Docs, Sheets & Slides" Add-On for Google Chrome.
