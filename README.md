<p align="center">
  <img src="https://i.ytimg.com/vi/pTHBZ6AyzOg/maxresdefault.jpg" height="300" width = "700"/>
</p>
<br>

**Summarization** is the task of condensing a piece of text to a shorter version, reducing the size of the initial text while at the same time preserving key informational elements and meaning of the content. Manual text summarization is a laborious task, the automation task is gaining popularity. Applications for text summarization include Text classification, news summarization, headline generation, question answering.
In general, there are two different approaches for automatic summarization: extraction and abstraction.

**Extractive Approach:**        
Extractive summarization picks up the sentence directly from the document based on a scoring function to form a coherent summary. This method work by identifying section of the text, cropping out and stich together portions of the content to produce a condensed version.

**Abstractive Approach:**       
Abstractive summarization methods aim at producing summary by interpreting the text using advanced NLP techniques in order to generate a new shorter text – parts of which may not appear as part of the original document, that conveys the most critical information from the original text. Thus they are not restricted to select some sentences and rephrasing them into passages. 

## Objective : 1) Text Summarization Using Spacy

### Library  

spacy <br>

### Description: 
Summarization of the original text by identifying sentence scores and then reviving the information to a summarized format.

## Objective : 2) Text Summarization Using Bart Tokenizer

### Library  

transfomers <br>
bart tokenizer <br>

### Description: 
Summarization of the original text by tokenizing and then providing max length that the sentence should consider to provide a summary. 

## Objective : 3) Text Summarization Using Transformer Pipeline

### Library  

transfomers <br>

### Description: 
Summarization of the original text by tokenizing and then providing min length that the sentence should consider to provide a summary. 
