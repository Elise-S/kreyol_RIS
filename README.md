# Welcome in this repository. 

-------------
This project is part of a master thesis production. The experiment build consist of building a Regex Search engine based on POS-tags for four Caribbean French-based Creoles, in order to explore which morpho-syntactic structures would be discriminative among them.

-------------

In this repository you will find:
- The raw datasets, extracted from FineWeb-2 and Glotcc-v1;
- The methodological pipeline, composed of fours subfolers corresponding at each steps:
    1. Data exploration and reshaping to extract text data
    2. The addition of the WALS annotations from the forms
    3. The tokenisation/sentensization/POS-taggins, the comparison between ht-adolphe.udpipe2.17 and fr-gsd.udpipe2.17 models' POS-tag predictions, and explorations
    4. The Regex Search Index (instructions to reproduce the experiment is to be found in _RIS_application_main.py_)
