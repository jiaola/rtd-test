# acquired 

[http://purl.obolibrary.org/obo/mondo/patterns/acquired.yaml](http://purl.obolibrary.org/obo/mondo/patterns/acquired.yaml)
## Description 

Pattern for extending a etiology-generic disease class to an acquired form.  Here acquired means that basis for the disease is acquired during the individuals lifetime. It need not exclude genetic etiology, but it excludes inherited.
## Contributors 
* [https://orcid.org/0000-0002-6601-2165](https://orcid.org/0000-0002-6601-2165) 
## Name 

acquired {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)}

## Annotations 

* annotation: exact_synonym\([oio:hasExactSynonym](http://purl.obolibrary.org/obo/oio_hasExactSynonym)\)  
text: acquired {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)}

## Definition 

An instance of {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)} that is acquired during the lifetime of the individual.

## Equivalent to 

{disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)} and {has modifier\([RO:0002573](http://purl.obolibrary.org/obo/RO_0002573)\)} some {acquired\([MONDO:0021141](http://purl.obolibrary.org/obo/MONDO_0021141)\)}

## Data preview: 
| defined:class                                | defined:class:label                | disease                                      | disease:label                |
|:---------------------------------------------|:-----------------------------------|:---------------------------------------------|:-----------------------------|
| MONDO:0018686 | acquired Creutzfeldt-Jakob disease | MONDO:0005357 | Creutzfeldt Jacob disease    |
| MONDO:0060779 | acquired Fanconi syndrome          | MONDO:0001083 | Fanconi renotubular syndrome |
| MONDO:0045023 | acquired adrenogenital syndrome    | MONDO:0015898 | adrenogenital syndrome       |
| MONDO:0019624 | acquired angioedema                | MONDO:0010481 | angioedema                   |
| MONDO:0015610 | acquired aplastic anemia           | MONDO:0015909 | aplastic anemia              |

See full table [here](https://github.com/monarch-initiative/mondo/blob/master/src/patterns/data/matches/acquired.tsv) 
