# Overview of my work on semantic graphs

This is an overview over the code/data associated with my dissertation.

## MR tools
                                                  
### MR metrics & MR-to-MR alignment

#### Structural matching

- [Smatch++](https://github.com/flipz357/smatchpp), [📜](https://aclanthology.org/2023.findings-eacl.118/): optimal and standardized Smatch 
- [Smaragd](https://github.com/PhMeier/Smaragd/), [📜](https://arxiv.org/abs/2203.13226): fast approximated Smatch with neural network

#### Advanced matching beyond structure

- [S2match](https://github.com/Heidelberg-NLP/amr-metric-suite), [📜](https://aclanthology.org/2020.tacl-1.34/): Smatch matching with node labels matched via word embeddings
- [WWLK](https://github.com/flipz357/weisfeiler-leman-amr-metrics), [📜](https://aclanthology.org/2021.tacl-1.85/): Weisfeiler Leman MR Kernel with embeddings for contextualied matching, many-to-many node alignment

### Graph processing, reading, writing

- [Smatch++](https://github.com/flipz357/smatchpp), [📜](https://aclanthology.org/2023.findings-eacl.118/): can read and modify graphs, standardization, sub-graph extraction

### MR-to-text alignment

- [WWLK-aligner](https://github.com/flipz357/Simple-AMR-Aligner), [📜](https://aclanthology.org/2021.tacl-1.85/): Easy-to-use Wasserstein amr-text alignment

### MR metric evaluation

- [BAMBOO](https://github.com/flipz357/bamboo-amr-benchmark), [📜](https://aclanthology.org/2021.tacl-1.85/): Live BAMBOO benchmark for MR metric comparison

## MR applications

- [Explainable sentence embeddings (S3BERT)](https://github.com/flipz357/S3BERT), [📜](https://aclanthology.org/2022.aacl-main.48/): Infusing fine-grained similarity into a state-of-the-art sentence embedding model for explainable and decomposable embeddings
- [Explainable NLG evaluation](https://github.com/flipz357/MFscore), [📜](https://aclanthology.org/2021.eacl-main.129/): Evaluation of NLG systems in meaning space
- [AMR4NLI](https://github.com/flipz357/amr4nli), [📜](https://arxiv.org/abs/2306.00936): Asymmetric and unsupervised application of MR metrics for transparent entailment rating
- [Textual argument similarity](https://github.com/Heidelberg-NLP/amr-argument-sim), [📜](https://aclanthology.org/2021.argmining-1.3/)

## Neural graph encoder

- [Penman-informed CNN](https://github.com/flipz357/amr-quality-rater), [📜](https://aclanthology.org/2020.aacl-main.27/): Simple and efficient neural graph encoding of graphs such as AMRs, dependency trees, etc.

## Corpora of (A)MR annotations

- [NLI AMR](https://github.com/flipz357/amr4nli), [📜](https://arxiv.org/abs/2306.00936): >1 mio Silver AMR pairs of five NLI data sets
- [ParsEval](https://github.com/Heidelberg-NLP/AMRParseEval), [📜](https://aclanthology.org/2022.eval4nlp-1.4/): 800 Parsed AMRs with human quality annoations (domain: little Prince, AMR3)
- [Textual Similarity](https://github.com/flipz357/bamboo-amr-benchmark), [📜](https://aclanthology.org/2021.tacl-1.85/): Silver AMRs of text similarity benchmarks (e.g., STS) that are annoated with human textual similarity ratings
- [Textual argument similarity](https://github.com/Heidelberg-NLP/amr-argument-sim), [📜](https://aclanthology.org/2021.argmining-1.3/): Silver AMRs of textual argument similarity that are annoated with human textual similarity ratings
