# NOA-Meteo-Data-Downloader
Greetings and happy data processsing! 

In order to use this script you need to specify the years/months you are interested in.
To do that a parameters file is used:

You will find the parameters.txt in the same folder as the script. By default, it contains some example parameters.

The format of the parameters is:

station_name;year;year(month, month...,month),year,...

----------------------------------------------------------------------------------------------------------------------------


First you need to find the name of the station which is the first parameter. You can do that by navigating to http://meteosearch.meteo.gr/ and using the webpage's menu to
find some data on the station you are interested in. Then, the name of the station should be in the url in the form:
.../data/{station name}/....

Copy this name and paste it at the very beginning of the parameters file, followed be the character ";"


------------------------------------------------------------------------------------------------------------------------------

You need to add the years you need written in the form 20XX separated by the character ";"

Example: 2013;2015;2017

------------------------------------------------------------------------------------------------------------------------------

If you only need some months of a specified year (e.g. Only January and July) you can specify them within a parenthesis after the year,
denoted as the number of each month (January is 1, February is 12 etc)

Example: 2013;2015;2016(1,7);2018;2019(1,2,3,6,8)

------------------------------------------------------------------------------------------------------------------------------

NOTE: Make sure to leave no blank spaces and format the parameters according to the specifications described, or else the script will fail


-------------------------------------------------------------------------------------------------------------------------------
Lymperis Efstathios, 2020
