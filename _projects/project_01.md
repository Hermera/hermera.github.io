---
title: 'Combine Temporal Convolution and Self-attention'
collection: projects
excerpt: 'We proposed an effective model to combine self-attention and temporal convolution for action segmen
tation task, and achieved state of the art results on three public benchmarks.'
during: 2020.07.01
layout: single
permalink: /projects/combine_temporal_convolution_and_self_attention
---



Algorithms for the action segmentation task typically use temporal models to predict what action is occurring at each frame for a minute-long daily activity. The function of these temporal models can be decoupled into two aspects. The first is feature transformation, which aims to learn a map- ping from low-level appearance feature space to the high-level semantic feature space. The second is feature aggregation that combines features from other timestamps to help embed the current frame.

While recent researchers try to perform the action segmentation task based on temporal convolutions, we observe that the feature aggregation nability of temporal convolution is limited due to its inherent characteristics. To address the problem, we explore how to combine the self-attention operator with the great potential to make up for the shortcomings of temporal convolution on feature aggregation as a basic building module. Further, we propose a Multi-Stage Temporal Convolution Attention Network (MS-TCAN) to adapt the combined module efficiently for the action segmentation task. We conduct comprehensive experiments on three challenging datasets: 50Salads, GTEA and Breakfast, showing the superior performance of our approach.

More details can be found [here](/files/paper_667.pdf).

![](/images/projects/01.png)

