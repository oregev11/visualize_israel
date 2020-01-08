# Israely hospitals distance visualiztion
The point of this pipeline is to visualize all cities of israel while showing thier size in population and distance from nearest hospital.

hospitals_empty.csv
all hospitals inisrael by name and ad-hoc codes

hospitals.csv:
all major hospitals of israel with ad-hoc codes and WGS position
the WGS coordinates were obtained from the Gmaps API in notebook 4.
The classification for group were added manually according to index I found somewehere in the health department site (couldnt find an officail list)
Group 1 stands for tertiary hospitals. 
Group 2 smaller hospitals
Group 3 even smaller hospitals :-)
Group 4 Pediatric Hospital (Shnider)

israel.csv
cities from the lamas 2018 report with ad-hoc codes, WGS points and population data

isrHospitalDisMat.csv
distance matrix from each city in israel to all major hospitals.



