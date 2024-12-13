# This repo is built for the paper: Review of Zero-Shot Remote Sensing Image Scene Classification [<a href="https://ieeexplore.ieee.org/document/10552052">Paper</a>]
# Citation
If it is helpful for your work, please cite this paper:
``` 
@ARTICLE{10552052,
  author={Tan, Xiaomeng and Xi, Bobo and Li, Jiaojiao and Zheng, Tie and Li, Yunsong and Xue, Changbin and Chanussot, Jocelyn},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={Review of Zero-Shot Remote Sensing Image Scene Classification}, 
  year={2024},
  volume={},
  number={},
  pages={1-16},
  keywords={Semantics;Training;Remote sensing;Image recognition;Task analysis;Scene classification;Aerospace electronics;Multimodal learning;remote sensing image scene classification;zero-shot learning},
  doi={10.1109/JSTARS.2024.3410995}}
```
The paradigm of ZSRSSC is below:
![image](fig1.tif)
- [ZSL papers](#ZSL)
- [ZSRSSC papers](#ZSRSSC)
# ZSL
![image](fig2.tif)
- [ZSL papers](#ZSL)
  - [Attribute Learning](#att)
  - [Cross Modal Transfer](#cmt)
  - [Generative Network](#gen)
  - [Large-scale Pre-trained Models](#lpm)
- TODO : collect more related papers. Contributions are welcome.
## Attribute Learning <a name="att" style="display: none;"></a>
Learning to detect unseen object classes by between-class attribute transfer [<a href="https://ieeexplore.ieee.org/document/5206594">pdf</a>]

## Cross Modal Transfer <a name="cmt" style="display: none;"></a>
### Semantic space
Zero-Shot Learning Through Cross-Modal Transfer [<a href="https://arxiv.org/abs/1301.3666">pdf</a>]

DeViSE: A Deep Visual-Semantic Embedding Model [<a href="https://papers.nips.cc/paper_files/paper/2013/hash/7cce53cf90577442771720a370c3c723-Abstract.html">pdf</a>]

Label-Embedding for Attribute-Based Classification(CVPR2013) [<a href="https://openaccess.thecvf.com/content_cvpr_2013/papers/Akata_Label-Embedding_for_Attribute-Based_2013_CVPR_paper.pdf">pdf</a>]

Zero-Shot Learning by Convex Combination of Semantic Embeddings [<a href="https://arxiv.org/abs/1312.5650">pdf</a>]

Zero-Shot Recognition Using Dual Visual-Semantic Mapping Paths(CVPR2017) [<a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Zero-Shot_Recognition_Using_CVPR_2017_paper.pdf">pdf</a>]

Semantic Autoencoder for Zero-Shot Learning(CVPR2017) [<a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Kodirov_Semantic_Autoencoder_for_CVPR_2017_paper.pdf">pdf</a>]
### Common space
Learning Deep Representations of Fine-Grained Visual Descriptions(CVPR2016) [<a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/Reed_Learning_Deep_Representations_CVPR_2016_paper.pdf">pdf</a>]

Latent Embeddings for Zero-Shot Classification(CVPR2016) [<a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/Xian_Latent_Embeddings_for_CVPR_2016_paper.pdf">pdf</a>]

Semantics-Preserving Locality Embedding for Zero-Shot Learning [<a href="https://www.researchgate.net/publication/332817872_Semantics-Preserving_Locality_Embedding_for_Zero-Shot_Learning">pdf</a>]
### Visual space
Learning a Deep Embedding Model for Zero-Shot Learning(CVPR2017) [<a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Learning_a_Deep_CVPR_2017_paper.pdf">pdf</a>]

Learning to Compare: Relation Network for Few-Shot Learning(CVPR2018) [<a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Sung_Learning_to_Compare_CVPR_2018_paper.pdf">pdf</a>]
## Generative Network <a name="gen" style="display: none;"></a>
Feature Generating Networks for Zero-Shot Learning(CVPR2018) [<a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Xian_Feature_Generating_Networks_CVPR_2018_paper.pdf">pdf</a>]

Generalized Zero- and Few-Shot Learning via Aligned Variational Autoencoders(CVPR2019) [<a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Schonfeld_Generalized_Zero-_and_Few-Shot_Learning_via_Aligned_Variational_Autoencoders_CVPR_2019_paper.pdf">pdf</a>]

Generative Dual Adversarial Network for Generalized Zero-Shot Learning(CVPR2019) [<a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Huang_Generative_Dual_Adversarial_Network_for_Generalized_Zero-Shot_Learning_CVPR_2019_paper.pdf">pdf</a>]

Creativity Inspired Zero-Shot Learning(ICCV2019) [<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Elhoseiny_Creativity_Inspired_Zero-Shot_Learning_ICCV_2019_paper.pdf">pdf</a>]

Zero-Shot Learning With Attentive Region Embedding and Enhanced Semantics [<a href="https://ieeexplore.ieee.org/document/9881214">pdf</a>]
## Large-scale Pre-trained Models <a name="lpm" style="display: none;"></a>
Learning to Prompt for Vision-Language Models [<a href="https://arxiv.org/abs/2109.01134">pdf</a>]

Conditional Prompt Learning for Vision-Language Models(CVPR2022) [<a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Conditional_Prompt_Learning_for_Vision-Language_Models_CVPR_2022_paper.pdf">pdf</a>]

Robust Fine-Tuning of Zero-Shot Models(CVPR2022) [<a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Wortsman_Robust_Fine-Tuning_of_Zero-Shot_Models_CVPR_2022_paper.pdf">pdf</a>]

Combined scaling for zero-shot transfer learning [<a href="https://arxiv.org/abs/2111.10050">pdf</a>]
# ZSRSSC
Zero-Shot Scene Classification for High Spatial Resolution Remote Sensing Images [<a href="https://ieeexplore.ieee.org/document/7902107">pdf</a>]

Structural Alignment based Zero-shot Classification for Remote Sensing Scenes [<a href="https://ieeexplore.ieee.org/document/8645056">pdf</a>]

联合稳健跨域映射和渐进语义基准修正的零样本遥感影像场景分类 [<a href="http://xb.chinasmp.com/CN/lexeme/showArticleByLexeme.do?articleID=12440">pdf</a>]

Robust deep alignment network with remote sensing knowledge graph for zero-shot and generalized zero-shot remote sensing image scene classification [<a href="https://www.sciencedirect.com/science/article/abs/pii/S092427162100201X">pdf</a>]

Learning Deep Cross-Modal Embedding Networks for Zero-Shot Remote Sensing Image Scene Classification [<a href="https://ieeexplore.ieee.org/document/9321719">pdf</a>]

Deep Semantic-Visual Alignment for zero-shot remote sensing image scene classification [<a href="https://www.sciencedirect.com/science/article/abs/pii/S0924271623000527">pdf</a>]

Vision-Language Models for Zero-Shot Classification of Remote Sensing Images [<a href="https://www.mdpi.com/2076-3417/13/22/12462">pdf</a>]

Mining Contrastive Relations Between Cross-Modal Features for Zero-Shot Remote Sensing Image Scene Classification [<a href="https://ieeexplore.ieee.org/document/10443709">pdf</a>]

Zero-Shot Remote Sensing Scene Classification Method Based on Local-Global Feature Fusion and Weight Mapping Loss [<a href="https://ieeexplore.ieee.org/document/10368306">pdf</a>]

Self-supervised embedding for generalized zero-shot learning in remote sensing scene classification [<a href="https://www.semanticscholar.org/paper/Self-supervised-embedding-for-generalized-zero-shot-Damalla-Datla/8cd3ba24ec67e36ee5168a2ac646f2467d99b4a1">pdf</a>]

MFINet: A Novel Zero-Shot Remote Sensing Scene Classification Network Based on Multimodal Feature Interaction [<a href="https://ieeexplore.ieee.org/document/10557622">pdf</a>]
