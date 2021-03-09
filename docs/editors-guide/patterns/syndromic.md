# syndromic 

[http://purl.obolibrary.org/obo/mondo/patterns/syndromic.yaml](http://purl.obolibrary.org/obo/mondo/patterns/syndromic.yaml)
## Description 

Some diseases exist in both isolated and syndromic forms. For example, aniridia ([MONDO_0019172 aniridia](http://purl.obolibrary.org/obo/MONDO_0019172), [MONDO_0020148'syndromic aniridia'](http://purl.obolibrary.org/obo/MONDO_0020148) and [MONDO_0007119 'isolated aniridia'](http://purl.obolibrary.org/obo/MONDO_0007119). Use this pattern to define the syndromic form of a disease when a term exists for the isolated/syndromic-neutral version. In general, this pattern should be used in parallel with isolated. E.g. if you make a term 'syndromic disease, you should also have 'isolated disease' [see pattern here(https://github.com/monarch-initiative/mondo/blob/master/src/patterns/dosdp-patterns/isolated.yaml). 
Note that the isolated and syndromic forms will be inferred to be disjoint due to the GCI pattern.
## Contributors 
* [https://orcid.org/0000-0002-6601-2165](https://orcid.org/0000-0002-6601-2165) 
* [https://orcid.org/0000-0001-5208-3432](https://orcid.org/0000-0001-5208-3432) 
## Name 

syndromic {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)}

## Annotations 

* annotation: exact_synonym\([oio:hasExactSynonym](http://purl.obolibrary.org/obo/oio_hasExactSynonym)\)  
text: syndromic {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)}

* annotation: related_synonym\([oio:hasRelatedSynonym](http://purl.obolibrary.org/obo/oio_hasRelatedSynonym)\)  
text: syndrome associated with {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)}

## Definition 

A {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)} that is part of a larger syndrome.

## Equivalent to 

{disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)} and {has modifier\([RO:0002573](http://purl.obolibrary.org/obo/RO_0002573)\)} some {syndromic\([MONDO:0021127](http://purl.obolibrary.org/obo/MONDO_0021127)\)}

## Data preview 
| defined:class                                | defined:class:label                   | disease                                      | disease:label                 |
|:---------------------------------------------|:--------------------------------------|:---------------------------------------------|:------------------------------|
| MONDO:0015150 | complex hereditary spastic paraplegia | MONDO:0019064 | hereditary spastic paraplegia |
| MONDO:0017263 | inherited ichthyosis syndromic form   | MONDO:0015947 | inherited ichthyosis          |
| MONDO:0016463 | syndromic agammaglobulinemia          | MONDO:0015977 | agammaglobulinemia            |
| MONDO:0020148 | syndromic aniridia                    | MONDO:0019172 | aniridia                      |
| MONDO:0015246 | syndromic anorectal malformation      | MONDO:0019938 | anorectal malformation        |

See full table [here](https://github.com/monarch-initiative/mondo/blob/master/src/patterns/data/matches/syndromic.tsv) 
