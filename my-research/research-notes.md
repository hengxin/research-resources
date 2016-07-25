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
