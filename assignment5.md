Done
# SQL query:
```
SELECT 
m15.city,
m15.state,
m15.`2014_murders`,
m15.`2015_murders`,
m16.`2016_murders`
FROM murder_2015_final AS m15
JOIN murder_2016_prelim AS m16
ON m15.city = m16.city
```
# Which table's column is the better one to keep?
I choose the column form the table 2015_murders, for the data is from FBI Uniform Crime Reporting, which is more reliable and comprehensive than the sources of the table 2016_murders, local police department.
# csv
```
city,state,2014_murders,2015_murders,2016_murders
Baltimore,Maryland,211,344,230
Chicago,Illinois,411,478,536
Houston,Texas,242,303,212
Cleveland,Ohio,63,120,89
Washington,D.C.,105,162,105
Milwaukee,Wisconsin,90,145,84
Philadelphia,Pennsylvania,248,280,213
Kansas City,Missouri,78,109,90
Nashville,Tennessee,41,72,49
St. Louis,Missouri,159,188,133
Oklahoma City,Oklahoma,45,73,30
Louisville,Kentucky,56,81,79
Denver,Colorado,31,53,33
Los Angeles,California,260,282,205
Dallas,Texas,116,136,118
New York,New York,333,352,252
Orlando,Florida,15,32,73
Minneapolis,Minnesota,31,47,26
Omaha,Nebraska,32,48,20
Sacramento,California,28,43,21
Anchorage,Alaska,12,26,26
Charlotte-Mecklenburg,North Carolina,47,61,25
New Orleans,Louisiana,150,164,127
Albuquerque,New Mexico,30,43,46
Aurora,Colorado,11,24,16
Fort Wayne,Indiana,12,25,34
Long Beach,California,23,36,29
Durham,North Carolina,21,34,30
Indianapolis,Indiana,136,148,117
Newark,New Jersey,93,104,72
Tulsa,Oklahoma,46,55,52
Portland,Oregon,26,34,14
San Francisco,California,45,53,32
Cincinnati,Ohio,60,66,50
Bakersfield,California,17,22,22
Colorado Springs,Colorado,20,25,15
Las Vegas,Nevada,122,127,125
Oakland,California,80,85,52
San Diego,California,32,37,30
Anaheim,California,14,18,4
Greensboro,North Carolina,23,26,20
Jersey City,New Jersey,24,27,14
Fort Worth,Texas,54,56,49
Virginia Beach,Virginia,17,19,13
Atlanta,Georgia,93,94,85
Henderson,Nevada,3,4,3
Jacksonville,Florida,96,97,78
Raleigh,North Carolina,16,17,7
Wichita,Kansas,26,27,10
Chandler,Arizona,1,1,3
Plano,Texas,4,4,5
Stockton,California,49,49,38
Toledo,Ohio,24,24,8
Chula Vista,California,7,6,1
Phoenix,Arizona,114,112,111
Riverside,California,12,10,7
San Jose,California,32,30,35
Detroit,Michigan,298,295,221
Seattle,Washington,26,23,14
El Paso,Texas,21,17,14
Tucson,Arizona,35,31,18
Arlington,Texas,13,8,17
Lexington,Kentucky,20,15,16
Memphis,Tennessee,140,135,158
St. Petersburg,Florida,19,14,14
Columbus,Ohio,83,77,70
Honolulu,Hawaii,21,15,9
Laredo,Texas,14,8,9
Lincoln,Nebraska,7,1,9
Miami,Florida,81,75,45
Santa Ana,California,18,12,20
Mobile,Alabama,31,24,12
Fresno,California,47,39,19
Austin,Texas,32,23,28
San Antonio,Texas,103,94,111
Corpus Christi,Texas,27,17,9
Pittsburgh,Pennsylvania,69,57,46
Boston,Massachusetts,53,38,28
Buffalo,New York,60,41,38
```
