# Fitbit

This is the documentation for code written to harvest Fitbit's API to get my user data for data analysis. The code is broken into a few individual files which perform different tasks, I will discuss them briefly below.

------------------------
APIRequest.py 
------------------------
Handles the creation of the web queries to the API, handling the tokens, and saving the returned data to disk.

-----------------------
IniFile.txt
-----------------------
Stores the tokens for later use.

-----------------------
FitbitDataUtilities.py
-----------------------
Reads in the files saved to disk and performs usesful preprocessing to the data.

-----------------------
hrData.csv
-----------------------
The location of the daily minute by minute HR log. 
