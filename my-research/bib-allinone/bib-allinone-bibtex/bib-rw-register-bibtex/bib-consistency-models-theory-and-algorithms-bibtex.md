# Bibs on Consistency Models: Theory and Algorithms (BibTex)

## Distributed Shared Memory (DSM)

- [[LH@TOCS'89]; DSM](http://dl.acm.org/citation.cfm?id=75105)
```
@article{li:tocs89,
  author = {Li, Kai and Hudak, Paul},
  title = {Memory Coherence in Shared Virtual Memory Systems},
  journal = {ACM Trans. Comput. Syst.},
  volume = {7},
  number = {4},
  month = nov,
  year = {1989},
  pages = {321--359},
  url = {http://doi.acm.org/10.1145/75104.75105},
  publisher = {ACM},
}
```

## Frameworks of Consistency Models
- [[SN@JACM'04]](http://dl.acm.org/citation.cfm?id=1017464)
```
@article{Steinke04,
  author = {Steinke, Robert C. and Nutt, Gary J.},
  title = {A Unified Theory of Shared Memory Consistency},
  journal = {J. ACM},
  volume = {51},
  number = {5},
  month = sep,
  year = {2004},
  pages = {800--849},
  numpages = {50},
  publisher = {ACM},
}
```

- [[Viotti@CSUR16]](http://doi.acm.org/10.1145/2926965)
```
@article{viotti:csur16,
 author = {Viotti, Paolo and Vukoli\'{c}, Marko},
 title = {Consistency in Non-Transactional Distributed Storage Systems},
 journal = {ACM Comput. Surv.},
 volume = {49},
 number = {1},
 month = jun,
 year = {2016},
 pages = {19:1--19:34},
 articleno = {19},
 numpages = {34},
 url = {http://doi.acm.org/10.1145/2926965},
 publisher = {ACM},
} 
```

- [[Aguilera@TCDE16]](http://sites.computer.org/debull/A16mar/p3.pdf)
```
% journal = {Bulletin of the IEEE Computer Society Technical Committee on Data Engineering (TCDE '16)},
@article{aguilera:tcde16,
  author = {Aguilera, Marcos K. and Terry, Douglas B.},
  title = {The Many Faces of Consistency},
  journal   = {{IEEE} Data Eng. Bull.},
  volume = {39},
  number = {1},
  month = mar,
  year = {2016},
  pages = {3--13},
}
```

## Consistency Models (in chronological order)

### Sequential consistency
- [[Lamport@TC'79]](http://research.microsoft.com/en-us/um/people/lamport/pubs/multi.pdf)
```
@article{Lamport79,
 author = {Lamport, L.},
 title = {How to Make a Multiprocessor Computer That Correctly Executes Multiprocess Programs},
 journal = {IEEE Trans. Comput.},
 volume = {28},
 number = {9},
 year = {1979},
 pages = {690--691},
 url = {http://dx.doi.org/10.1109/TC.1979.1675439},
 publisher = {IEEE Computer Society},
}
```

## Atomicity

- [[Lamport@DC'86:1]](http://link.springer.com/article/10.1007%2FBF01786227)
```
@article{interprocess-Lamport86-dc,
  author = {Lamport, Leslie},
  title = {On interprocess communication (Part I: Basic formalism)},
  journal = {Distrib. Comput.},
  volume = {1},
  number = {2},
  year = {1986},
  pages = {77--85},
}
```

- [[Lamport@DC'86:2]](http://link.springer.com/article/10.1007%2FBF01786228)
```
@article{interprocess-Lamport86-dc,
  author = {Lamport, Leslie},
  title = {On interprocess communication (Part II: Algorithms)},
  journal = {Distrib. Comput.},
  volume = {1},
  number = {2},
  year = {1986},
  pages = {86--101},
}
```

- [[ABD@JACM'95]](http://dl.acm.org/citation.cfm?id=200869)
```
@article{Attiya95,
 author = {Attiya, Hagit and Bar-Noy, Amotz and Dolev, Danny},
 title = {Sharing Memory Robustly in Message-passing Systems},
 journal = {J. ACM},
 volume = {42},
 number = {1},
 month = jan,
 year = {1995},
 pages = {124--142},
 numpages = {19},
 publisher = {ACM},
}
```

- [[LS@FTCS'97]](http://dl.acm.org/citation.cfm?id=795670.796859)
```
@inproceedings{Lynch97,
 author = {Lynch, N. A. and Shvartsman, A. A.},
 title = {Robust Emulation of Shared Memory Using Dynamic Quorum-acknowledged Broadcasts},
 booktitle = {Proceedings of the 27th International Symposium on Fault-Tolerant Computing (FTCS '97)},
 series = {FTCS '97},
 year = {1997},
 pages = {272--},
 publisher = {IEEE Computer Society},
}
```

- [[Attiya@EATCS'10]](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.154.6450)
```
@article{Attiya10,
title = {Robust Simulation of Shared Memory: 20 Years After.},
author = {Attiya, Hagit},
journal = {Bulletin of the {EATCS}},
volume = 100,
pages = {99-113},
year = 2010,
}
```

## PRAM
- [[Lipton@TR'88]](https://www.cs.princeton.edu/research/techreps/TR-180-88)
```
@techreport{Lipton88,
  author = {Lipton, R.J. and Sandberg, J.S.},
  title = {{PRAM}: a scalable shared memory},
  month = sep,
  year = {1988},
  institution = {CS-TR-180-88, Princeton University},
}
```

- [[Ahamad@SPAA'93]](http://doi.acm.org/10.1145/165231.165264)
```
@inproceedings{ahamad:spaa93,
 author = {Ahamad, Mustaque and Bazzi, Rida A. and John, Ranjit and Kohli, Prince and Neiger, Gil},
 title = {The Power of Processor Consistency},
 booktitle = {Proceedings of the Fifth Annual ACM Symposium on Parallel Algorithms and Architectures},
 series = {SPAA '93},
 year = {1993},
 pages = {251--260},
 url = {http://doi.acm.org/10.1145/165231.165264},
 publisher = {ACM},
} 
```

## Linearizability
- [[HW@TOPLAS'90]](http://dl.acm.org/citation.cfm?id=78972)
```
@article{Herlihy90,
 author = {Herlihy, Maurice P. and Wing, Jeannette M.},
 title = {Linearizability: A Correctness Condition for Concurrent Objects},
 journal = {ACM Trans. Program. Lang. Syst.},
 volume = {12},
 number = {3},
 month = jul,
 year = {1990},
 pages = {463--492},
 publisher = {ACM},
}
```

## Regular

- [[Shao@SIAM J. Comput.'11]](http://dl.acm.org/citation.cfm?id=2078669)
```
@article{shao:sicomp11,
 author = {Shao, Cheng and Welch, Jennifer L. and Pierce, Evelyn and Lee, Hyunyoung},
 title = {Multiwriter Consistency Conditions for Shared Memory Registers},
 journal = {SIAM J. Comput.},
 volume = {40},
 number = {1},
 month = jan,
 year = {2011},
 pages = {28--62},
}
```

% attiya:sicomp98
- [[Attiya@SIAM J. Comput.'98]](http://epubs.siam.org/doi/abs/10.1137/S0097539795289215)
```
@article{attiya:sicomp98,
  author = {Hagit Attiya and Roy Friedman},
  title = {A Correctness Condition for High-Performance Multiprocessors},
  journal = {SIAM Journal on Computing},
  volume = {27},
  number = {6},
  pages = {1637-1670},
  year = {1998},
}
```

## Synchronized Consistency Models

- [[Dubois@IEEE Computer'88]; Weak Ordering](http://dl.acm.org/citation.cfm?id=44837)
```
@article{dubois:ieee-computer88,
 author = {Dubois, Michel and Scheurich, Christoph and Briggs, Fay{\'e} A.},
 title = {Synchronization, Coherence, and Event Ordering in Multiprocessors},
 journal = {Computer},
 volume = {21},
 number = {2},
 month = feb,
 year = {1988},
 pages = {9--21},
 url = {http://dx.doi.org/10.1109/2.15},
 publisher = {IEEE Computer Society Press},
} 
```

- [[Adve@ISCA'90]; Weak Ordering](http://dl.acm.org/citation.cfm?id=325100)
```
@inproceedings{adve:isca90,
 author = {Adve, Sarita V. and Hill, Mark D.},
 title = {Weak Ordering\&Mdash;a New Definition},
 booktitle = {Proceedings of the 17th Annual International Symposium on Computer Architecture},
 series = {ISCA '90},
 year = {1990},
 pages = {2--14},
 url = {http://doi.acm.org/10.1145/325164.325100},
 publisher = {ACM},
} 
```

- [[Gharachorloo@ISCA'90]; Release Consistency](http://dl.acm.org/citation.cfm?id=325102)
```
@inproceedings{gibbons:isca90,
 author = {Gharachorloo, Kourosh and Lenoski, Daniel and Laudon, James and Gibbons, Phillip and Gupta, Anoop and Hennessy, John},
 title = {Memory Consistency and Event Ordering in Scalable Shared-memory Multiprocessors},
 booktitle = {Proceedings of the 17th Annual International Symposium on Computer Architecture},
 series = {ISCA '90},
 year = {1990},
 pages = {15--26},
 url = {http://doi.acm.org/10.1145/325164.325102},
 publisher = {ACM},
} 
```

- [[Gibbons@SPAA'91]; Release Consistency](http://dl.acm.org/citation.cfm?id=113406)
```
@inproceedings{gibbons:spaa91,
 author = {Gibbons, Phillip B. and Merritt, Michael and Gharachorloo, Kourosh},
 title = {Proving Sequential Consistency of High-performance Shared Memories (Extended Abstract)},
 booktitle = {Proceedings of the Third Annual ACM Symposium on Parallel Algorithms and Architectures},
 series = {SPAA '91},
 year = {1991},
 pages = {292--303},
 url = {http://doi.acm.org/10.1145/113379.113406},
 publisher = {ACM},
} 
```

- [[Bershad@TR91]; Entry Consistency](http://dl.acm.org/citation.cfm?id=865207)
```
@techreport{bershad:tr91,
 author = {Bershad, Brian N. and Zekauskas, Matthew J. and Sawdon, Wayne A.},
 title = {The Midway Distributed Shared Memory System},
 year = {1993},
 source = {\url{http://www.ncstrl.org:8900/ncstrl/servlet/search?formname=detail\&id=oai\%3Ancstrlh\%3Acmucs\%3ACMU\%2F\%2FCS-93-119}},
 publisher = {Carnegie Mellon University},
 address = {Pittsburgh, PA, USA},
} 
```

- [[Agrawal@PODC'94]; Mixed Consistency](http://dl.acm.org/citation.cfm?id=197967)
```
@inproceedings{agrawal:podc94,
 author = {Agrawal, Divyakant and Choy, Manhoi and Va Leong, Hong and Singh, Ambuj K.},
 title = {Mixed Consistency: A Model for Parallel Programming (Extended Abstract)},
 booktitle = {Proceedings of the Thirteenth Annual ACM Symposium on Principles of Distributed Computing},
 series = {PODC '94},
 year = {1994},
 pages = {101--110},
 url = {http://doi.acm.org/10.1145/197917.197967},
 publisher = {ACM},
} 
```

- [[Iftode@SPAA'96]; Scope Consistency](http://dl.acm.org/citation.cfm?id=237567)
```
@inproceedings{iftode:spaa96,
 author = {Iftode, Liviu and Singh, Jaswinder Pal and Li, Kai},
 title = {Scope Consistency: A Bridge Between Release Consistency and Entry Consistency},
 booktitle = {Proceedings of the Eighth Annual ACM Symposium on Parallel Algorithms and Architectures},
 series = {SPAA '96},
 year = {1996},
 pages = {277--287},
 url = {http://doi.acm.org/10.1145/237502.237567},
 publisher = {ACM},
} 
```

## Multi-level Consistency Models

- [[Ladin@TOCS'92]; Lazy Replication](http://dl.acm.org/citation.cfm?id=138877)
```
@article{ladin:tocs92,
 author = {Ladin, Rivka and Liskov, Barbara and Shrira, Liuba and Ghemawat, Sanjay},
 title = {Providing High Availability Using Lazy Replication},
 journal = {ACM Trans. Comput. Syst.},
 volume = {10},
 number = {4},
 month = nov,
 year = {1992},
 pages = {360--391},
 url = {http://doi.acm.org/10.1145/138873.138877},
 publisher = {ACM},
} 
```

- [[Fekete@TCS'99]; Eventually Serializable](http://dl.acm.org/citation.cfm?id=310279)
```
@article{fekete:tcs99,
 author = {Fekete, Alan and Gupta, David and Luchangco, Victor and Lynch, Nancy and Shvartsman, Alex},
 title = {Eventually-serializable Data Services},
 journal = {Theor. Comput. Sci.},
 volume = {220},
 number = {1},
 month = jun,
 year = {1999},
 pages = {113--156},
 url = {http://dx.doi.org/10.1016/S0304-3975(98)00239-4},
 publisher = {Elsevier Science Publishers Ltd.},
} 
```

- [[Yu@TOCS'02]; Continuous Consistency](http://dl.acm.org/citation.cfm?id=566342)
```
@article{yu:tocs02,
 author = {Yu, Haifeng and Vahdat, Amin},
 title = {Design and Evaluation of a Conit-based Continuous Consistency Model for Replicated Services},
 journal = {ACM Trans. Comput. Syst.},
 volume = {20},
 number = {3},
 month = aug,
 year = {2002},
 pages = {239--282},
 url = {http://doi.acm.org/10.1145/566340.566342},
 publisher = {ACM},
} 
```

- [[Krishnamurthy@DSN'02]; probabilistic partial quorum system](http://dl.acm.org/citation.cfm?id=738266)
```
@inproceedings{krishnamurthy:dsn02,
 author = {Krishnamurthy, Sudha and Sanders, William H. and Cukier, Michel},
 title = {An Adaptive Framework for Tunable Consistency and Timeliness Using Replication},
 booktitle = {Proceedings of the 2002 International Conference on Dependable Systems and Networks},
 series = {DSN '02},
 year = {2002},
 pages = {17--26},
 url = {http://dl.acm.org/citation.cfm?id=647883.738266},
 publisher = {IEEE Computer Society},
} 
```

- [[zhan:icdcs05]; Mixed Consistency](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.259.3993)
```
@inproceedings{zhan:icdcs05,
  author = {Zhiyuan Zhan and Mustaque Ahamad and Michel Raynal},
  title = {Mixed Consistency Model: Meeting Data Sharing Needs of Heterogeneous Users},
  booktitle = {Proc. 25th IEEE Int. Conference on Distributed Computing Systems (ICDCS’05), IEEE Computer},
  year = {2005},
  pages = {209--218},
  publisher = {Society Press}
}
```

- [[Li@OSDI'12]; RedBlue Consistency](http://dl.acm.org/citation.cfm?id=2387906)
```
@inproceedings{li:osdi12,
 author = {Li, Cheng and Porto, Daniel and Clement, Allen and Gehrke, Johannes and Pregui\c{c}a, Nuno and Rodrigues, Rodrigo},
 title = {Making Geo-replicated Systems Fast As Possible, Consistent when Necessary},
 booktitle = {Proceedings of the 10th USENIX Conference on Operating Systems Design and Implementation},
 series = {OSDI'12},
 year = {2012},
 pages = {265--278},
 url = {http://dl.acm.org/citation.cfm?id=2387880.2387906},
 publisher = {USENIX Association},
} 
```

- [[McKenzie@Big Data'15]; Continuous Consistency Models](http://dl.acm.org/citation.cfm?id=2878255)
```
@inproceedings{mckenzie:bigdata15,
 author = {McKenzie, Marlon and Fan, Hua and Golab, Wojciech},
 title = {Fine-tuning the Consistency-latency Trade-off in Quorum-replicated Distributed Storage Systems},
 booktitle = {Proceedings of the 2015 IEEE International Conference on Big Data (Big Data)},
 series = {BIG DATA '15},
 year = {2015},
 pages = {1708--1717},
 url = {http://dx.doi.org/10.1109/BigData.2015.7363942},
 publisher = {IEEE Computer Society},
} 
```

## Computability and Complexity

### Computability of Registers
- [[DS@SIAM J. Comput.'97]](http://dl.acm.org/citation.cfm?id=249364.249372)
```
@article{Dolev97,
 author = {Dolev, Danny and Shavit, Nir},
 title = {Bounded Concurrent Time-Stamping},
 journal = {SIAM J. Comput.},
 volume = {26},
 number = {2},
 month = apr,
 year = {1997},
 pages = {418--455},
 numpages = {38},
}
```

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

### Complexity of Registers
- [[DGLC@PODC'04]](http://dl.acm.org/citation.cfm?id=1011802)
```
@inproceedings{Dutta04,
 author = {Dutta, Partha and Guerraoui, Rachid and Levy, Ron R. and Chakraborty, Arindam},
 title = {How Fast Can a Distributed Atomic Read Be?},
 booktitle = {Proceedings of the Twenty-third Annual ACM Symposium on Principles of Distributed Computing},
 series = {PODC '04},
 year = {2004},
 pages = {236--245},
 numpages = {10},
 publisher = {ACM},
}
```

- [[GV@PODC'07]](http://dl.acm.org/citation.cfm?id=1281120)
```
@inproceedings{Guerraoui07,
 author = {Guerraoui, Rachid and Vukoli\'{C}, Marko},
 title = {Refined Quorum Systems},
 booktitle = {Proceedings of the Twenty-sixth Annual ACM Symposium on Principles of Distributed Computing},
 series = {PODC '07},
 year = {2007},
 pages = {119--128},
 numpages = {10},
 publisher = {ACM},
}
```

- [[GNS@DISC'08]](http://link.springer.com/chapter/10.1007%2F978-3-540-87779-0_20)
```
@inproceedings{Georgiou08,
 author = {Georgiou, Chryssis and Nicolaou, Nicolas C. and Shvartsman, Alexander A.},
 title = {On the Robustness of (Semi) Fast Quorum-Based Implementations of Atomic Shared Memory},
 booktitle = {Proceedings of the 22Nd International Symposium on Distributed Computing},
 series = {DISC '08},
 year = {2008},
 pages = {289--304},
 numpages = {16},
}
```