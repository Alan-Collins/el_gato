# Known Problematic Alleles
el_gato demonstrates a better ability to correctly call sequence types (STs) for *L. pneumophila* compared to other tools available, particularly in handling *mompS*. However, el_gato is not fully accurate. For example, when both the *mompS* alleles 28 and a novel alllele type (NAT) are identified as possible options for an isolate (e.g., SRR23514483), el_gato cannot reliably distinguish between them, even with 250 base pairs (bp) read lengths. This limitation arises because the biallelic SNP separating these alleles is located at position 509 in the *L. pneumophila* Paris genome, whereas the diagnostic reverse primer spans positions 940–960. Differentiation would therefore require reads exceeding 400 bp. Similar challenges are likely to occur with other mompS alleles beyond those described here. Thus, we are tracking that information. 

### Table listing known alleles that el_gato can not differenatiate between
gene | allele number | alternative allele number | NCBI example
-----|---------------|---------------------------|-----
*mompS* | 28 | Novel Allele Type | SRR23514483
