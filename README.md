# visualize_israel
Simple pipelines to visualize data of cities using Python libraries - demonstrated on the cities of israel.

# Notebooks:
  - 1_Get_WGS_choords_Israel_cities.ipynb
    
    Extract the all israely monicipal authorities ('cities' for simplicity) names from the israely Central Beuro for Statistic (Lamas) 2018
    report.
    Run this name via the Google Maps API to get their address.
    
  - 2_Add_WGS_to_the_Lamas_file.ipynb
    
    Paste the addresses back in the Lamas table and validate the coordinates.
    
  - 3_Visualize_the_Cities_of_ Israel_by_population.ipynb
   
    Visualize the cities of israel by population using GeoVies and Bokeh.
    
  # Files
  - 1_bycode2018.xlsx
    
    israely Central Beuro for Statistic (Lamas) 2018 report
  
  - 2_israel_cities_with_lamas_codes_WGS.csv
    
    All cities of israel with thier WGS coordinates
    
  - 3_lamas_2018_WGS.csv
     
     israely Central Beuro for Statistic (Lamas) 2018 report with WGS coordinates added
  
