# Distributed Shared Memory

## Concepts

### Computer Architecture
- [The DOSMOS project](http://perso.ens-lyon.fr/laurent.lefevre/DOSMOS/DSM.html)
```
A distributed shared memory is a mechanism allowing end-users' processes to access shared data 
without using inter-process communications.
```

- [Thesis96: Mechanisms for Distributed Shared Memory](ftp://ftp.cs.wisc.edu/wwt/theses/reinhardt-2side.pdf)
```
Two prevalent types of distributed-memory machines — message passing and distributed shared memory — handle 
these tasks in markedly different ways.
```
```
In contrast, distributed shared memory (DSM) systems distribute and communicate data automatically. 
These systems provide the abstraction of one global, uniformly fast memory.
```
```
I identify three mechanisms that underlie nearly all DSM systems: messaging, local storage management,
and memory access control.
```

- Paper: Distributed Shared Memory: Concepts and Systems

### Distributed Systems (and Particularly, Distributed Storage Systems)
- [CACM14: Implementing Distributed Shared Memory for Dynamic Networks](http://cacm.acm.org/magazines/2014/6/175173-implementing-distributed-shared-memory-for-dynamic-networks/fulltext#R30)
```
A distributed shared memory service emulates a shared memory space comprised of 
readable and writable objects (often called registers) over a networked platform 
consisting of distributed network nodes that communicate by message passing.
```

### Database Systems

### 

### General
- Paper: A Suite Of Formal Definitions For Consistency Criteria In Distributed Shared Memories
```
Numerous protocols implementing a DSM on top of a distributed memory parallel machine 
or on top of a distributed system have been proposed. References [29] and [30] survey systems 
offering a DSM to their users
```

## Systems

## Related Concepts and Systems

### Tuple Space
- [Tuple Space Middleware for Wireless Networks](http://research.microsoft.com/en-us/um/people/pcosta/papers/costa09tuple.pdf)
```
The following outlines the main tuple space approaches developed for mobile settings: 
TSpaces, L^{2}imbo, LIME, EgoSpaces, and TOTA.
```
