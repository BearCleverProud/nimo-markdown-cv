---
layout: cv
title: Conghao Xiong
email:
  url: mailto:conghao.xiong@gmail.com
  text: conghao.xiong@gmail.com
homepage:
  url: http://bearcleverproud.github.io
  text: BearCleverProud
---

# Conghao **Xiong**

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## Education

### **Harbin Institute of Technology** `2015.9 - 2021.7`

```
Harbin, China
```

- B.Eng in Computer Science, Honour School of HIT
- Natural Language Processing track, GPA: 3.72

### **the Johns Hopkins University** `2019.9 - 2021.5`

```
Baltimore, MD, USA
```

- Visiting Student and Researcher at Computer Science Department
- Natural Language Processing track, GPA: 3.86

### **the University of Cambridge** `2017.2 - 2017.2`

```
Cambridge, UK
```

- Visiting Student
- Grades: 89.6(Best Group Award)

## Research Experience

### **The Johns Hopkins University, Centre for Language and Speech Processing(CLSP)** `JHU, 2020.10 - NOW`
_Undergraduate Research, co-work with [Kelly Marchisio](https://github.com/kellymarchisio) and supervised by Dr. [Philipp Koehn](http://www.cs.jhu.edu/~phi/)_<br>
Topic: Semi-Supervised Machine Translation <br>

### **Harbin Institute of Technology, Machine Intelligence and Translation Lab(MI&T Lab)** `HIT, 2020.10 - NOW`
_Capstone Thesis, supervised by Dr. [Bing Xu](http://mitlab.hit.edu.cn/2018/0608/c9183a210160/page.htm)_<br>
Topic: Dialog Emotion Recognition <br>

### **The Johns Hopkins University, Centre for Language and Speech Processing(CLSP)** `JHU, 2019.9 - 2020.7`
_Undergraduate Research supervised by Dr. [Philipp Koehn](http://www.cs.jhu.edu/~phi/)_<br>
Topic: Unsupervised Bilingual Word Induction<br>
- Studied and implemented **Word2Vec**, **Multilingual Word Embedding**, **Orthogonalisation** and **Normalisation** <br>
- Turned the pure **linear mapping** into **non‐linear mapping** to enhance the **expressiveness** of the model <br>
- Modified to the network structure, improved all language pairs accuracy by at least **2%** with **initial dictionary**, some **4%**<br>

### **Harbin Institute of Technology, Centre for Social Computing and Information Retrieval(SCIR)** `HIT, 2019.3 - 2019.8`
_Undergraduate Research supervised by Dr. [Weinan Zhang](http://ir.hit.edu.cn/~wnzhang/)_<br>
Topic: Style Transfer for Dialog Bot<br>
- Style transfer is to transfer a text into another style while **preserving its meaning**(e.g. ”I like this” ‐> ”Omg!!! I really like this!!!”) <br>
- Applied **back translation** with different **decoders** to generate different styles using **GAN** <br>
- Employed a seq2seq model with **language model** of a given style, and another **reinforcement learning** model with even better performance. <br>

### **Harbin Institute of Technology** `HIT, 2017.11 -2017.12` <br>
Topic: Machine Learning Applications on Wearable Devices <br>
- **Collected force data** from the joints and touching faces of the wearble suit <br>
- Used machine learning techniques to **minimise the overall forces** <br>
- Applied different methods like **Linear Regression**, **Decision Tree**, **Deep Learning**, etc. <br>

## Project

### Dialog Chatbot for New Word Explanation `HIT, 2020.10 - 2020.11` <br>
- **Crawled** the papers' title, abstract, keyword from the [CNKI](https://www.cnki.net), [Baidu Academic](https://xueshu.baidu.com) <br>
- Identified which are the **new words** and retrieved **explanation** from [BaiduBaike](https://baike.baidu.com) or [WikiPedia](https://www.wikipedia.org) to build a **JSON file**<br>
- Build a chatbot which could interactively **explain** the new words from the file extracted from the second step<br>

### Intelligent Platform for Teachers and Students `JHU, 2020.3 - 2020.5` <br>
- Built a system which could **link the problem to the corresponding chapters** from the textbook <br>
- Tried to use **BERT** to calculate the **sentence probability** but it turned out to be too **time-consuming**<br>
- Used **Topic Modelling** in the final product with **Micro-Avg F-1 score 0.58** given 5 chapters in [Stanford NLP Book](https://web.stanford.edu/~jurafsky/slp3/) <br>

### Amazon Review Prediction `JHU, 2020.4 - 2020.5` <br>
- Built a system predicting the **rating of a comment text** with **MSE 0.46** on the score scale of 0-5 using **CNN+BiLSTM** and **BERT**<br>
- Built a system predicting the **categories the costumer will probably buy** given the purchase histories with the **accuracy of 0.78** using **SVM** <br>

### Super Mario Reinforcement Learning Project `JHU, 2020.4 - 2020.5` <br>
- Built a neural network using **Proximal Policy Optimisation**, which enables the Mario agent to finish world 1 level 1 by 20 seconds<br>
- Trained Mario to kill **as many monsters as possible**

### Database for Crime Data in Baltimore `JHU, 2019.11 - 2019.12` <br>
- Designed the **scheme** for the database according to the dataset from [Baltimore Police Open Data](https://data.baltimorecity.gov/Public-Safety/BPD-Part-1-Victim-Based-Crime-Data/wsfq-mvij)
- **Convert the csv file to sql file** and import the data into the database
- Designed some queries to extract some interesting information

### Orbit System Generic class Development `HIT, 2019.2 - 2019.6` <br>
- Built a Orbit System generic **class/interface**, along with 5 different applications using this generic **class/interface**
- Implemented various design patterns like **Abstract Factory Pattern**, **Prototype Pattern**, **Adaptor Pattern**, **Bridge Pattern**, etc.

## Honours & Awards

First Class or Second Class of RenMin Scholarship `HIT, 2015-2021` <br>
Best Group Award `University of Cambridge, 2017` <br>
The Satellite Scholarship `HIT, 2016` <br>

---

## Skills

Languages: C/C++, Java, Python, Matlab <br>
Framework: Pytorch, Fasttext, Fairseq, Gensim, Transformers, AllenNLP, Scipy, Cupy, Numpy, Pandas, Sklearn <br>
Database: MySQL <br>
Others: Latex, Markdown, Git, Vim, SSH, WordPress, Pycharm, Intellij, Xcode, Eclipse <br>

<!-- ### Footer

Last updated: 19 Oct 2020 -->
