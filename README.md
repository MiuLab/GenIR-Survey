# Generative IR Survey Paper Structure

## Introduction
- Briefly introduce the history and trend in IR
- Traditional DPR (Retrieve then Rank)
<img width="439" alt="image" src="https://github.com/MiuLab/GenIR-Survey/assets/81730878/14bf607d-74b3-4e75-ac59-6d92accd68e9">

- propose an alternative IR architecture called differentiable search index (DSI), direct seq2seq map query to document ID
<img width="733" alt="image" src="https://github.com/MiuLab/GenIR-Survey/assets/81730878/4347b414-6673-4231-980a-cf1422907728">

![image](https://github.com/MiuLab/GenIR-Survey/assets/109788532/66cd210d-999a-469a-8055-941aeff361e1)


## Definition of GenIR (DSI)
<img width="1014" alt="image" src="https://github.com/MiuLab/GenIR-Survey/assets/81730878/6850745b-3a90-4946-b57a-ed38e0055ce9">

### Intro to DSI
Two Major Components
- Indexing
- Retrieval
  
## Identifier Strategies in Generative IR
### Document Identifiers

- Transformer Memory as a Differentiable Search Index
- DSI++: Updating Transformer Memory with New Documents
- Learning to Tokenize for Generative Retrieval

### String Identifiers

- Autoregressive Search Engines: Generating Substrings as Document Identifiers
- Semantic-Enhanced Differentiable Search Index Inspired by Learning Strategies
- Learning to Rank in Generative Retrieval
- TOME: A Two-stage Approach for Model-based Retrieval
- Multiview Identifiers Enhanced Generative Retrieval

## Enhancing Query Generation and Expansion
- generating more training data
- document representation as queries

## Document Representation in DSI
- DSI
    - Direct Indexing
    - Set Indexing
    - Inverted Index
- Bridging the Gap
    - queries as representation
    - Bridging the Gap Between Indexing and Retrieval for Differentiable Search Index with Query Generation
    - Multiview Identifiers Enhanced Generative Retrieval

## Add New Documents
- DSI++: Updating Transformer Memory with New Documents
- Continual Learning for Generative Retrieval over Dynamic Corpora

## Evaluation of Generative IR
Compare the performance of traditional IR systems with DSI-based IR systems

## Limitations and Future Directions
- **Challenges with DSI**: Address potential issues
  - generating non-existent document IDs (FM Index)
  - scaling DSI systems to handle large data volumes.

This structure aims to provide a comprehensive overview of Generative IR and the pivotal role of Differentiable Search Indexes, making it accessible to newcomers while detailing the progress and challenges in the field.
