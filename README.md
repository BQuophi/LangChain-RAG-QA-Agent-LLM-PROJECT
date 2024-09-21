# LangChain-RAG-QA-Agent-LLM-PROJECT

Project from IBMSkillsNetwork 
## Project Overview
- This project demonstrates how to use LangChain to create a question-and-answer (Q&A) agent based on a large language model (LLM) and retrieval augmented generation (RAG) technology. The project leverages the IBM Watsonx Granite LLM and LangChain to set up and configure a Retrieval Augmented Generation (RAG) pipeline.
Introduction

- In the era of information overload, finding accurate and relevant answers to specific questions can be challenging. Traditional search engines often return an overwhelming amount of information, much of which may not be directly relevant to the user's query. This is where Question-and-Answer (Q&A) agents come into play, providing users with precise answers to their questions by leveraging advanced natural language processing (NLP) and machine learning technologies.

- The rapid advancements in large language models (LLMs) have significantly improved the capabilities of Q&A systems. However, these models sometimes struggle with providing grounded and contextually accurate answers, especially when dealing with complex or niche queries. This is where Retrieval Augmented Generation (RAG) technology becomes essential. RAG enhances the performance of Q&A agents by retrieving relevant information from external knowledge bases and integrating it into the generation process.
This project demonstrates how to build a sophisticated Q&A agent using LangChain,  IBM Watsonx Granite, and RAG technology.


## Background
### Large Language Models (LLMs)
- Large Language Models (LLMs) are advanced artificial intelligence systems trained on vast amounts of text data. These models, like GPT-4, are capable of understanding, generating, and manipulating human language with high accuracy. LLMs are often based on the Transformer architecture.
- Introduced in the famous “Attention is All You Need” paper by Google researchers in 2017, the Transformer architecture is a neural network design that excels in processing sequences of data, such as text.
  
![Screenshot (2728)](https://github.com/user-attachments/assets/48a35669-754a-4d11-9247-26815c7f5770)

Source :[Google Research](https://research.google/pubs/attention-is-all-you-need/)

- LLMs are pre trained on a vast array of language tasks—like translation, summarization, and text completion—using extensive datasets. This pretraining helps the models learn the intricacies of language, enabling them to understand and generate human-like text with high accuracy.This makes them able to perform a wide range of language-based tasks. They have transformed various industries by enabling applications like chatbots, virtual assistants, and content creation tools.
  
### LangChain
![image](https://github.com/user-attachments/assets/cc4ade1f-6075-47da-a15f-d4a03c446f44)

[Source(Techchilli)](https://techchilli.com/artificial-intelligence/what-is-langchain/)
- LangChain is a framework that helps you build applications using large language models (LLMs). It provides tools to easily connect different parts of an AI application, like retrieving information and generating text. With LangChain, you can create complex workflows for natural language processing (NLP) tasks without needing to write a lot of code from scratch. This makes it easier for developers to build sophisticated AI applications quickly and efficiently.
- [Read More](https://www.langchain.com/retrieval)

### IBM Watsonx Granite
- IBM  Granite is a family of artificial intelligence (AI) models purpose-built for business, engineered from scratch to help ensure trust and scalability in AI-driven applications. [Source](https://www.ibm.com/granite?utm_source=skills_network&utm_content=in_lab_content_link&utm_id=Lab-Granite+with+LangChain%3A+An+LLM+and+RAG+to+Answer+Questions_v1_1720558829)
  
- These IBM models — built on a decoder-only architecture — aim to help businesses scale AI. For instance, businesses can use them to apply retrieval augmented generation for searching enterprise knowledge bases to generate tailored responses to customer inquiries; use summarization to condense long-form content — like contracts or call transcripts — into short descriptions; and deploy insight extraction and classification to determine factors like customer sentiment. (Source)
  
- Granite offers robust natural language understanding and generation capabilities. Granite is designed to handle a wide range of language tasks, providing powerful APIs for developers to build and integrate AI solutions into their applications. By leveraging Watsonx Granite, developers can enhance their applications with advanced language processing capabilities, ensuring high accuracy and performance.
  
### Retrieval Augmented Generation (RAG)
![image](https://github.com/user-attachments/assets/e98ca302-7b80-42fe-bbaf-d65e219f9c18)
[Source(Truera.com)](https://truera.com/ai-quality-education/generative-ai-rags/what-is-retrieval-augmented-generation-rag-for-llms/)

- RAG is an AI framework for retrieving facts from an external knowledge base to ground large language models (LLMs) on the most accurate, up-to-date information and to give users insight into LLMs' generative process.

- LLMs, despite being trained on vast datasets, have a fixed knowledge base up until their training cut-off. RAG allows these models to dynamically access external databases or documents, effectively extending their knowledge beyond the training data. This is crucial for providing up-to-date and comprehensive information.

- In addition, LLMs sometimes generate plausible but incorrect information, known as hallucinations. RAG mitigates this by providing concrete references from retrieved documents, ensuring the generated responses are based on verified information.

- For more visit : [RAG](https://research.ibm.com/blog/retrieval-augmented-generation-RAG?utm_source=skills_network&utm_content=in_lab_content_link&utm_id=Lab-Granite+with+LangChain%3A+An+LLM+and+RAG+to+Answer+Questions_v1_1720558829)

### Question-and-Answer (Q&A) Agent
A Q&A agent is an AI system designed to answer user queries by understanding and processing natural language inputs. These agents utilize LLMs and other NLP techniques to interpret questions and generate precise answers. Q&A agents are used in various applications, including customer support, virtual assistants, and educational tools, providing users with quick and accurate information based on their queries.

In reference to a documentation on Hugging Face : 

- “Question Answering models can retrieve the answer to a question from a given text, which is useful for searching for an answer in a document. Some question answering models can generate answers without context!
- Question Answering (QA) models can be used to automate the response to frequently asked questions by using a knowledge base (documents) as context. In other words the answers are derived from the context provided using metrics like exact-match and f1-score.
- 
Read more on [Hugging Face](https://huggingface.co/tasks/question-answering”)

### Summary
- The project showcases how modern AI technologies can be harnessed to create advanced Q&A systems that provide precise and contextually relevant answers. By combining LangChain’s flexible framework with IBM Watsonx Granite’s powerful language model and RAG technology, we have demonstrated a practical application of these tools in handling real-world information retrieval and question answering tasks.

---

### Questions Based on the Sample.

Try  out these questions using the Q/A Agent 

1. **Who is known for her beautiful rose bushes in the community garden?**
2. **What type of plants does Tom enjoy planting in the garden?**
3. **Why did the local school visit the community garden?**
4. **What did Emma share with the children during their visit?**
5. **What kind of food was served during the picnic in the garden?**
6. **How did the community garden contribute to the sense of camaraderie among the members?**
7. **What is one activity that community members do together in the garden?**
8. **How did Tom feel about gardening when he first moved to town?**
9. **What did the children learn about during their field trip to the garden?**
10. **What makes the community garden a special place for its members?**
