# CSE6060_HandonTasks
Hands On task in SNLP class

### 1. NLTK Introduction(22-05-2020).ipynb
This file contains all the tasks of the first hands-on class along with the Homework of finding out the frequency distribution and conditional frequency distribution of various presidents from inaugral corpus.
 
### 2. 26-05-2020 Hands On Session.ipynb
This file consists of tasks of second hand-on class where we did various types of stemmers, wordnet lemmatizer, how to segment chinese using jieba and also the introduction to basic text processing pipeline.

### 3. POS_Tagging.ipynb
In this notebook you can find the task of POS-Tagging, where a downloaded <a href="http://www.gutenberg.org/files/15474/15474-0.txt">Indian Mythology book Mahabharata (Volume 1)</a> from Gutenberg and formed word clouds for frequently occuring words on the basis of frequency distribution and conditional distribution.

### 4. POS_tagging_hindi.ipynb
In this notebook I tried using hindi corpus and try POS-Tagging them but I found already a corpus exists in nltk where POS_tagged words are present and also I was not finding the source to download some hindi corpus hence I didn't continue further.

### 5. 12.06.2020 Hands On Session.ipynb
This notebook contains the task of the 3rd Hands-On class, where we get to know how to use stopwords, classify the words as male and female as well as how to vectorize the text and use cosine similarity on the vectorized data.

### 6. Plagarism_Task.ipynb
This notebook contains the task for plagarism check but it is still a work in progress, it contains the work which I did until now.

### 7. (Hands On Session)19-06-2020.ipynb.ipynb
This notebooks contains tasks i.e. 
 1. <b>Downloading Getty's Address</b> 
 2. <b>Removing Stop Words from the address</b>
 3. <b>Extracting bigrams</b>
 4. <b>Extracting collocations in as a team</b>

### 8. Exploring TextBlob.ipynb
In this jupyter notebook, I have explored various features provided by TextBlob library for NLP tasks like 
1. <b>Tokenization</b>
2. <b>part-of-speech tagging</b>
3. <b>Lemmatization</b>
4. <b>WordNetIntegration</b>
5. <b>Sentimental Analysis</b>
etc.

### 9. Using Using StanfordNLP(Stanza) Lib.ipynb
This jupyter notebook explores various function like tokenization, pos tagging, lemmatization, dependency parsing on a <b>Hindi</b> corpus downloaded from internet using Stanza library (<b>StanfordNLP</b> library renamed to <b>Stanza</b>)

<b>Applications</b>
<li><b>StanfordNLP</b> is derived from <b>CoreNLP</b> library which is a industry standard library and is written in Java so it will be a good fit with Chatbots like Google Assistant etc in Regional Language specially for rural areas of India as most people in rural area have their own version of regional language which will help them in farming and there daily day to day lifes. As StanfordNLP comes with out of the box support for 53 languages from around the world, so it will be a seamless integration.</li>
<li>Another application can be analysing content on social media and other websites as most of the content on these websites is in regional language, so it will we really helpful in tackling fake news and other illegal activites on internet which might go unnoticed if someone does it manually.</li>

### 10. Embeddings.ipynb
In this notebook, worked an example of how to do <b>Word2Vec</b> embedding and in this I scraped a news article from a website (<a href="https://theprint.in/ilanomics/this-recession-is-different-india-can-bounce-back-much-faster-than-in-the-past/439612/">Link</a>).

### 11. LOR_Chunking.ipynb
In this notebook, implemented chunking on sample LOR documents.

### 12.WebScrapping_getting NER.ipynb
In this notebook, scrapped a news article from the <a href="https://theprint.in/ilanomics/this-recession-is-different-india-can-bounce-back-much-faster-than-in-the-past/439612/">Link</a> and found <b>NER (Named Entity Relationship)</b> using <b>spacy</b> and <b>nltk</b>.

### 13. Sentiment Analysis on Movie Reviews Using Logistic Regression.ipynb
This notebook contains the content of Hands on session on 26-06-2020 in which we saw how to do sentimental analysis on movie reviews <a href="https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews">(Dataset)</a> end to end with storing model into a pickle file.

### 14. Use Spacy.ipynb
This notebook contains just an example of how to implement NER using spacy library.

### Papers Referred on Regional Language (Hindi)
[1]. Gaikwad, Vijay, and Yashodhara Haribhakta. "Adaptive GloVe and FastText Model for Hindi Word Embeddings." In Proceedings of the 7th ACM IKDD CoDS and 25th COMAD, pp. 175-179. 2020.
[2]. Jha, Vikas Kumar, P. Hrudya, P. N. Vinu, Vishnu Vijayan, and P. Prabaharan. "DHOT-Repository and Classification of Offensive Tweets in the Hindi Language." Procedia Computer Science 171 (2020): 2324-2333.
[3]. Sharma, Richa, Sudha Morwal, Basant Agarwal, Ramesh Chandra, and Mohammad S. Khan. "A deep neural network-based model for named entity recognition for Hindi language." Neural Computing and Applications (2020): 1-13.
