# nlp
Reading text file from computer:
Import spacy
budget = open("Budget speech.txt",'r',encoding="utf8")
budget
text = budget.read()
nlp=spacy.load('en_core_web_sm')
doc=nlp(text)
print(doc)

Reading text file from computer:
Import spacy
budget = open("Budget speech.txt",'r',encoding="utf8")
budget
text = budget.read()
nlp=spacy.load('en_core_web_sm')
doc=nlp(text)
print(doc)




Number of pos count 
listt = []
for i in doc_1:
    listt.append(i.pos_)
print(listt)


from collections import Counter
counts = Counter(listt)
print(counts)


Sheet 1 content:
 
 
 
Sheet2:
Is it a punctuation stop left punction right punctuation
Is it an alphabet a digit lower case upper case title case bracket quote
Number url
 
 
Sheet 3:
List of string comma separated wala
How to read a dataframe
Separating a document into sentences
Tagger
POS
POS count yee apni word doc mein dekhna code ke liye
Visualization of POS
Converting the text into DF with tokens,pos
 
Sheet 4 PARSER AND NER
Token
Tagger
Parser : Tries to find the dependence between the tokens.
Noun chunks
Named entity recognizer
NER for web data
Converting str to doc using NLP
List of entities
Most appeared entities
 
Sheet5
Ruled based matching
How many sentences
Token matching
Phrase matching
Different occurences
Word of length
 
Sheet 6 Similarity batane ke liye poori file chalani hain gandu
Choosing the tokens ismein root words nikale hue hain lemma wala
Creation of a corpus
Giving an id to each token
Bag of words
Creating bow matrix
TFIDF Vectorisation
Similarity of documents chutiye number daalna who phir sabka comparison dikhayega
Sheet 6 word ki similarity gandu
Topic modelling 
Creating a word list
Creating a corpus
LDA model
Displaying topics
 
Sheet 7 Topic modelling
LDA wali sheet hain yee
Accessing tesxt
Create a word list
Creating a corpus
LDA
Displaying model
 
 Sheet 8
Sentiment
Text classification polarity subjectivity wala hain yee
Model wala hain yee naives ka
 
Sheet 9
full_text = []


for i in range(len(data)):
    for j in data[i]:
        full_text.append(j)
