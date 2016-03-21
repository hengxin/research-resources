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
@inproceedings{Golab:2014:CBE:2672596.2672698,
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
