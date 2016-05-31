# Thesis2016
Thesis project 2016, Nina and Kristoffer

The main file
the corpora files are currently hardcoded into the main.py file and should be changed if you wish to run on a smaller corpus or not at all.


Corpus



SUPPORTING MODULES

The GrammarPipeline is an executable python script which reads the ddt-1.0.xml file and serializes the final CNF PCFG to grammar.out. This file must be manually moved to the Pipeline/SyntacticParser folder in order to be read by the pipeline.

The input pickler contains two scripts: one which reads the raw text files retrieved by the web crawler, and one which can add a new corpus to an existing, pickled one.

The SynonymDictionary mines synonymordbogen.dk for synonyms to seed words hardcoded in the .py file. The synonyms are output to the dictionary_crawler_results.txt file.
# Thesis2016
