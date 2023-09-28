# Geological-Ontology

This project builds Geological Ontology which includes main entities like Geological objects, Geological phenomena, and Units of Earth structure. Initially, the ontology was built manually and further, it was automatically extended using web scraping and BeautifulSoup library. The entities that are extended automatically are, Minerals, Rocks, and Soil.

#### Dependencies
- BeautifulSoup
- requests
- pandas
- re
- time
- Owlready2

### Structure
The project is structured as a set of Jupyter Notebook files and one ontology file:
All the Jupyter files include code for scraping the links for each entity(Minerals, Rocks, and Soil), then storing the data into Pandas Dataframe. Further, the Dataframes are processed to remove any duplicates and then the results are stored in a CSV file.
- mineral_scraping.ipynb scraps two links.
 
- rocks_scraping.ipynb scraps three links.

- soil_scraping.ipynb scraps two links.

Further, the entities scraped from these Jupyter files were added to the manually created Ontology with the help of the Owlready2 package.
