# Library-of-Congress
Pulling Library of Congress information using their public API


Library of Congress Newspaper Data

Package Installs - You will need to install the package called 'requests' to make the http request calls.

I used the public API to perform searches in the Library of Congress newspaper data by creating a program which prints the following data:

- Query for all newspaper publications and print out the total number of newspapers.
- Query for all newspaper publications for which there is digital content and print the state with the highest number of publications.  Print the state name and the number of publications. (via newspapers.json)
- Query for all newspaper publications for which there is digital content and print the state with the least number of publications.  Print the state name and the number of publications. (via newspapers.json)
- Query for all newspaper publications for Alabama and print out the state name and the total number of newspapers.


Using the newspapers.json resource will do the following for a state of your choice:
- Print out the state name and the total number of newspapers.
- Loop thru the newspapers and query for additional information using the url property to do the following for the first 20 newspapers:
- Print the title of each newspaper
- Print the starting year of each newspaper
- Print the total number of issues available

