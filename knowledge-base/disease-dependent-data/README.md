# Disease-dependent data

**Disease-dependent** data varies with different diseases, including [LogFC](differential-expression.md) (_Differential expression in Log2 fold change_), [GDA ](target-disease-association.md)(_Gene Disease Association score_) and [Genetics](target-prioritization-factors.md) (_Odd ratio or Beta-values from population studies_).

<table data-full-width="false"><thead><tr><th width="194">Data type</th><th width="160">Representation</th><th width="228">Experiment types</th><th>Sources</th></tr></thead><tbody><tr><td>LogFC</td><td>[-Inf, +Inf]</td><td>RNAseq, Ptoteomics</td><td>Verge, AD (Mayo, ROSMAP, MSBB)</td></tr><tr><td>GDA</td><td>[0, 1]</td><td>AI, Meta-scores</td><td>Open Targets</td></tr><tr><td>Genetics</td><td>[-1, 1]</td><td><p>GWAS w/ eQTL (OR/Beta),</p><p>GeneBurden (OR/Beta)</p></td><td>Open Targets Genetics</td></tr></tbody></table>
