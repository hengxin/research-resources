# Bibs on Consistency Models: Theory and Algorithms (BibTex)

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
 issue_date = {July 2016},
 volume = {49},
 number = {1},
 month = jun,
 year = {2016},
 issn = {0360-0300},
 pages = {19:1--19:34},
 articleno = {19},
 numpages = {34},
 url = {http://doi.acm.org/10.1145/2926965},
 publisher = {ACM},
} 
```
- [[Aguilera@TCDE16]](http://sites.computer.org/debull/A16mar/p3.pdf)
```
@article{aguilera:tcde16,
  author = {Aguilera, Marcos K. and Terry, Douglas B.},
  title = {The Many Faces of Consistency},
  journal = {Bulletin of the IEEE Computer Society Technical Committee on Data Engineering (TCDE '16)},
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
