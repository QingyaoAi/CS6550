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
* __35%__ of your grade will be determined by the class project, including:
  * Project Proposal (10%)
  * Project Report (10%)
  * Final Presentation (15%)
* __15%__ of your grade will be determined by the paper presentation. 
*	__15%__ of your grade will be determined by Assignment 1.
* __15%__ of your grade will be determined by Assignment 2.
*	__15%__ of your grade will be determined by Assignment 3.
*	__5%__ of your grade will be determined by your participation. Students who finish the class project, the paper presentation, and all assignments will receive the full credits of participation. 

## Tentative Class Schedule

Week, Date | Topic | Reminder | Slides | Readings
------------ | ------------- | ------------- | ------------- | -------------
Week 01, 01/06 - 01/10 | __&#9642; Course Overview__ <br /> Introduce information retrieval and the course organization. <br />__&#9642; The life of a query__ <br /> Modern search engine architecture overview and how information is retrieved for a given search query. ||| 
Week 02, 01/13 - 01/17 | __&#9642; Evaluation__ <br /> Introduce the concept of ranking and how to evaluate IR systems with ranking metrics.<br />__&#9642; Crawls and feeds__ <br /> How to collect and create information retrieval collections. ||| NDCG: <a href="https://www.cc.gatech.edu/~zha/CS8803WST/dcg.pdf">Järvelin and Kekäläinen (TOIS 2002)</a> <br /> ERR <a href="http://www.olivier.chapelle.cc/pub/err.pdf" target="\blank">Chapelle et al. (CIKM 2009)</a> <br /> BigTable <a href="https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf" target="\blank">Chang et al. (OSDI 2006)</a>
Week 03, 01/20 - 01/24 | __&#9642; Processing text__ <br /> The basic techniques for text processing such as stemming, stop words removal, etc.<br />__&#9642; Processing Web__ <br /> Link analysis and spam detection. ||| Zipf’s Law and Heap’s Law <a href="https://www.researchgate.net/profile/Hideki_Takayasu/publication/258693213_Zipf%27s_Law_and_Heaps%27_Law_Can_Predict_the_Size_of_Potential_Words/links/5a54ba810f7e9b205de4428f/Zipfs-Law-and-Heaps-Law-Can-Predict-the-Size-of-Potential-Words.pdf" target="\blank">Sano et al. (2012)</a> <br /> Topic-sensitive PageRank <a href="http://ilpubs.stanford.edu:8090/573/1/2002-6.pdf" target="\blank">Haveliwala (WWW 2002)</a>  
Week 04, 01/27 - 01/31 | __&#9642; Indexing__ <br /> Introduce basic indexing techniques (e.g., inverted index) for efficient information retrieval.<br />__&#9642; Compression__ <br /> Data compression and index compression algorithms. ||| BitFunnel <a href="https://dl.acm.org/doi/10.1145/3077136.3080789" target="\blank">Goodwin et al. (SIGIR 2017)</a> 
Week 05, 02/03 - 02/07 | __&#9642; Queries and Interfaces__ <br /> Interface design and query process techniques including suggestions, reformulation, etc.<br />__&#9642; Retrieval Model (1)__ <br /> Vector space models. | __Assignment 1 Due (02/09)__ || Local vs. Global Analysis <a href="https://my.eng.utah.edu/~cs7961/papers/XuCroft-SIGIR96.pdf" target="\blank">Xu and Croft (SIGIR 1996)</a>
Week 06, 02/10 - 02/14 | __&#9642; Retrieval Model (2)__ <br />Classic probabilistic models. <br /> __&#9642; Retrieval Model (3)__<br /> Language modeling approaches and smoothing. ||| 2-Possion Model <a href="https://www.researchgate.net/profile/Stephen_Robertson2/publication/221299140_Some_Simple_Effective_Approximations_to_the_2-Poisson_Model_for_Probabilistic_Weighted_Retrieval/links/0c960534ff2c4a2c5f000000.pdf" target="\blank">Robertson (SIGIR 1994)</a> <br /> Query Likelihood model <a href="https://dl.acm.org/citation.cfm?id=291008" target="\blank">Ponte and Croft (SIGIR 1998)</a> <br /> KL-divergence model <a href="https://dl.acm.org/citation.cfm?id=383970" target="\blank">Lafferty and Zhai (SIGIR 2001)</a> <br /> Language smoothing <a href="https://dl.acm.org/citation.cfm?id=383970" target="\blank">Lafferty and Zhai (SIGIR 2001)</a> 
Week 07, 02/17 - 02/21 | __&#9642; Retrieval Model (4)__<br />Enhanced language modeling approaches. <br /> __&#9642; Relevance Feedback__<br />The concept and basic techniques of relevance feedback and pseudo relevance feedback. ||| Dependence models <a href="https://dl.acm.org/citation.cfm?id=1076115" target="\blank">Metzler and Croft (SIGIR 2005)</a> <br /> <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.646.9974&rep=rep1&type=pdf" target="\blank">Huston and Croft (CIKM 2014)</a> <br /> Relevance Model <a href="https://dl.acm.org/citation.cfm?id=3130376" target="\blank">Lavrenko and Croft (SIGIR 2001)</a> <br />Model-based feedback model <a href="https://dl.acm.org/citation.cfm?id=502654" target="\blank">Zhai and Lafferty (CIKM 2001)</a>
Week 08, 02/24 - 02/28 | __&#9642; Search Result Diversification__<br />The motivation of result diversification and classic models. <br /> __&#9642; Learning to Rank (1)__<br />The motivation and basic concepts of learning to rank, including query-document pairs, feature vectors, etc. ||| Maximal Marginal Relevance <a href="http://www.cs.cmu.edu/afs/.cs.cmu.edu/Web/People/jgc/publication/MMR_DiversityBased_Reranking_SIGIR_1998.pdf" target="\blank">Carbonell and Goldstein (SIGIR 1998)</a> <br /> Diversity evaluation <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.149.9999&rep=rep1&type=pdf" target="\blank">larke et al. (SIGIR 2008)</a> <br /> LTR textbook <a href="https://www.morganclaypool.com/doi/pdf/10.2200/S00607ED2V01Y201410HLT026" target="\blank">Li.</a>
Week 09, 03/02 - 03/06 | __&#9642; Learning to Rank (2)__<br />The optimization paradigms for learning-to-rank models, e.g. pointwise, pairwise, and listwise methods. <br /> __&#9642; Clustering and Search__<br />The concepts and algorithms for text clustering and their applications in search.  | __Assignment 2 Due (03/08)__ ||  Cluster-based LM <a href="https://dl.acm.org/citation.cfm?id=1009026" target="\blank">Liu and Croft (SIGIR 2004)</a> <br /> RankNet <a href="https://www.researchgate.net/profile/Christopher_Burges/publication/221345726_Learning_to_Rank_using_Gradient_Descent/links/00b49518c11a6cbcb8000000.pdf" target="\blank">Burges et al. (ICML 2008)</a> <br /> ListMLE <a href="http://icml2008.cs.helsinki.fi/papers/167.pdf" target="\blank">Xia et al. (ICML 2008)</a> <br /> ListMLE <a href="http://icml2008.cs.helsinki.fi/papers/167.pdf" target="\blank">Xia et al. (ICML 2008)</a> <br /> LambdaMART <a href="https://pdfs.semanticscholar.org/0df9/c70875783a73ce1e933079f328e8cf5e9ea2.pdf" target="\blank">Burges. </a> <br /> DLCM <a href="https://arxiv.org/pdf/1804.05936.pdf" target="\blank">Ai et al. (SIGIR 2018) </a>
Week 10, 03/09 - 03/13 | __Spring Break__ | __Project Proposal Due (03/15)__
Week 11, 03/16 - 03/20 | __&#9642; Class Project Proposal Presentation__<br />Proposal presentation and mutual evaluation<br /> __&#9642; Beyond bag-of-words (1)__ <br />Latent space models and distributed representations. ||| LSI <a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/%28SICI%291097-4571%28199009%2941%3A6%3C391%3A%3AAID-ASI1%3E3.0.CO%3B2-9" target="\blank">Deerwester et al. (JASIS 1990)</a> <br /> LDA-LM <a href="http://www-labs.iro.umontreal.ca/~nie/IFT6255/wei.pdf" target="\blank">Wei and Croft (SIGIR 2006)</a>
Week 12, 03/23 - 03/27 |  __&#9642; Beyond bag-of-words (2)__ <br /> Neural Information Retrieval. <br /> __&#9642; Recommendation systems (1)__<br />The basic concepts and naive collaborative filetering algorithms. <br />||| DSSM <a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/cikm2013_DSSM_fullversion.pdf" target="\blank">Huang et al. (CIKM 2013)</a> <br /> DRMM <a href="https://arxiv.org/pdf/1711.08611.pdf" target="\blank">Guo et al. (CIKM 2016)</a> <br /> K-NRM <a href="https://arxiv.org/abs/1706.06613" target="\blank">Xiong et al. (SIGIR 2017)</a>
Week 13, 03/30 - 04/03 |  __&#9642; Recommendation systems (2)__<br /> Advanced matrix factorization and representation learning techniques. <br /> __&#9642; Adv. User Study and Crowdsourcing__<br />The study and applications of user modeling and crowdsourcing in information retrieval. | __Assignment 3 Due (04/05)__||  NCF <a href="https://arxiv.org/pdf/1708.05031.pdf" target="\blank">He et al. (WWW 2017)</a> <br /> JRL <a href="http://www.shichuan.org/hin/topic/Embedding/2017.%20CIKM%20Joint%20Representation%20Learning%20for%20Top%20N%20Recommendation%20with%20Heterogeneous%20Information%20Sources.pdf" target="\blank">Zhang et al. (CIKM 2017)</a>
Week 14, 04/06 - 04/10 | __&#9642; Adv. Click Models and Unbiased Learning__<br />The idea of biased user behavior and the algorithms for unbiased optimization. <br /> __&#9642; Adv. Personalization__<br />How to personalize retrieval results according to individual information needs.
Week 15, 04/13 - 04/17 |  __&#9642; Adv. Question Answering__<br />Introduction on classic and state-of-the-art methods for question answering in open domains. <br /> __&#9642; Class Project Final Presentation (1)__<br />The presentation and evaluation of course projects.
Week 16, 04/20 - 04/24 | __&#9642; Class Project Final Presentation (2)__<br />The presentation and evaluation of course projects.
Week 17, 04/27 - 05/01 | __&#9642; Class Ended__ | __Project Final Report Due (04/29)__

## Acknowledgements
Special thanks to Dr. Hamed Zamani from Microsoft Research, Prof. Jiepu Jiang from Virginia Tech University, Prof. Yongfeng Zhang from Rutgers University, and Prof. James Allan from University of Massachusetts Amherst.
Some teaching materials are borrowed from their courses on CS656: Information Retrieval and CS691: Recommender System.
