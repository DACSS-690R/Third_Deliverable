# Michele Carlin's Third Deliverable

## I merged gender & ethnicity variables into my ClerkshipGrades file matching on ID. ClerkshipGrades file is in long format so students have more than one row of data therefore I used a left join to merge the gender & ethnicity info from one line to many lines in the ClerkshipGrades file.

## I used fuzzy merge to update the location names in the ClerkshipGrades file (see below to see how the locations in the ClerkshipGrades file should be mapped to those in the Locations file).
Location (Locations file) ------>  Location_new (ClerkshipGrades file)<br>
Baystate Medical Center ------>  locations containing "Baystate"<br>
Berkshire Medical Center ------>  locations containing "Berkshire"<br>
Boston Area Hospitals ------>  locations containing "Boston"<br>
Pioneer Valley Hospitals ------>  locations containing "Pioneer"<br>
Southeast Area Hospitals ------>  locations containing "Southeast"<br>
UMMHC Hospitals ------>  locations containing "UMMHC"<br>
St. Vincent Hospital Massachusetts ------>  locations containing "Vincent"<br>
Worcester Area Hospitals ------>  locations containing "Worcester"<br>
All other locations ------>  remain as is

## Lastly, I reshaped the data from wide to long

## Here is the link to my coding: https://dacss-690r.github.io/Third_Deliverable/
