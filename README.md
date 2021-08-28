# Awesome Consistency 

A curated selection of materials describing and discussing data consistency models. 

## Papers

[Granularity of locks and degrees of consistency in a shared data base, Gray et al. (1976).](http://jimgray.azurewebsites.net/papers/granularity%20of%20locks%20and%20degrees%20of%20consistency%20rj%201654.pdf) (Degrees 0-3)

[How to Make a Multiprocessor Computer That Correctly Executes Multiprocess Programs. Lamport, (1979).](https://www.microsoft.com/en-us/research/uploads/prod/2016/12/How-to-Make-a-Multiprocessor-Computer-That-Correctly-Executes-Multiprocess-Programs.pdf) (Sequential Consistency)

[PRAM: A Scalable Shared Memory, Lipton et al., (1998)](https://www.cs.princeton.edu/research/techreps/TR-180-88) (PRAM = read your writes, monotonic writes, monotonic reads). 

[Linearizability: A Correctness Condition for Concurrent Objects, Herlihy et al. (1990).](https://cs.brown.edu/~mph/HerlihyW90/p463-herlihy.pdf) (Linearizability)

[ANSI SQL-92 (1992).](http://synthesis.ipi.ac.ru/synthesis/student/oodb/essayRef/sqlFoundation.pdf) (Read Uncommitted, Read Committed, Repeatable Read, Serializability)

[Session Guarantees for Weakly Consistent Replicated Data, Terry et al., (1994)](https://www.cs.utexas.edu/~lorenzo/corsi/cs380d/papers/SessionGuaranteesBayou.pdf) (Read Your Writes, Monotonic Reads, Writes Follow Reads, Monotonic Writes)

[A Critique of ANSI SQL Isolation Levels, Berenson et al. (1995).](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-95-51.pdf) (Snapshot Isolation)

[Weak consistency: A generalized theory and optimistic implementations for distributed transactions, Adya. (1999).](http://pmg.csail.mit.edu/papers/adya-phd.pdf) (Graph-based isolation level definitions of PL-{2+, 2L, SI, FCV, MSR, CS, SU})

[Generalized Isolation Level Definitions, Adya et al. (2000).](http://pmg.csail.mit.edu/papers/icde00.pdf) (Graph-based isolation level definitions of PL-{1, 2, 2.99, 3})

[Database Replication Using Generalized Snapshot Isolation, Elnikety et al., (2005).](https://infoscience.epfl.ch/record/53561/files/srds2005-gsi.pdf) (Generalised Snapshot Isolation, Prefix Consistent SI)

[Lazy Database Replication with Snapshot Isolation, Daudjee et al, (2006).](http://www.vldb.org/conf/2006/p715-daudjee.pdf) (Strong Session SI)

[Eventually Consistent, Vogels, (2009).](https://dl.acm.org/doi/pdf/10.1145/1435417.1435432) (Eventual, Causal, Read Your Writes, Sessionm Monotonic Read, Monotonic Write Consistency)

[Replicated Data Consistency Explained Through Baseball, Terry, (2013).](https://www.microsoft.com/en-us/research/wp-content/uploads/2011/10/ConsistencyAndBaseballReport.pdf) (Consistent Prefix, Bounded Staleness, Monotonic Reads, Read My Writes, Eventual, and Strong Consistency)

[Non-Monotonic Snapshot Isolation: scalable and strong consistency for geo-replicated transactional systems, Ardekani et al., (2013).](https://pages.lip6.fr/Marc.Shapiro/papers/NMSI-SRDS-2013.pdf) (Non-Monotonic Snapshot Isolation)

[Transactional storage for geo-replicated systems, Sovran et al., (2011).](http://www.news.cs.nyu.edu/~jinyang/pub/walter-sosp11.pdf) (Parallel
Snapshot Isolation)

[Highly Available Transactions: Virtues and Limitations (Extended Version), Bailis et al. (2014).](https://arxiv.org/abs/1302.0309.pdf) (Monotonic Atomic View)

[Scalable Atomic Visibility with RAMP Transactions, Bailis et al. (2014).](https://dl.acm.org/doi/pdf/10.1145/2909870?download=true) (Read Atomic)

[A Framework for Transactional Consistency Models with Atomic Visibility, Cerone et al., (2015).](https://drops.dagstuhl.de/opus/volltexte/2015/5375/pdf/15.pdf) (Isolation level definitions based on visibility and arbitration)

[Consistency in Non-Transactional Distributed Storage Systems, Viotti et al., (2016).](https://arxiv.org/pdf/1512.00168.pdf) (Excellent survery of non-transactional semantics)

[Seeing is Believing: A Client-Centric Specification of Database Isolation, Crooks et al. (2017).](http://www.cs.cornell.edu/lorenzo/papers/Crooks17Seeing.pdf) (State-based isolation level definitions) 

[Fast General Distributed Transactions with Opacity, Shamis et al. (2019)](https://www.microsoft.com/en-us/research/uploads/prod/2019/01/mod057.pdf) (Opacity)


## Blog Posts 

### Daniel Abadi

+ [Introduction to Transaction Isolation Levels](http://dbmsmusings.blogspot.com/2019/05/introduction-to-transaction-isolation.html)
+ [Correctness Anomalies under Serializable Isolation](http://dbmsmusings.blogspot.com/2019/06/correctness-anomalies-under.html)
+ [Overview of Consistency Levels in Database Systems](http://dbmsmusings.blogspot.com/2019/07/overview-of-consistency-levels-in.html)
+ [The dangers of conditional consistency guarantees](ttp://dbmsmusings.blogspot.com/2019/07/the-dangers-of-conditional-consistency.html)
+ [An explanation of the difference between Isolation levels vs. Consistency levels](http://dbmsmusings.blogspot.com/2019/08/an-explanation-of-difference-between.html)

### Peter Bailis

+ [Understanding Weak Isolation Is a Serious Problem](http://www.bailis.org/blog/understanding-weak-isolation-is-a-serious-problem/)
+ [When is "ACID" ACID? Rarely.](http://www.bailis.org/blog/when-is-acid-acid-rarely/)
+ [Linearizability versus Serializability](http://www.bailis.org/blog/linearizability-versus-serializability/)
+ [Stickiness and Client-Server Session Guarantees](http://www.bailis.org/blog/stickiness-and-client-server-session-guarantees/)

### Martin Kleppmann

[Hermitage: Testing the "I" in ACID](https://martin.kleppmann.com/2014/11/25/hermitage-testing-the-i-in-acid.html)
























