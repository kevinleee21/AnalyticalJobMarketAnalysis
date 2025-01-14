# Analytical Job Market Analysis

## Libraries Overview and Installation
---

1. **Pandas**  
     ```bash
     pip install pandas
     ```
2. **Matplotlib**  
   - **What it does**: This library helps create charts and graphs, like bar charts or line graphs, to visualize data. It turns numbers into visuals, making the data easier to understand.  
   - **How to set it up**:  
     ```bash
     pip install matplotlib
     ```
3. **Plotly Express**
   - For interactive visualizations
     ```bash
     pip install plotly
     ```

4. **NLTK (Natural Language Toolkit)**  
   - toolkit that helps analyze and understand text, like breaking down sentences into words, removing unnecessary words, and simplifying words to their root forms and it is essential for processing written information, like finding key phrases or cleaning up messy text.  
   - **How to set it up**:  
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
5. **String**  
   - built-in Python tool for handling text, such as removing punctuation or extra spaces. It is powerful tool for cleaning and preparing text for analysis.  

6. **Scipy**  
   - used for mathematical calculations, like finding trends in numbers or understanding how data is distributed and helps measure things like how "skewed" (off-center) data is, which tells us if something unusual is happening in the data.    
     ```bash
     pip install scipy
     ```
7. **SentenceTransformers**  
   - tool that compares the meaning of sentences. It helps find similarities between different pieces of text, even if the wording is different. Important for analyzing and understanding large amounts of text, such as comparing job descriptions or categorizing text data.  
     ```bash
     pip install sentence-transformers
     ```
