# Bibs All-In-One (in BibTeX)

## Computability and Complexity

### Computability of Registers

- [[Taubenfeld@ICDCN'13]](http://link.springer.com/chapter/10.1007%2F978-3-642-35668-1_29)
```
@inproceedings{Taubenfeld13,
  author    = {Gadi Taubenfeld},
  title     = {Weak Read/Write Registers},
  booktitle = {Proceedings of the 14th International Conference on Distributed Computing and Networking},
  pages     = {423--427},
  year      = {2013},
}
```

## The Consensus Problem

- [[FL@IPL'82]](http://www.sciencedirect.com/science/article/pii/0020019082900333)
```
@article{Fischer82,
author = {Michael J. Fischer and Nancy A. Lynch},
title = {A lower bound for the time to assure interactive consistency},
journal = {Information Processing Letters},
volume = {14},
number = {4},
pages = {183 - 186},
year = {1982},
}
```

- [[Lamport@FDiDC]](http://dl.acm.org/citation.cfm?id=1809321)
```
@incollection{Lamport03,
 author = {Lamport, Leslie},
 chapter = {Lower Bounds for Asynchronous Consensus},
 title = {Future Directions in Distributed Computing},
 editor = {Schiper, Andr{\'e} and Shvartsman, Alex A. and Weatherspoon, Hakim and Zhao, Ben Y.},
 year = {2003},
 pages = {22--23},
 publisher = {Springer-Verlag},
}
```

## Quorum Systems
- [[Thomas@TODS'79]](http://dl.acm.org/citation.cfm?id=320076)
```
@article{Thomas:1979:MCA:320071.320076,
 author = {Thomas, Robert H.},
 title = {A Majority Consensus Approach to Concurrency Control for Multiple Copy Databases},
 journal = {ACM Trans. Database Syst.},
 volume = {4},
 number = {2},
 month = jun,
 year = {1979},
 pages = {180--209},
 publisher = {ACM},
} 
```

## Consistency Models

### Timed Consistency Models

- [[SRH@SPAA'97]](http://dl.acm.org/citation.cfm?id=258513)
```
@inproceedings{Singla-SPAA97,
 author = {Singla, Aman and Ramachandran, Umakishore and Hodgins, Jessica},
 title = {Temporal Notions of Synchronization and Consistency in Beehive},
 booktitle = {Proceedings of the Ninth Annual ACM Symposium on Parallel Algorithms and Architectures},
 series = {SPAA '97},
 year = {1997},
 pages = {211--220},
 publisher = {ACM},
}
```

### Consistency/Latency Tradeoff
- [[TPKBAA@SOSP'13]](http://dl.acm.org/citation.cfm?id=2522731)
```
@inproceedings{Terry13,
 author = {Terry, Douglas B. and Prabhakaran, Vijayan and Kotla, Ramakrishna and Balakrishnan, Mahesh and Aguilera, Marcos K. and Abu-Libdeh, Hussam},
 title = {Consistency-based Service Level Agreements for Cloud Storage},
 booktitle = {Proceedings of the Twenty-Fourth ACM Symposium on Operating Systems Principles},
 series = {SOSP '13},
 year = {2013},
 pages = {309--324},
 publisher = {ACM},
}
```

- [[MFG@Big Data'15]](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7363942)
```
@inproceedings{McKenzieFG15,
  author    = {Marlon McKenzie and
               Hua Fan and
               Wojciech M. Golab},
  title     = {Fine-tuning the consistency-latency trade-off in quorum-replicated
               distributed storage systems},
  booktitle = {2015 {IEEE} International Conference on Big Data, Big Data 2015, Santa
               Clara, CA, USA, October 29 - November 1, 2015},
  pages     = {1708--1717},
  year      = {2015},
  publisher = {IEEE},
}
```

- [[BKTM@CLOUD'11]](http://dl.acm.org/citation.cfm?id=2055544)
```
@inproceedings{Bermbach11,
 author = {Bermbach, David and Klems, Markus and Tai, Stefan and Menzel, Michael},
 title = {MetaStorage: A Federated Cloud Storage System to Manage Consistency-Latency Tradeoffs},
 booktitle = {Proceedings of the 2011 IEEE 4th International Conference on Cloud Computing},
 series = {CLOUD '11},
 year = {2011},
 pages = {452--459},
 publisher = {IEEE Computer Society},
}
```

### Benchmarking Consistency Models

#### Verifying

- [[GLS@PODC'11]](http://dl.acm.org/citation.cfm?id=1993834&CFID=583993644&CFTOKEN=80708905)
```
@inproceedings{Golab11,
 author = {Golab, Wojciech and Li, Xiaozhou and Shah, Mehul A.},
 title = {Analyzing Consistency Properties for Fun and Profit},
 booktitle = {Proceedings of the 30th Annual ACM SIGACT-SIGOPS Symposium on Principles of Distributed Computing},
 series = {PODC '11},
 year = {2011},
 pages = {197--206},
 publisher = {ACM},
}
```

- [[GHL@ICDCS'13]](http://dl.acm.org/citation.cfm?id=2549701&CFID=583993644&CFTOKEN=80708905)
```
@inproceedings{Golab13,
 author = {Golab, Wojciech and Hurwitz, Jeremy and Li, Xiaozhou (Steve)},
 title = {On the k-Atomicity-Verification Problem},
 booktitle = {Proceedings of the 2013 IEEE 33rd International Conference on Distributed Computing Systems},
 series = {ICDCS '13},
 year = {2013},
 pages = {591--600},
 publisher = {IEEE Computer Society},
}
```

-[[GRAKG@ICDCS'14]](http://dl.acm.org/citation.cfm?id=2672698&CFID=583993644&CFTOKEN=80708905)
```
@inproceedings{Golab14,
 author = {Golab, Wojciech and Rahman, Muntasir Raihan and Auyoung, Alvin and Keeton, Kimberly and Gupta, Indranil},
 title = {Client-Centric Benchmarking of Eventual Consistency for Cloud Storage Systems},
 booktitle = {Proceedings of the 2014 IEEE 34th International Conference on Distributed Computing Systems},
 series = {ICDCS '14},
 year = {2014},
 pages = {493--502},
 publisher = {IEEE Computer Society},
}
```

- [[GLLN@PODC'15]](http://dl.acm.org/citation.cfm?id=2767407&CFID=583993644&CFTOKEN=80708905)
```
@inproceedings{Golab15,
 author = {Golab, Wojciech and Li, Xiaozhou (Steve) and L\'{o}pez-Ortiz, Alejandro and Nishimura, Naomi},
 title = {Computing Weak Consistency in Polynomial Time: [Extended Abstract]},
 booktitle = {Proceedings of the 2015 ACM Symposium on Principles of Distributed Computing},
 series = {PODC '15},
 year = {2015},
 pages = {395--404},
 publisher = {ACM},
}
```

#### Quantifying

#### Monitoring

## Distributed Systems

### Distributed Storage Systems

- [[Google@OSDI'06]](http://dl.acm.org/citation.cfm?id=1267323)  % Google's Bigtable
```
@inproceedings{Google06,
 author = {Chang, Fay and Dean, Jeffrey and Ghemawat, Sanjay and Hsieh, Wilson C. and Wallach, Deborah A. and Burrows, Mike and Chandra, Tushar and Fikes, Andrew and Gruber, Robert E.},
 title = {Bigtable: A Distributed Storage System for Structured Data},
 booktitle = {Proceedings of the 7th USENIX Symposium on Operating Systems Design and Implementation - Volume 7},
 series = {OSDI '06},
 year = {2006},
 pages = {205-218},
 publisher = {USENIX Association},
} 
```

- [[Amazon@SOSP'07]](http://dl.acm.org/citation.cfm?id=1294281) % Amazon's Dynamo
```
@inproceedings{DeCandia:2007:DAH:1294261.1294281,
 author = {DeCandia, Giuseppe and Hastorun, Deniz and Jampani, Madan and Kakulapati, Gunavardhan and Lakshman, Avinash and Pilchin, Alex and Sivasubramanian, Swaminathan and Vosshall, Peter and Vogels, Werner},
 title = {Dynamo: Amazon's Highly Available Key-value Store},
 booktitle = {Proceedings of Twenty-first ACM SIGOPS Symposium on Operating Systems Principles},
 series = {SOSP '07},
 year = {2007},
 pages = {205--220},
 publisher = {ACM},
}
```

- [[LM@SIGOPS OSR'10]](http://dl.acm.org/citation.cfm?id=1773922)
```
@article{Lakshman20,
 author = {Lakshman, Avinash and Malik, Prashant},
 title = {Cassandra: A Decentralized Structured Storage System},
 journal = {SIGOPS Oper. Syst. Rev.},
 volume = {44},
 number = {2},
 month = apr,
 year = {2010},
 pages = {35--40},
 publisher = {ACM},
}
```

- [[Microsoft@SOSP'11]](http://dl.acm.org/citation.cfm?id=2043571)  % Microsoft's WAS
```
@inproceedings{Microsoft11,
 author = {Calder, Brad and Wang, Ju and Ogus, Aaron and Nilakantan, Niranjan and Skjolsvold, Arild and McKelvie, Sam and Xu, Yikang and Srivastav, Shashwat and Wu, Jiesheng and Simitci, Huseyin and Haridas, Jaidev and Uddaraju, Chakravarthy and Khatri, Hemal and Edwards, Andrew and Bedekar, Vaman and Mainali, Shane and Abbasi, Rafay and Agarwal, Arpit and Haq, Mian Fahim ul and Haq, Muhammad Ikram ul and Bhardwaj, Deepali and Dayanand, Sowmya and Adusumilli, Anitha and McNett, Marvin and Sankaran, Sriram and Manivannan, Kavitha and Rigas, Leonidas},
 title = {Windows Azure Storage: A Highly Available Cloud Storage Service with Strong Consistency},
 booktitle = {Proceedings of the Twenty-Third ACM Symposium on Operating Systems Principles},
 series = {SOSP '11},
 year = {2011},
 pages = {143--157},
 publisher = {ACM},
}
```

- [[Google@OSDI'12]](http://dl.acm.org/citation.cfm?id=2491245)  % Google's Spanner
```
@inproceedings{Google12,
 author = {Corbett, James C. and Dean, Jeffrey and Epstein, Michael and Fikes, Andrew and Frost, Christopher and Furman, J. J. and Ghemawat, Sanjay and Gubarev, Andrey and Heiser, Christopher and Hochschild, Peter and Hsieh, Wilson and Kanthak, Sebastian and Kogan, Eugene and Li, Hongyi and Lloyd, Alexander and Melnik, Sergey and Mwaura, David and Nagle, David and Quinlan, Sean and Rao, Rajesh and Rolig, Lindsay and Saito, Yasushi and Szymaniak, Michal and Taylor, Christopher and Wang, Ruth and Woodford, Dale},
 title = {Spanner: Google's Globally-distributed Database},
 booktitle = {Proceedings of the 10th USENIX Conference on Operating Systems Design and Implementation},
 series = {OSDI'12},
 year = {2012},
 pages = {251--264},
 publisher = {USENIX Association},
}
```

### Consistency Models in Distributed Storage Systems

- [[Vogels@CACM'09]](http://dl.acm.org/citation.cfm?id=1435432)
```
@article{Vogels09,
 author = {Vogels, Werner},
 title = {Eventually Consistent},
 journal = {Commun. ACM},
 volume = {52},
 number = {1},
 month = jan,
 year = {2009},
 pages = {40--44},
 publisher = {ACM},
}
```

- [[Terry@CACM'13]](http://dl.acm.org/citation.cfm?id=2534706.2500500&coll=portal&dl=ACM)
```
@article{Terry13-cacm,
 author = {Terry, Doug},
 title = {Replicated Data Consistency Explained Through Baseball},
 journal = {Commun. ACM},
 volume = {56},
 number = {12},
 month = dec,
 year = {2013},
 pages = {82--89},
 publisher = {ACM},
}
```

## Distributed Transactions

### Commit Protocols
- [[NAAA@SIGMOD'15]](http://dl.acm.org/citation.cfm?doid=2723372.2723729)
```
@inproceedings{Nawab15,
 author = {Nawab, Faisal and Arora, Vaibhav and Agrawal, Divyakant and El Abbadi, Amr},
 title = {Minimizing Commit Latency of Transactions in Geo-Replicated Data Stores},
 booktitle = {Proceedings of the 2015 ACM SIGMOD International Conference on Management of Data},
 series = {SIGMOD '15},
 year = {2015},
 pages = {1279--1294},
 publisher = {ACM},
}
```
