## Geocoding-desambiguation
For more details check the [Geocoding Desambiguation Algorithm](https://docs.google.com/document/d/1KpS31tPzXV_MPS0bz4GA9yYQ-vcX2l8cc0ZCSU3tEyg/edit)

The main Step:

#### 1 - Extract SNE (Spatial Named Entities) with Spacy from the Corpus

  * Geocoding is performed with geonames, accessible from [geocoder python](https://pypi.org/project/geocoder/)
  * use ./code/extracSneFromCorpus.ipynb for this task (the output is stored in ./code/candidates/
#### 2 - Desambiguate all SNE geocoded in 1
  * to this end, use the ./code/main.ipynd script
  
#### 2 - Evaluate the desambiguation performance
  * ......

