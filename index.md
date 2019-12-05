# *Introduction to Information Retrieval*

Class Hours: Tuesday/Thursday 9:10-10:30am, WEB 1250

## Instructor

<a href="http://aiqingyao.org">Qingyao Ai</a>

Office Hours: Thursday 10:40am-11:40am, MEB 2172

## Prerequisites

* Linear Algebra, Basic Probability (typical Distributions, MLE)
* Programming Languages: Python and Java

## Text Books (optional):
* <a href="http://ciir.cs.umass.edu/irbook">*Search Engines: Information Retrieval in Practice*</a>. Bruce Croft, Donald Metzler, and Trevor Strohman, Pearson Education, 2009.
* <a href="https://nlp.stanford.edu/IR-book/information-retrieval-book.html">*Introduction to Information Retrieval*</a>. Christopher D. Manning, Prabhakar Raghavan, and Hinrich Schuetze, Cambridge University Press, 2007. 
* <a href="http://people.ischool.berkeley.edu/~hearst/irbook">*Modern Information Retrieval*</a>. Baeza-Yates Ricardo and Berthier Ribeiro-Neto. 2nd edition, Addison-Wesley, 2011.
* <a href="http://www.ir.uwaterloo.ca/book">*Information Retrieval: Implementing and Evaluating Search Engines*</a>. Stefan Buttcher, Charlie Clarke, Gordon Cormack, MIT Press, 2010.


## Resources

## Grading

The grade will count the assessments using the following proportions:
* __30%__ of your grade will be determined by the class project, including:
  * Project Proposal (5%)
  * Project Report (15%)
  * Final Presentation (10%)
* __20%__ of your grade will be determined by the mid-term exam. 
*	__15%__ of your grade will be determined by Assignment 1.
* __15%__ of your grade will be determined by Assignment 2.
*	__15%__ of your grade will be determined by Assignment 3.
*	__5%__ of your grade will be determined by your participation. Student who finish the class project, the mid-term exam, and all assignments will receive the full credits of participation. 

__\**Bonus*__:

__5%__ to __10%__ bonus points are available for students who sign up and finish a paper presentation in one of the lectures. Papers can be selected from *Readings* of the class schedule or proposed by the student. Each presentation include 15 minutes talk and 5 minutes QA. The bonus points are determined according to the quality of the presentation. 

P.S. Doing presentation with classmates together is acceptable, but the bonus points would be split and assigned equally to all the participants. 

## Tentative Class Schedule

Week, Date | Topic | Reminder | Slides | Readings
------------ | ------------- | ------------- | ------------- | -------------
Week 01, 01/06 - 01/10 | __&#9642; Course Overview__ <br /> Introduce information retrieval and the course organization. <br />__&#9642; The life of a query__ <br /> Modern search engine architecture overview and how information is retrieved for a given search query. ||| 
Week 02, 01/13 - 01/17 | __&#9642; Evaluation__ <br /> Introduce the concept of ranking and how to evaluate IR systems with ranking metrics.<br />__&#9642; Crawls and feeds__ <br /> How to collect and create information retrieval collections. ||| NDCG: <a href="https://www.cc.gatech.edu/~zha/CS8803WST/dcg.pdf">Järvelin and Kekäläinen (TOIS 2002)</a>
Week 03, 01/20 - 01/24 | __&#9642; Processing text__ <br /> The basic techniques for text processing such as stemming, stop words removal, etc.<br />__&#9642; Processing Web__ <br /> Link analysis and spam detection.
Week 04, 01/27 - 01/31 | __&#9642; Indexing__ <br /> Introduce basic indexing techniques (e.g., inverted index) for efficient information retrieval.<br />__&#9642; Compression__ <br /> Data compression and index compression algorithms.
Week 05, 02/03 - 02/07 | __&#9642; Queries__ <br /> Query process techniques including suggestions, reformulation, etc.<br />__&#9642; Retrieval Model (1)__ <br /> Vector space models.
Week 06, 02/10 - 02/14 | __&#9642; Retrieval Model (2)__ <br />Basic language modeling approaches and smoothing. <br /> __&#9642; Retrieval Model (3)__<br />Query likelihood model and KL-divergence. ||| Query Likelihood model <a href="https://dl.acm.org/citation.cfm?id=291008" target="\blank">Ponte and Croft (SIGIR 1998)</a> <br /> KL-divergence model <a href="https://dl.acm.org/citation.cfm?id=383970" target="\blank">Lafferty and Zhai (SIGIR 2001)</a> <br /> Language smoothing <a href="https://dl.acm.org/citation.cfm?id=383970" target="\blank">Lafferty and Zhai (SIGIR 2001)</a>
Week 07, 02/17 - 02/21 | __&#9642; Retrieval Model (4)__<br />Enhanced language modeling approaches. <br /> __&#9642; Relevance Feedback__<br />The concept and basic techniques of relevance feedback and pseudo relevance feedback. ||| Cluster-based LM <a href="https://dl.acm.org/citation.cfm?id=1009026" target="\blank">Liu and Croft (SIGIR 2004)</a> <br /> Dependence models <a href="https://dl.acm.org/citation.cfm?id=1076115" target="\blank">Metzler and Croft (SIGIR 2005)</a> <br /> <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.646.9974&rep=rep1&type=pdf" target="\blank">Huston and Croft (CIKM 2014)</a> <br /> Relevance Model <a href="https://dl.acm.org/citation.cfm?id=3130376" target="\blank">Lavrenko and Croft (SIGIR 2001)</a> <br />Model-based feedback model <a href="https://dl.acm.org/citation.cfm?id=502654" target="\blank">Zhai and Lafferty (CIKM 2001)</a>
Week 08, 02/24 - 02/28 | __&#9642; Search Result Diversification__<br />The motivation of result diversification and classic models. <br /> __&#9642; Mid-term Exam__
Week 09, 03/02 - 03/06 | __&#9642; Learning to Rank (1)__<br />The motivation and basic concepts of learning to rank, including query-document pairs, feature vectors, etc. <br /> __&#9642; Learning to Rank (2)__<br />The optimization paradigms for learning-to-rank models, e.g. pointwise, pairwise, and listwise methods.
Week 10, 03/09 - 03/13 | __Spring Break__ 
Week 11, 03/16 - 03/20 | __&#9642; Course Project Proposal Presentation__<br />Proposal presentation and mutual evaluation<br /> __Classification and Clustering__<br />The concepts and algorithms for text classification and clustering.
Week 12, 03/23 - 03/27 | __&#9642; Beyond bag-of-words (1)__ <br />Latent space models and distributed representations. <br /> __&#9642; Beyond bag-of-words (2)__ <br />Neural Information Retrieval. ||| LSI <a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/%28SICI%291097-4571%28199009%2941%3A6%3C391%3A%3AAID-ASI1%3E3.0.CO%3B2-9" target="\blank">Deerwester et al. (JASIS 1990)</a>
Week 13, 03/30 - 04/03 | __&#9642; Recommendation systems (1)__<br />The basic concepts and naive algorithms for recommender systems. <br /> __&#9642; Recommendation systems (2)__<br /> Collaborative filtering.
Week 14, 04/06 - 04/10 | __&#9642; Adv. User Study and Crowdsourcing__<br />The study and applications of user modeling and crowdsourcing in information retrieval. <br /> __&#9642; Adv. Click Models and Unbiased Learning__<br />The idea of biased user behavior and the algorithms for unbiased optimization.
Week 15, 04/13 - 04/17 | __&#9642; Adv. Personalization__<br />How to personalize retrieval results according to individual information needs. <br /> __&#9642; Adv. Question Answering__<br />Introduction on classic and state-of-the-art methods for question answering in open domains.
Week 16, 04/20 - 04/24 | __&#9642; Course Project Final Presentation__<br />The presentation and evaluation of course projects.
Week 17, 04/27 - 05/01 | __&#9642; Course Project Report Due__

## Acknowledgements
Special thanks to Dr. Hamed Zamani from Microsoft Research, Prof. Jiepu Jiang from Virginia Tech University, and Prof. James Allan from University of Massachusetts Amherst.
Some teaching materials are borrowed from their course sites for CS656: Information Retrieval.
