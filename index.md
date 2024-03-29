# *Introduction to Information Retrieval*

Class Hours: Monday/Wednesday  3:00pm-4:20pm, AEB 320

Note that CS4960 and CS6550 have been cross-listed on Canvas as __CS 6550-001__.

__*University leadership has urged all faculty, students, and staff to model the vaccination, testing, and masking behaviors we want to see in our campus community.*__
These include:
* __Vaccination__
* __Masking indoors__
* __If unvaccinated, getting weekly asymptomatic coronavirus testing__

More information can be found below.

## Instructor

<a href="http://aiqingyao.org">Qingyao Ai</a>

Office Hours: Wednesday 10:30am-11:30am, MEB 2172 (hallway)

<!--## Student Feedback

<img src="https://github.com/QingyaoAi/CS6550/blob/master/SmartEvals.png" width="40%">-->

## TA

Tao Yang

Office Hours: Thursday 2:00pm-3:00pm, MEB 3159

## Prerequisites

* Linear Algebra, Basic Probability (typical Distributions, MLE)
* Programming Languages: Python and Java
* “C-” or better in CS3500

## Text Books (optional):
* <a href="http://ciir.cs.umass.edu/irbook">*Search Engines: Information Retrieval in Practice*</a>. Bruce Croft, Donald Metzler, and Trevor Strohman, Pearson Education, 2009.
* <a href="https://nlp.stanford.edu/IR-book/information-retrieval-book.html">*Introduction to Information Retrieval*</a>. Christopher D. Manning, Prabhakar Raghavan, and Hinrich Schuetze, Cambridge University Press, 2007. 
* <a href="http://people.ischool.berkeley.edu/~hearst/irbook">*Modern Information Retrieval*</a>. Baeza-Yates Ricardo and Berthier Ribeiro-Neto. 2nd edition, Addison-Wesley, 2011.
* <a href="http://www.ir.uwaterloo.ca/book">*Information Retrieval: Implementing and Evaluating Search Engines*</a>. Stefan Buttcher, Charlie Clarke, Gordon Cormack, MIT Press, 2010.


## Resources

## Grading

The grade will count the assessments using the following proportions (tentative and subject to change):
* __35%__ of your grade will be determined by the class project, including:
  * Project Proposal (10%)
  * Project Report (10%)
  * Final Presentation (15%)
* __15%__ of your grade will be determined by the paper presentation. 
*	__10%__ of your grade will be determined by Assignment 1.
*	__5%__ of your grade will be determined by Lab 1.
* __10%__ of your grade will be determined by Assignment 2.
* __5%__ of your grade will be determined by Lab 2.
*	__10%__ of your grade will be determined by Assignment 3.
*	__5%__ of your grade will be determined by Lab 3.
*	__5%__ of your grade will be determined by your participation. Students who finish the class project peer reviews, the paper presentation, and all assignments/labs will receive the full credits of participation. 

## Tentative Class Schedule

Week, Date | Topic | Reminder | Slides | Readings
------------ | ------------- | ------------- | ------------- | -------------
Week 01, 08/23 - 08/27 | __&#9642; Course Overview__ <br /> Introduce information retrieval and the course organization. <br />__&#9642; The life of a query__ <br /> Modern search engine architecture overview and how information is retrieved for a given search query. ||| 
Week 02, 08/30 - 09/03 | __&#9642; Evaluation__ <br /> Introduce the concept of ranking and how to evaluate IR systems with ranking metrics.<br />__&#9642; Crawls and feeds__ <br /> How to collect and create information retrieval collections. ||| NDCG: <a href="https://www.cc.gatech.edu/~zha/CS8803WST/dcg.pdf">Järvelin and Kekäläinen (TOIS 2002)</a> <br /> ERR <a href="http://www.olivier.chapelle.cc/pub/err.pdf" target="\blank">Chapelle et al. (CIKM 2009)</a> <br /> BigTable <a href="https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf" target="\blank">Chang et al. (OSDI 2006)</a>
Week 03, 09/06 - 09/10 | __&#9642; Labor Day__<br />__&#9642; Processing text__ <br /> The basic techniques for text processing such as stemming, stop words removal, etc.<br /> ||| Zipf’s Law and Heap’s Law <a href="https://www.researchgate.net/profile/Hideki_Takayasu/publication/258693213_Zipf%27s_Law_and_Heaps%27_Law_Can_Predict_the_Size_of_Potential_Words/links/5a54ba810f7e9b205de4428f/Zipfs-Law-and-Heaps-Law-Can-Predict-the-Size-of-Potential-Words.pdf" target="\blank">Sano et al. (2012)</a>   
Week 04, 09/13 - 09/17 | __&#9642; Processing Web__ <br /> Link analysis and spam detection.<br />__&#9642; Indexing__ <br /> Introduce basic indexing techniques (e.g., inverted index) for efficient information retrieval. ||| Topic-sensitive PageRank <a href="http://ilpubs.stanford.edu:8090/573/1/2002-6.pdf" target="\blank">Haveliwala (WWW 2002)</a><br /> BitFunnel <a href="https://dl.acm.org/doi/10.1145/3077136.3080789" target="\blank">Goodwin et al. (SIGIR 2017)</a> 
Week 05, 09/20 - 09/24 | __&#9642; Compression__ <br /> Data compression and index compression algorithms.<br />__&#9642; Queries and Interfaces__ <br /> Interface design and query process techniques including suggestions, reformulation, etc. | __Assignment 1 Due (09/26)__ || Local vs. Global Analysis <a href="https://my.eng.utah.edu/~cs7961/papers/XuCroft-SIGIR96.pdf" target="\blank">Xu and Croft (SIGIR 1996)</a>
Week 06, 09/27 - 10/01 | __&#9642; Retrieval Model (1)__ <br /> Vector space models.<br />__&#9642; Retrieval Model (2)__ <br />Classic probabilistic models. |__Lab 1 Due (10/03)__|| 2-Possion Model <a href="https://www.researchgate.net/profile/Stephen_Robertson2/publication/221299140_Some_Simple_Effective_Approximations_to_the_2-Poisson_Model_for_Probabilistic_Weighted_Retrieval/links/0c960534ff2c4a2c5f000000.pdf" target="\blank">Robertson (SIGIR 1994)</a> 
Week 07, 10/04 - 10/08 |  __&#9642; Retrieval Model (3)__<br /> Language modeling approaches and smoothing.<br />__&#9642; Retrieval Model (4)__<br />Enhanced language modeling approaches. |||  Query Likelihood model <a href="https://dl.acm.org/citation.cfm?id=291008" target="\blank">Ponte and Croft (SIGIR 1998)</a> <br /> KL-divergence model <a href="https://dl.acm.org/citation.cfm?id=383970" target="\blank">Lafferty and Zhai (SIGIR 2001)</a> <br /> Language smoothing <a href="https://dl.acm.org/citation.cfm?id=383970" target="\blank">Lafferty and Zhai (SIGIR 2001)</a> <br /> Dependence models <a href="https://dl.acm.org/citation.cfm?id=1076115" target="\blank">Metzler and Croft (SIGIR 2005)</a> <br /> <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.646.9974&rep=rep1&type=pdf" target="\blank">Huston and Croft (CIKM 2014)</a>
Week 08, 10/11 - 10/15 |  __&#9642;Fall Break__  ||| 
Week 09, 10/18 - 10/22 |  __&#9642; Relevance Feedback__<br />The concept and basic techniques of relevance feedback and pseudo relevance feedback. <br />__&#9642; Search Result Diversification__<br />The motivation of result diversification and classic models.  ||| Relevance Model <a href="https://dl.acm.org/citation.cfm?id=3130376" target="\blank">Lavrenko and Croft (SIGIR 2001)</a> <br />Model-based feedback model <a href="https://dl.acm.org/citation.cfm?id=502654" target="\blank">Zhai and Lafferty (CIKM 2001)</a><br />Maximal Marginal Relevance <a href="http://www.cs.cmu.edu/afs/.cs.cmu.edu/Web/People/jgc/publication/MMR_DiversityBased_Reranking_SIGIR_1998.pdf" target="\blank">Carbonell and Goldstein (SIGIR 1998)</a> <br /> Diversity evaluation <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.149.9999&rep=rep1&type=pdf" target="\blank">larke et al. (SIGIR 2008)</a> 
Week 10, 10/25 - 10/29 |  __&#9642; Learning to Rank (1)__<br />The motivation and basic concepts of learning to rank, including query-document pairs, feature vectors, etc.<br />__&#9642; Learning to Rank (2)__<br />The optimization paradigms for learning-to-rank models, e.g. pointwise, pairwise, and listwise methods.   | __Assignment 2 Due (10/31)__ || LTR textbook <a href="https://www.morganclaypool.com/doi/pdf/10.2200/S00607ED2V01Y201410HLT026" target="\blank">Li.</a>  <br /> RankNet <a href="https://www.researchgate.net/profile/Christopher_Burges/publication/221345726_Learning_to_Rank_using_Gradient_Descent/links/00b49518c11a6cbcb8000000.pdf" target="\blank">Burges et al. (ICML 2008)</a> <br /> ListMLE <a href="http://icml2008.cs.helsinki.fi/papers/167.pdf" target="\blank">Xia et al. (ICML 2008)</a> <br /> ListMLE <a href="http://icml2008.cs.helsinki.fi/papers/167.pdf" target="\blank">Xia et al. (ICML 2008)</a> <br /> LambdaMART <a href="https://pdfs.semanticscholar.org/0df9/c70875783a73ce1e933079f328e8cf5e9ea2.pdf" target="\blank">Burges. </a> <br /> DLCM <a href="https://arxiv.org/pdf/1804.05936.pdf" target="\blank">Ai et al. (SIGIR 2018) </a>
Week 11, 11/01 - 11/05 | __&#9642; Class Project Proposal Presentation__<br />Proposal presentation and mutual evaluation<br /> __&#9642; Clustering and Search__<br />The concepts and algorithms for text clustering and their applications in search. | __Project Proposal Due (11/03)__<br /> __Lab 2 Due (11/07)__ || Cluster-based LM <a href="https://dl.acm.org/citation.cfm?id=1009026" target="\blank">Liu and Croft (SIGIR 2004)</a>
Week 12, 11/08 - 11/12 |  __&#9642; Beyond bag-of-words (1)__ <br />Latent space models and distributed representations.<br />__&#9642; Beyond bag-of-words (2)__ <br /> Neural Information Retrieval. ||| LSI <a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/%28SICI%291097-4571%28199009%2941%3A6%3C391%3A%3AAID-ASI1%3E3.0.CO%3B2-9" target="\blank">Deerwester et al. (JASIS 1990)</a> <br /> LDA-LM <a href="http://www-labs.iro.umontreal.ca/~nie/IFT6255/wei.pdf" target="\blank">Wei and Croft (SIGIR 2006)</a><br />Neural Ranking Models <a href="https://arxiv.org/abs/1903.06902" target="\blank">Guo et al. (IPM 2019)</a> <br /> DSSM <a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/cikm2013_DSSM_fullversion.pdf" target="\blank">Huang et al. (CIKM 2013)</a> <br /> DRMM <a href="https://arxiv.org/pdf/1711.08611.pdf" target="\blank">Guo et al. (CIKM 2016)</a> <br /> K-NRM <a href="https://arxiv.org/abs/1706.06613" target="\blank">Xiong et al. (SIGIR 2017)</a>
Week 13, 11/15 - 11/19 |  __&#9642; Recommendation systems (1)__<br />The basic concepts and naive collaborative filetering algorithms. <br />__&#9642; Recommendation systems (2)__<br /> Matrix factorization and latent representation learning techniques.  | ||  NCF <a href="https://arxiv.org/pdf/1708.05031.pdf" target="\blank">He et al. (WWW 2017)</a> <br /> JRL <a href="http://www.shichuan.org/hin/topic/Embedding/2017.%20CIKM%20Joint%20Representation%20Learning%20for%20Top%20N%20Recommendation%20with%20Heterogeneous%20Information%20Sources.pdf" target="\blank">Zhang et al. (CIKM 2017)</a> 
Week 14, 11/22 - 11/26 |  __&#9642; Adv. User Study and Crowdsourcing__<br />The study and applications of user modeling and crowdsourcing in information retrieval.<br />__&#9642; Adv. Click Models and Unbiased Learning__<br />The idea of biased user behavior and the algorithms for unbiased optimization. |__Assignment 3 Due (11/28)__||  User experience <a href="https://dl.acm.org/doi/10.1145/2854946.2854976" target="\blank">Crescenzi et al. (CHIIR 2016)</a> <br /> Crowdsourcing <a href="https://dl.acm.org/doi/abs/10.1145/1357054.1357127" target="\blank">Kittur et al. (CHI 2008)</a><br />Cascade Model <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.112.1288&rep=rep1&type=pdf" target="\blank">Craswell et al. (WSDM 2008)</a> <br /> DBN <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.215.7270&rep=rep1&type=pdf" target="\blank">Chapelle and Zhang (WWW 2009)</a> <br /> UBM <a href="https://www.researchgate.net/profile/Georges_Dupret/publication/200110492_A_user_browsing_model_to_predict_search_engine_click_data_from_past_observations/links/54e4c5ea0cf29865c3351048.pdf" target="\blank">Dupret and Piwowarski (SIGIR 2008)</a> <br /> IPW <a href="https://www.cs.cornell.edu/people/tj/publications/joachims_etal_17a.pdf" target="\blank">Joachims et al. (WSDM 2017)</a> <br /> Regression EM <a href="https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/3bace79f9bcead0b20dec31e2a0878346ad2fb0d.pdf" target="\blank">Wang et al. (WSDM 2018)</a> <br /> DLA <a href="https://arxiv.org/abs/1804.05938" target="\blank"> Ai et al. (SIGIR 2018)</a> 
Week 15, 11/29 - 12/03 |   __&#9642; Adv. Personal Search and Product Search__<br />Introducing IR techniques for domain-specific applications such as email search and e-commerce search.<br />__&#9642; Adv. Question Answering__<br />Introduction on classic and state-of-the-art methods for question answering in open domains. |__Lab 3 Due (12/05)__||   Stuff I’ve seen <a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/gavinj-siscore-sigir2003-final.pdf" target="\blank">Dumais et al. (SIGIR 2003)</a> <br /> Email Re-finding <a href="https://pdfs.semanticscholar.org/6e95/3a5caa643ef2e310473b680ef23262bb80ce.pdf" target="\blank"> Ai et al. (WWW 2017)</a> <br /> HEM <a href="https://ciir-publications.cs.umass.edu/pub/web/getpdf.php?id=1260" target="\blank"> Ai et al. (SIGIR 2017)</a>  <br /> E-commerce Search Taxonomy <a href="https://www.researchgate.net/profile/Parikshit_Sondhi/publication/326133502_A_Taxonomy_of_Queries_for_E-commerce_Search/links/5b78b746a6fdcc5f8b53928f/A-Taxonomy-of-Queries-for-E-commerce-Search.pdf" target="\blank">Sondhi et al. (SIGIR 2018)</a> <br />QA Performance <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.441.6742&rep=rep1&type=pdf" target="\blank"> Moldovan et al. (TOIS 2003)</a> <br /> Non-factoid QA with LTR <a href="https://ciir-publications.cs.umass.edu/pub/web/getpdf.php?id=1195" target="\blank">Liu et al. (ECIR 2016)</a> <br /> Risk of QA <a href="http://www.bigdatalab.ac.cn/~gjf/papers/2019/SIGIR-conf.pdf" target="\blank"> Su et al. (SIGIR 2019)</a> 
Week 16, 12/06 - 12/10 | __&#9642; Class Project Final Presentation (1)__<br />The presentation and evaluation of course projects (first half).<br /> __&#9642; Class Project Final Presentation (2)__<br />The presentation and evaluation of course projects (second half). | __Project and Paper Presentation Slides Due (12/10)__
Week 17, 12/13 - 12/17 | __&#9642; Class Ended__ | __Project Final Report Due (12/18)__

## Acknowledgements
Special thanks to Prof. Jiepu Jiang from University of Wisconsin-Madison, Prof. Yongfeng Zhang from Rutgers University, Prof. James Allan and Prof. Hamed Zamani from University of Massachusetts Amherst.
Some teaching materials are borrowed from their courses on CS656: Information Retrieval and CS691: Recommender System.


## Vaccination

* Get a COVID-19 vaccination if you have not already done so. Vaccination is proving highly effective in preventing severe COVID-19 symptoms, hospitalization and death from coronavirus. Vaccination is the single best way to stop this COVID resurgence in its tracks.
Many in the campus community already have gotten vaccinated: (1) More than 80% of U. employees (2) Over 70% of U. students 
* Visit http://mychart.med.utah.edu/, http://alert.utah.edu/covid/vaccine , or http://vaccines.gov/ to schedule your vaccination.

## Masking

* While masks are no longer required outside of Health Sciences facilities, UTA buses and campus shuttles, CDC guidelines now call for everyone to wear face masks indoors.
* Check the CDC website periodically for masking updateshttps://www.cdc.gov/coronavirus/2019-ncov/vaccines/fully-vaccinated-guidance.html Treat masks like seasonal clothing (i.e. during community surges in COVID transmission, masks are strongly encouraged indoors and in close groups outside).

## Testing

* If you are not yet vaccinated, get weekly asymptomatic coronavirus tests. This is a helpful way to protect yourself and those around you because asymptomatic individuals can unknowingly spread the coronavirus to others.
* Asymptomatic testing centers are open and convenient: Online scheduling Saliva test (no nasal swabs) Free to all students returning to campus (required for students in University housing) Results often within 24 hours Visit alert.utah.edu/covid/testing
* Remember: Students must self-report if they test positive for COVID-19 via this website: https://coronavirus.utah.edu/.

## Student Mental Health Resources

* Rates of burnout, anxiety, depression, isolation, and loneliness have noticeably increased during the pandemic. If you need help, reach out for campus mental health resources, including counseling, trainings and other support.
* Consider participating in a Mental Health First Aid or other wellness-themed training provided by our Center for Student Wellness and sharing these opportunities with your peers, teaching assistants and department colleagues.



