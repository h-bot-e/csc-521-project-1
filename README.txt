README.txt

Haris Bhatti
CSC 521

My program is designed to retrieve data from the Library of Congress website, using a combination of ArrayLists and
HashMaps.  The GUI was made using frames, JButtons and a Combo Box.  My goal was to retrieve data from the web and 
allow users to choose the first five films of a given year in alphabetical order, presented in the form of buttons.
Upon pushing a button, the contributors would be displayed, these contributors are pulled from the website.  Additionally
to allow my program to update the querystring, I designed the programa to allow choosing a year from 1977 to 1986 which
would then change the buttons to display movies from the correlating year.  

My Javadoc is available in this same folder.

Queries that the website takes ranges from year to number of items available.  To keep the GUI neat, the program is designed
for only five results at a time so the year should remain 5.  I used GiveMeWeb(int count, int year) to allow directly changing the
querystring with ease.  The HashMap is important for allowing the table to search for the results again with each selection.  The
resulting buttons are then cleared to make room for the new results.

There are no major bugs in the program, however the querystring for Alcatraz, released in 1980 has no information for contributors
on the website.  The program still works, however this particular film is missing its data on the website and is the only one.