# pldi2017
- http://pldi17.sigplan.org/home

## Learning and Probabilistic
### DemoMatch: API Discovery from Demonstrations

### Similarity of Binaries through re-Optimization

### Synthesizing Program Input Grammars

### Compiling Markov Chain Monte Carlo Algorithms for Probabilistic Modeling
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1473.JPG)

## Compiler Optimizations
### Cache Locality Optimization for Recursive Programs
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1474.JPG)

- TODO
- function recurresion とかspawnを使わないで、thread内で次の計算を呼び出すようにすると、同じ軽量thread内で呼び出すことになるので、cache hit 率が高くなる。

### Fusing Effectful Comprehensions
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1475.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1476.JPG)

- 小さいmoduler codeの組み合わせで複雑な処理を表現したい。しかし、performanceが悪くなってしまう。生成されたBSTをfuseする仕組みを作って効率的なコード生成を行う。

### Generalizations of the Theory and Deployment of Triangular Inequality for Compiler-Based Strength Reduction
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1477.JPG)

- 三角不等式による[演算子強度低減](https://ja.wikipedia.org/wiki/%E6%BC%94%E7%AE%97%E5%AD%90%E5%BC%B7%E5%BA%A6%E4%BD%8E%E6%B8%9B)の最適化を行う

### ALIVE-INFER: Data-Driven Precondition Inference for Peephole Optimizations in LLVM
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1478.JPG)

- 局所最適化

## Language Implementation
### Bringing the Web up to Speed with WebAssembly ( ＊＊ Distigwish ＊＊ )
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1479.JPG)

### Miniphases: Compilation using Modular and Efficient Tree Transformations
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1480.JPG)

### Proactive and Adaptive Energy-Aware Programming with Mixed Typechecking
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1481.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1482.JPG)

### Simple, fast and safe manual memory management
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1483.JPG)

## Concurrency Analysis
### BARRACUDA: Binary-level Analysis of Runtime RAces in CUDA programs
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1484.JPG)

### BigFoot: Static Check Placement for Dynamic Race Detection ( **Best Artifact** )
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1485.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1486.JPG)

- メモリアクセスをする箇所全てでcheckをしていたが、静的解析を先に行うことでcheckする箇所を減らした。

### Dynamic Race Prediction in Linear Time
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1487.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1488.JPG)

### Systematic Black-Box Analysis of Collaborative Web Applications
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1489.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1490.JPG)

## Dynamic Analysis and Testing

### Achieving High Coverage for Floating-point Code via Unconstrained Programming
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1491.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1492.JPG)

### Instruction Punning: Lightweight Instrumentation for x86-64
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1493.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1494.JPG)

### Low Overhead Dynamic Binary Translation on ARM (＊＊ Distigwish ＊＊)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1495.JPG)

### Skeletal Program Enumeration for Rigorous Compiler Testing
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1496.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1497.JPG)

## Static Analysis
### Compositional Recurrence Analysis Revisited
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1498.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1499.JPG)

### Context Transformations for Pointer Analysis
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1500.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1501.JPG)

### Efficient and Precise Points-to Analysis: Modeling the Heap by Merging Equivalent Automata
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1502.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1503.JPG)

### Static Deadlock Detection for Asynchronous C# Programs
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1504.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1505.JPG)

## Synthesis
### Component-based Synthesis of Table Consolidation and Transformation Tasks from Examples
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1512.JPG)

### Network Configuration Synthesis with Abstract Topologies
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1513.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1514.JPG)

### Synthesizing Highly Expressive SQL Queries from Input-Output Examples
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1515.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1516.JPG)

### Synthesizing Memory Models from Framework Sketches and Litmus Tests
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1517.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1518.JPG)

## Static Analysis and Security
### Decomposition Instead of Self-Composition for Proving the Absence of Timing Channels
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1519.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1520.JPG)

### Automatic Program Inversion using Symbolic Transducers
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1521.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1522.JPG)

### Control-Flow Recovery from Partial Failure Reports
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1523.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1524.JPG)

### Rigorous Analysis of Software Countermeasures against Cache Attacks
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1525.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1526.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1527.JPG)

## Parallelization and Concurrency 
### Synthesis of Divide and Conquer Parallelism for Loops
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1528.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1529.JPG)

### Futhark: Purely Functional GPU-programming with Nested Parallelism and In-place Array Updates
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1530.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1531.JPG)

### Gradual Synthesis for Static Parallelization
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1532.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1533.JPG)

### Verifying invariants of lock-free data structures with rely-guarantee and refinement type
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1534.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1535.JPG)

- TODO

## Functional Programming
### Compiling without continuations (＊＊ Distigwish ＊＊)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1538.JPG)

### FunTAL: Reasonably Mixing a Functional Language with Assembly

### HoTTSQL: Proving Query Rewrites with Univalent SQL Semantics
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1539.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1540.JPG)

### Levity Polymorphism
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1541.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1542.JPG)

## Correctness
### Repairing Sequential Consistency in C/C++11 (＊＊Distigwish＊＊)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1543.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1544.JPG)

- 既存のC++11の規約とPower PC、ARMの命令セットだと、正しく実装されていないメモリのconsistency実装がある。
- 新しいRC++11規約を作ってうまく問題を乗り越えた。

### ming Undefined Behavior in LLVM
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1545.JPG)

- Undefined という変数があるが、現状の規約だとconsistencyではない。
- freezeという関数を作って問題に対処した。

## Verified Computation
### A Formally Verified Compiler for Lustre
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1546.JPG)
[short slide](https://github.com/keisuke-umezawa/pldi2017/blob/master/image/IMG_1547.JPG)

### Flatten and Conquer (A Framework for Efficient Analysis of String Constraints)

## Systems and Performance
### Low-Synchronization, Mostly Lock-Free, Elastic Scheduling for Streaming Runtimes

### Practical Partial Evaluation for High-Performance Dynamic Language Runtimes

### Responsive Parallel Computation: Bridging Competitive and Cooperative Threading

### StreamQRE: Modular Specification and Efficient Evaluation of Quantitative Queries over Streaming Data
