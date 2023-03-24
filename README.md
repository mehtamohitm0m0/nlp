# nlp
Reading text file from computer:
Import spacy
budget = open("Budget speech.txt",'r',encoding="utf8")
budget
text = budget.read()
nlp=spacy.load('en_core_web_sm')
doc=nlp(text)
print(doc)
