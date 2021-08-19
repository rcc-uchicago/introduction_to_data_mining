# Introduction to Data Mining
Introduction to data mining, Fall 2021 by Kaihua Ding

- [x] NYT
- [x] Search Engine Scrapping 
- [x] YouTube Mining / Scraping  
- [x] Mining pdfs 
- [ ] Twitter
- [ ] scraber vs beautiful soup
- [ ] Graph data structure

### Mining New York Times
Did you know that NYT does not publish the same number of articles every day? The following is a article number count plot mined using NYT archival metadata between January 2020 and July 2021. 

![newplot(1)](https://user-images.githubusercontent.com/86792402/129825407-d1c3fe2e-0fda-46f2-80b0-065a668565dc.png)

In this workshop, we will work through a self-supervised learning method. Using sentiment tool to produce labels for our training first, then we are going to train our own NLP word embedding models! Word embedding is a vector representation of text. Word embedding changes in different context (different text corpus). For example, the word "football" means american football in the US, but it means "soccer" in the UK. Word embedding can change wildly depends on context corpus! If you want to extract meaning out of your text data and if the granular information is important to your study, it's alwasy a good use of your time to train your own word embeddings! 

### Mining pdfs
In order to process pdfs, we need to convert the pdf into usable data structure for our textual analysis, i.e., string. 

I will walk you through a brief example, using RCC_cheatsheet.pdf.
1) convert pdf to text, 
2) chop up text through delimiter spliting, 
3) lower case / capitale case management,
4)  named entitiy regonition

### Mining Social Media


### Web Scrapping

### Graph Data Structures (Internet is a Graph)

