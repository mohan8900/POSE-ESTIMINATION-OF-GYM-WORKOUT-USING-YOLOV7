# POSE-ESTIMINATION-OF-GYM-WORKOUT-USING-YOLOV7

# Aim:
he aim of this project is to develop an advanced document search and retrieval system that leverages Google's Gemini Pro, integrated with LangChain and FAISS for high-dimensional similarity searches. The goal is to enable rapid, accurate, and efficient indexing and retrieval of relevant information from multiple PDF documents, providing a powerful tool for extracting knowledge in research, legal, and academic contexts.
# About:
This project integrates Google's Gemini Pro, LangChain, and FAISS to create an advanced document search and retrieval system. It efficiently indexes and searches through multiple PDF documents using FAISS vector embeddings for high-dimensional similarity searches. This combination allows for fast, accurate retrieval of relevant information, making it an ideal tool for research, legal, and academic use cases that require detailed document analysis.
# Features
```
-Advanced Search & Retrieval
-FAISS Vector Embeddings
-Multi-PDF Indexing
-LangChain Integration
-Contextual Knowledge Extraction
-Scalability
```
# Requirements:
```
-Python 3.8+: Main programming language.
-Google's Gemini Pro API: For LLM-powered search.
-LangChain: To chain tasks with the language model.
-FAISS: For vector-based similarity search.
-PyPDF2/PDFMiner: For PDF text extraction.
-Sentence-Transformers: To generate vector embeddings.
-Hardware: High-performance CPU/GPU, ample storage, 8GB+ RAM.
-Optional Cloud Platform: For scalability and large datasets.
```
# System Architecture:
![image](https://github.com/user-attachments/assets/ff5ace68-3fd0-4354-b282-c872712f70a6)
# Output:
### After browsing for our website, the following page will be shown first. 
![image](https://github.com/user-attachments/assets/7c288e5f-1784-42c4-ade8-ecd702717239)

### Click the browse file buttom to upload the pdf documents
![image](https://github.com/user-attachments/assets/a2d48321-6658-4746-9e49-3006689d5045)

### After uploading the pdf doc’s click on summit & process button
![image](https://github.com/user-attachments/assets/3a7236a4-62f3-41ff-ade4-a4fc99911cae)

### Then ask the question which is related to the uploaded pdf’s and it will give you the content of the related query asked.
![image](https://github.com/user-attachments/assets/580c1710-2d54-4f89-9caa-6c6f1a425ac1)

### Additionly we give that you can print the content,record a screencast,setting(change background mode & change the font ).  
![image](https://github.com/user-attachments/assets/40020dc2-d9ca-47af-988b-4ed81fc96b0d)

# Results of the "Chat with PDF using Gemini" Project:

PDF Upload & Processing:
Result: Text extracted from PDFs, split into chunks, and embeddings created/stored in FAISS.
Success Message: "Processing completed!"

User Question Submission:
Result: Relevant text chunks are retrieved from the FAISS index based on the user's question.

Answer Generation:
Result: Google Generative AI generates an accurate answer from the PDF content.
Example: User asks, "What are the climate change factors?"
Generated Answer: "Temperature changes, altered rainfall, and CO2 levels."

Edge Cases:
No PDFs: Error: "Please upload a PDF."
No Answer: Response: "Answer is not available in the context.

# Articles published / References:
[1] Asbjørn Følstad and Marita Skjuve. 2019. Chatbots for customer service: user experience and motivation. In Proceedings of the 1st International Conference on Conversational User Interfaces (CUI '19). Association for Computing Machinery, New York, NY, USA, Article 1, 1–9. https://doi.org/10.1145/3342775.3342784
[2] Su, Hongjin, Weijia Shi, Jungo Kasai, Yizhong Wang, Yushi Hu, Mari Ostendorf, Wen Yih, Noah A. Smith, Luke Zettlemoyer, and Tao Yu. "One Embedder, Any Task: Instruction-Finetuned Text Embeddings." ArXiv, (2022). /abs/2212.09741. N W Marti et al 2020 J. Phys.: Conf. Ser. 1516 012022
[3] Kim, S., Rawat, A. S., Zaheer, M., Jayasumana, S., Sadhanala, V., Jitkrittum, W., Menon, A. K., Fergus, R., & Kumar, S. (2023). EmbedDistill: A Geometric Knowledge Distillation for Information Retrieval. ArXiv. /abs/2301.12005 
[4] Dao, Mai Thi Hong. "International Journal of Management and Organizational Research." (2023)

[5] Jahan, Md Saroar, et al. "A Comprehensive Study on NLP Data Augmentation for Hate Speech Detection: Legacy Methods, BERT, and LLMs." arXiv preprint arXiv:2404.00303 (2024).
[6] Malode, Vishal Manjunatha. Benchmarking public large language model. Diss. Technische Hochschule Ingolstadt, 2024.
[7] L. Padoan, M. Cesetti, L. Brunello, M. Antonelli, B. Zamengo and F. Silvestri, "Mobility ChatBot: supporting decision making in mobility data with chatbots," 2024 25th IEEE International Conference on Mobile Data Management (MDM), Brussels, Belgium, 2024, pp. 295-300, doi: 10.1109/MDM61037.2024.00061. keywords: {Structured Query Language;Large language models;Decision making;Natural languages;Data visualization;Transportation;Writing;Mobility data;Large Language Models;decision making;agents},


















