# xmi2hpo.py
* Script to parse HPO terms with the CUI id extracted from the cTAKES natural language processor
* Input is folder containing xmi files from cTAKES
* Output is desired folder for the HPO results
* Usage: `python xmi2hpo.py -i INPUT_PATH -o OUTPUT_PATH`
* requires internet connection and the obo_parser.py which creates HPO.tsv

# obo_parser.py
* Script to parse HPO terms and their linked CUI ids from the HPO obo file  `http://purl.obolibrary.org/obo/hp.obo`
* is automatically used by the xmi2hpo.py function, so does not need to be executed.

# HPO.tsv
* TSV file that contains the HPO terms and relevant information including attributed CUI ids
* Is automatically updated when running the xmi2hpo.py function
