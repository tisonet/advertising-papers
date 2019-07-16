# Advertising papers

## Bidding,  budget, delivery
[2018 - Bidding Machine: Learning to Bid for Directly Optimizing Profits in Display Advertising](https://arxiv.org/pdf/1803.02194.pdf)

[2018 - Audience Size Forecasting](http://delivery.acm.org/10.1145/3220000/3219893/p744-shi.pdf?ip=194.228.13.109&id=3219893&acc=OPENTOC&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E054E54E275136550&__acm__=1562700116_324a5d17e38a06a6d1fe2d885ff5a19b)

[2018 - Optimal Bidding, Allocation and Budget Spending for a Demand Side Platform Under Many Auction Types](https://arxiv.org/pdf/1805.11645.pdf)

[2017 - Attribution Modeling Increases Efficiency of Bidding in Display Advertising](https://arxiv.org/pdf/1707.06409.pdf)

[2017 - Profit Maximization for Online Advertising Demand-Side Platforms](https://arxiv.org/pdf/1706.01614.pdf)

[2015 - Smart Pacing for Effective Online Ad Campaign Optimization](https://arxiv.org/pdf/1506.05851.pdf)
<details>
  <summary>Czech notes</summary>
  Ad requesty jsou rozdeleny do vice skupin, dle predikovaneho vykonu (CTR, CR). Kazda skupina ma vypocten pacing rate. Algoritmus se snazi bidovat na skupiny s nejvyse predikovanou hodnotou pokud stiha odtacet budget. Adaptivne upravuje pacing rate dle toho jak odtaci. Kdyz nestiha odtacet, zvysuje pacing rate i pro skupiny s mensim vykonem, napr. s nizsim CTR prediction. 
  </details>

[2013 - Real Time Bid Optimization with Smooth Budget Delivery in Online Advertising](https://arxiv.org/abs/1305.3011)
<details>
  <summary>Czech notes</summary>
  Maximalizace dosazeni daneho cile (CTR, CR, eCPC, eCPA) pri dodrzeni rozlozeni budgetu v ramci celeho behu kampane. Budget lze rozkladat na casove sloty dle cile, napr. utracet nejvice v hodinach kdy se nejvice nakupuje na shopu, ci klika. Metoda stavi na metrice pancing rate, tedy urceni idealniho poctu bidu ze vsech adrequestu, odpovidajicich cileni, abychom odtaceli spravne budget.  Dale hledame hladinu predikovane CTR, CR kdy ma smysl jeste bidovat a s jakou cenou.
  </details>

[2012 - Bid Optimizing and Inventory Scoring in Targeted Online Advertising](http://www0.cs.ucl.ac.uk/staff/w.zhang/rtb-papers/lin-bid.pdf)
<details>
  <summary>Czech notes</summary>
  
  Modifikace zakladni ceny bidu dle predikce pravdepodobnosti konverze dle inventory. Ma cenu bidovat s dvakrat vetsi cenou pro uzivatel, kteri maji dvakrat vetsi pravdepodobnost konverze. Inventory, kontext zobrazeni stranky ma vliv na konverzi. Typ cteni (clanek o SQL nebo bulvar), viditelnost reklam, atd. meni pravdepodobnost konverze. Zkouseli vice bidovacich strategii, 1 - pomerne menit bid price dle predikovane CVR, 2 - agresivni pristup,  zarezavat uzivatele s malou pravdepodobnosti konverze (<0.8), bidovat dvakrat vice pro dobe uzivatele CVR>1.2 a 3 - baseline, bidovat konstani cenu. Druha stategie mela nejvetsi CVR, ale take vetsi CPA (mensi marze pro DSP). Vhodne pro nove klienty, kteri porovnavaji vykon s jinymi systemy.       
  </details>

[2011 - Real-Time Bidding Algorithms for Performance-Based Display Ad Allocation](http://www0.cs.ucl.ac.uk/staff/w.zhang/rtb-papers/rtb-perf-bid.pdf)






## Frequency cap
[2015 - Research on the Frequency Capping Issue in RTB Advertising: A Computational Experiment Approach](https://www.researchgate.net/publication/333310382_Research_on_the_Frequency_Capping_Issue_in_RTB_Advertising_A_Computational_Experiment_Approach)

[2014 - Frequency Capping in Online Advertising](https://theory.epfl.ch/moranfe/Publications/Journals/Journal%20of%20Scheduling%202014.pdf)

## Performance metrics
[2015 - Evaluating and Optimizing Online Advertising Forget the click, but there are good proxies](https://core.ac.uk/download/pdf/43024035.pdf)

## User profile
[2016 - Improving Advertisement Recommendation by Enriching User Browser Cookie Attributes](https://dl.acm.org/citation.cfm?id=2983374&dl=ACM&coll=DL)

[2011 - Scalable Distributed Inference of Dynamic User Interests for Behavioral Targeting](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.296.3731&rep=rep1&type=pdf)

[2009 - Audience Selection for On-line Brand Advertising: Privacy-friendly Social Network Targeting](https://www.erim.eur.nl/fileadmin/centre_content/future_energy_business/images/informs_award/2009/Social_Network_Audience_selection.pdf)

[2007 - Demographic Prediction Based on User’s Browsing Behavior](https://www2007.org/papers/paper686.pdf)

## Look A Like
[2018 - Adaptive look-alike targeting in social networks advertising](https://www.sciencedirect.com/science/article/pii/S1877050918315692)

[2016 - Audience Expansion for Online Social Network Advertising](https://www.kdd.org/kdd2016/papers/files/adf0483-liuA.pdf)

[2016 - A Sub-linear, Massive-scale Look-alike Audience Extension System](http://proceedings.mlr.press/v53/ma16.pdf)

[2016 - Score Look-Alike Audiences](https://ieeexplore.ieee.org/abstract/document/7836728)

[2015 - Effective Audience Extension in Online Advertising](https://dl.acm.org/citation.cfm?id=2788603)

[Social Networks: Finding Highly Similar Users and Their Inherent Patterns](https://pdfs.semanticscholar.org/d1c9/8fa2a273d24e0ea055d7d93ab9e36a59302e.pdf)

## Context
[2008 - Contextual Advertising by Combining Relevance with Click Feedback](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.129.6137&rep=rep1&type=pdf)

## Scaling
[2015 - From 0.5 Million to 2.5 Million: Efficiently Scaling up Real-Time Bidding](http://www0.cs.ucl.ac.uk/staff/w.zhang/rtb-papers/turn-throatling.pdf)

## Retargeting
[2013 - When Does Retargeting Work? Information Specificity in Online Advertising](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.572.1526&rep=rep1&type=pdf)

## Conversion/Click rate prediction

[2018 - Reacting to Variations in Product Demand: An Application for Conversion Rate (CR) Prediction in Sponsored Search](https://arxiv.org/pdf/1806.08211.pdf)

[2017 - Optimized Cost per Click in Taobao Display Advertising](https://arxiv.org/pdf/1703.02091.pdf)

[2017 - Cost-sensitive Learning for Utility Optimization in Online Advertising Auctions](https://arxiv.org/pdf/1603.03713.pdf)

[2017 - Modeling Delayed Feedback in Display Advertising](https://arxiv.org/pdf/1603.03713.pdf)

[2017 - Advertisement Click-Through Rate Prediction Based on the Weighted-ELM and Adaboost Algorithm](https://www.researchgate.net/publication/320986634_Advertisement_Click-Through_Rate_Prediction_Based_on_the_Weighted-ELM_and_Adaboost_Algorithm)

[2014 - Practical Lessons from Predicting Clicks on Ads at Facebook](https://quinonero.net/Publications/predicting-clicks-facebook.pdf)

[2013 - Ad Click Prediction: a View from the Trenches (Google)](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/41159.pdf)

[2012 - Multimedia Features for Click Prediction of New Ads in Display Advertising](https://maths-people.anu.edu.au/~johnm/courses/mathdm/talks/dimitri-clickadvert.pdf)
<details>
  <summary>Czech notes</summary>
  
 Resi cold start CTR predictoru pro nove ady. Extrahuje vlastnosti z adu (img, flash) jako jsou barvy, svetlost, stupne sede, kontrast, barevnost, texturea, text pres OCR, objekty na obrazku, jejich mnozstvi a dle techto vlastnosti predikuji CTR. 
</details>

[2012 - The Impact of Visual Appearance on User Response in Online Display Advertising](https://arxiv.org/pdf/1202.2158.pdf)

[2012 - Estimating Conversion Rate in Display Advertising from Past Performance Data](http://wnzhang.net/share/rtb-papers/cvr-est.pdf)
<details>
  <summary>Czech notes</summary>
  
  Uzivatele, publishery a advertisery rozdeluji do taxonomii. Predikuji CVR na zaklade historickych statistik. Jake maji CVR podobni    uzivatele na podobnych webech. Pro predikci vyuzivaji logistickou regresi.   
</details>

[2010 - Estimating Rates of Rare Events with Multiple Hierarchies through Scalable Log-linear Models](https://web.njit.edu/~zhiwei/CS732/papers/Agarwal_KDD2010.pdf)

[2010 - Personalized Click Prediction in Sponsored Search](http://www.wsdm-conference.org/2010/proceedings/docs/p351.pdf)

[2010 - Predicting the Click-Through Rate for Rare/New Ads](https://pdfs.semanticscholar.org/acd0/25300131a53447ebb539d28ba8baaa62a520.pdf)

[2007 - Predicting Clicks: Estimating the Click-Through Rate for New Ads](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/predictingclicks.pdf)
