# Papers about Commonsense Causality
This is the paper list for the literature summarized in our survey published in EMNLP 2024: [The Odyssey of Commonsense Causality: From Foundational Benchmarks to Cutting-Edge Reasoning](https://arxiv.org/abs/2406.19307)

## Citation 🫡

If you find our survey useful for your research on commonsense causality, please support us by citing our work as follows:

```bibtex
@article{cui2024odyssey,
  title={The Odyssey of Commonsense Causality: From Foundational Benchmarks to Cutting-Edge Reasoning},
  author={Cui, Shaobo and Jin, Zhijing and Sch{\"o}lkopf, Bernhard and Faltings, Boi},
  journal={arXiv preprint arXiv:2406.19307},
  year={2024}
}
```

## Handbook for researchers interested in commonsense causality
![Alt text](hanbook-shaobo.png?raw=true "Handbook for researchers interested in commonsense causality.")



## Benchmarks
## Overview of Causal Datasets

| Dataset | Annotation Unit | \#Overall | \#Causal | C.F. | Brief Introduction | License |
|---------|-----------------|-----------|----------|------|--------------------|---------|
| **First-Principle Causality** |
| **CauseEffectPairs** [Mooij et al., 2016](https://jmlr.org/papers/volume17/14-518/14-518.pdf) | Variable | 108 | 108 | - | 108 different cause-effect pairs selected from 37 datasets covering domains like meteorology, economy, medicine, engineering, biology. Focuses on the causal discovery problem (deciding whether X causes Y or Y causes X). | FreeBSD |
| **IHDP** [Shalit et al., 2017](http://proceedings.mlr.press/v70/shalit17a.html) | Variable | 2,000 | 2,000 | ½ | IHDP is the Infant Health and Development Program dataset, focusing on the effect of home visits on cognitive test scores for infants. | Custom Dataset Terms |
| **CRAFT** [Ates et al., 2022](https://aclanthology.org/2022.findings-acl.205) | Video | 58,000 | - | Full | A video question-answering dataset requiring comprehension of physical forces and object interactions. Contains descriptive and counterfactual questions. | MIT |
| **Commonsense Causality in Text Format** |
| **Temporal-Causal** [Bethard et al., 2008](https://aclanthology.org/L08-1018/) | Clause | 1,000 | 271 | - | A corpus of 1,000 event pairs covering both temporal and causal relations. | Missing |
| **CW** [Ferguson & Sanford, 2008](https://www.sciencedirect.com/science/article/pii/S0749596X07000770) | Clause | 128 | 128 | Full | CW is collected from psycholinguistic experiments and includes counterfactual examples. | Missing |
| **SemEval07-T4** [Girju et al., 2007](https://aclanthology.org/S07-1003/) | Phrase | 220 | 114 | - | Focuses on semantic analysis and automatic recognition of relations between word pairs, including causal relations. | Missing |
| **SemEval10-T8** [Hendrickx et al., 2010](https://aclanthology.org/S10-1006/) | Phrase | 10,717 | 1,331 | - | Similar to SemEval07-T4, focuses on classification of semantic relations between pairs of nominals, including cause-effect relations. | CC BY 3.0 Unported |
| **COPA** [Roemmele et al., 2011](http://www.aaai.org/ocs/index.php/SSS/SSS11/paper/view/2418) | Sentence | 2,000 | 1,000 | - | Each question has a premise and two plausible causes/effects, with the correct one being more plausible. | BSD 2-Clause |
| **EventCausality** [Do et al., 2011](https://aclanthology.org/D11-1027) | Clause | 583 | 583 | - | A causality corpus built by detecting causality between events using discourse connectives. | Missing |
| **BioCause** [Mihuailua et al., 2013](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-14-2) | Clause | 851 | 851 | - | Contains 851 causal relations from 19 biomedical journal articles in infectious diseases. | Creative Commons |
| **CausalTimeBank** [Mirza et al., 2014](https://aclanthology.org/W14-0702) | Sentence | 318 | 318 | - | Timebank corpus with causal samples taken from TempEval-3 corpus. | CC BY-NC-SA 3.0 |
| **CaTeRs** [Mostafazadeh et al., 2016](https://aclanthology.org/W16-1007) | Sentence | 2,502 | 308 | - | Causal and temporal relations annotated from ROCStories corpus. | Missing |
| **AltLex** [Hidey & McKeown, 2016](https://aclanthology.org/P16-1135) | Clause | 44,240 | 4,595 | - | An open class of markers that contains causality. | Missing |
| **BECauSE 2.0** [Dunietz et al., 2017](https://aclanthology.org/W17-0812) | Sentence | 729 | 554 | - | Focuses on causal relations and other co-existing relations. | MIT |
| **ESL** [Caselli & Vossen, 2017](https://aclanthology.org/W17-2711) | Sentence | 2,608 | 2,608 | - | A corpus for detecting causal and temporal relations. | CC BY 3.0 Unported |
| **PDTB** [Webber et al., 2019](http://www.lrec-conf.org/proceedings/lrec2008/pdf/754_paper.pdf) | Clause | 7,991 | 7,991 | - | Marks discourse relations, including causation, grounded in explicit words or phrases. | LDC User Agreement |
| **TimeTravel** [Qin et al., 2019](https://aclanthology.org/D19-1509) | Sentence | 109,964 | 29,849 | ½ | Contains original stories, counterfactual facts, and new storylines compatible with the counterfactual facts. | MIT |
| **GLUCOSE** | Clause | 670K | 670K | - | Annotates 10 dimensions of causal explanation from short stories, focusing on implicit causes and effects. | Creative Commons Attribution-NonCommercial 4.0 |
| **XCOPA** [Ponti et al., 2020](https://aclanthology.org/2020.emnlp-main.185) | Sentence | 11,000 | 11,000 | - | Multilingual version of the COPA dataset, spanning 11 languages. | CC BY 4.0 |
| **SemEval20-T5** [Yang et al., 2020](https://aclanthology.org/2020.semeval-1.40) | Clause | 25,501 | 25,501 | Full | Dataset for determining counterfactual statements and extracting antecedents and consequents. | Missing |
| **CausalBank** [Li et al., 2021](https://www.ijcai.org/proceedings/2020/0502.pdf) | Clause | 314M | 314M | - | Cause-effect statements collected from the Common Crawl corpus using causal lexical patterns. | - |
| **e-CARE** [Du et al., 2022](https://aclanthology.org/2022.acl-long.33) | Sentence | 21,324 | 21,324 | - | Cause-effect pairs and conceptual explanations for causation. | MIT |
| **CoSIm** [Kim et al., 2022](https://aclanthology.org/2022.naacl-main.66) | Image + Text | 3,500 | 3,500 | Full | A multimodal counterfactual reasoning dataset for commonsense scene imagination, with both text and image components. | MIT |
| **CRASS** [Frohberg & Binder, 2022](https://aclanthology.org/2022.lrec-1.229) | Sentence | 274 | 274 | Full | Focuses on counterfactual reasoning in a question-answering format. | Apache 2.0 |
| **IfQA** [Yu et al., 2023](https://aclanthology.org/2023.emnlp-main.515/) | Sentence | 3,800 | 3,800 | Full | Open-domain counterfactual question-answering dataset. | Missing |
| **CW-extended** [Li et al., 2023](https://aclanthology.org/2023.acl-short.70) | Sentence | 10,848 | 10,848 | Full | Augmentation of CW dataset through word replacements, focusing on counterfactual statements. | Missing |
| **CausalQuest** [Ceraolo et al., 2024](https://arxiv.org/abs/2405.20318) | Sentence | 13,500 | 13,500 | ½ | A dataset of natural causal questions collected from social networks, search engines, and AI assistants. | Apache 2.0 |
| **δ-CAUSAL** [Cui et al., 2024](https://aclanthology.org/2024.findings-acl.384/) | Sentence | 11,245 | 11,245 | ½ | Causal dataset exploring defeasibility and uncertainty in commonsense causality. | MIT |
| **Commonsense Causality in Knowledge Graph Format** |
| **CausalNet** [Luo et al., 2016](http://www.aaai.org/ocs/index.php/KR/KR16/paper/view/12818) | Word | 11M | 11M | - | Vast collection of causal relationships from Bing web pages. | Missing |
| **ConceptNet** [Speer et al., 2017](https://arxiv.org/abs/1612.03975) | Phrase | 473,000 | - | - | Knowledge graph version of the Open Mind Common Sense project, including causal relations. | CC BY-SA 4.0 |
| **Event2Mind** [Rashkin et al., 2018](https://aclanthology.org/P18-1043) | Phrase | 25,000 | - | - | Annotates intent and reactions to given events, including causal relations. | MIT |
| **ATOMIC** [Sap et al., 2019](https://aclanthology.org/D19-1454) | Sentence | 877K | - | ½ | Collects commonsense knowledge in the form of "if-then" relations. | CC BY 4.0 |
| **ASER** [Zhang et al., 2020](https://dl.acm.org/doi/10.1145/3366423.3380107) | Sentence | 64M | 494K | - | Eventuality knowledge graph extracted from large textual data. | MIT |
| **CauseNet** [Heindorf et al., 2020](https://dl.acm.org/doi/10.1145/3340531.3412763) | Word | 11M | 11M | - | Causal relations extracted from web sources with 83% precision. | CC BY 4.0 |
| **CEGraph** [Li et al., 2021](https://arxiv.org/abs/2107.09846) | Phrase | 89.1M | 89.1M | - | Large lexical causal knowledge graph associated with CausalBank. | Missing |



