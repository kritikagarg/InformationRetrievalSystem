# TREC-COVID Information Retrieval System

## Overview
This project develops an information retrieval system to identify relevant COVID-19 documents. It aims to aid public understanding, support clinicians, and contribute to global pandemic research.

## Dataset
- **CORD-19**: Round 5 dataset from Kaggle, including 128K research papers in JSON and metadata formats.

## Methodology
1. **Data Pre-processing**: Transform raw documents into a searchable format.
2. **Document Indexing**: Utilize Elasticsearch for efficient indexing and retrieval.
3. **Document Retrieval**: Implement query schemes for optimal document fetching.
4. **Re-ranking**: Apply BERT-based models to enhance document relevance ranking.

## Results & Evaluation
- Utilized Trec_eval for evaluation.
- Achieved significant precision improvements with various query combinations and re-ranking techniques.
- Best results observed with COVID-SciBERT model in re-ranking phase.

## Usage
Instructions for setting up and running the system are provided, detailing steps from data pre-processing to document re-ranking.

## License
Refer to the LICENSE file for licensing details.

For further information and detailed methodology, refer to the full report.
