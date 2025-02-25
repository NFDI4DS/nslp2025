---
layout: default
title: MESD shared task
nav_order: 5
---

# MESD: Metadata Extraction from Scholarly Documents

Making scholarly data FAIR (i.e., findable, accessible, interoperable, reusable) is essential to foster the progress of research, as each new study builds upon the foundation of previous work. Central to achieving FAIR publications is the availability of robust metadata. While publishers now systematically collect metadata through rigorous validation processes, historically, especially among smaller and mid-sized publishers, the collection of accessible metadata was inconsistent. Consequently, many articles lack accessible metadata, making it challenging for researchers to discover and use these publications.

To address these challenges, the MESD shared task will provide participants with training and validation datasets to develop and refine metadata extraction techniques. The training dataset will consist of 500 samples, while the validation set will include 100 samples. Each sample will comprise a) the original PDF document, b) extracted text, and c) a metadata file detailing nine predefined labels and the locations of these labels in the extracted text. Note that while most documents will contain standard labels such as “Title”, “Authors” and “Abstract”, some may lack others, such as “DOI” or “publication venue”.

A label-free test dataset of 100 samples will be released in the last week of the shared task timeline. Participants will then be required to upload the results of their systems on this dataset to our platform. The evaluation of submissions will focus on multiple metrics including accuracy, precision, recall, and F1 score (the F1 score will determine the ranking). This evaluation is based on **Levenshtein Similarity** compared to the gold standard is at least 95%; meaning that while the label need not match exactly, it must closely resemble the source document's relevant tokens. Additionally, participants are encouraged to discuss the complexity of their methods, considering both training and inference stages, to provide insights into the practical application and scalability of their solutions. **The evaluation function is provided in the [main repository](https://github.com/zeyd31/S2ORC_Exp500v1/tree/main/Evaluation)**

## Dataset

You can download the **S2ORC_Exp500v1** dataset here: [Download Link](https://github.com/zeyd31/S2ORC_Exp500v1)

# Organisers

[Zeyd Boukhers](https://fit.fraunhofer.de/fdda) (Fraunhofer FIT, Germany): [Email](zeyd.boukhers@fit.fraunhofer.de)

# Important dates

* Release of training datasets: January 27, 2025
* Release of testing datasets: February 15, 2025 (Released: [Download Link](https://github.com/zeyd31/S2ORC_Exp500v1/tree/main/test))
* Deadline for system submissions: ~~February 25, 2025~~ March 2, 2025
* Announcement of results: ~~February 27, 2025~~ March 4, 2025
* Paper submission deadline: March 6, 2025
* Notification of acceptance: April 3, 2025
* Camera-ready submission: April 17, 2025
* Workshop: June 1 or 2 2025

All deadlines are 23:59 UTC-12:00 (“anywhere on Earth”).
