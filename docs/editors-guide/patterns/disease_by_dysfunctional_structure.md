# disease_by_dysfunctional_structure 

[http://purl.obolibrary.org/obo/mondo/patterns/disease_by_dysfunctional_structure.yaml](http://purl.obolibrary.org/obo/mondo/patterns/disease_by_dysfunctional_structure.yaml)
## Description 


Diseases classified by a perturbation in an anatomical structure (such as a subcellular component, or an organ)
## Contributors 
* [https://orcid.org/0000-0002-6601-2165](https://orcid.org/0000-0002-6601-2165) 
## Name 

{structure\([UBERON:0000061](http://purl.obolibrary.org/obo/UBERON_0000061)\)} disease

## Annotations 

* annotation: exact_synonym\([oio:hasExactSynonym](http://purl.obolibrary.org/obo/oio_hasExactSynonym)\)  
text: disease of {structure\([UBERON:0000061](http://purl.obolibrary.org/obo/UBERON_0000061)\)}

## Definition 

Any disease in which the causes of the disease is a perturbation of the {structure\([UBERON:0000061](http://purl.obolibrary.org/obo/UBERON_0000061)\)} leading to its dysfunction.

## Equivalent to 

{disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)} and {disease has basis in dysfunction of\([RO:0004020](http://purl.obolibrary.org/obo/RO_0004020)\)} some {structure\([UBERON:0000061](http://purl.obolibrary.org/obo/UBERON_0000061)\)}

## Data preview 
| defined:class                                | defined:class:label             | structure                                     | structure:label       |
|:---------------------------------------------|:--------------------------------|:----------------------------------------------|:----------------------|
| MONDO:0004880 | bowel dysfunction               | UBERON:0004907 | lower digestive tract |
| MONDO:0001343 | impaired renal function disease | UBERON:0002113 | kidney                |
| MONDO:0019744 | rare renal tubular disease      | UBERON:0009773 | renal tubule          |

See full table [here](https://github.com/monarch-initiative/mondo/blob/master/src/patterns/data/matches/disease_by_dysfunctional_structure.tsv) 
