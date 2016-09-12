# Research Notes

## June 2016

### 2016-06-27

Relation between interval order (real-time relation) and locality

Mathematical (*axiomatic*) study on Lamport's "solid arrow" and "dashed arrow" model

### 2016-06-28

Further work on "Beyond Lamport's Logic Clock" (JACM)

### 2016-06-29

About Cassandra:
- Quantifying RWN w.r.t. Atomicity/Regular; single-writer vs. multi-writer
- Learning source code 

## July 2016

### 2016-07-02

Experiments on quantifying atomicity violations in PA2AM:
- An observation: long-lived writes are more likely to induce atomicity violations. 
Thus, optimize the write path is crucial to avoiding atomicity violations.
- An idea: carry out experiments with Cassandra
  - Cassandra's write path: commitlog -> memtable -> (*async*) ssttable
  - No *real* write in this write path!
- Reference: Understanding the Causes of Consistency Anomalies in Apache Cassandra, VLDB'15

### 2016-07-07 (Thu.)

- Cassandra projects:
  - products like Jinsan Kuaipan

- Replicated data structures:
  - Cassandra does not provide them.
    - Wrong! Cassandra supports *Collections*.
  - What is the consistency model of Redis' replicated data structures?

- Redis:
  - architecture?

### 2016-07-09 (Sat.)

- **paper-tc-2am-minor-revision:**
  - Numerical analysis: the rate of atomicity violations seems to have a *limiting value* as the number of clients increases.
  - Possible reason: It is the limit of the system capacity.
  - Thus, *limitation* is not always bad.

### 2016-07-11 (Mon.)

- About causality:
  - respect real-time orders of *w/r* and *r/r* to enhence liveness
  - what is strength of such consistency model (compared to causality)
  - real-time causality: implementation (ref: JACM'07)
  - semi-sync. causality (ref: beyond Lamport's clock)
  - the "bolt-on" paper
- About *availablity*:
  - multi-object availability: (ref: Haifeng YU)
  - new definition of "single object available"

### 2016-07-15 (Fri.)

- Are there semi-/partially- synchronous quorum systems?
- Simulating atomic shared memories under partial synchronous timing model
  - Is it possible to achieve fast writes and/or fast reads?
  - Algorithms
  - deployed in Cassandra

### 2016-07-16 (Sat.)

- **Ideas** about network partition models
  - blog article: The “network partitions are rare” fallacy
  - infer probabilistic partition info from probabilistic failure detectors
  - graph theory: generalized reachability; generalized scc
  - matrix theory: matrix blocks/clusters; **matrix decomposition**

### 2016-07-17 (Sun.)

- Weak CAP Principle: (from paper "Harvest, Yield, and Scalable Tolerant Systems")
  - The stronger the guarantees made about any two of *strong consistency, high availability, or resilience to partitions*, 
    the weaker the guarantees that can be made about the third.
  - **Research:** Mathematically analyze/quantify the trade-offs among *consistency, availability, and partition-tolerance* 
    in the context of the RWN protocol of Cassandra.

### 2016-07-18 (Mon.)

- Paper: "Don't Settle for Eventual Consistency"
  - intra-datacenters: implements linearizability
  - inter-datacenters: implements causal+ consistency
  - **Research:** 
    - implements real-time causal consistency defined in JACM'07
    - extends to transactional system:
      - intra-datacenters: implements SI or even SR
      - inter-datacenters: implements PSI or Monotonic SI (for scalability)
    - *TODO:*
      - tradeoffs in transactional systems (FIT for example)
      - scalability issues
- **Ideas** about Apache Cassandra
 - Cassandra relies on synchronized clocks of each clients to determine fresher values.
 - What about semi-synchronized timing model?
 - What about version clock?
- VPC problem:
 - generalize the Read-Centric algorithm to causality verification.

### 2016-07-19 (Tue.)

- Implement transactions on top of key-value stores
  - impossibility results???
  - consistency levels of underlying key-value stores vs. consistency levels of transactions

### 2016-07-20 (Wed.)

- Cache coherence vs. sequential consistency
  - consensus number theory?
  - impossibility results about implementing sequential consistency on top of cache coherence
  - single variable vs. multiple variables

### 2016-07-21 (Thu.)

- Infer partition model from failure model
  - probabilistic partition model from probabilistic failure detection information
  - paper "The Cost and Limits of Availability for Replicated Services" by H. Yu and A. Vahdat @ TOCS'06

    ```
    ... unlike replica failures, there is currently no convincing way to mathematically model the occurrences
    of network partitions. It is also NP-hard [Rosenthal 1977] to derive the partition model from link and node
    failure models.
    ```
  - ***Idea:*** using data mining technologies

### 2016-07-22 (Fri.)

- linearizable shared memory under partial synchronous timing model
  - idea: fast read + fast write; using (wall-clock, id) timestamp
  - paper: TOCS94, "Sequential consistency versus linearizability"
  - paper: arXiv16, "On Composition and Implementation of sequential consistency"

### 2016-07-23 (Sat.)

- ***Paper:*** Quantifying Isolation Anamolies
  - related blog: By Peter Bailis, ["Understanding Weak Isolation Is a Serious Problem"](http://www.bailis.org/blog/understanding-weak-isolation-is-a-serious-problem/)
    - QUOTED: `a PBS-style white-box probabilistic analysis of Postgres, MySQL, or another RDBMS could be enlightening`
  - ***Research:*** Quantifying snapshot isolation/read committed???

### 2016-07-25 (Mon.)

- Linear logic and session types
  - [abcd: A Basis for Concurrency and Distribution](http://groups.inf.ed.ac.uk/abcd/)

### 2016-07-27 (Wed.)

- ***paper:*** causal memory
  - some kinds of programs runs correctly on causal memory as on sequential memory
  - extend this idea to transactional programs

## August 2016

### 2016-08-03 (Wed.)

- Atomicity is a safety property; See [Lynch-Book-1996].
  - Are safe, regular, causality, (etc,) also safety properties?
  - What are the benefits of these consistency models as safety properties?

### 2016-08-04 (Thu.)

- ***Category theory:***
  - git
  - transactions (isolations)
  - commute digram (CRDTs?)

### 2016-08-08 (Mon.)

- About *quantifying consistency models*:
  - quantifying given traces; Golab
  - quantifying protocols: Quantifying eventual consistency; pa2am

- ***Research Idea:*** weaken "Atomicity" in ACID
  - CAV paper: Causal Atomicity
  - "Scalable visible atomicity" paper

### 2016-08-13 (Sat.)

- Verifying hybrid consistency
  - complexity
  - variants and algorithms
  - Question: harder than NP-Complete + (NP?)

### 2016-08-14 (Sun.)

- Verifying causal consistency
  - wrong: Wei@TPDS'16
  - complexity
  - relationship with hybrid consistency

- Unifying non-transactional with transactional consistency models
  - possible bridge: atomic visibility
  - possible bridge: hybrid consistency

### 2016-08-15 (Mon.)

- paper: From causal consistency to sequential consistency (by Raynal)
  - with JACM'04
  - with "bolt on causal consistency"
  - ***research idea:*** self configurable among 
	session guarantees, pram, causal consistency, sequential consistency
- paper: eventually serializable data services
  - ***research idea:*** extends to transactions
  - ref: eventually consistent transactions (MSR)

### 2016-08-18 (Thu.)

- ***research idea:*** Weaken program order
  - lessons from architecture
  - nonsequential execution (paper by Attiya)

- ***research idea:*** Weaken intra-transaction order

### 2016-08-19 (Fri.)

- ***research idea:*** new transactional consistency models
  - fork-join on read/write registers; extends to transactions
  - pull/pull model of git

### 2016-08-21 (Sun.)

- ***research idea:*** discounting modality in causality
  - ref: "Averaging in LTL" (CONCUR14); "Discounting in LTL" (arXiv14)
  - DAG: not a tree!

- ***research idea:*** implements a FileSync app on top of Cassandra (or others)
  - tree data structure + consistency models (eventual; causal; sequential)
  - File APIs: 
    - files: mv (including rename), rm, touch
    - dirs: ls, mv (including rename), rm, mkdir, cd
  - refs: attya@PODC16

### 2016-08-25 (Thu.)

- CAS, Test&Set, RMW
  - randomized
  - obstruction free
  - refs: "atomic visibility" (bailis@vldb)

- Between CAS and Transactional Objects
  - refs: k-CAS (spaa03)

### 2016-08-27 (Sat.)

- To learn ACP (atomic commitment protocol)
  - 2PC, 3PC, Paxos commit
- ACP under partial-sync. model

### 2016-08-28 (Sun.)

- Papers to read:
  - Kung&Papadimitriou: SIGMOD79 "An optimality theory of concurrency control for databases"
- ***research idea:***
  - query-guided data partitioning, data replication, consistency, availability
    - in Cassandra model
    - refs: "Vertical Partitioning Algorithms for Database Design" (TODS86)

### 2016-08-30 (Tus.)

- Functional data structures used in distributes storage systems
  - refs: "Immutability Changes Everything" (CACM16)
- ***research idea:*** Replicated set:
  - inspired by hybrid system: add/remote are strong; read/scan are weak.

## September 2016

### 2016-09-02 (Fri.)

- Implement a bib manager tool using Cassandra
  - supporting tags: filtering by tags

### 2016-09-10 (Sat.)

- ***research idea:*** runtime verification of consistency models using 
  (timed/probabilistic) temporal logic/ knowledge logic
  - refs: "Monitoring Data Usage in Distributed Systems" (TSE13)

### 2016-09-11 (Sun.)

- ***research idea:*** Paxos Commit protocol for transactions over underlying atomic registers???
