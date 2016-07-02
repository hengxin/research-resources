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
- Reference: Understanding the Causes of Consistency Anomalies in Apache Cassandra, VLDB'15