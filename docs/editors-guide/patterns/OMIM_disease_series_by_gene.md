# OMIM_disease_series_by_gene 
## URL 
[http://purl.obolibrary.org/obo/mondo/patterns/disease_series_by_gene.yaml](http://purl.obolibrary.org/obo/mondo/patterns/disease_series_by_gene.yaml)
## Description 

This pattern is meant to be used for OMIM diseases, including children of OMIM phenotypic series (OMIMPS), which are represented as grouping classes in Mondo. Notes about the OMIMPS (see also OMIM_phenotypic_series.yaml):  - every instance of the OMIMPS metaclass should be equivalent to (via annotated xref) to something in OMIMPS namespace - the OMIMPS will never have an asserted causative gene as logical axiom (and no single causative gene in text def) - the OMIMPS must never be equivalent to an OMIM:nnnnnn (often redundant with the above rule) - the OMIMPS must have an acronym synonym, e.g. HPE - the OMIMPS must have two or more subclasses (direct or indirect) that are equivalent to OMIMs and conform to this pattern - the subclasses should (not must) have a logical def that uses the PS as a genus  - the OMIM subclasses must have acronym synonyms that are the parent syn + number, e.g. HPE1, HPE2 - the primary label for the children should also be parent + {"type"} + number - the first member will usually have the same number local ID as the PS Examples: [holoprosencephaly 1](http://purl.obolibrary.org/obo/MONDO_0009349), [3M syndrome 1](http://purl.obolibrary.org/obo/MONDO_0010117)
## Contributors 
* [https://orcid.org/0000-0002-6601-2165](https://orcid.org/0000-0002-6601-2165) 
* [https://orcid.org/0000-0001-5208-3432](https://orcid.org/0000-0001-5208-3432) 
## Classes 
* disease: [MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001) 
* gene: [SO:0000704](http://purl.obolibrary.org/obo/SO_0000704) 
_To be completed_