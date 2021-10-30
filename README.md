# Feeding-a-Gazetteer
This data accompanies the paper "Feeding a Gazetteer: Leveraging word embeddings for toponym mining", presented at the 5th ACM SIGSPATIAL International Workshop on Geospatial Humanities, Nov 2 2021. https://ludovicmoncla.github.io/sigspatial-geohumanities-2021/index.html .  It includes: 
* The Corpus of 5 Hebrew 19th century Newspapers, based on https://github.com/omilab/historical_press.
* A "seed" set of 1000 toponyms that have dated attestation for their use in the relevant period, taken from the Kima Gazetteer https://data.geo-kima.org/ 
* The notebook "Finding_Locations_in_Historic_Newspapers.ipynb", written by Nitzan Gado, which was used to clean the corpus, train an embedding model, query it for given terms, and then load the seed set and extract the top most similar terms for all seed set terms.  
* Set of our results.
* The notebook "Visualisation, Exploration and QA.ipynb" written by Nitzan Gado, that enables exploration of the results, of the corpus and distribution of toponyms in it.
