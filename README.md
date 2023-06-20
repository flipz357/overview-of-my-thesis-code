# Overview of dissertation

This is an overview over the works associated with my dissertation.

## AMR tools

### Graph processing, reading, writing

- [Smatch++](https://github.com/flipz357/smatchpp), [📜](https://aclanthology.org/2023.findings-eacl.118/): can read and modify graphs, standardization, sub-graph extraction
                                                  
### AMR metrics & AMR-to-AMR alignment

#### Structural matching

- [Smaragd](https://github.com/PhMeier/Smaragd/), [📜](https://arxiv.org/abs/2203.13226): fast approximated Smatch with neural network
- [Smatch++](https://github.com/flipz357/smatchpp), [📜](https://aclanthology.org/2023.findings-eacl.118/): optimal/standardized Smatch and subgraph Smatch

#### Advanced matching beyond structure

- [S2match](https://github.com/Heidelberg-NLP/amr-metric-suite), [📜](https://aclanthology.org/2020.tacl-1.34/): Smatch matching with node labels matched via word embeddings, also included in Smatch++
- [SXmatch](https://github.com/shirawein/Crossling-AMR-Eval), [📜](https://aclanthology.org/2022.coling-1.336/): S2match with cross lingual embedding matching
- [WWLK](https://github.com/flipz357/weisfeiler-leman-amr-metrics), [📜](https://aclanthology.org/2021.tacl-1.85/): Weisfeiler Leman AMR Kernel with embeddings for contextualied matching, many-to-many node alignment 

### AMR-to-text alignment

- [WWLK-aligner](https://github.com/flipz357/Simple-AMR-Aligner), [📜](https://aclanthology.org/2021.tacl-1.85/): Easy-to-use Wasserstein amr-text alignment

## AMR applications

- [Explainable NLG evaluation](https://github.com/flipz357/MFscore), [📜](https://aclanthology.org/2021.eacl-main.129/): Evaluation of NLG systems in meaning space
- [Explainable semantic search (S3BERT)](https://github.com/flipz357/S3BERT), [📜](https://aclanthology.org/2022.aacl-main.48/): Infusing fine-grained similarity into a state-of-the-art sentence embedding model for explainable and decomposable embeddings
- [AMR4NLI](https://github.com/flipz357/amr4nli), [📜](https://arxiv.org/abs/2306.00936): Asymmetric and unsupervised application of MR metrics for transparent entailment rating
- [Argument similarity], [📜](https://aclanthology.org/2021.argmining-1.3/): Unsupervised application of MR metrics similarity of natural langauge arguments

## Neural graph encoder

- [Penman-informed CNN](https://github.com/flipz357/amr-quality-rater), [📜](https://aclanthology.org/2020.aacl-main.27/): Simple and efficient neural graph encoding of graphs such as AMRs, dependency trees, etc.

## Corpora of AMR annotations

- [NLI AMR](https://github.com/flipz357/amr4nli), [📜](https://arxiv.org/abs/2306.00936): >1 mio Silver AMR pairs of five NLI data sets
- [ParsEval](https://github.com/Heidelberg-NLP/AMRParseEval), [📜](https://aclanthology.org/2022.eval4nlp-1.4/): 800 Parsed AMRs with human quality annoations (domain: little Prince, AMR3)
- [Textual Similarity](https://github.com/flipz357/bamboo-amr-benchmark), [📜](https://aclanthology.org/2021.tacl-1.85/): Silver AMRs of text similarity benchmarks (e.g., STS) that are annoated with human textual similarity ratings
- [Textual argument similarity], [📜](https://aclanthology.org/2021.tacl-1.85/): Silver AMRs of textual argument similarity that are annoated with human textual similarity ratings
