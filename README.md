# Generative IR Survey Paper Structure

## Introduction
- Traditional DPR (Retrieve then Rank)
- propose an alternative IR architecture called differentiable search index (DSI), direct seq2seq map query to document ID
## Definition of GenIR (DSI)
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
