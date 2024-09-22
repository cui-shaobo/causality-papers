# Papers about Commonsense Causality
This is the paper list for the literature summarized in our survey published in EMNLP 2024: [The Odyssey of Commonsense Causality: From Foundational Benchmarks to Cutting-Edge Reasoning](https://arxiv.org/abs/2406.19307)

## Benchmarks
## Overview of Causal Datasets

| Dataset | Annotation Unit | \#Overall | \#Causal | C.F. | Brief Introduction | License |
|---------|-----------------|-----------|----------|------|--------------------|---------|
| **First-Principle Causality** |
| **CauseEffectPairs** [Mooij et al., 2016](#) | Variable | 108 | 108 | - | 108 different cause-effect pairs selected from 37 datasets covering domains like meteorology, economy, medicine, engineering, biology. Focuses on the causal discovery problem (deciding whether X causes Y or Y causes X). | FreeBSD |
| **IHDP** [Shalit et al., 2017](#) | Variable | 2,000 | 2,000 | ½ | IHDP is the Infant Health and Development Program dataset, focusing on the effect of home visits on cognitive test scores for infants. | Custom Dataset Terms |
| **CRAFT** [Ates et al., 2022](#) | Video | 58,000 | - | Full | A video question-answering dataset requiring comprehension of physical forces and object interactions. Contains descriptive and counterfactual questions. | MIT |
| **Commonsense Causality in Text Format** |
| **Temporal-Causal** [Bethard et al., 2008](#) | Clause | 1,000 | 271 | - | A corpus of 1,000 event pairs covering both temporal and causal relations. | Missing |
| **CW** [Ferguson & Sanford, 2008](#) | Clause | 128 | 128 | Full | CW is collected from psycholinguistic experiments and includes counterfactual examples. | Missing |
| **SemEval07-T4** [Girju et al., 2007](#) | Phrase | 220 | 114 | - | Focuses on semantic analysis and automatic recognition of relations between word pairs, including causal relations. | Missing |
| **SemEval10-T8** [Hendrickx et al., 2010](#) | Phrase | 10,717 | 1,331 | - | Similar to SemEval07-T4, focuses on classification of semantic relations between pairs of nominals, including cause-effect relations. | CC BY 3.0 Unported |
| **COPA** [Roemmele et al., 2011](#) | Sentence | 2,000 | 1,000 | - | Each question has a premise and two plausible causes/effects, with the correct one being more plausible. | BSD 2-Clause |
| **EventCausality** [Do et al., 2011](#) | Clause | 583 | 583 | - | A causality corpus built by detecting causality between events using discourse connectives. | Missing |
| **BioCause** [Mihuailua et al., 2013](#) | Clause | 851 | 851 | - | Contains 851 causal relations from 19 biomedical journal articles in infectious diseases. | Creative Commons |
| **CausalTimeBank** [Mirza et al., 2014](#) | Sentence | 318 | 318 | - | Timebank corpus with causal samples taken from TempEval-3 corpus. | CC BY-NC-SA 3.0 |
| **CaTeRs** [Mostafazadeh et al., 2016](#) | Sentence | 2,502 | 308 | - | Causal and temporal relations annotated from ROCStories corpus. | Missing |
| **AltLex** [Hidey & McKeown, 2016](#) | Clause | 44,240 | 4,595 | - | An open class of markers that contains causality. | Missing |
| **BECauSE 2.0** [Dunietz et al., 2017](#) | Sentence | 729 | 554 | - | Focuses on causal relations and other co-existing relations. | MIT |
| **ESL** [Caselli & Vossen, 2017](#) | Sentence | 2,608 | 2,608 | - | A corpus for detecting causal and temporal relations. | CC BY 3.0 Unported |
| **PDTB** [Webber et al., 2019](#) | Clause | 7,991 | 7,991 | - | Marks discourse relations, including causation, grounded in explicit words or phrases. | LDC User Agreement |
| **TimeTravel** [Qin et al., 2019](#) | Sentence | 109,964 | 29,849 | ½ | Contains original stories, counterfactual facts, and new storylines compatible with the counterfactual facts. | MIT |
| **GLUCOSE** | Clause | 670K | 670K | - | Annotates 10 dimensions of causal explanation from short stories, focusing on implicit causes and effects. | Creative Commons Attribution-NonCommercial 4.0 |
| **XCOPA** [Ponti et al., 2020](#) | Sentence | 11,000 | 11,000 | - | Multilingual version of the COPA dataset, spanning 11 languages. | CC BY 4.0 |
| **SemEval20-T5** [Yang et al., 2020](#) | Clause | 25,501 | 25,501 | Full | Dataset for determining counterfactual statements and extracting antecedents and consequents. | Missing |
| **CausalBank** [Li et al., 2021](#) | Clause | 314M | 314M | - | Cause-effect statements collected from the Common Crawl corpus using causal lexical patterns. | - |
| **e-CARE** [Du et al., 2022](#) | Sentence | 21,324 | 21,324 | - | Cause-effect pairs and conceptual explanations for causation. | MIT |
| **CoSIm** [Kim et al., 2022](#) | Image + Text | 3,500 | 3,500 | Full | A multimodal counterfactual reasoning dataset for commonsense scene imagination, with both text and image components. | MIT |
| **CRASS** [Frohberg & Binder, 2022](#) | Sentence | 274 | 274 | Full | Focuses on counterfactual reasoning in a question-answering format. | Apache 2.0 |
| **IfQA** [Yu et al., 2023](#) | Sentence | 3,800 | 3,800 | Full | Open-domain counterfactual question-answering dataset. | Missing |
| **CW-extended** [Li et al., 2023](#) | Sentence | 10,848 | 10,848 | Full | Augmentation of CW dataset through word replacements, focusing on counterfactual statements. | Missing |
| **CausalQuest** [Ceraolo et al., 2024](#) | Sentence | 13,500 | 13,500 | ½ | A dataset of natural causal questions collected from social networks, search engines, and AI assistants. | Apache 2.0 |
| **δ-CAUSAL** [Cui et al., 2024](#) | Sentence | 11,245 | 11,245 | ½ | Causal dataset exploring defeasibility and uncertainty in commonsense causality. | MIT |
| **Commonsense Causality in Knowledge Graph Format** |
| **CausalNet** [Luo et al., 2016](#) | Word | 11M | 11M | - | Vast collection of causal relationships from Bing web pages. | Missing |
| **ConceptNet** [Speer et al., 2017](#) | Phrase | 473,000 | - | - | Knowledge graph version of the Open Mind Common Sense project, including causal relations. | CC BY-SA 4.0 |
| **Event2Mind** [Rashkin et al., 2018](#) | Phrase | 25,000 | - | - | Annotates intent and reactions to given events, including causal relations. | MIT |
| **ATOMIC** [Sap et al., 2019](#) | Sentence | 877K | - | ½ | Collects commonsense knowledge in the form of "if-then" relations. | CC BY 4.0 |
| **ASER** [Zhang et al., 2020](#) | Sentence | 64M | 494K | - | Eventuality knowledge graph extracted from large textual data. | MIT |
| **CauseNet** [Heindorf et al., 2020](#) | Word | 11M | 11M | - | Causal relations extracted from web sources with 83% precision. | CC BY 4.0 |
| **CEGraph** [Li et al., 2021](#) | Phrase | 89.1M | 89.1M | - | Large lexical causal knowledge graph associated with CausalBank. | Missing |



