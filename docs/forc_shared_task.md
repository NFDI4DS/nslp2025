---
layout: default
title: FoRC shared task
nav_order: 6
---

# FoRC: Field of Research Classification

A core application of NSLP is classifying scienfitic articles for their respective field of research (FoR). While some respositories already use a classification system, these are often limited either in terms of the used taxonomy or in terms of the classification model. The FoRC shared task aims to classify scientific documents into (sub-)topics according to a predefined schema. The second iteration of the task (see [NSLP 2024](https://nfdi4ds.github.io/nslp2024/docs/forc_shared_task.html) for the first) will focus on classifying computational linguistics publications taken from the ACL Anthology using the FoRC4CL taxonomy, consisting of 170 core CL (sub-)topics in a three-tiered hierarchy. The previous iteration's corpus, FoRC4CL, will be extended with weakly supervised data to create a larger training corpus. Metadata fields include ACL Anthology ID, title, abstract, author(s), URL to the full text, publisher, publication year and month, proceedings title, DOI, and venue. As a multi-label hierarchical classification problem, this subtask will be evaluated by computing micro and macro precison, recall, and F1-score.

**Data**
You can download the data on Zenodo following this link: [https://zenodo.org/records/14888497](https://zenodo.org/records/14888497).
The data includes the original FoRC4CL corpus as well as additional 41,107 weakly supervised ACL publications.
A link to the codabench competition page will be provided by February 21, 2025. 

**Organisers**

* Maria Francis (DFKI, Berlin, Germany & University of Trento, Trento, Italy)
* Raia Abu Ahmad (DFKI, Berlin, Germany)
* Ekaterina Borisova (DFKI, Berlin, Germany) 
* Georg Rehm (DFKI, Berlin, Germany) 

**Contact**

* maria.francis@dfki.de

**Important dates**

* Training and testing data release: Feburary 18, 2025
* System submissions deadline: March 25, 2025
* Paper submissions: March 27, 2025
* Notification of acceptance: April 10, 2025
* Camera-ready submission: April 17, 2025
