# DSGEM


## 目录
- [简介](#简介)
- [论文摘要](#论文摘要)
- [致谢](#致谢)

## 简介
PyTorch code for 2023 IET Computer Vision paper ["DSGEM: Dual Scene Graph Enhancement Module based Visual Question Answering"](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/cvi2.12186).

## 论文摘要
Visual Question Answering (VQA) aims to appropriately answer a text question by understanding the image content. 
Attention based VQA models mine the implicit relationships between objects according to the feature similarity, which neglects the explicit relationships between objects, e.g., the relative position. 
Most Visual Scene Graph based VQA models exploit the relative positions or visual relationships between objects to construct the visual scene graph, while they suffer from the semantic insufficiency of visual edge relations. 
Besides, the scene graph of text modality is often ignored in these works. 
In this paper, we propose a novel Dual Scene Graph Enhancement Module (DSGEM) that exploits the relevant external knowledge to simultaneously construct two interpretable scene graph structures of image and text modalities, which makes the reasoning process more logical and precise. Specifically, we respectively build the visual and textual scene graphs 
with the help of commonsense knowledge and  syntactic structure, which explicitly endows the specific semantics to each edge relation. 
Then, two scene graph enhancement modules are proposed to propagate the involved external and structural knowledge to explicitly guide the feature interaction between objects (nodes). 

## 致谢
This repository is partly based on [LXMERT](https://github.com/airsplay/lxmert#google-drive) repository.


