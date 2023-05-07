# CS598DLH_finalProj
- This is the repo for UIUC CS598 Deep Learning for Healthcare final project. 
- Group ID 52. Members are Youyou Zhang and Siwei Zhang.

## Original paper citation
- Hsieh K, Wang Y, Chen L, Zhao Z, Savitz S, Jiang X, Tang J, Kim Y. Drug Repurposing for COVID-19 using Graph Neural Network with Genetic, Mechanistic, and Epidemiological Validation. Res Sq [Preprint]. 2020 Dec 11:rs.3.rs-114758. doi: 10.21203/rs.3.rs-114758/v1. Update in: Sci Rep. 2021 Nov 30;11(1):23179. PMID: 33330858; PMCID: PMC7743080.
- Author's repo link: https://github.com/yejinjkim/drug-repurposing-graph 

## Data
- The mentioned 3 CTD datasets can be found under `data/CTD`. The most up-to-date data CTD data can be downloaded from [CTDbase] (http://ctdbase.org/detail.go?type=disease&acc=MESH%3AD000086382)
- The mentioned virus-host protein-protein interaction data from a [Nature] (https://www.nature.com/articles/s41586-020-2286-9#Sec36) publication by Gordon et al. can be found under `data/biology-database`.
- The mentioned pre-trained [DRKG embedding](https://github.com/gnn4dr/DRKG) can be downloaded from the link repo.

## Instructions
- Run `preprocessing.ipynb` to process all raw data and export as a pickle file.
- Run `graph-representation-ranking.ipynb` to builds a SARS-CoV-2 knowledge graph and built an initial ranking model that predicts antiviral effectiveness.
- Run `graph-representation-ranking-hybird.ipynb` to 
