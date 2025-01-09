---
description: Advanced analysis functions and modifications of inherent network parameters
---

# Right panel

Now we focus on the functions of right panel.

<figure><img src="../.gitbook/assets/1736048626483.png" alt=""><figcaption><p>Right panel of network visualization page</p></figcaption></figure>

### Network Analysis

You can reduce the network complexity and focus on the key drivers of your network here by selecting different radio buttons.

* **Community detection**

We offer community detection algorithm **Leiden** [\[1\]](right-panel.md#citation) in our tool, you can easily use this algorithm to find possible communities in the network, based on your own choice of **Resolution** and **Weighted**.

1. Click Leiden.
2. Select proper Resolution, check or uncheck Weighted, to involve edge weight or not.
3. Click Apply.
4. Select/Deselect communities to keep/drop the detected communities in the network.

<figure><img src="../.gitbook/assets/1736307018650.png" alt=""><figcaption><p>Community detection</p></figcaption></figure>

* **Edge Weight Cut-off**

This feature allows you to filter out the nodes with less edge weight, so that you can focus more on the clustered nodes.

1. Use the **range slider** or directly **type in** the number to select an appropriate value and filter out the nodes with edge weight less than the selected value.

<figure><img src="../.gitbook/assets/1736310113691.png" alt=""><figcaption><p>Edge weight cut-off</p></figcaption></figure>

* **Node Degree Cut-off**

This feature allows you to shrink the network based on the node degree of specific features.

1. In the dropdown list, you can select your preferred feature.
2. Use the **range slider** or directly **type in** the proper number to select an appropriate gene degree, making the network reduced as you want. We currently provide 2 types of values to reduce the network — Gene degree and Tissue Specificity values.

<figure><img src="../.gitbook/assets/1736309998103 (1).png" alt=""><figcaption><p>Node degree cut-off</p></figcaption></figure>

* **Hub Genes**

Hub Genes will highlight the nodes only with larger or equal to the number of edges defined by yourself.&#x20;

1. Use the **range slider** or directly **type in** the proper number to select an appropriate value to highlight the nodes with node degrees more than or equal to the selected value.

<figure><img src="../.gitbook/assets/1736310857889.png" alt=""><figcaption><p>Hub genes</p></figcaption></figure>

### Network Info

When the network is rendered, the basic information of the network is shown here, i.e. total nodes, total edges.

### Legends

You can see the Legend of each feature in Node Color section.

1. Choose a feature in Node Color section on the [Left panel](left-panel.md), then navigate to Legends section on the [Right panel](right-panel.md) to get the legend of a specific feature.

<figure><img src="../.gitbook/assets/1736395190478.png" alt=""><figcaption><p>Legends when selecting Druggability in Node Color</p></figcaption></figure>

### Network Layout

You can make the node clusters more separated.

1. Use the **range slider** or directly **type in** the proper number in Link Distance, this will make the edge of the network longer, helping the clusters separated from each other.
2. Use the **range slider** or directly **type in** the proper number in Charge Strength, this will separate the nodes from each other.

<figure><img src="../.gitbook/assets/1736397446375.png" alt=""><figcaption><p>Change Link Distance</p></figcaption></figure>

<figure><img src="../.gitbook/assets/1736397593098 (1).png" alt=""><figcaption><p>Change Charge Strength</p></figcaption></figure>

You can also toggle "Animation" button to stop dancing of the network.

### Network Style

You can change basic parameters of the network.

* **Node Size**

You can make node size larger/smaller.

<figure><img src="../.gitbook/assets/1736398182205.png" alt=""><figcaption><p>Change Node Size</p></figcaption></figure>

* **Node Label Size**

You can make node label size larger/smaller.

<figure><img src="../.gitbook/assets/1736398407283.png" alt=""><figcaption><p>Change Node Label Size</p></figcaption></figure>

* **Label Density**

You can change the label density here.

<figure><img src="../.gitbook/assets/1736398695366.png" alt=""><figcaption><p>Change Label Density</p></figcaption></figure>

* **Show Edge Label**

You can make edge label (edge weight) appear/disappear. To view more edge labels, simply zoom in the network.

<figure><img src="../.gitbook/assets/1736403488547.png" alt=""><figcaption><p>Show Edge Label</p></figcaption></figure>

You can also refer to the information icon <img src="../.gitbook/assets/1736049289149(1).png" alt="" data-size="line"> for the large network tips.

* **Show Edge Color**

You can change the edge color here. Please refer to the Legends section on the [Right Panel](right-panel.md) for the color meaning.

<figure><img src="../.gitbook/assets/1736404223829.png" alt=""><figcaption><p>Show Edge Color</p></figcaption></figure>

* **Node Color**

You can change the node color here, simply by selecting different color or type different color names.

<figure><img src="../.gitbook/assets/1736404655031.png" alt=""><figcaption><p>Change Node Color</p></figcaption></figure>

***

#### Citation 1

> _\[1] Traag, V. A., et al. « From Louvain to Leiden: Guaranteeing Well-Connected Communities ». Scientific Reports, vol. 9, no 1, décembre 2019, p. 5233. DOI.org (Crossref), doi:10.1038/s41598-019-41695-z. https://arxiv.org/abs/1810.08473_
