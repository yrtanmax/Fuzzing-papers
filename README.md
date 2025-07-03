# Fuzzing-papers
A compilation of classic articles in the field of database fuzzing.

### keywords

| | | | | |
| ---------- | --------------------------------- | -------------------------------- | ------------------------------- | ----------------------- |
| **Generation** |**`DBsec`**:Database security      |
| **Bugs**       |**`logic`**:logic bugs             |  **`crash`**:crash bugs  |  **`perf.`**:performance bugs  |
| **Oracle**     |**`Diff`**:Differencial oracle     |  **`Con-sol`**:Constraint-solving oracle  |  **`Meta`**:Metamorphic oracle  |
| **DBMS **      |**`RDB`**:Relational Database      |  **`GDB`**:Gragh Databases  |  **`TSDB`**:Time Series Database  |  **`VDB`**:Vector Database  |
| **Innovation** |**`cov.`**:Coverage-guided testing |  **`optim.`**:join optimization  |  **`trans.`**:transaction bugs  |

## 2025

- [[SIGMOD '25](https://dl.acm.org/doi/10.1145/3698829)] Understanding and reusing test suites across database systems.

- [[SIGMOD '25](https://dl.acm.org/doi/10.1145/3698810)] Finding logic bugs in spatial database engines via affine equivalent inputs.
- [[SIGMOD '25](https://dl.acm.org/doi/10.1145/3709674)] Constant optimization driven database system testing [__`CODD`__]
- [[VLDB '25](https://www.vldb.org/pvldb/vol18/p1879-li.pdf)] Fucci: Database Transaction Fuzzing via Random Conflict Construction and Multilevel Constraint Solving [__`Fucci`__]
- [[TDSC '25](https://ieeexplore.ieee.org/document/10812868)] Improving multitasking DBMS fuzzing with more accurate coverage and testcase trimming.
- [[EuroSys '25](https://dl.acm.org/doi/10.1145/3689031.3696064)] Understanding and detecting SQL function bugs: using simple boundary arguments to trigger hundreds of DBMS bugs.
- [[arXiv25](http://arxiv.org/abs/2505.02012)] Testing database systems with large language model synthesized fragments.
- [[ISSTA '25](https://dl.acm.org/doi/10.1145/3728908)] QTRAN: extending metamorphic-oracle based logical bug detection techniques for multiple-DBMS dialect support [__`Qtran`__]
- [[arXiv25](http://arxiv.org/abs/2501.01236)] Enhanced Differential Testing in Emerging Database Systems [__`SQLxDiff`__]

## 2024

- [[SIGMOD '24](https://dl.acm.org/doi/10.1145/3626722)] Correlation joins over time series data streams utilizing complementary dimension reduction and transformation.

- [[OSDI '24](https://www.usenix.org/conference/osdi24/presentation/jiang)] Detecting logic bugs in database engines via equivalent expression transformation.
- [[VLDB Endowment'24](https://dl.acm.org/doi/10.14778/3659437.3659445)] Detecting metadata-related logic bugs in database systems via raw database construction.
- [[VLDB Endowment'24](https://dl.acm.org/doi/10.14778/3712221.3712247)] Semantic conformance testing of relational DBMS.
- [[ICSE '24](https://dl.acm.org/doi/10.1145/3597503.3639207)] Understanding transaction bugs in database systems.
- [[ICSE '24](https://ieeexplore.ieee.org/abstract/document/10548201)] Detecting logic bugs in graph database management systems via injective and surjective graph query transformation.
- [[ISSTA '24](https://dl.acm.org/doi/10.1145/3650212.3680392)] Testing gremlin-based graph database systems via query disassembling.
- [[ISSTA '24](https://doi.org/10.1145/3650212.3680317)] SQLess: dialect-agnostic SQL query simplification [__`SQLess`__]
- [[ICST '24](https://ieeexplore.ieee.org/document/10638597)] Differential optimization testing of gremlin-based graph database systems.
- [[Journal of Systems and Software ‘24(CCF B)](https://www.sciencedirect.com/science/article/pii/S0164121223002674)] Database management system performance comparisons: a systematic literature review.

## 2023

- [[arXiv23](http://arxiv.org/abs/2311.06728)] A Comprehensive Survey on Database Management System Fuzzing: Techniques, Taxonomy and Experimental Comparison.

- [[SIGMOD '23](https://dl.acm.org/doi/10.1145/3588909)] Detecting Logic Bugs of Join Optimizations in DBMS [__`TQS`__]
- [[SEC '23](https://www.usenix.org/conference/usenixsecurity23/presentation/jiang-zu-ming)] DynSQL: Stateful Fuzzing for Database Management Systems with Complex and Valid {SQL} Query Generation [__`DynSQL`__]
- [[ICDE '23](https://ieeexplore.ieee.org/document/10184875)] Sequence-Oriented DBMS Fuzzing.
- [[ICSE '23](https://dl.acm.org/doi/10.1109/ICSE48619.2023.00175)] Testing database systems via differential query execution [__`DQE`__]
- [[ICSE '23](https://ieeexplore.ieee.org/document/10172773)] Detecting isolation bugs via transaction oracle construction [__`GDBMeter`__]
- [[ICSE '23](https://ieeexplore.ieee.org/document/10172878)] Coverage guided fault injection for cloud systems.
- [[ICSE-Companion '23](https://ieeexplore.ieee.org/document/10172822)] Randomized differential testing of RDF stores.
- [[EuroSys '23](https://dl.acm.org/doi/10.1145/3552326.3587442)] Model checking guided testing for distributed systems.
- [[USENIX ATC '23](https://www.usenix.org/conference/atc23/presentation/hao)] Pinolo: detecting logical bugs in database management systems with approximate query synthesis [__`Pinolo`__]
- [[OSDI '23](https://www.usenix.org/conference/osdi23/presentation/jiang)] Detecting transactional bugs in database engines via {graph-based} oracle construction.
- [[ISSTA 2023](https://dl.acm.org/doi/10.1145/3597926.3598044)] Testing graph database engines via query partitioning.

## 2022

- [[ASE '22](https://dl.acm.org/doi/10.1145/3551349.3560431)] Griffin : Grammar-Free DBMS Fuzzing [__`Griffin`__]

- [[ASE '22](https://dl.acm.org/doi/10.1145/3551349.3556924)] Differentially Testing Database Transactions for Fun and Profit [__`DT2`__]
- [[USENIX Security '22](https://www.usenix.org/conference/usenixsecurity22/presentation/liang)] Detecting logical bugs of DBMS with coverage-based guidance.
- [[ISSTA '22](https://dl.acm.org/doi/10.1145/3533767.3534409)] Finding bugs in gremlin-based graph database systems via randomized differential testing.
- [[ICSE '22](https://ieeexplore.ieee.org/document/9793961)] Automatic detection of performance bugs in database systems using equivalent queries.

## 2021

- [[Bench '20](http://link.springer.com/10.1007/978-3-030-71058-3_5)] Artemis: An Automatic Test Suite Generator for Large Scale OLAP Database [__`Artemis`__]

## 2020

- [[OSDI'20](https://arxiv.org/abs/2001.04174)] Testing database engines via pivoted query synthesis [__`PQS`__]

- [[CCS '20](https://dl.acm.org/doi/10.1145/3372297.3417260)] SQUIRREL: Testing Database Management Systems with Language Validity and Coverage Feedback [__`SQUIRREL`__]
- [[WOOT '20](https://www.usenix.org/conference/woot20/presentation/fioraldi)] {AFL++} : combining incremental steps of fuzzing research [__`afl++`__]

## 2019

- [[VLDB '19](https://dl.acm.org/doi/10.14778/3357377.3357382)] APOLLO: automatic detection and diagnosis of performance regressions in database systems [__`APOLLO`__]

## 2010

- [[ASE ‘10](https://dl.acm.org/doi/10.1145/1858996.1859063)] Automated SQL query generation for systematic testing of database engines.

## 2007

- [[VLDB '07](https://www.vldb.org/conf/2007/papers/industrial/p1243-bati.pdf)] A genetic approach for random testing of database systems.

## 1998

- [[VLDB 1998](https://www.vldb.org/conf/1998/p618.pdf)] Massive Stochastic Testing of SQL.
