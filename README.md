Steps to Solving our Problem:

1. Gathering data – we used online databases of election results in North Carolina as well as demographic data of the precincts in North Carolina. Sources: 
data2.nhgis.org – Demographic Data 
https://www.ncsbe.gov/election-results - Election Results  
2. Cleaning the Data 
3. Once we obtained the data, we used python to organize and connect the relevant data so that it could be used in our classifier algorithms. 
Difficulties 
4. One issue that we had when cleaning our data was that different election results had slightly different formats as CSV files. Thus we had to use two separate functions to collect the election result data, one for the 2004 and 2006 elections and a different one for the 2008 election. 
Connecting the demographic data and election results was difficult. The precinct names and labels in the respective files were slightly different so we created a similarity function in order to properly pair the data.
5. Once the data was cleaned, we put these data into two different classifiers. The first was a Naïve Bayes classifier and the second was a Nearest Neighbor classifier. 
6. Lastly, we used these classifiers to see if elections could accurately be predicted using the demographic data. We compared the predicted election result (either democrat or republican) to the actual election result in order to determine the accuracy of these classifiers. 
