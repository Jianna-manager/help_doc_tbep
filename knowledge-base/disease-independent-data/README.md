# Disease-independent data

**Disease-independent** data DO NOT vary with different diseases, including [Pathway](pathways.md) (_Pathway membership from MSigDB_), [Druggability](druggability.md) (_Druggability score form MantisML and Open Target_) and [Tissue Enrichment](tissue-specificity.md) (_Tissue-specific expression from GTEX and HPA_).

<table data-full-width="false"><thead><tr><th width="194">Data type</th><th width="156">Representation</th><th width="228">Experiment types</th><th>Sources</th></tr></thead><tbody><tr><td>Pathway</td><td>Binary</td><td>Curation</td><td>KEGG, Reactome</td></tr><tr><td>Druggability</td><td>[0, 1]</td><td>AI, Meta-scores</td><td>DrugnomeAI</td></tr><tr><td>Tissue Enrichment</td><td>[0, +Inf]</td><td>single cell RNAseq &#x26; single cell databases</td><td>GTEx, HPA</td></tr></tbody></table>
