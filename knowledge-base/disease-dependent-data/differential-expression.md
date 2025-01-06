---
description: Differential expression in Log2 fold change, value ranging from -Inf to +Inf
---

# Differential Expression

Differential expression results for disease vs control are calculated based on transcriptomic and Proteomic data and is available from knowledge base in the form of log2-fold change.

We have 4 different diseases — PSP, ALS, FTD and OI. Let's go through them one by one.

## PSP

There are 2 types of LogFC data available in PSP disease -- Verge data and AD (Alzheimer’s Disease) data.&#x20;

* Verge data

The summary of Verge data is listed below:

| Condition                            | No. of Sample |
| ------------------------------------ | ------------- |
| Control (Ctrl)                       | 72            |
| Progressive Supranuclear Palsy (PSP) | 78            |

| Tissue name     | Abbreviation |
| --------------- | ------------ |
| Cerebellum      | CBE          |
| Globus Pallidus | GP           |

| Dataset | Constrasts                             |
| ------- | -------------------------------------- |
| Verge   | Diagnosis-tissue wise (PSP Vs Control) |

You can use the Verge data to color or resize the nodes in the network. The name in the dropdown list of LogFC Verge data follows the format of **{disease name}\_{"LogFC"}\_{data type}\_{"DEGS"}\_{tissue Abbr.}\_{"log2FoldChange"}**, for example, "PSP\_LogFC\_Verge\_DEGS\_GP\_log2FoldChange", shown as below:

<figure><img src="../../.gitbook/assets/1735775213788.png" alt=""><figcaption><p>PSP LogFC Verge data naming convention</p></figcaption></figure>

* AD (Alzheimer’s Disease) data

The summary of AD data is listed below:

<table><thead><tr><th width="130">Brain Bank</th><th width="287">Description</th><th width="387">Brain Region</th></tr></thead><tbody><tr><td>Mayo</td><td>Study of Alzheimer’s disease and related dementias on donors from the Mayo Clinic Brain Bank and Banner Health</td><td><table data-header-hidden><thead><tr><th></th></tr></thead><tbody><tr><td>Cerebellum (CBE)</td></tr><tr><td>Temporal cortex (TCX)</td></tr></tbody></table></td></tr><tr><td>ROSMAP</td><td>Two longitudinal studies of aging and Alzheimer’s disease with brain donation upon death - The Religious Order Study (ROS) and Memory and Aging Project (MAP) run by Rush Alzheimer’s Disease Center.</td><td><table data-header-hidden><thead><tr><th></th></tr></thead><tbody><tr><td>Dorsolateral prefrontal cortex (DLPFC)</td></tr><tr><td>Posterior cingulate cortex (PCC)</td></tr><tr><td>Anterior cingulate cortex (ACC)</td></tr></tbody></table></td></tr><tr><td>MSBB</td><td>Study of Alzheimer’s disease on donors from the Mount Sinai/JJ Peters VA Medical Center NIH Brain and Tissue Repository</td><td><table data-header-hidden><thead><tr><th></th></tr></thead><tbody><tr><td>Frontal pole (FP)</td></tr><tr><td>Inferior frontal gyrus (IFG)</td></tr><tr><td>Parahippocampal gyrus (PHG)</td></tr><tr><td>Prefrontal cortex (PFC)</td></tr><tr><td>Superior temporal gyrus (STG)</td></tr></tbody></table></td></tr></tbody></table>

<table><thead><tr><th width="129">Brain Bank</th><th width="204">Brain Region</th><th width="203">Contrasts</th><th>Annotation</th></tr></thead><tbody><tr><td>Mayo</td><td>CBE, TCX</td><td>Diagnosis-tissue wise (AD Vs Control)</td><td>ADvsCtrl</td></tr><tr><td>MSBB</td><td>FP, IFG, PHG, PFC, STG</td><td>Diagnosis-tissue wise (AD Vs Control)</td><td>ADvsCtrl</td></tr><tr><td>MSBB</td><td>FP, IFG, PHG, PFC, STG</td><td>Diagnosis-tissue-gender (AD Vs Control)</td><td><p>ADFemalevsCtrlFemale</p><p>ADMalevsCtrlMale</p></td></tr><tr><td>ROSMAP</td><td>DLPFC, PCC,ACC</td><td>Diagnosis-tissue wise (AD Vs Control)</td><td>ADvsCtrl</td></tr><tr><td>ROSMAP</td><td>DLPFC, PCC,ACC</td><td>Diagnosis-tissue-gender-age of death (AD Vs Control)</td><td><p>ADFemalevsCtrlFemale_agedeath</p><p>ADMalevsCtrlMale_agedeath</p></td></tr></tbody></table>

You can use the AD data to color or resize the nodes in the network. The name in the dropdown list of LogFC AD data follows the format of **{disease name}\_{"LogFC"}\_{contrast annotation}\_{brain bank}\_{brain region}**, for example, "PSP\_logFC\_ADvsCtrl\_Mayo\_TCX", shown as below:

<figure><img src="../../.gitbook/assets/1735775251922.png" alt=""><figcaption><p>PSP LogFC AD data naming convention</p></figcaption></figure>

## ALS

The LogFC data of ALS is from [this paper](differential-expression.md#citation-1) \[1]. According to the paper, to identify how ALS iPSMN changes compare between ALS genetic backgrounds, the effect of each genetic subgroup on gene expression is examined separately, including C9orf72 mutants, SOD1 mutants, FUS mutants,  TARDBP mutants and sporadic iPSMNs (without an identifiable ALS mutation).

You can use the ALS data to color or resize the nodes in the network. The name in the dropdown list of LogFC Verge data follows the format of **{disease name}\_{"LogFC"}\_{"rnaseq"}\_{"PMID37080969."}\_{mutant}\_{"fold\_change"}**, for example, "ALS\_LogFC\_rnaseq\_PMID37080969.tardbp\_fold\_change", shown as below:

<figure><img src="../../.gitbook/assets/1735797230622.png" alt=""><figcaption><p>ALS LogFC data naming convention</p></figcaption></figure>

## FTD



## OI



***

#### Citation 1

> _\[1] Ziff OJ, Neeves J, Mitchell J, Tyzack G, Martinez-Ruiz C, Luisier R, Chakrabarti AM, McGranahan N, Litchfield K, Boulton SJ, Al-Chalabi A, Kelly G, Humphrey J, Patani R. Integrated transcriptome landscape of ALS identifies genome instability linked to TDP-43 pathology. Nat Commun. 2023 Apr 20;14(1):2176. doi: 10.1038/s41467-023-37630-6. PMID: 37080969; PMCID: PMC10119258._
