

# Named Entity Recognition (NER)

__Named Entity Recognition (NER)__ , also known as entity chunking/extraction , is a popular technique used in information extraction to identify and segment the named entities and classify or categorize them under various predefined classes.

Data Set used - https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus

## Tag Distribution

The GMB dataset utilizes IOB tagging or _Inside, Outside Beginning_. IOB is a common tagging format for tagging tokens which we have discussed earlier. To refresh your memory:

+ __I- prefix__ before a tag indicates that the tag is inside a chunk.
+ __B- prefix__ before a tag indicates that the tag is the beginning of a chunk.
+ __O-  tag__ indicates that a token belongs to no chunk (outside).

The tags in this dataset are explained as follows:

+ __geo__ = Geographical Entity
+ __org__ = Organization
+ __per__ = Person
+ __gpe__ = Geopolitical Entity
+ __tim__ = Time indicator
+ __art__ = Artifact
+ __eve__ = Event
+ __nat__ = Natural Phenomenon

Anything outside these classes is termed as other, denoted as __O__. 

## 1- Conditional Random Fields

 CRF is an undirected graphical model whose nodes can be divided into exactly two disjoint sets $X$ and $Y$, the observed and output variables, respectively; the conditional distribution $p(Y|X)$ is then modeled.


## 2- Spacy

## 3- Transforemers in [Transformers Folder ] (https://github.com/ShreeCharranR/Transformers---NLP-Experiments)
