# CataTQA
**CataTQA: A Benchmark for Tool-Augmented LLM Question Answering over Heterogeneous Catalysis Tables**

## Abstact 
Despite their success in general question answering, large language models (LLMs) struggle with hallucinations and inaccurate reasoning in scientific domains. A major challenge stems from experimental data, which are often stored in external sources like supplementary materials and domain-specific databases. These tables are large, heterogeneous, and semantically complex, making them difficult for LLMs to interpret. While external tools show promise, current benchmarks fail to assess LLMs' ability to navigate this data—particularly in locating relevant tables, retrieving key columns, interpreting experimental conditions, and invoking tools.To address this gap, we introduce CataTQA, a new benchmark for catalytic materials. CataTQA features an automated dataset framework and four auxiliary tools. We evaluate tool-enhanced LLMs across five dimensions: table location, column retrieval, condition analysis, tool calling, and question answering, identifying their strengths and weaknesses.Our work sets a new benchmark for evaluating LLMs in scientific fields and paves the way for future advancements.

## setup
```python
  pip install -r requirements.txt
```
## download dataset
  metadata: <https://huggingface.co/datasets/CuiQiang/CataTQA_Metadata>    
  dataset: <https://huggingface.co/datasets/CuiQiang/CataTQA>
## benchmark
