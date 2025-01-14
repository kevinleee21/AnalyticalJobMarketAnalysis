# Analytical Job Market Analysis

![image](https://github.com/user-attachments/assets/6e603c70-40d1-4117-ab63-1ffb3ac92c63)

## Project Overview 📖

### What makes a job analytical?

With the rise of Data Scientist and Data Analyst roles in the industry, these positions have garnered significant attention from job seekers due to their competitive salaries, remote work opportunities, and intellectually stimulating challenges. As an aspiring data scientist, I found myself intrigued by what truly defines a job as analytical. The term "analytical" is broad, spanning across various industries and disciplines, which further fueled my curiosity. To delve deeper into this topic, I conducted an analysis to explore the following key questions:

   1. What criteria classify a job as analytical?
   2. Are analytical jobs at risk of being replaced by AI?
   3. What skills are essential for these roles?
   4. What kind of education is typically required for analytical positions?
      
This exploration aims to shed light on the evolving nature of analytical roles and their place in the modern workforce.

### Approach

I began by formulating my own definition of the term "analytical." To further refine my approach, I utilized datasets from the O*NET Database, which provides comprehensive labor market data. Using natural language processing (NLP), I developed a model to classify jobs as analytical or not, based on semantic similarity in textual data.

The process involved normalizing the similarity scores, rescaling them into weights, and calculating the weighted average of work activities associated with each job. Jobs were then classified as analytical if they surpassed a predefined threshold. With this classification in place, I analyzed various characteristics of these roles, including required skills, educational qualifications, and their susceptibility to automation. This systematic approach provided insights into the defining features of analytical jobs and their evolving landscape in the workforce.

### Libraries Overview and Installation
---

1. **Pandas**
   - library used to organize and analyze data in tables. Makes it a lot easier to clean data and identify patterns or missing data
     ```bash
     pip install pandas
     ```
3. **Matplotlib**  
   - helps create charts and graphs, like bar charts or line graphs, to visualize data and turns numbers into visuals, making the data easier to understand.   
     ```bash
     pip install matplotlib
     ```
4. **Plotly Express**
   - For interactive visualizations
     ```bash
     pip install plotly
     ```
5. **NLTK (Natural Language Toolkit)**  
   - toolkit that helps analyze and understand text, like breaking down sentences into words, removing unnecessary words, and simplifying words to their root forms and it is essential for processing written information, like finding key phrases or cleaning up messy text.  
     ```bash
     pip install nltk
     ```
     After installation, you need to download some tools within NLTK:
     ```python
     import nltk
     nltk.download('punkt')  # For splitting text into words
     nltk.download('stopwords')  # For removing unimportant words
     nltk.download('wordnet')  # For simplifying words
     ```
6. **String**  
   - built-in Python tool for handling text, such as removing punctuation or extra spaces. It is powerful tool for cleaning and preparing text for analysis.  

7. **Scipy**  
   - used for mathematical calculations, like finding trends in numbers or understanding how data is distributed and helps measure things like how "skewed" (off-center) data is, which tells us if something unusual is happening in the data.    
     ```bash
     pip install scipy
     ```
8. **SentenceTransformers**  
   - tool that compares the meaning of sentences. It helps find similarities between different pieces of text, even if the wording is different. Important for analyzing and understanding large amounts of text, such as comparing job descriptions or categorizing text data.  
     ```bash
     pip install sentence-transformers
     ```
