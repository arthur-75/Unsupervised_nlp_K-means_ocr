# Unsupervised nlp K-means ocr job interview question
Unsupervised text classification (OCR data) using k-means with 100% accuracy. 

Objective:
Each year, the accounting management service is scaning thousands of invoices and contracts. All these pdf scans are stored in a Database, and manually flaged. The accounting service wants to automate the process.
Given a bunch of documents without label are you able to separate invoices from contracts?
As a Data Scientist you offer to implement a machine learning solution. Nonetheless, accounting services bring to your attention:
Formats are constantly evolving therefore, you cannot use past documents to design your solution
They will send you TEXT data after passing pdf into an OCR (noise may happen)

More Technically
/train folder contains raw text invoices and contracts (0000.txt to 0799.txt)
/val folder contains raw text invoices and contracts (0000.txt to 0799.txt) and label.csv to evaluate performances.
You are asked to:
Build a machine learning process to seperate invoices from contracts without previous knowledge.
Evaluate the performances on the validation (/val) dataset.
