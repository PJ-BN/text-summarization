# Article Summarization

This is a small NLP project which can summarize an article. In this model i've used **spaCY** library to generate the model. Here I've used one of the inbuilt pipeline of spaCY **Pytextrank**. 

**PyTextRank** is a Python implementation of TextRank as a spaCy pipeline extension, for graph-based natural language work -- and related knowledge graph practices. This includes the family of textgraph algorithms:

- TextRank
- PositionRank
- Biased TextRank
- TopicRank

**Popular use cases for this library include:**

- phrase extraction: get the top-ranked phrases from a text document
- low-cost extractive summarization of a text document
- help infer concepts from unstructured text into more structured representation


The required libraries for this project are:

``` bash
python -m spacy download en_core_web_lg
pip install pytextrank
```
