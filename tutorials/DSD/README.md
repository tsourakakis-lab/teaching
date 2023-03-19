# Dense subgraph discovery tutorials 

# KDD 2015 and SDM 2021 

This repo contains slides for the original DSD tutorial with Aris Gionis (KTH) and for an updated version with the doctoral candidate Tianyi Chen (BU). The latter version contains recent updates as well as some unpublished experimental results. 


## Basic information 
Finding dense subgraphs is a fundamental graph-theoretic problem, that lies in the heart of numerous graph-mining applications, ranging from finding communities in social networks to detecting regulatory motifs in DNA and anomaly detection. The problem of finding dense subgraphs has been studied extensively in theoretical computer science, and recently, due to the relevance of the problem in real-world applications, it has attracted considerable attention in the data-mining community.

In this tutorial we aim to provide a comprehensive overview of (i) major algorithmic techniques for finding dense subgraphs in large graphs and (ii) graph mining applications that rely on dense subgraph extraction. We will present fundamental concepts and algorithms that date back to 80’s, as well as the latest advances in the area, from theoretical and from practical point-of-view. We will motivate the problem of finding dense subgraphs by discussing how it can be used in real-world applications. We will discuss different density definitions and the complexity of the corresponding optimization problems. We will also present efficient algorithms for different density measures and under different computational models. Specifically, we will focus on scalable streaming, distributed and MapReduce algorithms. Finally we will discuss problem variants, extensions, and will provide pointers for future research directions.

## Target Audience 

The tutorial will be designed to give a broad overview of the main techniques and problem variants, allowing graph-mining researchers to enrich their algorithmic toolbox. The tutorial will include cutting edge research on the topic of dense subgraph discovery, with anomaly detection applications. The intended duration of this tutorial is two hours.

The target audience are researchers and students interested in state-of-the-art graph mining algorithms and applications related to dense subgraph extraction. A computer-science background (B.Sc.\ or equivalent), and familiarity with undergraduate algorithm design and graph theory are prerequisites. The tutorial will focus on intuition and examples, carefully introducing only the minimal necessary theoretical tools, and focusing on applications.



### References 
- A. V. Goldberg. Finding a maximum density subgraph. UCB technical report, 1984
- M. Charikar. Greedy approximation algorithms for finding dense components in a graph. APPROX, 2000
- S. Khuller and B. Saha. On finding dense subgraphs. Automata, Languages and Programming (ICALP), 2009
- C. Ma, Y Fang, R Cheng, L Lakshmanan, W Zhang, X Lin. Efficient Algorithms for Densest Subgraph Discovery on Large Directed Graphs SIGMOD 2020 [Note: corrects the Khuller-Saha algorithm for directed graphs]
-D. Boob, Yu Gao, R. Peng, S. Sawlani, C. E. Tsourakakis, Di Wang, J. Wang.
Flowless: Extracting Densest Subgraphs Without Flow Computations WWW 2020
- M. Danisch, T.-H. Chan, M. Sozio. Large scale density-friendly graph decomposition via convex programming WWW ’17
- C. Tsourakakis. The k-clique densest subgraph problem. WWW 2015
- B Sun, M Danisch, T-H. Hubert Chan, M. Sozio. KClist++: A Simple Algorithm for Finding k-Clique Densest Subgraphs in Large Graphs VLDB 2020
- R. Andersen and K. Chellapilla. Finding dense subgraphs with size bounds. Workshop on Algorithms and Models for the Web-graph (WAW), 2009
- C. Tsourakakis, F. Bonchi, A. Gionis, F. Gullo, and M. Tsiarli. Denser than the densest subgraph: Extracting optimal quasi-cliques with quality guarantees. Knowledge Discovery and Data Mining (KDD), 2013
- N. Tatti and A. Gionis. Density-friendly graph decomposition. International World Wide Web Conference, 2015
- B. Bahmani, R. Kumar, and S. Vassilvitskii. Densest subgraph in streaming and map-reduce. Proceedings of the VLDB Endowment, 2012
- F Bonchi, D Garcia Soriano, A Miyauchi, CE Tsourakakis. Finding Densest k-connected Subgraph
- A. Epasto, S. Lattanzi, M. Sozio. Efficient densest subgraph computation in evolving graphs. International World Wide Web Conference, 2015
- A. McGregor, D. Tench, S. Vorotnikova, H. T. Vu. Densest subgraph in dynamic graph streams. CoRR abs/1506.04417, 2015
- M. Bhattacharya, Sayan Henzinger, D. Nanongkai, and C. Tsourakakis. Space- and time-efficient algorithms for maintaining dense subgraphs on one-pass dynamic streams. Symposium on Theory of Computing (STOC), 2015
- P. Rozenshtein, N. Tatti, and A. Gionis. Discovering dynamic communities in interaction networks. ECML PKDD, 2014
- O. D. Balalau, F. Bonchi, T. Chan, F. Gullo, and M. Sozio. Finding subgraphs with maximum total density and limited overlap. Web Search and Data Mining (WSDM) 2015
- CE Tsourakakis, T. Chen, N. Kakimura, J. Pachocki. Novel Dense Subgraph Discovery Primitives: Risk Aversion and Exclusion Queries
- V Jethava, A Martinsson, C Bhattacharyya, D Dubhashi The Lovász ϑ function, SVMs and finding large dense subgraphs JMLR 2013
- A. Miyauchi, N Kakimura. Finding a Dense Subgraph with Sparse Cut CIKM 2018
- Y Kuroki, A Miyauchi, J Honda, Μ Sugiyama. Online Dense Subgraph Discovery via Blurred-Graph Feedback ICML 2020
- E. Fratkin, B. T. Naughton, D. Brutlag, S. Batzoglou. Motifcut: regulatory motifs finding with maximum density subgraphs. Bioinformatics, 22(14):e150–e157, 2006
- A. Angel, N. Sarkas, N. Koudas, and D. Srivastava. Dense subgraph maintenance under streaming edge weight updates for real-time story identification. Proceedings of the VLDB Endowment, 2012
- A. Gionis, F. Junqueira, V. Leroy, M. Serafini, I. Weber. Piggybacking on social networks. Proceedings of the VLDB Endowment, 2013
- B Hooi, H A Song, A Beutel, N Shah, K Shin, C Faloutsos. Fraudar: Bounding graph fraud in the face of camouflage Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining
- K Shin, T Eliassi Rad, C Faloutsos: Corescope: Graph mining using k-core analysis—patterns, anomalies and algorithms ICDM 2016
- Li et al. FlowScope: Spotting Money Laundering Based on Graphs. AAAI 2020
- J Chen, Y Saad Dense subgraph extraction with application to community detection IEEE Transactions on knowledge and data engineering. 2010

