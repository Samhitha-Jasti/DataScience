### Text Analytics: 
Using NLP to transfer unstructured text in data to normalized and structured form for analysis and machine learning model.

**How is Text Analytics different from Text Mining:**

Text Mining gives insights and solutions that are qualitative in nature, it tell us what is the analysis with text data.
Text Analytics drives the insights and quantify on them to find main cause through visualization tools, it basically explains the problems with insights that we get from text data.

**Purpose of Text Analytics:**

It is used to draw helpful insights from unstructured data.Text Analytics can be mainly used in organisations for reviewing customer reviews. 
It helps in preventing future trouble.

**Applications of Text Analytics:**
1) Customer Feedback Analysis
2) Product Support
3) Sentiment Analysis 
4) Text Classification,Text Generation,etc.

**Future Possibilities in Text Analytics:**
1) Competitive Businesses
2) Customer Feedback Management
3) Communication
4) Medical Diagnosis
5) Employee Management Systems

One of the most important application of Text Analytics is Topic Analysis. Let's see what is topic analysis, types and it's mechanism.

**What is Topic Analysis:**

Topic analysis is a Natural Language Processing (NLP) technique that allows us to automatically extract meaning from text by identifying recurrent themes or topics.
It automatically assigns topic to text data. (or) Topic analysis (also called topic detection, topic modeling, or topic extraction) is a machine learning technique that organizes and understands large collections of text data, by assigning “tags” or categories according to each individual text’s topic or theme.

#### Purpose of Topic Analysis:
 1) Topic analysis uses natural language processing (NLP) to break down human language to find patterns and unlock semantic structures within texts to extract insights 
and help make data-driven decisions.
 2) Topic Tagging helps in analyzing huge amounts of text data in a fast and cost-effective way.
Approaches to Topic Analysis:
There are two different approaches to topic analysis:
 3) Topic Analysis can be used in many fields like Customer Service, Business Intelligence, Sales and Marketing.
 4) Topic analysis helps businesses become more efficient by saving time on repetitive manual tasks and gathers insights from the text data they manage on a daily basis.
 
### Steps involved in Topic Analysis:
 **1) NLP Topic modeling:**
Used to discover the main topics within a bunch of texts. This is an unsupervised machine learning technique. It doesn't need to define topic tags or train data beforehand.

 **2) NLP Topic classification:**
Used to automatically categorize texts by topics. This is a supervised machine learning technique. This technique needs to know the topics of text before starting the analysis.
This technique is much more effective and accurate than Clustering algorithms.

The main difference between these two techniques is that one uses a supervised algorithm (topic classification), and the other an unsupervised algorithm (topic modeling). 

#### Mechanism of Topic Analysis:
Models of Topic Analysis are able to detect topics in a text with Machine Learning algorithms that count words and find similar group of patterns.
For example, consider we want to know Customers opinion on newly launched features of a laptop. Our topic of interest is Portability,Design and price.
So, now instead of going through whole data set, it will be easier if we just concentrate on out topics of interest.
For Price, analysis models might detect patterns such as currency symbols followed by numbers, related words (affordability, expensive, cheap), 
synonyms (cost, price tag, worth) or phrases (worth every penny), and label the corresponding text accordingly.

#### How does Topic Modelling and Topic classification works?
If we are trying to determine the topics of the texts, we need topic modelling. If we have the topics and we need to classify them, then we need Topic Classification.
Unsupervised Learning is easier compared to Supervised Learning, but when dealing large sets, it needs quality data. 
And the models doesn't really label all the topics and give it to us. Rather, they will churn out collections of documents that the algorithm thinks are related, and 
specific terms that it used to infer these relations. It will be our job to figure out what these relations actually mean.
On the other hand, Supervised algorithms can make or break the model. If we are consistent in labelling the texts, model can classify new and unseen samples according to 
the topics.

#### Further Learning about Modelling and Classification:
The way these algorithms work is by assuming that each document is composed of a mixture of topics, and then trying to
find out how strong a presence each topic has in a given document. This is done by grouping together the documents based 
on the words they contain, and noticing correlations between them.

I'd like to keep this documentation a beginner friendly source, so I'm not ellaborating the algorithms for topic modelling.
Some of the popular algorithms for topic modelling is: LSA and LDA.

#### Latent Semantic Analysis(LSA):
This is the traditional method for topic modelling. It is based on principle called distributional hypothesis(words and text occuring in similar pieces of text have 
similar meaning). Like Naive Bayes, it is based on the word frequencies of the dataset. 
The general idea is that for every word in each document, you can count the frequency of that word and group together the documents that have high frequencies of the same words.
These algorithms ignore syntax and semantics such as word order, meaning and grammar and just treat every document as unsorted "bag of words".
Frequency is calculated by simply counting, but this approach seems to be limited so TF-IDF is used.
TF-IDF (term frequency-inverse document frequency) is a statistical measure that evaluates how relevant a word is to a document in a document set.
TF-IDF takes how common a word is in document. it gives priority to highly repeated words. After doing the word frequency calculation, we are left with a matrix that 
has a row for every word and a column for every document. Each cell is the calculated frequency for that word in that document. 
This is the document-term matrix; it relates documents to terms.

#### Latent Dirichlet Allocation(LDA):
LDA tries to map all the documents(known) to the unknown topics in such a way that words in each document are mostly
captured by the known topics. LDA works backward from the words in the generated document that make up the document and tries to guess the mixture of topics that resulted in that 
particular arrangement of words.

#### What if we don't have Topic tags?
No worries, the models are capable of generating topics from the text using frequency and space between the words.
But it's not that simple, it's little more complicated.
