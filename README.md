# KG PhD Course
This repository was made as part of the handin for the PhD course Knowledge Graphs and Semantic Web technologies in 2024 at Aalborg University.

This implements a system that performs CSV to KG matching, as specified on the [course GitHub](https://github.com/city-knowledge-graphs/phd-course).

## Usage
To run the CSV-to-KG matching:

1. Download the CSV tables [WikidataTables2024R1.tar.gz](https://github.com/sem-tab-challenge/2024/blob/main/data/WikidataTables2024R1.tar.gz) from semtab 2024.

2. Extract the contents into the /data/ folder, such that the folder structure becomes KG-PHD-COURSE/data/WikidataTables2024R1/DataSets/...

3. Run the CSV2KG.ipynb notebook, which performs both CEA, CTA, and CPA for the 10 first tables.