---
icon: database
description: Various data
---

# Knowledge Base

The knowledge base provides the node and edge properties of network visualization and analysis, based on the [Reference Genome data](reference-genome-data.md) and [Protein-Protein Interaction (PPI) network data](protein-protein-interaction-ppi-data.md).

We have different kinds of data available on the left panel of network visualization page, which allows you to change the network property based on personal needs. The data behind each feature is divided into 2 different types -- [**disease-dependent**](disease-dependent-data/) and [**disease independent**](disease-independent-data/).

Data types are transformed to defined representations, so that they can be handled consistently and displayed intuitively by the frontend.

* **Disease-dependent** data varies with different diseases, including [LogFC](disease-dependent-data/differential-expression.md) (_Differential expression in Log2 fold change_), [GDA ](disease-dependent-data/target-disease-association.md)(_Gene Disease Association score_) and [Genetics](disease-independent-data/target-prioritization-factors.md) (_Odd ratio or Beta-values from population studies_). Currently, you can switch among 4 different diseases — ALS (Amyotrophic lateral sclerosis), FTD (Frontotemporal dementia), OI (Osteogenesis imperfecta) and PSP (Progressive Supranuclear Palsy).
* **Disease-independent** data DO NOT vary with different diseases, including [Pathway](disease-independent-data/pathways.md) (_Pathway membership from KEGG and Reactome_), [Druggability](disease-independent-data/druggability.md) (_Druggability score form Open Targets_) and [Tissue Enrichment](disease-independent-data/tissue-specificity.md) (_Tissue-specific expression from GTEX and HPA_).

### Knowledge Base Summary

<table data-full-width="false"><thead><tr><th width="194">Data type</th><th width="154">Representation</th><th width="228">Experiment types</th><th>Sources</th></tr></thead><tbody><tr><td>LogFC</td><td>[-Inf, +Inf]</td><td>RNAseq, Proteomics</td><td>Verge, AD (Mayo, ROSMAP, MSBB)</td></tr><tr><td>GDA</td><td>[0, 1]</td><td>AI, Meta-scores</td><td>Open Targets</td></tr><tr><td>Genetics</td><td>[-1, 1]</td><td><p>GWAS w/ eQTL (OR/Beta),</p><p>GeneBurden (OR/Beta)</p></td><td>Open Targets Genetics</td></tr><tr><td>Pathway</td><td>Binary</td><td>Curation</td><td>KEGG, Reactome</td></tr><tr><td>Druggability</td><td>[0, 1]</td><td>AI, Meta-scores</td><td>DrugnomeAI</td></tr><tr><td>Tissue Enrichment</td><td>[0, +Inf]</td><td>single cell RNAseq &#x26; single cell databases</td><td>GTEx, HPA</td></tr></tbody></table>
