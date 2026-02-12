# Integrated-Islamic-Ontology
#### This repository offers the **integrated Islamic ontology**, a systematically organised bilingual Arabic-English framework of knowledge derived from Islamic sources, including the Qur’an and Hadith.
  
#### This ontology was developed to unify multiple Quranic and Hadith resources, inclusding [QacSegment](http://textminingthequran.com/data/QacSegment.json), QuranOntology, [LK-Hadith corpus](https://github.com/ShathaTm/LK-Hadith-Corpus), related Quran-Hadith topics based on the related Quran-verse and Hadith-teachings in the [QH_Dataset](https://github.com/ShathaTm/Quran_Hadith_Datasets/blob/main/QH_Dataset.csv), and the generated topics from [HTT](https://github.com/Ibtisam-a/Hadith-Topics-using-GPT4/blob/main/Hadith-Teaching-Topics_HTT.xlsx). It provided a semantic framewrok for analysing and retrieving Islamic texts.

# IMPORTANT
## [Download the ontology:](https://doi.org/10.5281/zenodo.18624651)

# Usage
#### Open `FinalCompleted_IslamicResourcesOntology.ttl` in [Protégé](https://protege.stanford.edu/).
#### OR <br>
#### Using Python, you can load the ontology with *rdflib*:

```Python
from rdflib import Graph
g = Graph()
g.parse("FinalCompleted_IslamicResourcesOntology.ttl", format="ttl")
print(len(g))  # number of triples
