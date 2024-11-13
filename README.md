# Third_Deliverable

## Merged gender & ethnicity variables into ClerkshipGrades file matching on ID. ClerkshipGrades file is in long format so students have more than one row of data therefore I used a left join to merge the gender & ethnicity info from one line to many lines in the ClerkshipGrades file.

## Used fuzzy merge to update the location names in the ClerkshipGrades file (see below to see how the locations in the ClerkshipGrades file should be mapped to those in the Locations file).
Location (Locations file)	            Location_new (ClerkshipGrades file)
Baystate Medical Center	              locations containing "Baystate"
Berkshire Medical Center	            locations containing "Berkshire"
Boston Area Hospitals	                locations containing "Boston"
Pioneer Valley Hospitals	            locations containing "Pioneer"
Southeast Area Hospitals	            locations containing "Southeast"
UMMHC Hospitals	                      locations containing "UMMHC"
St. Vincent Hospital Massachusetts	  locations containing "Vincent"
Worcester Area Hospitals	            locations containing "Worcester"

All other locations remain as is
