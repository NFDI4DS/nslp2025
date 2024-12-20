---
layout: default
title: MESD shared task
nav_order: 5
---

# MESD: Metadata Extraction from Scholarly Documents

Making scholarly data FAIR (i. e., findable, accessible, interoperable, reusable) is essential to foster the progress of research, as each new study builds upon the foundation of previous work. Central to achieving FAIR publications is the availability of robust metadata. While publishers now systematically collect metadata through rigorous validation processes, historically, especially among smaller and mid-sized publishers, the collection of accessible metadata was inconsistent. Consequently, many articles lack accessible metadata, making it challenging for researchers to discover and use these publications.

To address these challenges, the MESD shared task will provide participants with training and validation datasets to develop and refine metadata extraction techniques. The training dataset will consist of 500 samples, while the validation set will include 100 samples. Each sample will comprise a) the original PDF document, b) extracted text, and c) a metadata file detailing nine predefined labels along with the locations of these labels in the extracted text. Note that while most documents will contain standard labels such as “Title”, “Authors” and “Abstract”, some may lack others, such as “DOI” or “publication venue”.

In the last week of the shared task timeline, a label-free test dataset of 100 samples will be released. Participants will then be required to upload the results of their systems on this dataset to our platform. The evaluation of submissions will focus on multiple metrics including accuracy, precision, recall, and F1 score (the F1 score will determine the ranking). This evaluation is based on an exact match criterion, i.e., for a label to be considered correctly extracted, it must include all the relevant tokens exactly as they appear in the source document. Additionally, participants are encouraged to discuss the complexity of their methods, considering both training and inference stages, to provide insights into the practical application and scalability of their solutions.

**Organisers**

Zeyd Boukhers (Fraunhofer FIT, Germany)

**Contact**

TBA

**Important dates**

TBA
