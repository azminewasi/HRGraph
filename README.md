# **HRGraph: Leveraging LLMs for HR Data Knowledge Graphs with Information Propagation-based Job Recommendation**
- **Authors:** Azmine Toushik Wasi
- Read in **ACL Anthology**: https://aclanthology.org/2024.kallm-1.6/

---
**Abstract:** Knowledge Graphs (KGs) serving as semantic networks, prove highly effective in managing complex interconnected data in different domains, by offering a unified, contextualized, and structured representation with flexibility that allows for easy adaptation to evolving knowledge. Processing complex Human Resources (HR) data, KGs can help in different HR functions like recruitment, job matching, identifying learning gaps, and enhancing employee retention. Despite their potential, limited efforts have been made to implement practical HR knowledge graphs. This study addresses this gap by presenting a framework for effectively developing HR knowledge graphs from documents using Large Language Models. The resulting KG can be used for a variety of downstream tasks, including job matching, identifying employee skill gaps, and many more. In this work, we showcase instances where HR KGs prove instrumental in precise job matching, yielding advantages for both employers and employees. Empirical evidence from experiments with information propagation in KGs and Graph Neural Nets, along with case studies underscores the effectiveness of KGs in tasks such as job and employee recommendations and job area classification. 

## Architecture
 Pipeline of *HRGraph*.

<p align="center">
  <img src="fig/HRKG.png" width="1000"/>
</p>

---

## Code and Process

1. `codes\1 LLM Prompting.ipynb` contains LLM Prompting example to get entities.
2. `codes\2 Pre-processing LLM Outputs and Individual KG Construction.ipynb` contains information on the pre-processing process (partial) and individual KG Construction.
3. `codes\3 Full KG Construction.ipynb` provides codes on combining all the KGs into one full KG with visualization.
4. `codes\4 Information Propagation-based Search.ipynb` provides the information propagation code  with visualization.
5. The `.pkl` files are not uploaded due to space constrains. But, they can be developed very easily following the procedure and code provided (some code adjustment and modification can be needed based on your system and design).

---

## Citation
```
@inproceedings{wasi-2024-hrgraph,
    title = "{HRG}raph: Leveraging {LLM}s for {HR} Data Knowledge Graphs with Information Propagation-based Job Recommendation",
    author = "Wasi, Azmine Toushik",
    booktitle = "Proceedings of the 1st Workshop on Knowledge Graphs and Large Language Models (KaLLM 2024)",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.kallm-1.6",
    pages = "56--62",
}
```
