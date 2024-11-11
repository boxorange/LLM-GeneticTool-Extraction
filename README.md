# LLM-GeneticTool-Extraction

This is the official code for the paper published at the 23rd Workshop on Biomedical Natural Language Processing (BioNLP) in 2024: [Leveraging LLMs and Web-based Visualizations for Profiling Bacterial Host Organisms and Genetic Toolboxes](https://aclanthology.org/2024.bionlp-1.28/)

## Overview
The project aims to evaluate various LLMs to extract bacterial hosts and genetic tools from literature using LLMs. We share annotated dataset for bacterial host organims and genetic tools which contains 1,777 entities tagged with 14 labels. 

## Citation
```bibtex
@inproceedings{park-etal-2024-leveraging,
    title = "Leveraging {LLM}s and Web-based Visualizations for Profiling Bacterial Host Organisms and Genetic Toolboxes",
    author = "Park, Gilchan  and
      Mutalik, Vivek  and
      Neely, Christopher  and
      Soto, Carlos  and
      Yoo, Shinjae  and
      Dehal, Paramvir",
    editor = "Demner-Fushman, Dina  and
      Ananiadou, Sophia  and
      Miwa, Makoto  and
      Roberts, Kirk  and
      Tsujii, Junichi",
    booktitle = "Proceedings of the 23rd Workshop on Biomedical Natural Language Processing",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.bionlp-1.28",
    doi = "10.18653/v1/2024.bionlp-1.28",
    pages = "370--379",
    abstract = "Building genetic tools to engineer microorganisms is at the core of understanding and redesigning natural biological systems for useful purposes. Every project to build such a genetic toolbox for an organism starts with a survey of available tools. Despite a decade-long investment and advancement in the field, it is still challenging to mine information about a genetic tool published in the literature and connect that information to microbial genomics and other microbial databases. This information gap not only limits our ability to identify and adopt available tools to a new chassis but also conceals available opportunities to engineer a new microbial host. Recent advances in natural language processing (NLP), particularly large language models (LLMs), offer solutions by enabling efficient extraction of genetic terms and biological entities from a vast array of publications. This work present a method to automate this process, using text-mining to refine models with data from bioRxiv and other databases. We evaluated various LLMs to investigate their ability to recognize bacterial host organisms and genetic toolboxes for engineering. We demonstrate our methodology with a web application that integrates a conversational LLM and visualization tool, connecting user inquiries to genetic resources and literature findings, thereby saving researchers time, money and effort in their laboratory work.",
}
```