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
- [``            ``] [Understanding and reusing test suites across database systems.](https://dl.acm.org/doi/10.1145/3698829)
- [``    CODD    ``] [Constant optimization driven database system testing.](https://dl.acm.org/doi/10.1145/3709674)
### VLDB
- [``   Fucci    ``] [Fucci: Database Transaction Fuzzing via Random Conflict Construction and Multilevel Constraint Solving.](https://www.vldb.org/pvldb/vol18/p1879-li.pdf)
- [``            ``] [Detecting Schema-Related Logic Bugs in Relational DBMSs via Equivalent Database Construction.](https://dl.acm.org/doi/10.14778/3734839.3734861)
- [``   trans.   ``] [Simple Testing Can Expose Most Critical Transaction Bugs: Understanding and Detecting Write-Specific Serializability Violations in Database Systems](https://dl.acm.org/doi/10.14778/3742728.3742747)
### TDSC
- [``            ``] [Improving multitasking DBMS fuzzing with more accurate coverage and testcase trimming.](https://ieeexplore.ieee.org/document/10812868)
### EuroSys
- [``            ``] [Understanding and detecting SQL function bugs: using simple boundary arguments to trigger hundreds of DBMS bugs.](https://dl.acm.org/doi/10.1145/3689031.3696064)
### ICSE
- [``   PUPPY    ``] [``   perf.    ``] [PUPPY: finding performance degradation bugs in DBMSs via limited-optimization plan construction.](https://ieeexplore.ieee.org/document/11029960)
- [``    Coni    ``] [Coni: Detecting Database Connector Bugs via State-Aware Test Case Generation.](https://dl.acm.org/doi/10.1109/ICSE55347.2025.00003)
### ISSTA
- [``   Qtran    ``] [QTRAN: extending metamorphic-oracle based logical bug detection techniques for multiple-DBMS dialect support.](https://dl.acm.org/doi/10.1145/3728908)
- [``            ``] [Detecting Isolation Anomalies in Relational DBMSs](https://dl.acm.org/doi/abs/10.1145/3728953)
### ATC
- [``            ``] [DDLumos: Understanding and Detecting Atomic DDL Bugs in DBMSs](https://www.usenix.org/conference/atc25/presentation/wu-zhiyong)
### arXiv25
- [``  SQLxDiff  ``] [Enhanced Differential Testing in Emerging Database Systems.](http://arxiv.org/abs/2501.01236)
- [`` SQLancer++ ``] [Scaling Automated Database System Testing.](https://arxiv.org/abs/2503.21424)
- [``   ShQveL   ``] [Testing database systems with large language model synthesized fragments.](http://arxiv.org/abs/2505.02012)
- [``            ``] [LLM-based Dynamic Differential Testing for Database Connectors with Reinforcement Learning-Guided Prompt Selection.](https://arxiv.org/abs/2506.11870)
### OTHER
- [``    CCFB    ``] [``   logic    ``] [ICPC '25] [Sembug: Detecting Logic Bugs in Dbms Through Generating Semantic-Aware Non-Optimizing Query](https://ieeexplore.ieee.org/abstract/document/11025894)

## 2024
### SIGMOD
- [``            ``] [Correlation joins over time series data streams utilizing complementary dimension reduction and transformation.](https://dl.acm.org/doi/10.1145/3626722)
- [``    DQP     ``] [Keep It Simple: Testing Databases via Differential Query Plans](https://dl.acm.org/doi/abs/10.1145/3654991).
- [``  Spatter   ``] [Finding Logic Bugs in Spatial Database Engines via Affine Equivalent Inputs.](https://dl.acm.org/doi/abs/10.1145/3698810)
### VLDB
- [``            ``] [Detecting metadata-related logic bugs in database systems via raw database construction.](https://dl.acm.org/doi/10.14778/3659437.3659445)
- [``            ``] [Semantic conformance testing of relational DBMS.](https://dl.acm.org/doi/10.14778/3712221.3712247)
### ICSE
- [``    CERT    ``] [CERT: finding performance issues in database systems through the lens of cardinality estimation.](https://dl.acm.org/doi/10.1145/3597503.3639076)
- [``    GQT     ``] [Detecting logic bugs in graph database management systems via injective and surjective graph query transformation.](https://ieeexplore.ieee.org/abstract/document/10548201)
- [``            ``] [Understanding Transaction Bugs in Database Systems.](https://dl.acm.org/doi/abs/10.1145/3597503.3639207)
- [``            ``] [Testing Graph Database Systems via Equivalent Query Rewriting.](https://dl.acm.org/doi/abs/10.1145/3597503.3639200)
- [``   Sedar    ``] [Sedar: Obtaining High-Quality Seeds for DBMS Fuzzing via Cross-DBMS SQL Transfer.](https://dl.acm.org/doi/abs/10.1145/3597503.3639210)
### ISSTA
- [``            ``] [Testing gremlin-based graph database systems via query disassembling.](https://dl.acm.org/doi/10.1145/3650212.3680392)
- [``   SQLess   ``] [SQLess: dialect-agnostic SQL query simplification.](https://doi.org/10.1145/3650212.3680317)
### TDSC
- [``    Tuzz    ``] [Improving Multitasking DBMS Fuzzing With More Accurate Coverage and Testcase Trimming.](https://ieeexplore.ieee.org/abstract/document/10812868)
### ICST
- [``            ``] [Differential optimization testing of gremlin-based graph database systems.](https://ieeexplore.ieee.org/document/10638597)
### USENIX Security
- [``            ``] [Towards Generic Database Management System Fuzzing.](https://www.usenix.org/conference/usenixsecurity24/presentation/yang-yupeng)
### ATC
- [``  WingFuzz  ``] [WingFuzz: Implementing Continuous Fuzzing for DBMSs.](https://www.usenix.org/conference/atc24/presentation/liang)
### OTHERS
- [``    EET     ``] [OSDI '24] [Detecting logic bugs in database engines via equivalent expression transformation.](https://www.usenix.org/conference/osdi24/presentation/jiang)
- [``  SQLaser   ``] [arXiv24] [SQLaser: Detecting DBMS Logic Bugs with Clause-Guided Fuzzing.](https://arxiv.org/abs/2407.04294)
- [``            ``] [Journal of Systems and Software ‘24(CCF B)] [Database management system performance comparisons: a systematic literature review.](https://www.sciencedirect.com/science/article/pii/S0164121223002674)
- [``  SQLPass   ``] [COMPSAC '24] [SQLPass: A Semantic Effective Fuzzing Method for DBMS.](https://ieeexplore.ieee.org/abstract/document/10633453)
- [``            ``] [FSE '24] [When Fuzzing Meets LLMs: Challenges and Opportunities.](https://dl.acm.org/doi/abs/10.1145/3663529.3663784)

## 2023
### SIGMOD
- [``    TQS     ``] [Detecting Logic Bugs of Join Optimizations in DBMS](https://dl.acm.org/doi/10.1145/3588909).
- [``    DBPA    ``] [DBPA: a benchmark for transactional database performance anomalies](https://dl.acm.org/doi/10.1145/3588926).
### ICDE
- [``    Lego    ``] [Sequence-Oriented DBMS Fuzzing](https://ieeexplore.ieee.org/document/10184875).
### ICSE
- [``    DQE     ``] [Testing database systems via differential query execution](https://dl.acm.org/doi/10.1109/ICSE48619.2023.00175).
- [``  GDBMeter  ``] [Detecting isolation bugs via transaction oracle construction](https://ieeexplore.ieee.org/document/10172773).
- [``            ``] [Coverage guided fault injection for cloud systems](https://ieeexplore.ieee.org/document/10172878).
- [``            ``] [Randomized differential testing of RDF stores](https://ieeexplore.ieee.org/document/10172822).
- [``    QPG     ``] [Testing Database Engines via Query Plan Guidance](https://ieeexplore.ieee.org/abstract/document/10172874).
### ISSTA
- [``            ``] [Testing graph database engines via query partitioning](https://dl.acm.org/doi/10.1145/3597926.3598044).
- [``  GDsmith   ``] [GDsmith: Detecting Bugs in Cypher Graph Database Engines](https://dl.acm.org/doi/abs/10.1145/3597926.3598046).
### EuroSys
- [``            ``] [Model checking guided testing for distributed systems](https://dl.acm.org/doi/10.1145/3552326.3587442).
### ATC
- [``   Pinolo   ``] [Pinolo: detecting logical bugs in database management systems with approximate query synthesis](https://www.usenix.org/conference/atc23/presentation/hao).
### OTHERS
- [``            ``] [arXiv23] [A Comprehensive Survey on Database Management System Fuzzing: Techniques, Taxonomy and Experimental Comparison.](http://arxiv.org/abs/2311.06728)
- [``   DynSQL   ``] [SEC '23] [DynSQL: Stateful Fuzzing for Database Management Systems with Complex and Valid {SQL} Query Generation.](https://www.usenix.org/conference/usenixsecurity23/presentation/jiang-zu-ming)
- [``            ``] [OSDI '23] [Detecting transactional bugs in database engines via {graph-based} oracle construction.](https://www.usenix.org/conference/osdi23/presentation/jiang)
- [``   Squill   ``] [MDPI '23] [Squill: Testing DBMS with Correctness Feedback and Accurate Instantiation.](https://www.mdpi.com/2076-3417/13/4/2519)
- [ Go-Randgen ] [GITHUB] [a QA tool to random generate sql by bnf pattern.](https://github.com/pingcap/go-randgen)

## 2022
### ASE
- [``  Griffin   ``] [Griffin : Grammar-Free DBMS Fuzzing.](https://dl.acm.org/doi/10.1145/3551349.3560431)
- [``    DT2     ``] [Differentially Testing Database Transactions for Fun and Profit.](https://dl.acm.org/doi/10.1145/3551349.3556924)
### ICSE
- [``   AMOEBA   ``] [Automatic detection of performance bugs in database systems using equivalent queries.](https://ieeexplore.ieee.org/document/9793961)
### ISSTA
- [``  Unicorn   ``] [Unicorn: detect runtime errors in time-series databases with hybrid input synthesis.](https://dl.acm.org/doi/10.1145/3533767.3534364)
- [``            ``] [Finding bugs in gremlin-based graph database systems via randomized differential testing.](https://dl.acm.org/doi/10.1145/3533767.3534409)
### USENIX Security
- [``            ``] [Detecting logical bugs of DBMS with coverage-based guidance.](https://www.usenix.org/conference/usenixsecurity22/presentation/liang)

## 2021
- [``  Artemis   ``] [Bench '20] [Artemis: An Automatic Test Suite Generator for Large Scale OLAP Database.](http://link.springer.com/10.1007/978-3-030-71058-3_5)
- [``   Eqsql    ``] [arXiv '21] [Duplicate-sensitivity Guided Transformation Synthesis for DBMS Correctness Bug Detection.](https://arxiv.org/abs/2107.03660)

## 2020

- [``    PQS     ``] [OSDI '20] [Testing database engines via pivoted query synthesis.](https://arxiv.org/abs/2001.04174)
- [``   NoREC    ``] [ESEC/FSE '20] [Detecting Optimization Bugs in Database Engines via Non-optimizing Reference Engine Construction.](https://dl.acm.org/doi/10.1145/3368089.3409710)
- [``  SQUIRREL  ``] [CCS '20] [SQUIRREL: Testing Database Management Systems with Language Validity and Coverage Feedback.](https://dl.acm.org/doi/10.1145/3372297.3417260)
- [``    TLP     ``] [OOPSLA '20] [Finding Bugs in Database Systems via Query Partitioning.](https://dl.acm.org/doi/10.1145/3428279)
- [``   afl++    ``] [WOOT '20] [AFL++: combining incremental steps of fuzzing research.](https://www.usenix.org/conference/woot20/presentation/fioraldi)
- [``  MutaSQL   ``] [DBTest '20] [Testing query execution engines with mutations.](https://dl.acm.org/doi/abs/10.1145/3395032.3395322)

## 2019
### VLDB
- [``   APOLLO   ``] [APOLLO: automatic detection and diagnosis of performance regressions in database systems.](https://dl.acm.org/doi/10.14778/3357377.3357382)

## 2015
### GITHUB
- [``  SQLsmith  ``] [A random SQL query generator.](https://github.com/anse1/sqlsmith)

## 2010
### ASE
- [``   ADUSA    ``] [Automated SQL query generation for systematic testing of database engines.](https://dl.acm.org/doi/10.1145/1858996.1859063)

## 2007
### VLDB
- [``   GARan    ``] [A genetic approach for random testing of database systems.](https://www.vldb.org/conf/2007/papers/industrial/p1243-bati.pdf)

## 1998
### VLDB
- [``    RAGS    ``] [Massive Stochastic Testing of SQL.](https://www.vldb.org/conf/1998/p618.pdf)
