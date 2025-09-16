# Fuzzing papers (DBMS)
A compilation of classic articles in the field of database management system (DBMS)fuzzing.

### keywords

**`DBsec`** : Database security  
**`logic`** : logic bugs &emsp; | &emsp; **`crash`** : crash bugs &emsp; | &emsp; **`perf.`** : performance bugs  
**`Diff`** : Differencial oracle &emsp; | &emsp; **`Con-sol`** : Constraint-solving oracle &emsp; | &emsp; **`Meta`** : Metamorphic oracle  
**`RDB`** : Relational Database  
**`VDB`** : Vector Database  &emsp; | &emsp; **`GDB`** : Gragh Databases &emsp; | &emsp; **`TSDB`** : Time Series Database  
**`cov.`** : Coverage-guided testing &emsp; | &emsp; **`optim.`** : join optimization &emsp; | &emsp; **`trans.`** : transaction bugs
 
## 2025
### SIGMOD
- [Understanding and reusing test suites across database systems.](https://dl.acm.org/doi/10.1145/3698829)
- [Finding logic bugs in spatial database engines via affine equivalent inputs.](https://dl.acm.org/doi/10.1145/3698810)
- [Constant optimization driven database system testing.](https://dl.acm.org/doi/10.1145/3709674) [__`CODD`__]
### VLDB
- [Fucci: Database Transaction Fuzzing via Random Conflict Construction and Multilevel Constraint Solving.](https://www.vldb.org/pvldb/vol18/p1879-li.pdf) [__`Fucci`__]
### TDSC
- [Improving multitasking DBMS fuzzing with more accurate coverage and testcase trimming.](https://ieeexplore.ieee.org/document/10812868)
### EuroSys
- [Understanding and detecting SQL function bugs: using simple boundary arguments to trigger hundreds of DBMS bugs.](https://dl.acm.org/doi/10.1145/3689031.3696064)
### ICSE
- [PUPPY: finding performance degradation bugs in DBMSs via limited-optimization plan construction.](https://ieeexplore.ieee.org/document/11029960) [**`PUPPY`**] [**`perf.`**]
- [Coni: Detecting Database Connector Bugs via State-Aware Test Case Generation.](https://dl.acm.org/doi/10.1109/ICSE55347.2025.00003) [**`Coni`**]
### ISSTA
- [QTRAN: extending metamorphic-oracle based logical bug detection techniques for multiple-DBMS dialect support.](https://dl.acm.org/doi/10.1145/3728908) [__`Qtran`__]
### arXiv25
- [Enhanced Differential Testing in Emerging Database Systems.](http://arxiv.org/abs/2501.01236) [__`SQLxDiff`__]
- [Scaling Automated Database System Testing.](https://arxiv.org/abs/2503.21424) [**`SQLancer++`**]
- [Testing database systems with large language model synthesized fragments.](http://arxiv.org/abs/2505.02012) [**`ShQveL`**]

## 2024
### SIGMOD
- [Correlation joins over time series data streams utilizing complementary dimension reduction and transformation.](https://dl.acm.org/doi/10.1145/3626722)
- [Keep It Simple: Testing Databases via Differential Query Plans](https://dl.acm.org/doi/abs/10.1145/3654991). [**`DQP`**]
- [Finding Logic Bugs in Spatial Database Engines via Affine Equivalent Inputs.](https://dl.acm.org/doi/abs/10.1145/3698810) [**`Spatter`**]
### VLDB
- [Detecting metadata-related logic bugs in database systems via raw database construction.](https://dl.acm.org/doi/10.14778/3659437.3659445)
- [Semantic conformance testing of relational DBMS.](https://dl.acm.org/doi/10.14778/3712221.3712247)
### ICSE
- [Understanding transaction bugs in database systems.](https://dl.acm.org/doi/10.1145/3597503.3639207)
- [CERT: finding performance issues in database systems through the lens of cardinality estimation.](https://dl.acm.org/doi/10.1145/3597503.3639076) [**`CERT`**]
- [Detecting logic bugs in graph database management systems via injective and surjective graph query transformation.](https://ieeexplore.ieee.org/abstract/document/10548201) [**`GQT`**]
- [Understanding Transaction Bugs in Database Systems.](https://dl.acm.org/doi/abs/10.1145/3597503.3639207)
- [Testing Graph Database Systems via Equivalent Query Rewriting.](https://dl.acm.org/doi/abs/10.1145/3597503.3639200)
- [Sedar: Obtaining High-Quality Seeds for DBMS Fuzzing via Cross-DBMS SQL Transfer.](https://dl.acm.org/doi/abs/10.1145/3597503.3639210) [**`Sedar`**]
### ISSTA
- [Testing gremlin-based graph database systems via query disassembling.](https://dl.acm.org/doi/10.1145/3650212.3680392)
- [SQLess: dialect-agnostic SQL query simplification.](https://doi.org/10.1145/3650212.3680317) [**`SQLess`**]
### TDSC
- [Improving Multitasking DBMS Fuzzing With More Accurate Coverage and Testcase Trimming.](https://ieeexplore.ieee.org/abstract/document/10812868) [**`Tuzz`**]
### ICST
- [Differential optimization testing of gremlin-based graph database systems.](https://ieeexplore.ieee.org/document/10638597)
### USENIX Security
- [Towards Generic Database Management System Fuzzing.](https://www.usenix.org/conference/usenixsecurity24/presentation/yang-yupeng)
### ATC
- [WingFuzz: Implementing Continuous Fuzzing for DBMSs.](https://www.usenix.org/conference/atc24/presentation/liang) [**`WingFuzz`**]
### OTHERS
- [OSDI '24] [Detecting logic bugs in database engines via equivalent expression transformation.](https://www.usenix.org/conference/osdi24/presentation/jiang) [**`EET`**]
- [arXiv24] [SQLaser: Detecting DBMS Logic Bugs with Clause-Guided Fuzzing.](https://arxiv.org/abs/2407.04294) [**`SQLaser`**]
- [Journal of Systems and Software ‘24(CCF B)] [Database management system performance comparisons: a systematic literature review.](https://www.sciencedirect.com/science/article/pii/S0164121223002674)
- [COMPSAC '24] [SQLPass: A Semantic Effective Fuzzing Method for DBMS.](https://ieeexplore.ieee.org/abstract/document/10633453) [**`SQLPass`**]
- [FSE '24] [When Fuzzing Meets LLMs: Challenges and Opportunities.](https://dl.acm.org/doi/abs/10.1145/3663529.3663784)

## 2023
### SIGMOD
- [Detecting Logic Bugs of Join Optimizations in DBMS](https://dl.acm.org/doi/10.1145/3588909). [**`TQS`**]
- [DBPA: a benchmark for transactional database performance anomalies](https://dl.acm.org/doi/10.1145/3588926). [**`DBPA`**]
### ICDE
- [Sequence-Oriented DBMS Fuzzing](https://ieeexplore.ieee.org/document/10184875). [**`Lego`**]
### ICSE
- [Testing database systems via differential query execution](https://dl.acm.org/doi/10.1109/ICSE48619.2023.00175). [**`DQE`**]
- [Detecting isolation bugs via transaction oracle construction](https://ieeexplore.ieee.org/document/10172773). [**`GDBMeter`**]
- [Coverage guided fault injection for cloud systems](https://ieeexplore.ieee.org/document/10172878).
- [Randomized differential testing of RDF stores](https://ieeexplore.ieee.org/document/10172822).
- [Testing Database Engines via Query Plan Guidance](https://ieeexplore.ieee.org/abstract/document/10172874). [**`QPG`**]
### ISSTA
- [Testing graph database engines via query partitioning](https://dl.acm.org/doi/10.1145/3597926.3598044).
- [GDsmith: Detecting Bugs in Cypher Graph Database Engines](https://dl.acm.org/doi/abs/10.1145/3597926.3598046). [**`GDsmith`**]
### EuroSys
- [Model checking guided testing for distributed systems](https://dl.acm.org/doi/10.1145/3552326.3587442).
### ATC
- [Pinolo: detecting logical bugs in database management systems with approximate query synthesis](https://www.usenix.org/conference/atc23/presentation/hao). [**`Pinolo`**]
### OTHERS
- [arXiv23] [A Comprehensive Survey on Database Management System Fuzzing: Techniques, Taxonomy and Experimental Comparison.](http://arxiv.org/abs/2311.06728)
- [SEC '23] [DynSQL: Stateful Fuzzing for Database Management Systems with Complex and Valid {SQL} Query Generation.](https://www.usenix.org/conference/usenixsecurity23/presentation/jiang-zu-ming) [__`DynSQL`__]
- [OSDI '23] [Detecting transactional bugs in database engines via {graph-based} oracle construction.](https://www.usenix.org/conference/osdi23/presentation/jiang)
- [MDPI '23] [Squill: Testing DBMS with Correctness Feedback and Accurate Instantiation.](https://www.mdpi.com/2076-3417/13/4/2519) [  **`Squill`**  ]
- [GITHUB] [a QA tool to random generate sql by bnf pattern.](https://github.com/pingcap/go-randgen) [  **`Go-Randgen`**  ]

## 2022
### ASE
- [Griffin : Grammar-Free DBMS Fuzzing.](https://dl.acm.org/doi/10.1145/3551349.3560431) [__`Griffin`__]
- [Differentially Testing Database Transactions for Fun and Profit.](https://dl.acm.org/doi/10.1145/3551349.3556924) [__`DT2`__]
### ICSE
- [Automatic detection of performance bugs in database systems using equivalent queries.](https://ieeexplore.ieee.org/document/9793961) [**`AMOEBA`**]
### ISSTA
- [Unicorn: detect runtime errors in time-series databases with hybrid input synthesis.](https://dl.acm.org/doi/10.1145/3533767.3534364) [**`Unicorn`**]
- [Finding bugs in gremlin-based graph database systems via randomized differential testing.](https://dl.acm.org/doi/10.1145/3533767.3534409)
 ### USENIX Security
- [Detecting logical bugs of DBMS with coverage-based guidance.](https://www.usenix.org/conference/usenixsecurity22/presentation/liang)

## 2021
- [Bench '20] [Artemis: An Automatic Test Suite Generator for Large Scale OLAP Database.](http://link.springer.com/10.1007/978-3-030-71058-3_5) [__`Artemis`__]
- [arXiv '21] [Duplicate-sensitivity Guided Transformation Synthesis for DBMS Correctness Bug Detection.](https://arxiv.org/abs/2107.03660) [  **`Eqsql`**  ]

## 2020

- [OSDI'20] [Testing database engines via pivoted query synthesis.](https://arxiv.org/abs/2001.04174) [__`PQS`__]
- [ESEC/FSE '20] [Detecting Optimization Bugs in Database Engines via Non-optimizing Reference Engine Construction.](https://dl.acm.org/doi/10.1145/3368089.3409710) [**`NoREC`**]
- [CCS '20] [SQUIRREL: Testing Database Management Systems with Language Validity and Coverage Feedback.](https://dl.acm.org/doi/10.1145/3372297.3417260) [__`SQUIRREL`__]
- [OOPSLA '20] [Finding Bugs in Database Systems via Query Partitioning.](https://dl.acm.org/doi/10.1145/3428279) [**`TLP`**]
- [WOOT '20] [AFL++: combining incremental steps of fuzzing research.](https://www.usenix.org/conference/woot20/presentation/fioraldi) [__**`afl++`**__]
- [DBTest '20] [Testing query execution engines with mutations.](https://dl.acm.org/doi/abs/10.1145/3395032.3395322) [  **`MutaSQL`**  ]

## 2019
### VLDB
- [APOLLO: automatic detection and diagnosis of performance regressions in database systems.](https://dl.acm.org/doi/10.14778/3357377.3357382) [__`APOLLO`__]

## 2015
### GITHUB
- [A random SQL query generator.](https://github.com/anse1/sqlsmith)A random SQL query generator. [  **`SQLsmith`**  ]

## 2010
### ASE
- [Automated SQL query generation for systematic testing of database engines.](https://dl.acm.org/doi/10.1145/1858996.1859063) [  **`ADUSA`**  ]

## 2007
### VLDB
- [A genetic approach for random testing of database systems.](https://www.vldb.org/conf/2007/papers/industrial/p1243-bati.pdf) [  **`GARan`**  ]

## 1998
### VLDB
- [Massive Stochastic Testing of SQL.](https://www.vldb.org/conf/1998/p618.pdf) [**`RAGS`**]
