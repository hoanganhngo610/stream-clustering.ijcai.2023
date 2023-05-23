---
layout: default
title: "The State-of-the-Art and Challenges of Data Stream Clustering Algorithms in Practice"
description: Tutorial presented at the 32<sup>nd</sup> International Joint Conference on Artificial Intelligence, 19<sup>th</sup> - 25<sup>th</sup> August 2023, Macau, S.A.R.
mathjax: true
---

<style type="text/css">
  .image-left {
    display: block;
    margin-left: auto;
    margin-right: auto;
    float: right;
  }
</style>

# Practical information

The agenda of the tutorial will be as follows:

* **Place**: Polytechnico di Torino
* **Time**: Friday, September 22<sup>nd</sup> 2023, afternoon (GMT+1)

# Abstract

With significant advantages upon run time, resource usage, and complexity, online machine learning and stream clustering algorithms are playing a critical role in data science. Besides substantial resource advantages, these algorithms achieve a comparable performance to traditional batch machine learning methods. This tutorial will first surveys online machine learning and data stream clustering. With the emergence of fairness and interpretability, we will also discuss certain attempts in inducing a fair and interpretable machine learning model for data streams. We will then put the tutorial into a practical context with `River`, a Python library resulted from a merge between `Creme` and `scikit-multiflow`. We will also illustrate `River` as a go-to platform for online machine learning development by providing a guidance on how to integrate an algorithm with a clear workflow, alongside actual examples of past problems and solutions during the development process.
    
Besides, during this tutorial, state-of-the-art algorithms, associated core research approaches, and future directions of data stream clustering will be presented. Truly incremental clustering validity indices will also be mentioned as an important part of the stream clustering process and will be investigated thoroughly. Currently available metrics require the information of all past points, which is impractical for unlimited data streams. `River` is the first package to design and deploy such incremental indices. 
    
Last but not least, the tutorial will demonstrate the use of `River` and the associated clustering module in real-world scenarios. From this, we propose methods of clustering configuration, hyper-parameter tuning, applications and settings for benchmarking using real-world problems and datasets. Preliminary benchmarking results will also be provided to showcase the advantages and consistency in the performance of implemented algorithms.

# Two-sentence tutorial description 

*(to be included into the conference registration brochure)*

This tutorial provides an in-depth survey to online (data stream) machine learning, with an emphasis on fairness and interpretability, which is then later put into a practical context with \texttt{River}, a go-to Python library for the task. Moreover, data stream clustering problems will also be further rigorously investigated by mentioning state-of-the-art-algorithms, solutions for the implementation of incremental clustering validity indices, associated core research approaches, and future directions.

# Two-paragraph tutorial description

*(suitable for a web page overview, as per requested by the Call for Tutorials from IJCAI 23)*

With significant advantages upon run time, resource usage, and complexity, online machine learning and stream clustering algorithms are playing a critical role in data science. Besides substantial resource advantages, these algorithms achieve a comparable performance to traditional batch machine learning methods. As such, the first part of this tutorial is devoted as a literature survey into the field, including a strong emphasis on fairness and interpretability, which is then put into a practical context with `River`, a go-to Python library resulted from a merge between `Creme` and `scikit-multiflow`.

Besides, we will also investigate the problem of data stream clustering rigorously with state-of-the-art algorithms, associated core research approaches and future directions. In parallel, we will also look into the design of incremental clustering validity indices, which is an important part of the benchmarking process. All preliminary results will be provided at the end to showcase the advantages and consistency in the performance of implemented algorithms within `River`.

# Motivation

The motivations for this tutorial lie in the following points:

- `River`, an open-source Python library for online machine learning, has become more and more popular. Being well-maintained and constantly developed, it has not only been used in academic research but also in industrial applications by top tech companies (including Harman Kardon, Bee2Beep, Lyft, etc.).
- Until now, the development of stream algorithms and truly incremental validity indices is quite scattered and uncentralized. Previously, algorithms are usually self-developed and self-maintained by the respective authors in various different programming languages, and a common framework is not available and widely known until `River` is generated. This causes a tremendous difficulty in testing and benchmarking currently available algorithms or facilitating further research/improvements. As such, we plan `River` to become not only a go-to library for any online machine learning task but also a pioneer framework for the implementation of any new algorithm within the field.
- Compared to other sections of online machine learning, although being an extremely important task, stream clustering particularly seems to receive less notice with very few thorough literature surveys, and even fewer works related to practical applications.
- Fairness and interpretability of online machine learning algorithms are of considerable importance, and significant efforts have also been put into the field, but they are not made widely aware of.

# Presenters' bibliography

The following authors will be in-person presenters, i.e., tutors who will attend IJCAI 2023 and present part of the tutorial: **Jacob Montiel**, **Hoang-Anh Ngo**, **Minh-Huong Le-Nguyen** and **Albert Bifet**.

<img src="presenter-pics/jacob-montiel.jpg" alt="drawing" width="220" style="border-radius:60%"/>{: .image-left } 

**Jacob Montiel** is currently a Data Scientist in AWS Security. He is formerly a research fellow at the University of Waikato, New Zealand and Adjunct Researcher in the DIG Team at Télécom Paris, Institut Polytechnique de Paris, France and the core developer and maintainer of `River`. 

His research interests are in the field of machine learning for evolving data streams. Prior to focusing on research, Jacob led the development work for onboard software for aircraft and engine’s prognostics at GE Aviation; working in the development of GE’s Brilliant Machines, part of the IoT and GE’s approach to Industrial Big Data.

*Website:* [https://jacobmontiel.github.io/](https://jacobmontiel.github.io/)

*Google Scholar profile:* [Jacob Montiel](https://scholar.google.com/citations?user=WOvISekAAAAJ&hl=en)

<br clear="left"/>

<img src="presenter-pics/hoang-anh.ngo.jpg" alt="drawing" width="220" style="border-radius:60%"/>{: .image-left } 

**Hoang-Anh Ngo** is currently supported by the AI Institute and the School of Computing and Mathematical Sciences, University of Waikato under an External Study Award (ESA) to support his research on `River`, the machine learning library in Python for data streams. 

His research interests lies in the field of machine learning for evolving data stream, particularly in online clustering and classification algorithms. Previously, he joined the team of IT Specialists in COVID-19 task force, formed by the Ministry of Health of Vietnam as a Epidemiological Modelling Unit head.

*Google Scholar profile:* [Hoang-Anh Ngo](https://scholar.google.com/citations?user=yelTvHAAAAAJ&hl=en)

<br clear="left"/>

<img src="presenter-pics/minh-huong.le-nguyen.jpg" alt="drawing" width="220" style="border-radius:60%"/>{: .image-left } 

**Minh-Huong Le-Nguyen** is a third-year doctoral student at LCTI, Télécom Paris, Institut Polytechnique de Paris in France. Her doctoral research focuses on the applications of machine learning on data streams to implement predictive maintenance in the railway industry. She received her Bachelor’s degree in Computer Science at University Pierre and Marie Curie (France) in 2013, then she graduated from Télécom Paris with a Master’s degree in Data Science in 2019.

*ResearchGate profile:* [Minh-Huong Le-Nguyen](https://www.researchgate.net/profile/Minh-Huong-Le-Nguyen)

<br clear="left"/>

<img src="presenter-pics/albert-bifet.jpg" alt="drawing" width="220" style="border-radius:60%"/>{: .image-left } 

**Albert Bifet** is a Professor of AI and the DIrector of the Te Ipu o te Mahara AI Institute  at University of Waikato, and Professor of Big Data at Data, Intelligence and Graphs (DIG) LTCI, Télécom Paris. Problems he investigate are motivated by large scale data, the Internet of Things (IoT), and Big Data Science. He co-leads the open source projects MOA (Massive On-line Analysis), Apache SAMOA (Scalable Advanced Massive Online Analysis) and StreamDM.

*Website:* [https://albertbifet.com/](https://albertbifet.com/)

*Google Scholar profile:* [Albert Bifet](https://scholar.google.com/citations?user=UYvAL8EAAAAJ&hl=en)

# Presenters' contact information

### Jacob Montiel

&nbsp; AI Institute, University of Waikato, New Zealand and LCTI, Télécom Paris, Institut Polytechnique de Paris, Frnace

&nbsp; Email: [jmontiel@waikato.ac.nz](mailto:jmontiel@waikato.ac.nz)

### Hoang-Anh Ngo

&nbsp; Artificial Intelligence Institute, University of Waikato, Hamilton, New Zealand

&nbsp; Email: [h.a.ngo@sms.ed.ac.uk](mailto:h.a.ngo@sms.ed.ac.uk)

### Minh-Huong Le Nguyen

&nbsp; LCTI, Télécom Paris, Institut Polytechnique de Paris, France

&nbsp; Email: [minh.lenguyen@telecom-paris.fr](mailto:minh.lenguyen@telecom-paris.fr)

### Albert Bifet

&nbsp; Artificial Intelligence Institute, University of Waikato, Hamilton, New Zealand and LCTI, Télécom Paris, Institut Polytechnique de Paris, France

&nbsp; Email: [abifet@waikato.ac.nz](mailto:abifet@waikato.ac.nz)


# Intended audience

The target audience of the tutorial includes any researchers and practitioners with interests in machine learning for big data, evolving data streams or IoT applications. 

Basic knowledge with the Python programming language would be necessary. Apart from that, there will be no particular requirements or prerequisites on previous experience on data stream learning. However, either experience with traditional machine learning frameworks (`scikit-learn`, `keras`, `pytorch`, etc.) or previous interactions with online machine learning packages/tools, for example `MOA` (in Java), `stream` in `R`, `scikit-multiflow`, `Creme` or `River` in Python, would be beneficial.

For any developer who wants to contribute to `River` or use `River` to employ their own research work, a thorough understanding of `Git`, functionalities of `GitHub` (how to open a pull request, an issue, a discussion, Github Actions, etc.), code formatters in Python (`flake8`, `black`, `isort`, etc.) would be necessary.

# Format and detailed schedule

The tutorial is intended to be of **3.5 hours** (half-day, consisting of **two 1:45h slots**), spread throughout **3 sections** with **two 15-minute breaks** between each section. The detailed outline of the tutorial is as follows:

1. Introduction to data stream (online) machine learning (**1 hour**):
    1. What is online machine learning, and why do we need online machine learning?
    1. Differences, advantages and disadvantages of online machine learning compared to batch/traditional machine learning.
    1. Methods and interventions to induce fairness and interpretability in machine learning for streaming data in general.
    1. Introduction to `River`:
        1. Its foundation as a merge between `Creme` and `scikit-multiflow`;
        1. Design principles;
        1. Major advantages of `River` towards its competitors;
        1. Major updates/improvements throughout the versions.
    1. A brief guidance on how to develop/implement a model within `River`, along with demo and examples of past problems and solutions within the development process.
    1. Future maintenance and development orientation for `River`.
1. Online clustering algorithms and evaluation metrics (`1 hour 15 minutes`):
    1. A literature survey on existing clustering algorithms, the general concepts, approaches and their evolution.
    1. Introduction to the state-of-the-art clustering algorithms implemented in `River` and their potential differences or advantages compared to previously implemented versions.
    1. How to improve accuracy in calculating micro-cluster centers and diameters through time using Welford's algorithm.
    1. An investigation into currently available static validity indices, arising problems and motivation for the foundation of their truly incremental versions.
    1. A comparative survey on the expansion of incremental clustering validity indices, particularly among the most significant and widely used one that are adapted and integrated to `River`.
    1. `textClust` [Carnein *et al.*, 2017a], the first text clustering algorithm to be implemented in `River`.
    1. A brief introduction to research on fairness and interpretability of data stream clustering algorithms.
    1. Potential future research directions towards improvement in time and accuracy of stream clustering.
1. Use cases and benchmarking (**45 minutes**):
    1. Practical applications.
    1. Comparison between online and traditional/batch clustering algorithms.
    1. Live visualization of stream algorithms and their results in synthetic and real-life scenarios.
    1. Motivation, setting and system requirements for conducting benchmarking.
    1. Tutorial on benchmarking using the River package and the associated available `git` repository and terminal.
    1. Preliminary benchmarking results.

# Brief outline

## Introduction to data stream machine learning

This first part is intended to provide the motivation and necessity of online stream learning. As a matter of fact, traditional machine learning methods can not deal with an particularly large amount of data with limited resources and time constrains, which means that there is an urgent need for specific data stream machine learning methods with comparable results. 

Besides providing insights on advantages and disadvantages of online machine learning, we will also provide an introduction to `River`, a Python library aimed to become a go-to toolkit for this purpose with numerous advantages and features towards its open source competitors. Not only will we present `River` as a tool, we will also provide a detailed guide on how to contribute to `River` or utilize `River` to facilitate participants' own research works.

To conclude this section,  we present the latest trends in research for fairness and interpretability of stream machine learning models. Having to handle an unlimited amount of data while having to maintain the accuracy under concept drifts, the research for a fair and interpretable AI is interesting, yet much more demanding compared to that of traditional machine learning models.

## A literature survey on online clustering algorithms and metrics

This part will first start with an extensive survey on online clustering algorithms. First, we will start with the development from the first algorithms that introduced the concept of micro-clusters/macro-clusters and online/offline phases (BIRCH/CluStream), then to the evolution based on different approaches. These approaches include either distance-based, grid-based, model-based or projected, two-phase, type of time windows (damped, sliding, landmark or pyramidal), or the use of medoids/centroids. Besides interpreting these approaches, respective algorithms and their implementations within `River` are also introduced, including KMeans, DenStream, DBStream, STREAMKMeans and EvoStream.

With the emerging research on fairness and interpretability of AI, we will also discuss certain attempts in inducing a fair and interpretable stream clustering algorithm, including

- The first attempts for a fair K-Means algorithm by Schmidt et al. (2018) [Schmidt *et al.*, 2018] or fair k-Center algorithm by Bera et al. (2022) [Bera *et al.*, 2022] have been introduced.
- Intepretable multiple data stream clustering with clipped stream representation has also been proposed by Laurinec and Lucká (2019) [Laurinec and Lucká, 2018].

From this, we will discuss their effectiveness and later on how to apply these certain approaches for a broader family of clustering algorithms.

Finally, one aspect of online clustering algorithms that are usually neglected is the use of incremental validation metrics. Currently, apart from `River`, there is no tool/package that facilitates the use of truly incremental metrics, i.e. metrics that only use the summary statistics and the latest observation instead of having to use information of all passed points, which is impractical in stream learning. As such, in this part, we will also focus on the construction and comparison between these metrics, and also how to apply them in analyzing clustering algorithms' performances when put into practice.

## Practical applications and benchmarking using the clustering module of `River`

The final part serves as a practical demonstration on the usage of `River` and the associated clustering module in real-life scenarios.

First, a brief demonstration of `River` will be presented and its essential functionalities will also be compared with respective traditional/batch machine learning algorithms in terms of performance, memory and time usage to prove that although online methods takes up less resources, they have the ability to obtain a similar accuracy.

The next part will be dedicated to stream clustering algorithm's benchmarking work. The setting, system requirement, benchmarking method and hyper-parameter tuning will all be discussed.

Last but not least, preliminary benchmarking results with dedicated datasets will also be provided to exhibit the advantages and consistency in the performance of implemented algorithms.

# Type of support material to be supplied to attendees

Participants will receive the following support material:
  
- Presentation slides;
- PDF versions (including results) of any quizzes and surveys within the tutorial;
- All Jupyter notebooks and demos executed within and/or related to the tutorial.

Apart from the printed materials, the electronic version will all be freely, publicly available on the dedicated tutorial's website.

# List of previous offerings of the tutorial and relationship with them

## List of previous offerings of the tutorial

There has been two previous offerings of similar tutorials on the topic at highly-ranked conferences, including:

- First offering:
  - **Title:** Online Clustering: Algorithms, Evaluation, Metrics, Applications and Benchmarking using `River`.
  - **Conference:** The 26th Pacific - Asia Conference on Knowledge Discovery and Data Mining (PAKDD 2022).
  - **Number of participants:**} Unknown. Due to the COVID-19 prevention measures and time differences, the tutorial is presented online with a pre-recorded video.    
- Second offering:
  - **Title:** Online Clustering: Online Clustering: Algorithms, Evaluation, Metrics, Applications and Benchmarking [Montiel *et al.*, 2022].
  - **Conference:** The 28th ACM SIGKDD Cofnerence on Knowledge Discovery and Data Mining (KDD '22).
  - **Content:** Publicly available within \href[the tutorial's website](https://hoanganhngo610.github.io/river-clustering.kdd.2022/) and [the conference's proceedings](https://dl.acm.org/doi/10.1145/3534678.3542600).
  - **Number of participants:** Approximately 50 participants.

## Relationship to previous editions

### Similarities

This tutorial will preserve its strong points from previous editions by
  - providing a deep, thorough literature survey of state-of-the-art stream clustering algorithms and future research directions; and
  - allowing participants to have essential understanding of online learning, put under a practical point of view by `River`. Moreover, they will also be provided with interactive  demonstration that simulates real-life scenarios.

### Differences

The main differences of this tutorial compared to its previous versions are:

  - First and foremost, this tutorial will be more developer-oriented. This means that, apart from providing guidance and use cases `River`, the authors also provide a detailed picture of the developing process and how to contribute/develop a user's own algorithm within the ecosystem, along with actual problems and solutions during the development process. This is expected to potentially solve the problem of scattered and unorganized implementation of currently available stream clustering algorithms. 
  - On top of that, a clear development and maintenance orientation under the form of a public roadmap will also be provided. This can be considered as one of the most crucial parts in the development of any open-source projects.
  - The tutorial will also tackle the problems and provide detailed insights as a literature review of fairness and interpretability of online machine learning algorithms in general and stream clustering algorithms in particular. This part is intended to address a comment on the tutorial offering at KDD'22. Moreover, this will also be the first tutorial to ever conduct a survey into this aspect of online machine learning.
  - This tutorial will also be the first to analyze the implementation strategy of truly incremental clustering metrics in `River`, which are not available in any other online machine learning tools/packages.
  - Apart from providing a guidance on how to conduct benchmarking with `River`, preliminary results for comparison will also be provided. This work has just been completed recently and were not provided within any previous editions of this tutorial.
  - The tutorial will also introduce a starting solution to new research pathways in stream clustering algorithms:
    - Text clustering algorithms (despite the fact that previously, text clustering can be done with an indirect approach, using Term Frequency - Inverse Document Frequency (TF-IDF) [Rajaraman and Ullman, 2011] with an arbitrary numerical stream clustering algorithm;
    - Improvement in accuracy of calculating micro-clusters' centers and diameters using Welford's algorithm [Chan *et al.*, 1982] instead of cluster feature vectors.

# Strategies to enhance audience and interactivity

Since it is intended to be a mix between a lecture-style and a practical-style tutorial, the authors intend to imply various strategies to enhance interaction and interest, including:

- Including various small Question and Answers sessions in the tutorial to enhance speaker - audience interaction, ideally once after every finished section;
- Interactive quizzes or surveys (e.g. quizzes hosted on [kahoot](https://www.kahoot.it) will also be useful in attracting attendance and making the atmosphere more relaxed, while, at the same time, they can also make sure that the audience can understand the content conveyed;
- Using interactive tools like Jupyter notebooks with `Holoviews` or `Plotly` to represent real-time results for the purpose of visualisation;
- Switching presenters on-the-go, not necessarily after each section, will significantly increase attendees' attention towards the tutorial;
- Instead of pre-filling all code snippets, a lot of tasks within the demo will be left blank so that users can try to have a practical experience with all parts, either within or after the tutorial. Having all tools, packages and frameworks open-source (including `River` and the associated demo repository) is also a plus in facilitating this practice.
- Organizing small coding challenges or competitions. Since the main theme of the practical part of this tutorial is live visualisation and benchmarking, a certain level of competitiveness would create an energetic and enjoyable environment.

# Ethical statement

There are no ethical concerns related to the topic of this tutorial.

# Related materials

For all related materials, including presentation slides, demos, source code, related papers and any other piece of information, please visit [this page](./related-materials.html).

# Citation

TBA

# References

[Ackermann et al., 2012] Marcel R. Ackermann, Marcus Martens, Christoph Raupach, Kamil Swierkot, Christiane  Lammersen, and Christian Sohler. Streamkm++: A clustering algorithm for data streams. *ACM J. Exp. Algorithmics*, 17, May 2012. 

[Aggarwal and Reddy, 2016] Charu C. Aggarwal and Chandan K. Reddy. *Data Clustering Algorithms and Applications*. Chapman and Hall/CRC, 2016. 

[Aggarwal et al., 2003] Charu C. Aggarwal, Jiawei Han, Jianyong Wang, and Phillip S. Yu. A framework for clustering evolving data streams. In *Proceedings of the 29th International Conference on Very Large Data Bases - Volume 29*, VLDB ’03, pages 81–92, Berlin, Germany, 2003. VLDB Endowment. 

[Amini et al., 2014] Amineh Amini, Teh Ying Wah, and Hadi Saboohi. On density-based data streams clustering algorithms: A survey. *Journal of Computer Science and Technology*, 29(1):116–141, January 2014. 

[Bera et al., 2022] Suman K. Bera, Syamantak Das, Sainyam Galhotra, and Sagar Sudhir Kale. Fair k-center clustering in mapreduce and streaming settings. In *Proceedings of the ACM Web Conference 2022*, WWW ’22, page 1414–1422, New York, NY, USA, 2022. Association for Computing Machinery. 

[Bifet et al., 2018] Albert Bifet, Ricard Gavald`a, Geoff Holmes, and Bernhard Pfahringer. *Machine Learning for Data Streams: with Practical Examples in MOA*. The MIT Press, Cambridge, MA, USA, 2018.

[Cao et al., 2006] Feng Cao, Martin Estert, Weining Qian, and Aoying Zhou. Density-based clustering over an evolving data stream with noise. In *Proceedings of the 2006 SIAM International Conference on Data Mining (SDM)*, pages 328–339, Philadelphia, PA, USA, 2006. Society for Industrial and Applied Mathematics (SIAM).

[Carnein and Trautmann, 2019] Matthias Carnein and Heike Trautmann. Optimizing data stream representation: An extensive survey on stream clustering algorithms. *Business & Information Systems Engineering*, 61:277–297, 2019.

[Carnein et al., 2017a] Matthias Carnein, Dennis Assenmacher, and Heike Trautmann. Stream clustering of chat messages with applications to twitch streams. In *Proceedings of the 36th International Conference on Conceptual Modeling (ER ’17)*, pages 79–88. Springer International Publishing, 2017.

[Carnein et al., 2017b] Matthias Carnein, Assenmacher Dennis, and Heike Trautmann. An empirical comparison of stream clustering algorithms. In *Proceedings of the Computing Frontiers Conference, CF’17*, pages 361––366, New York, NY, USA, 2017. Association for Computing Machinery.

[Chan et al., 1982] T.F. Chan, G. H. Golub, and R. J. LeVeque. Updating formulae and a pairwise algorithm for computing sample variances. In *COMSTATS 1982 5th Symposium*. Physica, Heidenberg, 1982.

[Chen and Tu, 2007] Yixin Chen and Li Tu. Density-based clustering for real-time stream data. In *Proceedings of the 13th ACM SIGKKDD internaional conference on Knowledge discovery and data mining*, KDD ’07, pages 133–142, New York, NY, USA, August 2007. Association for Computing Machinery.

[Ghesmoune et al., 2016] Mohammed Ghesmoune, Mustapha Lebbah, and Hanene Azzag. State-of-the-art on clustering data streams. *Big Data Analytics*, 1(1):13, 2016.

[Halford et al., 2019] Max Halford, Geoffrey Bolmier, Raphael Sourty, Robin Vaysse, and Adil Zouitine. `creme`, a Python library for online machine learning, 2019.

[Hashler and Bolanos, 2016] Michael Hashler and MatthewBolanos. Clustering data streams based on shared density between micro-clusters. *IEEE Transactions on Knowledge and Data Engineering*, 28(6):1449–1461, 2016.

[Javed et al., 2020] Ali Javed, Byung Suk Lee, and Donna M. Rizzo. A benchmark study on time series clustering. *Machine Learning with Applications*, 1:100001, September 2020.

[Laurinec and Lucká, 2018] Peter Laurinec and Mária Lucká. Interpretable multiple data streams clustering with clipped streams representation for the improvement of electricity consumption forecasting. *Data Mining and Knowledge Discovery*, 33:413–445, 2018.

[Mansalis et al., 2018] Stratos Mansalis, Eirini Ntoutsi, Nikos Pelekis, and Yannis Theodoridis. An evaluation of data stream clustering algorithm. *Statistical Analysis and Data Mining: The ASA Data Science Journal*, 11:167–187, 2018.

[Montiel et al., 2018] Jacob Montiel, Jesse Read, Albert Bifet, and Talel Abdessalem. Scikit-multiflow: A multi-output streaming framework. *Journal of Machine Learning Research*, 19(72):1–5, 2018.

[Montiel et al., 2021] Jacob Montiel, Max Halford, Saulo Martiello Mastelini, Geoffrey Bolmier, Raphael Sourty, Robin Vaysse, Adil Zouitine, Heitor Murilo Gomes, Jesse Read, Talel Abdessalem, and Albert Bifet. River: machine learning for streaming data in python. *Journal of Machine Learning Research*, 22:1–8, April 2021.

[Montiel et al., 2022] Jacob Montiel, Hoang-Anh Ngo, Minh-Huong Le-Nguyen, and Albert Bifet. Online clustering: Algorithms, evaluation, metrics, applications and benchmarking. In *Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining*, KDD ’22, page 4808–4809, New York, NY, USA, 2022. Association for Computing Machinery.

[O’Callaghan et al., 2002] L. O’Callaghan, N. Mishra, A. Meyerson, S. Guha, and R. Motwani. Streaming-data algorithms for high-quality clustering. In *Proceedings 18th International Conference on Data Engineering*, pages 685–694, San Jose, CA, USA, August 2002. IEEE. 

[Rajaraman and Ullman, 2011] Anand Rajaraman and Jeffrey David Ullman. *Data Mining*, page 1–17. Cambridge University Press, 2011.

[Schmidt et al., 2018] Melanie Schmidt, Chris Schwiegelshohn, and Christian Sohler. Fair coresets and streaming algorithms for fair k-means clustering. CoRR, abs/1812.10854, 2018. 

[Silva et al., 2020] Leonardo Enzo Brito Da Silva, Niklas Max Melton, and Donald C. Wunsch. Incremental cluster validity indices for online learning of hard partitions: Extensions and comparative study. *IEEE Access*, 8:22025–22047, January 2020. 