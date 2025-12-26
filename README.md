# Awesome-Critical-Nodes

## Critical Nodes Identification in Complex Networks: A Survey

Welcome to `Awesome-Critical-Nodes` GitHub repository! This repository hosts the introduction, papers of **Critical-Nodes** .

**Abstract**: Complex networks have become essential tools for understanding diverse phenomena in social systems, traffic systems, biomolecular systems, and financial systems. Identifying critical nodes is a central theme in contemporary research, serving as a vital bridge between theoretical foundations and practical applications. Nevertheless, the intrinsic complexity and structural heterogeneity characterizing real-world networks, with particular emphasis on dynamic and higher-order networks, present substantial obstacles to the development of universal frameworks for critical node identification. This paper provides a comprehensive review of critical node identification techniques, categorizing them into seven main classes: centrality, critical nodes deletion problem, influence maximization, network control, artificial intelligence, higher-order and dynamic methods. Our review bridges the gaps in existing surveys by systematically classifying methods based on their methodological foundations and practical implications, and by highlighting their strengths, limitations, and applicability across different network types. 
Our work enhances the understanding of critical node research by identifying key challenges, such as algorithmic universality, real-time evaluation in dynamic networks, analysis of higher-order structures, and computational efficiency in large-scale networks. The structured synthesis consolidates current progress and highlights open questions, particularly in modeling temporal dynamics, advancing efficient algorithms, integrating machine learning approaches, and developing scalable and interpretable metrics for complex systems.



<p align="center">
<img src="img/framework.png" height = "500" alt="" align=center />
</p>



If you find this repository helpful for your research, please cite our paper. 

```tex
@article{chen2025critical,
  title={Critical nodes identification in complex networks: a survey},
  author={Chen, Duxin and Chen, Jiawen and Zhang, Xiaoyu and Jia, Qinghan and Liu, Xiaolu and Sun, Ye and Lv, Linyuan and Yu, Wenwu},
  journal={arXiv preprint arXiv:2507.06164},
  year={2025}
}

@article{Chen2025CriticalNodes,
  author    = {Duxin Chen and Jiawen Chen and Xiaoyu Zhang and Qinghan Jia and Xiaolu Liu and Ye Sun and Linyuan L{\"u} and Wenwu Yu},
  title     = {Critical nodes identification in complex networks: a survey},
  journal   = {Complex Engineering Systems},
  year      = {2025},
  volume    = {5},
  number    = {3},
  pages     = {11},
  issn      = {2770-6249},
  doi       = {10.20517/ces.2025.34}
}

```


### 1. Neighbors-Based Ranking Methods

#### 1.1 Degree centrality

13. Bavelas, A. A mathematical model for group structures. Hum. Organ. 1948, 7, 16-30.

14. Nieminen, J. On the centrality in a graph. Scand. J. Psychol. 1974, 15, 332-36.

 
15. Chen, D.; Lü, L.; Shang, M. S.; Zhang, Y. C.; Zhou, T. Identifying influential nodes in complex networks. Phys. A. 2012, 391, 1777-87.

16. Ma, Y.; Cao, Z.; Qi, X. Quasi-Laplacian centrality: a new vertex centrality measurement based on Quasi-Laplacian energy of networks. Phys. A. 2019, 527, 121130.

17. Zhu, X.; Hao, R. Identifying influential nodes in social networks via improved Laplacian centrality. Chaos. Soliton. Fract. 2024, 189, 115675.



#### 1.2 K-shell decomposition
18. Kitsak, M.; Gallos, L. K.; Havlin, S.; et al. Identification of influential spreaders in complex networks. Nat. Phys. 2010, 6, 888-93.

19. Zeng, A.; Zhang, C. J. Ranking spreaders by decomposing complex networks. Phys. Lett. A. 2013, 377, 1031-35.

20. Li, C.; Wang, L.; Sun, S.; Xia, C. Identification of influential spreaders based on classified neighbors in real-world complex networks. Appl. Math. Comput. 2018, 320, 512-23.

21. Liu, J. G.; Ren, Z. M.; Guo, Q. Ranking the spreading influence in complex networks. Phys. A. 2013, 392, 4154-59.

22. Zareie, A.; Sheikhahmadi, A. A hierarchical approach for influential node ranking in complex social networks. Expert. Syst. Appl. 2018, 93, 200-211.

23. Ibnoulouafi, A.; El Haziti, M.; Cherifi, H. M-centrality: identifying key nodes based on global position and local degree variation. J. Stat. Mech. 2018, 2018, 073407.

24. Liu, Y.; Tang, M.; Zhou, T.; Do, Y. Core-like groups result in invalidation of identifying super-spreader by k-shell decomposition. Sci. Rep. 2015, 5, 9602.

 
25. Liu, Y.; Tang, M.; Zhou, T.; Do, Y. Improving the accuracy of the k-shell method by removing redundant links: from a perspective of spreading dynamics. Sci. Rep. 2015, 5, 13172.



#### 1.3 H-index
26. Lü, L.; Zhou, T.; Zhang, Q. M.; Stanley, H. E. The H-index of a network node and its relation to degree and coreness. Nat. Commun. 2016, 7, 10168.

 
27. Liu, Q.; Zhu, Y. X.; Jia, Y.; et al. Leveraging local h-index to identify and rank influential spreaders in networks. Phys. A. 2018, 512, 379-91.

28. Gao, L.; Yu, S.; Li, M.; Shen, Z.; Gao, Z. Weighted h-index for identifying influential spreaders. Symmetry 2019, 11, 1263.

29. Zareie, A.; Sheikhahmadi, A. EHC: extended H-index centrality measure for identification of users' spreading influence in complex networks. Phys. A. 2019, 514, 141-55.

#### 1.4 K-truss
30. Cohen, J. Trusses: cohesive subgraphs for social network analysis. National Security Agency Technical Report; 2008. Available from: https://www.researchgate.net/publication/242103824_Trusses_Cohesive_Subgraphs_for_Social_Network_Analysis[Last accessed on 10 Jul 2025].

31. Malliaros, F. D.; Rossi, M. E. G.; Vazirgiannis, M. Locating influential nodes in complex networks. Sci. Rep. 2016, 6, 19307.

#### 1.5 Structural hole
32. Yu, F.; Xia, X.; Li, W.; et al. Critical node identification for complex network based on a novel minimum connected dominating set. Soft. Comput. 2017, 21, 5621-29.

33. Yu, H.; Cao, X.; Liu, Z.; Li, Y. Identifying key nodes based on improved structural holes in complex networks. Phys. A. 2017, 486, 318-27.

34. Xu, H.; Zhang, J.; Yang, J.; Lun, L. Identifying important nodes in complex networks based on multiattribute evaluation. Math. Probl. Eng. 2018, 2018, 8268436.

35. Liu, Y.; Wang, J.; He, H.; Huang, G.; Shi, W. Identifying important nodes affecting network security in complex networks. Int. J. Distrib. Sens. Netw. 2021, 17, 1550147721999285.

36. Zhao, Z.; Li, D.; Sun, Y.; Zhang, R.; Liu, J. Ranking influential spreaders based on both node k-shell and structural hole. Knowl. Based. Syst. 2023, 260, 110163.

37. Ma, J.; Kong, L.; Li, H. An effective edge-adding strategy for enhancing network traffic capacity. Phys. A. 2023, 609, 128321.



#### 1.6 Neighborhood similarity

38. Wang, P.; Xu, B.; Wu, Y.; Zhou, X. Link prediction in social networks: the state-of-the-art. Sci. China. Inf. Sci. 2015, 1, 1-38.

39. Lu, P.; Zhang, Z. Critical nodes identification in complex networks via similarity coefficient. Mod. Phys. Lett. B. 2022, 36, 2150620.

40. Ai, J.; He, T.; Su, Z. Identifying influential nodes in complex networks based on resource allocation similarity. Phys. A. 2023, 627, 129101.

41. Rao, K. V.; Chowdary, C. R. CBIM: community-based influence maximization in multilayer networks. Inf. Sci. 2022, 609, 578-94.

42. Tong, T.; Yuan, W.; Jalili, M.; Dong, Q.; Sun, J. A novel ranking approach for identifying crucial spreaders in complex networks based on Tanimoto Correlation. Expert. Syst. Appl. 2024, 255, 124513.




### 2. Eigenvector-based Ranking Methods


#### 2.1 Eigenvector centrality
43. Bonacich, P. Factoring and weighting approaches to clique identification. J. Math. Sociol. 1971, 92, 1170-82.

44. Bonacich, P. Some unique properties of eigenvector centrality. Soc. Netw. 2007, 29, 555-64.

45. Ilyas, M. U.; Radha, H. Identifying influential nodes in online social networks using principal component centrality. In: 2011 IEEE International Conference on Communications. IEEE; 2011. pp. 1-5.

46. Estrada, E.; Rodríguez-Velázquez, J. A. Subgraph centrality in complex networks. Phys. Rev. E. 2005, 71, 056103.

47. Ahajjam, S.; El Haddad, M.; Badir, H. LeadersRank: towards a new approach for community detection in social networks. In: 2015 IEEE/ACS 12th International Conference of Computer Systems and Applications; 2015. pp. 1-8.

48. Martin, T.; Zhang, X.; Newman, M. E. Localization and centrality in networks. Phys. Rev. E. 2014, 90, 052808.

49. Zhong, L.; Shang, M.; Chen, X.; Cai, S. M. Identifying the influential nodes via eigencentrality from the differences and similarities of structure. Phys. A. 2018, 510, 77-82.


#### 2.2 Katz centrality
50. Katz, L. A new status index derived from sociometric analysis. Psychometrika 1953, 18, 39-43.

51. Zhang, Y.; Bao, Y.; Zhao, S.; Chen, J.; Tang, J. Identifying node importance by combining betweenness centrality and katz centrality. In: 2015 International Conference on Cloud Computing and Big Data; 2015. pp. 354-57.

#### 2.3 PageRank algorithm
52. Page, L.; Brin, S.; Motwani, R.; Winograd, T. The pagerank citation ranking: bring order to the web. Stanford University; 1998. Available from: http://ilpubs.stanford.edu:8090/422/[Last accessed on 10 Jul 2025].

53. Yang, Y.; Xie, G.; Xie, J. Mining important nodes in directed weighted complex networks. Discrete. Dyn. Nat. Soc. 2017, 2017, 9741824.

54. Chinchi, H.; Yian, L.; Wenhao, C.; Minghan, F.; Shoude, L. Unsupervised ranking using graph structures and node attributes. In Proceedings of the tenth ACM International Conference on Web Search and Data Mining; 2017. pp. 771-79.

55. Sheng, J.; Zhu, J.; Wang, Y.; Wang, B.; Hou, Z. Identifying influential nodes of complex networks based on trust-value. Algorithms 2020, 13, 280.

56. Su, Q.; Chen, C.; Sun, Z.; Li, J. Identification of critical nodes for cascade faults of grids based on electrical PageRank. Glob. Energy. Interconnect. 2021, 4, 587-95.

#### 2.4 Voting mechanism
57. Lü, L.; Zhang, Y. C.; Yeung, C. H.; Zhou, T. Leaders in social networks, the delicious case. PLoS. One. 2011, 6, e21202.

 
58. Li, Q.; Zhou, T.; Lü, L.; Chen, D. Identifying influential spreaders by weighted LeaderRank. Phys. A. 2014, 404, 47-55.

59. Zhang, J.; Chen, D.; Dong, Q.; Zhao, Z. Identifying a set of influential spreaders in complex networks. Sci. Rep. 2016, 6, 27823.

 
60. Kumar, S.; Panda, B. S. Identifying influential nodes in social networks: neighborhood Coreness based voting approach. Phys. A. 2020, 553, 124215.

61. Sun, H.; Chen, D.; He, J.; Ch'ng, E. A voting approach to uncover multiple influential spreaders on weighted networks. Phys. A. 2019, 519, 303-12.

62. Li, Y.; Yang, X.; Zhang, X.; Xi, M.; Lai, X. An improved voterank algorithm to identifying a set of influential spreaders in complex networks. Front. Phys. 2022, 10, 955727.

63. Liu, J.; Xiong, Q.; Shi, W.; Shi, X.; Wang, K. Evaluating the importance of nodes in complex networks. Phys. A. 2016, 452, 209-19.



### 3. Path-Based Ranking Methods




#### 3.1 Betweenness centrality
64. Freeman, L. C. A set of measures of centrality based on betweenness. Sociometry 1977, 40, 35-41.

65. Hage, P.; Harary, F. Eccentricity and centrality in networks. Soc. Netw. 1995, 17, 57-63.

66. Boccaletti, S.; Latora, V.; Moreno, Y.; Chavez, M.; Hwang, D. U. Complex networks: structure and dynamics. Phys. Rep. 2006, 424, 175-308.

67. Lü, Z.; Zhao, N.; Xiong, F.; Chen, N. A novel measure of identifying influential nodes in complex networks. Phys. A. 2019, 523, 488-97.

68. Song, Z.; Duan, H.; Ge, Y.; Qiu, X. A novel measure of centrality based on betweenness. In 2015 Chinese Automation Congress; 2015. pp. 174-78.

69. Ventresca, M.; Aleman, D. Efficiently identifying critical nodes in large complex networks. Comput. Soc. Netw. 2015, 2, 1-16.

70. Zhang, J.; Xu, X.; Li, P.; Zhang, K.; Small, M. Node importance for dynamical process on networks: a multiscale characterization. Chaos 2011, 21.

71. Yang, D.; Sun, Y.; Zhou, B.; Gao, X.; Zhang, H. Critical nodes identification of complex power systems based on electric cactus structure. IEEE. Syst. J. 2020, 14, 4477-88.

72. Kianian, S.; Rostamnia, M. An efficient path-based approach for influence maximization in social networks. Expert. Syst. Appl. 2021, 167, 114168.

73. Xiao, Y.; Chen, Y.; Zhang, H.; et al. A new semi-local centrality for identifying influential nodes based on local average shortest path with extended neighborhood. Artif. Intell. Rev. 2024, 57, 115.



#### 3.2 Closeness centrality
74. Freeman, L. C. Centrality in social networks: Conceptual clarification. Soc. Netw. 2002, 1, 238-63.

75. Latora, V.; Marchiori, M. Efficient behavior of small-world networks. Phys. Rev. Lett. 2001, 87, 198701.

 
76. Salavati, C.; Abdollahpouri, A.; Manbari, Z. Ranking nodes in complex networks based on local structure and improving closeness centrality. Neurocomputing 2019, 336, 36-45.

77. Okamoto, K.; Chen, W.; Li, X. Ranking of closeness centrality for large-scale social networks. In Proceedings of the 2nd Annual International Workshop on Frontiers in Algorithmics. Heidelberg: Springer-Verlag; 2008. p. 186-95.

78. Sheng, J.; Dai, J.; Wang, B.; et al. Identifying influential nodes in complex networks based on global and local structure. Phys. A. 2020, 541, 123262.




#### 3.3 Random walk
79. Iannelli, F.; Mariani, M. S.; Sokolov, I. M. Influencers identification in complex networks through reaction-diffusion dynamics. Phys. Rev. E. 2018, 98, 062302.

80. Dong, J.; Ye, F.; Chen, W.; Wu, J. Identifying influential nodes in complex networks via semi-local centrality. In 2018 IEEE International Symposium on Circuits and Systems; 2018. pp. 1-5.

81. Kermarrec, A. M.; Le Merrer, E.; Sericola, B.; Trédan, G. Second order centrality: distributed assessment of nodes criticity in complex networks. Comput. Commun. 2011, 34, 619-28.


 



### 4. Control-optimization based Ranking Methods



#### 4.1 Network control
82. Li, X.; Wang, X. Controlling the spreading in small-world evolving networks: stability, oscillation, and topology. IEEE. Trans. Autom. Control. 2006, 51, 534-40.

83. Ghosh, D.; Frasca, M.; Rizzo, A.; et al. The synchronized dynamics of time-varying networks. Phys. Rep. 2022, 949, 1-63.

84. D'Souza, R. M.; di Bernardo, M.; Liu, Y. Controlling complex networks with complex nodes. Nat. Rev. Phys. 2023, 5, 250-62.

85. Liu, Y.; Slotine, J. J.; Barabási, A. L. Controllability of complex networks. Nature 2011, 473, 167-73.

 
86. Ding, J.; Wen, C.; Li, G. Key node selection in minimum-cost control of complex networks. Phys. A. 2017, 486, 251-61.

87. Lu, J.; Liu, R.; Lou, J.; Liu, Y. Pinning stabilization of Boolean control networks via a minimum number of controllers. IEEE. Trans. Cybern. 2019, 51, 373-81.

 
88. Zhu, S.; Cao, J.; Lin, L.; Lam, J.; Azuma, S. I. Toward stabilizable large-scale Boolean networks by controlling the minimal set of nodes. IEEE. Trans. Autom. Control. 2023, 69, 174-88.

89. Yu, W.; DeLellis, P.; Chen, G.; Di Bernardo, M.; Kurths, J. Distributed adaptive control of synchronization in complex networks. IEEE. Trans. Autom. Control. 2012, 57, 2153-58.

90. Yu, W.; Chen, G.; Lu, J.; Kurths, J. Synchronization via pinning control on general complex networks. SIAM. J. Control. Optim. 2013, 51, 1395-416.

91. Ding, J.; Tan, P.; Lu, Y. Z. Optimizing the controllability index of directed networks with the fixed number of control nodes. Neurocomputing 2016, 171, 1524-32.

92. Amani, A. M.; Jalili, M.; Yu, X.; Stone, L. Finding the most influential nodes in pinning controllability of complex networks. IEEE. Trans. Circuits. Syst. Ⅱ. 2017, 64, 685-89.

93. Amani, A. M.; Jalili, M.; Yu, X.; Stone, L. Controllability of complex networks: choosing the best driver set. Phys. Rev. E. 2018, 98, 030302.

94. Liu, H.; Xu, X.; Lu, J. A.; Chen, G.; Zeng, Z. Optimizing pinning control of complex dynamical networks based on spectral properties of grounded Laplacian matrices. IEEE. Trans. Syst. Man. Cyber. Syst. 2018, 51, 786-96.

95. Wang, W.; Ni, X.; Lai, Y.; Grebogi, C. Optimizing controllability of complex networks by minimum structural perturbations. Phys. Rev. E. 2012, 85, 026115.

96. Bof, N.; Baggio, G.; Zampieri, S. On the role of network centrality in the controllability of complex networks. IEEE. Trans. Control. Netw. Syst. 2016, 4, 643-53.

97. Zhou, J.; Yu, X.; Lu, J. A. Node importance in controlled complex networks. IEEE. Trans. Circuits. Syst. Ⅱ. 2018, 66, 437-41.

98. Liu, H.; Wang, B.; Lu, J.; Li, Z. Node-set importance and optimization algorithm of nodes selection in complex networks based on pinning control. Acta. Phys. Sin. 2021, 70, 056401.

99. Bomela, W.; Sebek, M.; Nagao, R.; et al. Finding influential nodes in networks using pinning control: centrality measures confirmed with electrochemical oscillators. Chaos 2023, 33, 093128.

 
100. Jiang, Q.; Zhou, J.; Li, B.; Liu, H.; Lu, J. A. Pinning synchronization of a complex network: nodes, edges and higher-order edges. Europhys. Lett. 2024, 147, 61001.

101. Sun, G. Q.; He, R.; Hou, L. F.; et al. Optimal control of spatial diseases spreading in networked reaction-diffusion systems. Phys. Rep. 2025, 1111, 1-64.

102. Zhang, H. T.; Chen, Z.; Mo, X. Effect of adding edges to consensus networks with directed acyclic graphs. IEEE. Trans. Autom. Control. 2017, 62, 4891-97.

103. Mo, X.; Chen, Z.; Zhang, H. T. Effects of adding a reverse edge across a stem in a directed acyclic graph. Automatica 2019, 103, 254-60.

104. Jiang, S.; Zhou, J.; Small, M.; Lu, J. A.; Zhang, Y. Searching for key cycles in a complex network. Phys. Rev. Lett. 2023, 130, 187402.

 
105. Cao, H.; Zhang, H. T.; Xie, L. Synchronization acceleration of networked systems via edge addition to single-root weighted digraphs. IEEE. Trans. Autom. Control. 2024, 70, 1730-44.

106. Zhang, H. T.; Cao, H.; Chen, Z. A necessary and sufficient condition of an interfering reverse edge for a directed acyclic graph. IEEE. Trans. Autom. Control. 2022, 67, 4885-91.

107. Gao, S.; Zhang, S.; Chen, X. Effects of adding edges on the consensus convergence rate of weighted directed chain networks. IEEE. Trans. Autom. Control. 2025, 70, 4077-84.

#### 4.2 Maximization of connected Component optimization

108. Aringhieri, R.; Grosso, A.; Hosteins, P.; Scatamacchia, R. A general evolutionary framework for different classes of critical node problems. Eng. Appl. Artif. Intell. 2016, 55, 128-45.

109. Alozie, G. U.; Arulselvan, A.; Akartunalı, K.; Pasiliao Jr, E. L. Efficient methods for the distance-based critical node detection problem in complex networks. Comput. Oper. Res. 2021, 131, 105254.

110. Thulasiraman, K.; Swamy, M. N. S. Graphs:. theory. and. algorithms. 2011.

111. Boginski, V.; Commander, C. W. Identifying. critical. nodes. in. protein-protein. interaction. networks;. 2008..

112. Karygiannis, A.; Antonakakis, E.; Apostolopoulos, A. Detecting critical nodes for MANET intrusion detection systems. In Second International Workshop on Security, Privacy and Trust in Pervasive and Ubiquitous Computing; 2006. pp. 9-15.

113. Arulselvan, A.; Commander, C. W.; Shylo, O.; Pardalos, P. M. Cardinality-constrained critical node detection problem. Performance Models and Risk Management in Communications Systems; 2011, pp. 79-91.

114. Li, C.; Lin, S.; Shan, M. Finding influential mediators in social networks. In Proceedings of the 20th International Conference Companion on World Wide Web; 2011, pp. 75-6.

115. Ventresca, M.; Harrison, K. R.; Ombuki-Berman, B. M. An experimental evaluation of multi-objective evolutionary algorithms for detecting critical nodes in complex networks. In European Conference on the Applications of Evolutionary Computation. Springer; 2015, pp. 164-76.

116. Veremyev, A.; Boginski, V.; Pasiliao, E. L. Exact identification of critical nodes in sparse networks via new compact formulations. Optim. Lett. 2014, 8, 1245-59.

117. Ren, T.; Li, Z.; Qi, Y.; et al. Identifying vital nodes based on reverse greedy method. Sci. Rep. 2020, 10, 4826.

 
118. Wang, Y.; Cong, G.; Song, G.; Xie, K. Community-based greedy algorithm for mining top-k influential nodes in mobile social networks. In Proceedings of the 16th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining; 2010. pp. 1039-48.

119. Lam, C. Y.; Lin, J.; Sim, M. S.; Tai, K. Identifying vulnerabilities in critical infrastructures by network analysis. Int. J. Crit. Infrastruct. 2013, 9, 190-210.

120. Ventresca, M.; Aleman, D. A fast greedy algorithm for the critical node detection problem. In: International Conference on Combinatorial Optimization and Applications. Springer; 2014. pp. 603-12.

121. Tang, J.; Zhang, R.; Wang, P.; et al. A discrete shuffled frog-leaping algorithm to identify influential nodes for influence maximization in social networks. Knowl. Based. Syst. 2020, 187, 104833.


#### 4.3 Minimization of pair Connectivity optimization
122. Di Summa, M.; Grosso, A.; Locatelli, M. Branch and cut algorithms for detecting critical nodes in undirected graphs. Comput. Optim. Appl. 2012, 53, 649-80.

123. Arulselvan, A.; Commander, C. W.; Elefteriadou, L.; Pardalos, P. M. Detecting critical nodes in sparse graphs. Comput. Oper. Res. 2009, 36, 2193-200.

124. Shen, Y.; Dinh, T. N.; Thai, M. T. Adaptive algorithms for detecting critical links and nodes in dynamic networks. In: 2012 IEEE Military Communications Conference; 2012. pp. 1-6.

125. Ventresca, M.; Aleman, D. A derandomized approximation algorithm for the critical node detection problem. Comput. Oper. Res. 2014, 43, 261-70.

126. Dinh, T. N.; Thai, M. T. Assessing attack vulnerability in networks with uncertainty. In: 2015 IEEE Conference on Computer Communications; 2015. pp. 2380-88.

127. Sarker, S.; Veremyev, A.; Boginski, V.; Singh, A. Critical nodes in river networks. Sci. Rep. 2019, 9, 11178.

 
128. Pullan, W. Heuristic identification of critical nodes in sparse real-world graphs. J. Heuristics. 2015, 21, 577-98.

129. Addis, B.; Aringhieri, R.; Grosso, A.; Hosteins, P. Hybrid constructive heuristics for the critical node problem. Ann. Oper. Res. 2016, 238, 637-49.

130. Chen, W.; Jiang, M.; Jiang, C.; Zhang, J. Critical node detection problem for complex network in undirected weighted networks. Phys. A. 2020, 538, 122862.

131. Ventresca, M. Global search algorithms using a combinatorial unranking-based problem representation for the critical node detection problem. Comput. Oper. Res. 2012, 39, 2763-75.

132. Shen, Y.; Nguyen, N. P.; Xuan, Y.; Thai, M. T. On the discovery of critical links and nodes for assessing network vulnerability. IEEE/ACM. Trans. Netw. 2012, 21, 963-73.

133. Ventresca, M.; Aleman, D. A region growing algorithm for detecting critical nodes. In: International Conference on Combinatorial Optimization and Applications. Springer; 2014. pp. 593-602.

134. Yin, H.; Hou, J.; Gong, C. A mixed strength decomposition method for identifying critical nodes by decomposing weighted social networks. Europhys. Lett. 2023, 142, 61003.

135. Zhang, L.; Zhang, H.; Feng, X.; Yang, H.; Cheng, F. An evolutionary multitasking method for multi-objective critical node detection on interdependent networks. IEEE. Trans. Cognit. Commun. Netw. 2025, 11, 607-20.

136. Fortz, B.; Mycek, M.; Pióro, M.; Tomaszewski, A. Min-max optimization of node-targeted attacks in service networks. Networks 2024, 83, 256-88.

137. Jiang, W.; Li, P.; Li, T.; Fan, T.; Zhang, C. Identifying vital edges based on the cycle structure in complex networks. Phys. Lett. A. 2025, 530, 130137.

138. Kouam, W.; Hayel, Y.; Deugoué, G.; Kamhoua, C. A novel centrality measure for analyzing lateral movement in complex networks. Phys. A. 2025, 658, 130255.

139. Zhou, M.; Liu, H.; Liao, H.; Liu, G.; Mao, R. Finding the key nodes to minimize the victims of the malicious information in complex network. Knowl. Based. Syst. 2024, 293, 111632.



#### 4.4 Minimum spanning tree
140. Zhao, J.; Liu, X.; Guo, J. Evaluation method for node importance of communication network based on complex network analysis. In: Communications, Signal Processing, and Systems. Singapore: Springer; 2019.

141. Di Summa, M.; Grosso, A.; Locatelli, M. Complexity of the critical node problem over trees. Comput. Oper. Res. 2011, 38, 1766-74.

142. Hermelin, D.; Kaspi, M.; Komusiewicz, C.; Navon, B. Parameterized complexity of critical node cuts. Theor. Comput. Sci. 2016, 651, 62-75.

143. Addis, B.; Di Summa, M.; Grosso, A. Identifying critical nodes in undirected graphs: complexity results and polynomial algorithms for the case of bounded treewidth. Discrete. Appl. Math. 2013, 161, 2349-60.

144. Aringhieri, R.; Grosso, A.; Hosteins, P.; Scatamacchia, R. Local search metaheuristics for the critical node problem. Networks 2016, 67, 209-21.

145. Wang, H.; Shan, Z.; Ying, G.; et al. Evaluation method of node importance for power grid considering inflow and outflow power. J. Mod. Power. Syst. Clean. Energy. 2017, 5, 696-703.


### 5. Machine learning-based Ranking Methods



#### 5.1 Information entropy
146. Nikolaev, A. G.; Razib, R.; Kucheriya, A. On efficient use of entropy centrality for social network analysis and community detection. Soc. Netw. 2015, 40, 154-62.

147. Zareie, A.; Sheikhahmadi, A.; Jalili, M. Influential node ranking in social networks based on neighborhood diversity. Future. Gener. Comput. Syst. 2019, 94, 120-29.

148. Nitt, G. Using mapping entropy to identify node centrality in complex networks. Phys. A. 2016, 453, 290-97.

149. Fu, Y. H.; Huang, C. Y.; Sun, C. T. Identifying super-spreader nodes in complex networks. Math. Probl. Eng. 2015.

 
150. Guo, C.; Yang, L.; Chen, X.; et al. Influential nodes identification in complex networks via information entropy. Entropy 2020, 22, 242.

151. Xu, M.; Wu, J.; Liu, M.; et al. Discovery of critical nodes in road networks through mining from vehicle trajectories. IEEE. Trans. Intell. Trans. Syst. 2018, 20, 583-93.

152. Tulu, M. M.; Hou, R.; Younas, T. Identifying influential nodes based on community structure to speed up the dissemination of information in complex network. IEEE. Access. 2018, 6, 7390-401.

153. Ai, X. Node importance ranking of complex networks with entropy variation. Entropy 2017, 19, 303.

154. Wu, Y.; Dong, A.; Ren, Y.; Jiang, Q. Identify influential nodes in complex networks: a k-orders entropy-based method. Phys. A. 2023, 632, 129302.

155. Tong, T.; Dong, Q.; Sun, J.; Jiang, Y. Vital spreaders identification synthesizing cross entropy and information entropy with kshell method. Expert. Syst. Appl. 2023, 224, 119928.

156. Li, Y.; Cai, W.; Li, Y.; Du, X. Key node ranking in complex networks: a novel entropy and mutual information-based approach. Entropy 2019, 22, 52.





#### 5.2 Clustering coefficient
157. Chen, D. B.; Gao, H.; Lü, L.; Zhou, T. Identifying influential nodes in large-scale directed networks: the role of clustering. PLoS. One. 2013, 8, e77455.

 
158. Gao, S.; Ma, J.; Chen, Z.; Wang, G.; Xing, C. Ranking the spreading ability of nodes in complex networks based on local structure. Phys. A. 2014, 403, 130-47.

159. Yang, L.; Song, Y.; Jiang, G. P.; Xia, L. L. Identifying influential spreaders based on diffusion K-truss decomposition. Int. J. Mod. Phys. B. 2018, 32, 1850238.

160. Zareie, A.; Sheikhahmadi, A.; Jalili, M.; Fasaei, M. S. K. Finding influential nodes in social networks based on neighborhood correlation coefficient. Knowl. Based. Syst. 2020, 194, 105580.

161. Dablander, F.; Hinne, M. Node centrality measures are a poor substitute for causal inference. Sci. Rep. 2019, 9, 6846.

 
162. Liu, Y.; Song, A.; Shan, X.; Xue, Y.; Jin, J. Identifying critical nodes in power networks: a group-driven framework. Expert. Syst. Appl. 2022, 196, 116557.

163. Wang, B.; Zhang, J.; Dai, J.; Sheng, J. Influential nodes identification using network local structural properties. Sci. Rep. 2022, 12, 1833.

 
164. Zhang, X.; Zhu, J.; Wang, Q.; Zhao, H. Identifying influential nodes in complex networks with community structure. Knowl. Based. Syst. 2013, 42, 74-84.



#### 5.3 Graph conventional network
168. Zhao, G.; Jia, P.; Zhou, A.; Zhang, B. InfGCN: identifying influential nodes in complex networks with graph convolutional networks. Neurocomputing 2020, 414, 18-26.

169. Kumar, S.; Mallik, A.; Khetarpal, A.; Panda, B. Influence maximization in social networks using graph embedding and graph neural network. Inf. Sci. 2022, 607, 1617-36.

170. Ribeiro, L. F.; Saverese, P. H.; Figueiredo, D. R. struc2vec: learning node representations from structural identity. In Proceedings of the 23rd ACM SIGKDD International Conference on Knowledge Discovery & Data Mining; 2017. pp. 385-94.

171. Zhang, M.; Wang, X.; Jin, L.; Song, M.; Li, Z. A new approach for evaluating node importance in complex networks via deep learning methods. Neurocomputing 2022, 497, 13-27.

172. Liu, C.; Cao, T.; Zhou, L. Learning to rank complex network node based on the self-supervised graph convolution model. Knowl. Based. Syst. 2022, 251, 109220.



#### 5.4 Graph embeddings
173. Wei, P.; Zhou, J.; Yan, B.; Zeng, Y. ENIMNR: enhanced node influence maximization through node representation in social networks. Chaos. Soliton. Fract. 2024, 186, 115192.

174. Keikha, M. M.; Rahgozar, M.; Asadpour, M.; Abdollahi, M. F. Influence maximization across heterogeneous interconnected networks based on deep learning. Expert. Syst. Appl. 2020, 140, 112905.

175. Bouyer, A.; Beni, H. A.; Oskouei, A. G.; et al. Maximizing influence in social networks using combined local features and deep learning-based node embedding. Big. Data. 2024.

176. Wu, Y.; Hu, Y.; Yin, S.; et al. A graph convolutional network model based on regular equivalence for identifying influential nodes in complex networks. Knowl. Based. Syst. 2024, 301, 112235.

177. Ahmad, W.; Wang, B.; Chen, S. Learning to rank influential nodes in complex networks via convolutional neural networks. Appl. Intell. 2024, 54, 3260-78.

178. Rashid, Y.; Bhat, J. I. OlapGN: a multi-layered graph convolution network-based model for locating influential nodes in graph networks. Knowl. Based. Syst. 2024, 283, 111163.

179. Xiong, Y.; Hu, Z.; Su, C.; Cai, S. M.; Zhou, T. Vital node identification in complex networks based on autoencoder and graph neural network. Appl. Soft. Comput. 2024, 163, 111895.

180. Yu, E.; Wang, Y.; Fu, Y.; Chen, D.; Xie, M. Identifying critical nodes in complex networks via graph convolutional networks. Knowl. Based. Syst. 2020, 198, 105893.


#### 5.5 Graph attention network
181. Park, N.; Kan, A.; Dong, X. L.; Zhao, T.; Faloutsos, C. Estimating node importance in knowledge graphs using graph neural networks. In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining; 2019. pp. 596-606.

182. Park, N.; Kan, A.; Dong, X. L.; Zhao, T.; Faloutsos, C. Multiimport: inferring node importance in a knowledge graph from multiple input signals. In Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining; 2020. pp. 503-12.

183. Munikoti, S.; Das, L.; Natarajan, B. Scalable graph neural network-based framework for identifying critical nodes and links in complex networks. Neurocomputing 2022, 468, 211-21.

184. Ge, K.; Han, Q. B. Node importance estimation for knowledge graphs based on multi-perspectives attention fusion mechanism. Int. J. Pattern. Recognit. Artif. Intell. 2024, 38, 2459017.

185. Chen, X.; Lei, P. I.; Sheng, Y.; Liu, Y.; Gong, Z. Social influence learning for recommendation systems. In Proceedings of the 33rd ACM International Conference on Information and Knowledge Management; 2024. pp. 312-22.

186. Liu, Z.; Qiu, H.; Guo, W.; Zhu, J.; Wang, Q. NIE-GAT: node importance evaluation method for inter-domain routing network based on graph attention network. J. Comput. Sci. 2022, 65, 101885.

187. Kou, J.; Jia, P.; Liu, J.; Dai, J.; Luo, H. Identify influential nodes in social networks with graph multi-head attention regression model. Neurocomputing 2023, 530, 23-36.

#### 5.6 Graph contrast learning
188. Liu, L.; Zeng, W.; Tan, Z.; Xiao, W.; Zhao, X. Node importance estimation with multiview contrastive representation learning. Int. J. Intell. Syst. 2023, 2023, 5917750.

189. Zhang, T.; Hou, C.; Jiang, R.; et al. Label informed contrastive pretraining for node importance estimation on knowledge graphs. IEEE. Trans. Neural. Networks. Learn. Syst. 2025, 36, 4462-76.

190. Shu, J.; Zou, Y.; Cui, H.; Liu, L. Node importance evaluation in heterogeneous network based on attention mechanism and graph contrastive learning. Neurocomputing 2025, 626, 129555.

#### 5.7 Graph neural networks
191. Huang, C.; Fang, Y.; Lin, X.; et al. Estimating node importance values in heterogeneous information networks. In: 2022 IEEE 38th International Conference on Data Engineering; 2022. pp. 846-58.

192. Chen, Y.; Fang, Y.; Wang, Q.; Cao, X.; King, I. Deep structural knowledge exploitation and synergy for estimating node importance value on heterogeneous information networks. In: Proceedings of the AAAI Conference on Artificial Intelligence; 2024. pp. 8302-10.

193. Lin, X.; Zhang, T.; Hou, C.; et al. Node importance estimation leveraging LLMs for semantic augmentation in knowledge graphs. arXiv 2024.

194. Zhao, X.; Yu, H.; Huang, R.; et al. A novel higher-order neural network framework based on motifs attention for identifying critical nodes. Phys. A. 2023, 629, 129194.

195. Michos, I.; Neocleous, K.; Papadopoulou Lesta, V. Critical node detection in sparse graphs using hopfield neural networks. In Proceedings of the 13th Hellenic Conference on Artificial Intelligence; 2024. pp. 1-4.


#### 5.7 Reinforcement learning

196. Fan, C.; Zeng, L.; Sun, Y.; Liu, Y. Finding key players in complex networks through deep reinforcement learning. Nat. Mach. Intell. 2020, 2, 317-24.

 
197. Tan, X.; Zhou, Y.; Zhou, M.; Fu, Z. Learning to detect critical nodes in sparse graphs via feature importance awareness. IEEE. Trans. Autom. Sci. Eng. 2024, 22, 3772-82.

198. Jaques, N.; Lazaridou, A.; Hughes, E.; et al. Social influence as intrinsic motivation for multi-agent deep reinforcement learning. In: International Conference on Machine Learning; 2019. pp. 3040-49. Available from: https://proceedings.mlr.press/v97/jaques19a.html[Last accessed on 10 Jul 2025].

199. Chen, P.; Fan, W. Identifying critical nodes via link equations and deep reinforcement learning. Neurocomputing 2023, 126871.

200. Li, H.; Xu, M.; Bhowmick, S. S.; et al. Disco: influence maximization meets network embedding and deep learning. arXiv 2019.

201. Chen, T.; Yan, S.; Guo, J.; Wu, W. ToupleGDD: a fine-designed solution of influence maximization by deep reinforcement learning. IEEE. Trans. Comput. Soc. Syst. 2023, 11, 2210-21.

202. Ling, C.; Jiang, J.; Wang, J.; et al. Deep graph representation learning and optimization for influence maximization. arXiv 2023.

203. Li, H.; Xu, M.; Bhowmick, S. S.; et al. PIANO: influence maximization meets deep reinforcement learning. IEEE. Trans. Comput. Soc. Syst. 2022, 10, 1288-300.

204. Uthayasuriyan, A.; Chandran, G. H.; Kavvin, U. V.; Mahitha, S. H.; Jeyakumar, G. Adaptive hybridization of differential evolution and DQN-reinforcement learning to solve the influence maximization problem in social networks. Int. J. Intell. Eng. Syst. 2024, 17, 109-25.

205. Li, F.; Xu, Z.; Cheng, D.; Wang, X. AdaRisk: risk-adaptive deep reinforcement learning for vulnerable nodes detection. IEEE. Trans. Knowl. Data. Eng. 2024, 36, 5576-90.

206. Xu, L.; Ma, L.; Lin, Q.; et al. Influence maximization in hypergraphs based on evolutionary deep reinforcement learning. Inf. Sci. 2025, 698, 121764.

207. Zhu, W.; Zhang, K.; Zhong, J.; Hou, C.; Ji, J. BiGDN: an end-to-end influence maximization framework based on deep reinforcement learning and graph neural networks. Expert. Syst. Appl. 2025, 270, 126384.

208. Ahmad, W.; Wang, B. A learning-based influence maximization framework for complex networks via K-core hierarchies and reinforcement learning. Expert. Syst. Appl. 2025, 259, 125393.














### 6. Comprehensive index-based Ranking Methods



#### 6.1 K-shell decomposition




#### 6.2 K-shell decomposition




#### 6.3 K-shell decomposition






### 7. Comprehensive index-based Ranking Methods



#### 7.1 K-shell decomposition




#### 7.2 K-shell decomposition




#### 7.3 K-shell decomposition


 