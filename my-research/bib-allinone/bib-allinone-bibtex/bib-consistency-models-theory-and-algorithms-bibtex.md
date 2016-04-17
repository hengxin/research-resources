# Bibs on Consistency Models: Theory and Algorithms (BibTex)

## Framework
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

- [[Lamport@Dc'86:2]](http://link.springer.com/article/10.1007%2FBF01786228)
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
@inproceedings{Lynch:1997:RES:795670.796859,
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

- [[SWPL@SIAM J. Comput.'11]](http://dl.acm.org/citation.cfm?id=2078669)
```
@article{Shao11,
 author = {Shao, Cheng and Welch, Jennifer L. and Pierce, Evelyn and Lee, Hyunyoung},
 title = {Multiwriter Consistency Conditions for Shared Memory Registers},
 journal = {SIAM J. Comput.},
 volume = {40},
 number = {1},
 month = jan,
 year = {2011},
 pages = {28--62},
 numpages = {35},
}
```

## Computability and Complexity

### Computability of Registers
- [[DS@SIAM J. Comput.'97]](http://dl.acm.org/citation.cfm?id=249364.249372)
```
@article{Dolev:1997:BCT:249364.249372,
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
