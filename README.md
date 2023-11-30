# Generative Search System Project

## Project Overview

**Title:** Generative Search

**Team Members:**
- **Mohammad Tamim** (Team Captain, NetID: tamim2)
- **Timothy Cannella** (NetID: tdc5)
- **Luke Freitag** (NetID: lukegf2)

**Description:**  
Our project, "Generative Search," leverages Retrieval Augmented Generation (RAG) combined with Large Language Models (LLMs) to develop an innovative generative search system. Trained on the "CS 410 Text Information Systems" course transcripts from Coursera, this system aims to deliver contextually accurate and informative responses to user queries.

## Objectives

- To develop a search system that generates contextually relevant responses to queries related to the "CS 410 Text Information Systems" course material.
- To enhance information retrieval by transitioning from traditional search methods to a generative approach, thereby reducing the risk of false or misleading information.

## Methodology

### 1. Data Collection:
   - Collection and organization of "CS 410 Text Information Systems" transcripts.
   - Creation of a Q&A dataset with multiple paraphrases for each question.

### 2. Design, Development, and Testing:
   - Design and development of the Generative Search system using Python and Google Colab.
   - Conversion of questions to context-embedded vectors.
   - Implementation of an Online Generative Search Module using RAG and LLM.

### 3. Results Evaluation:
   - Preparation of an evaluation set of 50 questions, assessing both related and unrelated queries.
   - Quantitative evaluation using cosine similarity.
   - Qualitative evaluation through manual review of responses.

### 4. Reporting:
   - Development of a comprehensive final report detailing project methods, results, and recommendations.

## Repository Structure

- `build_vectors.ipynb`: Python notebook for converting questions to embedded vectors.
- `generative_search.ipynb`: Python notebook for the Generative Search system.
- `generative_search_development_evaluation.ipynb`: Notebook detailing the development process and evaluation of the Generative Search system.
- `Qualitative_Evaluation.csv`: Results of the qualitative evaluation.
- `Quantitative_Evaluation.csv`: Results of the quantitative evaluation.
- `TIS_Q&A.csv`, `TIS_Embedded_Q&A.csv`: Datasets used for the project.
- `TIS_Transcript Scraping.txt`: Transcript data from the "CS 410 Text Information Systems" course.
- `Final Project Report.pdf`: Comprehensive final report of the project.

**Note:** To run `generative_search.ipynb` in Google Colab, select: Runtime -> Change runtime type -> T4 GPU.

## Conclusion

Our team has successfully developed the Generative Search system, achieving our project objectives and demonstrating significant advancements in information retrieval. With the project now complete, we have documented our journey, challenges, and findings in the final report, showcasing our contributions to the field.

[GitHub Repository Link](https://github.com/tamimuiuc/CourseProject)
