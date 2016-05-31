# Bibs on Distributed Systems (Articles)

## Distributed Systems

### CAP Theorem
- [Marc's Blog: CAP and PACELC: Thinking More Clearly About Consistency](https://brooker.co.za/blog/2014/07/16/pacelc.html)
  
  Key points:
  - Five misconceptions about CAP
  - PACELC is better
  - PACELC is still ideal.
- [Marc's Blog: Is there a CAP theorem for Durability?](https://brooker.co.za/blog/2015/09/26/cap-durability.html)

  I'll define durability as "the ability to tolerate t node failures without losing data".
- [Probabilistic CAP and Timely Adaptive Key-value Stores]()
  
  Introduce PCAP (Probabilistic CAP Theorem) and PSLA (Probabilistic SLA)
- [CAP Theorem: Revisited; By Robert Greiner, 2014](http://robertgreiner.com/2014/08/cap-theorem-revisited/)

  Key points:
  - Given that networks aren’t completely reliable, you must tolerate partitions in a distributed system, period.
  - The decision between Consistency and Availability is a *software trade off*.
  
## Distributed Storage Systems
### PPTs
- [Desired Properties in a Storage System@Google: Jeff Dean](http://www.sigops.org/sosp/sosp09/slides/hotstorage_12_dean-slides.pdf)
  
  Key points:
  - Users specify desired properties for data
  - Support both strong-consistency and weak-consistency access modes
