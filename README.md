#Finding Greener Pastures

The FINAL PRESENTATION FILES folder holds the two final programs to run, PLOTS AND GRAPHS folder holds all of our images and our power point presentation is also here.

In this repository we attempt to find greener pastures for people in the United States using data. We have pulled in information from the Bureau of Labor Statistics, Womply .com, Burning  Glass Employment Services, Gmaps and Numbeo.com.

We used 53 cities in the USA to get a score where the best place to live is based on a chosen occupation
	estimated salary for given occupation types
	Our data is from 2019

Page 21 of the powerpoint presentation, found here in Greener-Pastures/Final Presentation files/Greener Pastures Presentation_Group 2.pptx, has our flow chart of how all the data sets work with each other

Greener-Pastures/Final Presentation files/Marker_Map.ipynb holds the data when an occupation is chosen. With in[3] you will have the opportunity to chose which of the 21 occupations you would like to see results for. In the example, #2: Arts, design, entertainment, sports, and media occupations was chosen.

When you scroll down to out[10] you will see the dataframe made from that occupation. It is sorted on the 'OCC VALUE' Column. The 'OCC VALUE' column is the hourly rate for that occupation is that city. In that dataframe you will find all other information as well. In this same example, Washington DC is the best city to live in for Arts, design, entertainment, sports, and media occupations with an hourly rate of 41.62 while Sacramento CA is the worst with a 20.73 hourly rate for the same occupation.

The DATA folder holds any files we were able to pull in without API use.

The DOCS folder has any documentation that can help with processing the data we collected such as BLS key information or explanations of our other data sources information type.

 We used multiple techniques to collect and clean the data. These can all be found in the DATA PROCESSING PY FILES folder. -Note some of these require you to put in your own Google api key. APPLICATION_MAIN is the final data processing file and creates the “MegaDf.csv”

We sent all of the data we collected and cleaned to the OUTPUT_FILES folder.

The FINAL PRESENTATION PY FILES folder holds the py files needed to run our final programs.
	HEAT MAP DISPLAY- plays through all of our heat maps to show progression of small business closures.
	MARKER MAP- is a basic program to collect information from the end user, create a marked heat map of the US with all needed information and also print out the top five cities for that persons chosen occupational field of interest.

The IMAGES folder holds all of the charts and graphs we made to both help process our information but also to analyze what the data told us. 

Finally the PROJECT folder holds the files needed for our presentation and project management.


Cities researched    :'Los Angeles', 'New York City', 'Chicago', 'Houston', 'Phoenix', 'San Diego',
 'Dallas', 'Las Vegas', 'Seattle', 'Fort Worth', 'San Antonio', 'San Jose',
 'Detroit', 'Philadelphia', 'Columbus', 'Austin', 'Charlotte', 'Indianapolis',
 'Jacksonville', 'Memphis', 'San Francisco', 'El Paso', 'Baltimore', 'Portland',
 'Boston', 'Oklahoma City', 'Louisville', 'Denver', 'Washington', 'Nashville',
 'Milwaukee', 'Albuquerque', 'Tucson', 'Fresno', 'Sacramento', 'Atlanta',
 'Kansas City', 'Miami', 'Raleigh', 'Omaha', 'Oakland', 'Minneapolis', 'Tampa',
 'New Orleans', 'Wichita', 'Cleveland', 'Bakersfield', 'Honolulu', 'Boise',
 'Salt Lake City', 'Virginia Beach', 'Colorado Springs', 'Tulsa'
