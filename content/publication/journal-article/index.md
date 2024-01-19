---
title: "Exploring Adaptive Graph Topologies and Temporal Graph Networks for EEG-Based Depression Detection"
authors:
- admin
- Rao Hong 
- Panfeng An
- Yunxia Li
- Ruiyun Hong
- Wenwu Chen
- Shengbo Chen
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-09-28T00:00:00Z"
doi: "10.1109/TNSRE.2023.3320693"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: " IEEE Transactions on Neural Systems and Rehabilitation Engineering ( Volume: 31)"
publication_short: ""

abstract: In recent years, Graph Neural Networks (GNNs) based on deep learning techniques have achieved promising results in EEG-based depression detection tasks but still have some limitations. Firstly, most existing GNN-based methods use pre-computed graph adjacency matrices, which ignore the differences in brain networks between individuals. Additionally, methods based on graph-structured data do not consider the temporal dependency information of brain networks. To address these issues, we propose a deep learning algorithm that explores adaptive graph topologies and temporal graph networks for EEG-based depression detection. Specifically, we designed an Adaptive Graph Topology Generation (AGTG) module that can adaptively model the real-time connectivity of the brain networks, revealing differences between individuals. In addition, we designed a Graph Convolutional Gated Recurrent Unit (GCGRU) module to capture the temporal dynamical changes of brain networks. To further explore the differential features between depressed and healthy individuals, we adopt Graph Topology-based Max-Pooling (GTMP) module to extract graph representation vectors accurately. We conduct a comparative analysis with several advanced algorithms on both public and our own datasets. The results reveal that our final model achieves the highest Area Under the Receiver Operating Characteristic Curve (AUROC) on both datasets, with values of 83% and 99%, respectively. Furthermore, we perform extensive validation experiments demonstrating our proposed method’s effectiveness and advantages. Finally, we present a comprehensive discussion on the differences in brain networks between healthy and depressed individuals based on the outputs of our final model’s AGTG and GTMP modules.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Affective Computing
- Brain-Computer Interactions
- Artificial Intelligence
featured: false
# featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10268256
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Model Framework'
  # caption: 'Model Framework: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['dl_project']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
