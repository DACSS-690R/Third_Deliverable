# Third_Deliverable

## Merged gender & ethnicity variables into ClerkshipGrades file matching on ID. ClerkshipGrades file is in long format so students have more than one row of data therefore I used a left join to merge the gender & ethnicity info from one line to many lines in the ClerkshipGrades file.

## Used fuzzy merge to update the location names in the ClerkshipGrades file (see below to see how the locations in the ClerkshipGrades file should be mapped to those in the Locations file).
Location (Locations file)	            Location_new (ClerkshipGrades file)<br>
Baystate Medical Center	              locations containing "Baystate"

Berkshire Medical Center	            locations containing "Berkshire"
Boston Area Hospitals	                locations containing "Boston"
Pioneer Valley Hospitals	            locations containing "Pioneer"
Southeast Area Hospitals	            locations containing "Southeast"
UMMHC Hospitals	                      locations containing "UMMHC"
St. Vincent Hospital Massachusetts	  locations containing "Vincent"
Worcester Area Hospitals	            locations containing "Worcester"
All other locations                   remain as is

## the first step in the fuzzy merge process seems to be working, and I matched on the fuzzy_1 results, but then when I try to run another round of fuzzy merging, I am running into a problem where the code to show locations only in the ClerkshipGrades file is showing me locations that should have been updated with the fuzzy_1 matching (e.g., from "Worcester Recovery Center and Hospital - Adolescent Unit" to "Worcester Area Hospitals")
 
