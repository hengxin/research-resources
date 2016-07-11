# Research Notes

## 2016-06-27

Relation between interval order (real-time relation) and locality

Mathematical (*axiomatic*) study on Lamport's "solid arrow" and "dashed arrow" model

## 2016-06-28

Further work on "Beyond Lamport's Logic Clock" (JACM)

## 2016-06-29

About Cassandra:
- Quantifying RWN w.r.t. Atomicity/Regular; single-writer vs. multi-writer
- Learning source code 

## 2016-07-02

Experiments on quantifying atomicity violations in PA2AM:
- An observation: long-lived writes are more likely to induce atomicity violations. 
Thus, optimize the write path is crucial to avoiding atomicity violations.
- An idea: carry out experiments with Cassandra
  - Cassandra's write path: commitlog -> memtable -> (*async*) ssttable
  - No *real* write in this write path!
- Reference: Understanding the Causes of Consistency Anomalies in Apache Cassandra, VLDB'15

## 2016-07-07 (Thu.)

- Cassandra projects:
  - products like Jinsan Kuaipan

- Replicated data structures:
  - Cassandra does not provide them. *Why?*
  - What is the consistency model of Redis' replicated data structures?

- Redis:
  - architecture?

## 2016-07-09 (Sat.)

- **paper-tc-2am-minor-revision:**
  - Numerical analysis: the rate of atomicity violations has a limiting value as the number of clients increases.
  - Possible reason: It is the limit of the system capacity.

## 2016-07-11 (Mon.)

- About causality:
  - respect real-time orders of *w/r* and *r/r* to enhence liveness
  - what is strength of such consistency model (compared to causality)
  - real-time causality: implementation (ref: JACM'07)
  - semi-sync. causality (ref: beyond Lamport's clock)
  - the "bolt-on" paper
- About *availablity*:
  - multi-object availability: (ref: Haifeng YU)
  - new definition of "single object available"
