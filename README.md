# About the Bioliver

The Bioliver (bio literature visualizer) is a visual knowledge discovery tool within the domain of biology. Bio literatures (e.g., papers from PubMed) are major source for bio entities recognition, based on dictionary matching. The Bioliver calcuates co-occurance of these recognized entities within a sentence for each particular document. Based on such co-occurance, the Bioliver provides a visual analytics tools to help discover hidden relationships among these important entities.

## Current stage:
1. Retrieve 78567 paper abstract from PubMed with keyword "obesity".
2. Construct bio entity dictionary in 5 categries based on UniProt, BioThesaurus, UMLS and KEGG.
3. Use NLTK to process all paper abstract and find bio entities based on 5 dictionaries.
4. Cacluate co-occurance frequency of the recognized bio entities.
5. Knowlege discover based on the co-occurance network.

