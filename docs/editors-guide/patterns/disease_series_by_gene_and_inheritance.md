# disease_series_by_gene_and_inheritance 

[http://purl.obolibrary.org/obo/mondo/patterns/disease_series_by_gene.yaml](http://purl.obolibrary.org/obo/mondo/patterns/disease_series_by_gene.yaml)
## Description 

This pattern is for diseases that are caused by a single mutation in a single gene, that have gene-based names, and are inherited by a specific mechanism, succh as autosomal dominant and autosomal recessive. 
Examples: [Growth hormone insensitivity syndrome with immune dysregulation](https://omim.org/phenotypicSeries/PS245590), Growth hormone insensitivity with immune dysregulation 1, autosomal recessive and Growth hormone insensitivity with immune dysregulation 2, autosomal dominant
## Contributors 
* [https://orcid.org/0000-0002-6601-2165](https://orcid.org/0000-0002-6601-2165) 
* [https://orcid.org/0000-0001-5208-3432](https://orcid.org/0000-0001-5208-3432) 
* [https://orcid.org/0000-0002-7356-1779](https://orcid.org/0000-0002-7356-1779) 
## Name 

{disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)} caused by mutation in {gene\([SO:0000704](http://purl.obolibrary.org/obo/SO_0000704)\)}, {mode_of_inheritance\([HP:0000005](http://purl.obolibrary.org/obo/HP_0000005)\)}

## Annotations 

* annotation: exact_synonym\([oio:hasExactSynonym](http://purl.obolibrary.org/obo/oio_hasExactSynonym)\)  
text: {gene\([SO:0000704](http://purl.obolibrary.org/obo/SO_0000704)\)} {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)}, {mode_of_inheritance\([HP:0000005](http://purl.obolibrary.org/obo/HP_0000005)\)}

* annotation: exact_synonym\([oio:hasExactSynonym](http://purl.obolibrary.org/obo/oio_hasExactSynonym)\)  
text: {gene\([SO:0000704](http://purl.obolibrary.org/obo/SO_0000704)\)} related {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)}, {mode_of_inheritance\([HP:0000005](http://purl.obolibrary.org/obo/HP_0000005)\)}

## Definition 

Any {disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)} in which the cause of the disease is a mutation in the {gene\([SO:0000704](http://purl.obolibrary.org/obo/SO_0000704)\)} gene, and has {mode_of_inheritance\([HP:0000005](http://purl.obolibrary.org/obo/HP_0000005)\)}.

## Equivalent to 

{disease\([MONDO:0000001](http://purl.obolibrary.org/obo/MONDO_0000001)\)} and {disease has basis in dysfunction of\([RO:0004020](http://purl.obolibrary.org/obo/RO_0004020)\)} some {gene\([SO:0000704](http://purl.obolibrary.org/obo/SO_0000704)\)} and {has modifier\([RO:0002573](http://purl.obolibrary.org/obo/RO_0002573)\)} some {mode_of_inheritance\([HP:0000005](http://purl.obolibrary.org/obo/HP_0000005)\)}

## Data preview: 
| defined:class                                | defined:class:label                            | disease                                      | disease:label           | gene                              | gene:label   | mode:of:inheritance                       | mode:of:inheritance:label       |
|:---------------------------------------------|:-----------------------------------------------|:---------------------------------------------|:------------------------|:----------------------------------|:-------------|:------------------------------------------|:--------------------------------|
| MONDO:0007818 | Hyper-IgE recurrent infection syndrome 1       | MONDO:0018037 | hyper-IgE syndrome      | http://identifiers.org/hgnc/11364 | STAT3        | HP:0000006 | Autosomal dominant inheritance  |
| MONDO:0100121 | SCN4A-related myopathy, autosomal recessive    | MONDO:0019952 | congenital myopathy     | http://identifiers.org/hgnc/10591 | SCN4A        | HP:0000007 | Autosomal recessive inheritance |
| MONDO:0010338 | X-linked distal spinal muscular atrophy type 3 | MONDO:0001516 | spinal muscular atrophy | http://identifiers.org/hgnc/869   | ATP7A        | HP:0001417 | X-linked inheritance            |
| MONDO:0020721 | X-linked sideroblastic anemia 1                | MONDO:0015194 | sideroblastic anemia    | http://identifiers.org/hgnc/397   | ALAS2        | HP:0001417 | X-linked inheritance            |
| MONDO:0007092 | amelogenesis imperfecta type 1B                | MONDO:0019507 | amelogenesis imperfecta | http://identifiers.org/hgnc/3344  | ENAM         | HP:0000006 | Autosomal dominant inheritance  |

See full table [here](https://github.com/monarch-initiative/mondo/blob/master/src/patterns/data/matches/disease_series_by_gene_and_inheritance.tsv) 
