# Ruta operacional

1. Fundamentals of Computer Science
    1. History and Evolution of Computing
        1. bla bla

    2. Discrete Mathematics and Logic
        1. Number Systems and Data Representation
            1. Positional systems and conversion
            2. Two's complement integers: range, addition/subtraction, and overflow
            3. Fixed point vs. floating point (IEEE 754): sign/exponent/mantissa
            4. Rounding modes and error (ULP); simple cancellation
            5. Detection of overflow and carry in the ALU (overview)
            6. Character encoding: ASCII/Unicode (UTF-8 preferred)
            7. Base conversion (successive division/repeated products)
            8. Special IEEE numbers (±0, subnormals, ±∞, NaN) — practical use
        2. Set Theory
            1. Basic operations (∪, ∩, \, Δ) and algebraic laws
            2. Cartesian product and construction of n-ary relations
            3. Subsets, partitions, and power set
            4. Indexed families; indexed union/intersection
            5. Finite/countable cardinality (useful for counting)
        3. Propositional and Predicate Logic
            1. Syntax/semantics; truth tables and useful equivalences
            2. Rules of inference (MP, MT) and argument validity
            3. Quantifiers ∀, ∃; scope and negation of quantifiers
            4. CNF/DNF and use for SAT/automation
            5. Notion of satisfiability and models; propositional resolution
            6. Bidirectional translation between natural language and formulas
        4. Proof Methodology
            1. Direct proof and proof by cases
            2. Contrapositive and contradiction (reductio)
            3. Simple and strong induction (equivalent)
            4. Loop invariants/variants for algorithm correctness
            5. Existence and uniqueness (standard techniques)
        5. Combinatorics and Counting Principles
            1. Sum and product rules; basic counting
            2. Permutations/combinations (with and without repetition)
            3. Binomial theorem and binomial coefficients
            4. Inclusion–exclusion (PIE) with canonical examples
            5. Pigeonhole principle (Dirichlet) applied
            6. Double counting and useful injections/bijections
        6. Discrete Probability
            1. Finite sample spaces; events and rules
            2. Conditional probability and basic Bayes
            3. Independence and product of events
            4. Bernoulli, Binomial, Geometric, Poisson distributions (typical use)
            5. Expectation/variance; indicators and linearity of expectation
            6. Markov/Chebyshev bounds (coarse estimates)
        7. Relations and Functions
            1. Relations: reflexive, symmetric, transitive
            2. Closures (reflexive/symmetric/transitive) and Warshall’s algorithm (idea)
            3. Equivalence relations and associated partitions
            4. Partial/total orders and Hasse diagrams
            5. Functions: domain/codomain, injective/surjective/bijective
            6. Composition and monotonicity
        8. Boolean Algebra
            1. Axioms and theorems; principle of duality
            2. CNF/DNF and correspondence with propositional logic
            3. Functionally complete sets (NAND/NOR)
            4. Karnaugh maps (2–4 variables) for simplification
            5. Quine–McCluskey method (outline)
            6. Modeling combinational circuits (logical level)
        9. Recurrences and Generating Functions
            1. Linear recurrences with constant coefficients
            2. Characteristic equation and repeated roots
            3. Non-homogeneous recurrences (simple particular solution / undetermined coefficients)
            4. Iteration/substitution and telescoping
            5. OGF/EGF: definition and basic operations
            6. Solving recurrences via generating functions
            7. Master theorem (statement) for divide & conquer
            8. Classic examples: Fibonacci and simple counting
        10. Number Theory and Modular Arithmetic
            1. gcd and Euclidean algorithm; Bézout identity
            2. Congruences and rings Z_n; modular inverse
            3. Chinese Remainder Theorem and composition of moduli
            4. Euler’s phi and Euler’s theorem; Fermat’s little theorem (use)
            5. Efficient modular exponentiation (mathematical idea)
            6. Modular hashing and dispersion (intuition)
        11. Linear Algebra for Computation (Discrete)
            1. Vectors/matrices over GF(2) and operations
            2. Linear systems mod 2; rank–nullity (statement)
            3. Incidence/adjacency matrices and the graph Laplacian
            4. Discrete inner product/orthogonality (idea)
            5. Relation to linear codes (notion of syndrome)
            6. Matrix representation of relations/transformations
        12. Information Theory (Discrete)
            1. Entropy H(X) and key properties (chain rule, subadditivity)
            2. Mutual information I(X;Y) and dependence
            3. Prefix codes and Kraft–McMillan inequality
            4. Huffman (optimal average length) and arithmetic coding (idea)
            5. Shannon’s source coding theorem (statement) and compression limits
            6. Compression rates and practical redundancy
        13. Discrete Optimization and Polyhedra
            1. Linear programming (standard form) and duality (statement)
            2. Flows and cuts; max-flow/min-cut theorem (formulation)
            3. Matching in graphs (notion) and applications
            4. Integral polyhedra (overview) and relaxations
            5. Submodularity and the greedy algorithm (optimality in key classes)
            6. Integer programming: idea of cutting/rounding (high level)
        14. Markov Chains and Random Walks (Discrete)
            1. Transition matrix P and distribution after n steps (Pⁿ)
            2. Classification of states: recurrent/transient/periodic
            3. Stationary distribution and detailed balance
            4. Absorbing chains and expected hitting times (statements)
            5. Random walks on graphs and hitting-time ideas
            6. Mixing time and ergodicity (notion)
            7. PageRank as a stationary vector (linear formulation)
    3. Automata and Models of Computation
        1. Formal foundations and proof methods
            1. Alphabets, strings and languages
            2. Sets, relations, functions and closures
            3. Decision problems and encodings
            4. Proof techniques (induction, diagonalization, contradiction)
            5. Asymptotic notation and constructible functions
            6. Resource measurement (time/space)
        2. Logic and specification foundations
            1. Propositional logic (SAT): Boolean satisfiability
            2. First-order logic (FOL) and quantification
            3. Satisfiability Modulo Theories (SMT) solvers: modeling and automation
            4. Dependent types and correctness-by-construction (DTT)
        3. Automata and regular languages
            1. Deterministic and nondeterministic finite automata (DFA / NFA)
            2. ε-transitions and the power of nondeterminism
            3. Subset construction (NFA → DFA)
            4. Minimization and equivalence of automata
            5. Regular expressions (RE) ↔ automata
            6. Closure properties and decidability
            7. Pumping lemma for regular languages
        4. Context-free languages and pushdown automata (PDA)
            1. Context-free grammars ↔ PDA
            2. Chomsky Normal Form (CNF) and transformations
            3. Top-down (LL) and bottom-up (LR) parsing; parse trees
            4. Acceptance by empty stack vs final state
            5. Closure properties and decidability of CFLs
            6. Pumping lemma for context-free languages
        5. Chomsky hierarchy and equivalent models
            1. Type 3 ↔ DFA / NFA / RE
            2. Type 2 ↔ PDA
            3. Type 1 ↔ Linear bounded automata (LBA)
            4. Type 0 ↔ Turing machines (TM)
            5. Linear grammars (left/right)
            6. Attributed grammars and semantics (compilers)
            7. Expressive power and practical uses
        6. Turing machines and variants
            1. Formal model and tape encoding
            2. Determinism, nondeterminism and variants (stay‑put, multi‑tape, multi‑track)
            3. Universal Turing machine and self‑interpretation
            4. Time complexity (DTIME) and space complexity (DSPACE)
            5. Limits of decidability (overview)
        7. Computability and decidability
            1. Lambda calculus and primitive / general recursive functions
            2. Halting problem
            3. Recursive and recursively enumerable languages (RE)
            4. Many‑one and Turing reductions; Turing degrees
            5. Rice’s theorem and variants
            6. Partially decidable problems and reduction patterns
            7. Fundamental barriers of computation
            8. Kolmogorov complexity (KC) and algorithmic randomness
        8. Computational complexity
            1. Classes P, NP and co‑NP: polynomial‑time verification
            2. Polynomial‑space complexity (PSPACE / NPSPACE)
            3. Exponential complexity (EXP / NEXP)
            4. Polynomial hierarchy (PH)
            5. Counting complexity (#P)
            6. Alternation (APTIME / APSPACE) and oracle machines
            7. Open relationships (P vs NP, etc.)
        9. Reductions and completeness
            1. Polynomial‑time (Karp) and Turing reductions
            2. NP‑complete problems: SAT, 3‑SAT, CLIQUE, VERTEX‑COVER
            3. PSPACE and NEXP complete examples
            4. Log‑space reductions (L / NL)
            5. Parsimony reductions and counting (#P‑completeness)
            6. Hardness under different models and optimization
            7. Practical applications and design guided by completeness
        10. Randomization, approximation and derandomization
            1. Probabilistic classes (BPP / RP / co‑RP / ZPP)
            2. Randomized algorithms (Monte Carlo / Las Vegas) and amplification
            3. Probabilistically Checkable Proofs (PCP) and hardness of approximation
            4. Approximation schemes (PTAS / FPTAS)
            5. Pseudorandom generators (PRG) and derandomization (RL vs L)
            6. Probabilistic finite automata (PFA)
        11. Advanced complexity and current frontiers
            1. Circuit complexity (AC⁰ / NC / P‑poly)
            2. Communication complexity (protocols, rank, lower bounds)
            3. Descriptive complexity (FO / MSO): Fagin’s theorem
            4. Parameterized complexity (FPT / W‑hierarchies / kernels)
            5. Fine‑grained complexity (SETH / OV / APSP‑hardness)
            6. Average‑case complexity and cryptography (one‑way functions)
            7. Constraint Satisfaction Problems (CSP) and complexity dichotomies
            8. Sublinear and streaming computation (streaming / sketching / F₀ / F₂)
            9. Lightweight verification and active learning (property testing)
        12. Formal verification and reasoning
            1. Temporal logics (LTL / CTL / CTL*)
            2. Model checking
            3. Hoare logic and program contracts
            4. Dependent types and correctness‑by‑construction (Coq / Agda)
            5. SMT solvers
            6. Security and isolation guarantees
        13. Quantum computing
            1. Qubits, superposition and measurement
            2. Quantum gates and algorithms (Shor / Grover)
            3. Quantum complexity classes (BQP / QMA)
            4. Error correction and noise thresholds
            5. Adiabatic computing and alternative models
            6. Quantum query and communication complexity
        14. Physical limits of computation
            1. Thermodynamics of information (Landauer’s bound)
            2. Reversible computation and energy cost
            3. Speed limits (Margolus–Levitin / Bremermann)
            4. Relativistic constraints and causality
            5. Analog computing and hypercomputation
            6. Miniaturization and physical stability
        15. Applications and bridges
            1. Grammars and compilers (static analysis)
            2. Logical modeling and verification in engineering (SAT / SMT)
            3. Algorithm design guided by hardness and approximability
            4. Data science and theoretical learning (PAC / VC)
            5. Integrative case studies (end‑to‑end)
    4. Computer Architecture
        1. Architectural models (von Neumann, Harvard)
            1. Classical von Neumann architecture
            2. Harvard architecture and separation of data/instructions
            3. Modified Harvard in modern processors
            4. Dataflow architectures
            5. Stack‑oriented architectures
            6. Register‑oriented machines
            7. VLIW architectures (very long instruction word)
            8. Vector / SIMD architectures
            9. Transactional architectures
            10. Reconfigurable and specialized architectures
        2. CPU and microarchitecture
            1. Control unit (hardwired vs microprogrammed)
            2. ALU and FPU
            3. Pipeline and stage segmentation
            4. Out‑of‑order execution
            5. Multiple issue and superscalar designs
            6. Branch prediction and speculation
            7. Register renaming and dependency elimination
            8. Instruction reordering (ROB and buffers)
            9. Micro‑op cache and processor front‑end
            10. Hyper‑Threading / SMT and intra‑core parallelism
            11. Dedicated vector / SIMD units
            12. Separation of front‑end and back‑end
        3. Memory hierarchy
            1. Architectural and physical registers
            2. L1 data and instruction caches
            3. Private per‑core L2 caches
            4. Shared L3 cache in multicore
            5. Replacement policies (LRU, pseudo‑LRU, FIFO)
            6. Write policies (write‑through / write‑back)
            7. Main memory DRAM / DDR
            8. High‑Bandwidth Memory (HBM)
            9. Fast persistent memory (NVRAM / PMem)
            10. Virtual memory and TLB
            11. Paging, segmentation and protection
            12. NUMA and memory affinity
        4. Instruction set architectures (ISA)
            1. CISC (e.g., x86 / x86‑64)
            2. RISC (e.g., ARM / RISC‑V)
            3. Reduced ISAs for embedded (microcontrollers)
            4. VLIW and packed instruction sets
            5. SIMD and vector extensions (SSE, AVX, NEON, SVE)
            6. AI / matrix‑oriented extensions (AMX, tensor ops)
            7. Atomic instructions and synchronization
            8. Privileged modes and user/kernel separation
            9. Compressed instruction sets
            10. Hardware crypto extensions (AES, SHA)
        5. Instruction‑level parallelism
            1. Basic and deep pipelining
            2. Superscalar and multiple issue
            3. Tomasulo’s algorithm and dynamic scheduling
            4. Speculative execution safety
            5. Predication and conditional execution
            6. VLIW and explicit ILP
            7. Loop unrolling
            8. Software pipelining
            9. Instruction fusion and macro‑op fusion
            10. Physical and security limits of ILP
        6. Multicore and multiprocessor architectures
            1. SMP (symmetric multiprocessing)
            2. Homogeneous CMP multicore
            3. Heterogeneous / big.LITTLE designs
            4. Manycore and massive parallelism
            5. GPU‑style parallelism
            6. NUMA and non‑uniform memory access
            7. Directory‑based coherence
            8. Coherence protocols (MESI / MOESI / MESIF)
            9. Cache snoop interconnects
            10. Hardware‑assisted virtualization for multicore
        7. Domain‑specific accelerators
            1. GPUs (SIMT parallelism)
            2. TPUs / NPUs / inference accelerators
            3. DSPs for signal and audio
            4. Reconfigurable FPGAs
            5. Dedicated ASICs
            6. Cryptographic accelerators
            7. Network accelerators (offload for crypto / compression)
            8. Multimedia encoders / decoders
            9. CPU offload for storage tasks
            10. SmartNIC / DPU for data‑plane processing
        8. Interconnects and system buses
            1. Traditional buses (FSB)
            2. Integrated memory controllers
            3. PCI Express and extensions
            4. Point‑to‑point interconnects (QPI, UPI, Infinity Fabric)
            5. Networks‑on‑Chip (NoC)
            6. On‑chip topologies (mesh, ring, crossbar, fat‑tree)
            7. Latency vs bandwidth in interconnect
            8. Cache coherence over bus/interconnect
            9. Emerging optical / photonic interconnects
            10. Scalability in multi‑node / multiprocessor systems
        9. Input/Output (I/O) and controllers
            1. DMA controllers and direct memory access
            2. Storage controllers (SATA, NVMe)
            3. Network controllers (traditional NICs and SmartNICs)
            4. Peripheral buses (USB, Thunderbolt)
            5. Root complex and PCIe bridges
            6. Memory‑mapped I/O (MMIO)
            7. Programmed I/O (PIO) vs interrupt‑driven I/O
            8. Interrupts and IRQ control
            9. APIC / LAPIC / IOAPIC
            10. MSI / MSI‑X and advanced signaling
        10. Power management and thermal performance
            1. Dynamic Voltage and Frequency Scaling (DVFS)
            2. Power gating / clock gating
            3. Thermal throttling and thermal control
            4. Power budget (TDP / power budget)
            5. On‑chip thermal sensors
            6. Thermal balancing across cores
            7. Low‑power / idle states (C / P / S states)
            8. Adaptive scaling according to load
            9. Firmware / BIOS policies
            10. Thermal design and physical dissipation
    5. Data Structures and Algorithms
        1. Time and space complexity (asymptotic notation)
            1. Big O
            2. Ω and Θ
            3. Best case, worst case and average case
            4. Amortized complexity
            5. Memory and cache costs
            6. Memory access complexity
        2. Algorithmic efficiency analysis
            1. Counting dominant operations
            2. Analysis of nested loops
            3. Recurrence analysis
            4. Early optimization vs micro-optimizations
            5. Time vs space trade-offs
            6. Asymptotic scalability
        3. Linear structures (lists, stacks, queues, deques)
            1. Arrays and contiguous lists
            2. Singly and doubly linked lists
            3. Stacks
            4. Queues
            5. Deques (double-ended queues)
            6. Circular lists
            7. Blocked / chunked lists
            8. Circular buffers
            9. Implementation on dynamic memory
            10. Costs of insertion, deletion and access
        4. Trees, heaps, tries and hierarchical structures
            1. Binary trees
            2. Binary search trees (BST)
            3. Balanced trees (AVL, Red-Black)
            4. B-trees and B+ trees
            5. Segment trees
            6. Fenwick / Binary Indexed Trees
            7. Heaps
            8. Priority queues
            9. Binomial and Fibonacci heaps
            10. Tries
            11. Compressed tries and radix trees
            12. Quadtrees and octrees
            13. Interval trees and range trees
            14. Decision trees
            15. Suffix trees
        5. Graphs
            1. Graph representations (adjacency matrix, adjacency list)
            2. Directed and undirected graphs; degree, paths, cycles, connectivity
            3. Weighted graphs
            4. Minimum spanning trees
            5. Shortest paths
            6. Cycle detection
            7. Topological sorting
            8. Strongly connected components
            9. Maximum flows
            10. Matching and pairings
            11. Bipartite graphs
            12. Connectivity and bridges
            13. Dynamic and online graphs
            14. Probabilistic graphs
            15. Coloring

        6. Hashing and hash tables
            1. Hash functions
            2. Collisions and resolution methods
            3. Open addressing
            4. Separate chaining
            5. Rehashing and load factor
            6. Consistent hashing
            7. Bloom filters
            8. Cuckoo hashing
            9. Immutable hash tables
            10. Trade-offs between hashes and balanced trees
        7. Sorting and searching algorithms
            1. Linear search
            2. Binary search
            3. Comparison sorts (quicksort, mergesort, heapsort)
            4. Non-comparison sorts (counting sort, radix sort, bucket sort)
            5. Stability of sorting
            6. Selection of the k-th element
            7. External sorting
            8. Partial and incremental sorting
            9. Approximate search
        8. Recursion and divide-and-conquer
            1. Classical recurrences
            2. Problem decomposition
            3. Mergesort / Quicksort as divide-and-conquer
            4. Recursive binary search
            5. Pruning and backtracking recursion
            6. Tail recursion and tail-call optimization
            7. Maximum depth and stack frames
        9. Dynamic programming and memoization
            1. Overlapping subproblems
            2. States and transitions
            3. Bottom-up tables
            4. Top-down memoization
            5. Space optimization
            6. Incremental reuse of results
            7. DP with solution reconstruction
            8. DP on directed acyclic graphs
            9. Probabilistic DP
        10. Concurrency algorithms and synchronization
            1. Critical sections
            2. Mutual exclusion
            3. Locks, mutexes and semaphores
            4. Barriers and cyclic barriers
            5. Message passing
            6. Lock-free algorithms
            7. Wait-free algorithms
            8. Memory consistency
            9. Consensus algorithms
            10. Deadlocks and prevention
            11. Scheduling and fairness
            12. Contention control
        11. Immutable or persistent data structures
            1. Persistent trees
            2. Persistent lists
            3. Immutable hash tries
            4. Copy-on-write
            5. Structural versioning
            6. Structural sharing
            7. Costs of logical mutation
            8. Purely functional data structures
        12. Probabilistic and approximate algorithms
            1. Monte Carlo algorithms
            2. Las Vegas algorithms
            3. Random sampling
            4. Data sketches
            5. Approximate counting and cardinality estimation
            6. Streaming sketches and algorithms
            7. Approximations for NP-hard problems
            8. Randomization for load balancing
            9. Probabilistic hashing
            10. Error tolerance and confidence control

    6. Operating Systems (processes, threads, memory, scheduling)
        1. Kernel design
            1. Monolithic kernel
            2. Microkernel
            3. Hybrid kernel and mixed variations
            4. Exokernel and least privilege
            5. Modular kernel with dynamic loading
            6. Interrupt control and exception handling
            7. Kernel services vs user-space services
            8. Stable interfaces (ABI/driver ABI)
            9. Privilege separation and execution modes
            10. Kernel evolution and binary compatibility
        2. Processes
            1. Process creation and termination
            2. Classic states (ready / running / blocked / zombie)
            3. Address space and isolation
            4. PCB (Process Control Block) and metadata
            5. Loading and linking executables
            6. Signals and signal handling
            7. fork / exec / wait and context inheritance
            8. Priority, niceness and scheduling policy
            9. Resource limits and quotas
            10. Credentials and process identity control
        3. Threads
            1. User threads vs kernel threads
            2. 1:1, M:1 and M:N models
            3. Context switching between threads
            4. Thread-local storage (TLS)
            5. Thread pools and reuse
            6. Fibers and lightweight coroutines
            7. CPU affinity and pinning
            8. Scheduling at thread level in SMT/Hyper-Threading
            9. Synchronization between threads in shared memory
            10. Costs of massive concurrency
        4. Scheduling (CPU scheduling)
            1. Cooperative vs preemptive scheduling
            2. Round Robin and fair share
            3. Fixed-priority scheduling
            4. Multi-level feedback queue (MLFQ)
            5. Completely Fair Scheduler (CFS) and equivalents
            6. Scheduling with deadlines and real-time
            7. CPU affinity and load balancing
            8. Priority inversion and priority inheritance
            9. Dispatch latency and quantum
            10. Policies for servers and low-latency workloads
        5. Memory management
            1. Isolated virtual address spaces
            2. Demand paging
            3. Multilevel page tables
            4. TLB and TLB misses
            5. Swapping and secondary storage
            6. Copy-on-write and efficient sharing
            7. ASLR (Address Space Layout Randomization)
            8. Huge pages / superpages
            9. Memory-mapped files (mmap)
            10. Page reclamation and replacement policies
            11. NUMA-aware memory management
            12. Execute protection and NX-marked regions
        6. Synchronization and concurrency
            1. Basic mutexes and locks
            2. Semaphores and counters
            3. Monitors and condition variables
            4. Critical sections and mutual exclusion
            5. Synchronization barriers
            6. Spinlocks and busy-wait locks
            7. Read-Copy-Update (RCU)
            8. Atomic operations (CAS / LL-SC)
            9. Deadlock, livelock and starvation
            10. Lock-free and wait-free techniques
        7. Inter-process communication (IPC)
            1. Pipes and FIFOs
            2. Local / network sockets
            3. Shared memory
            4. Signals and notifications
            5. Message queues
            6. RPC / local gRPC
            7. Asynchronous kernel calls
            8. Serialization and marshalling of data
            9. Synchronization of shared access
            10. Security and permission control in IPC
        8. File system and VFS (Virtual File System)
            1. Inodes, metadata and descriptors
            2. Hierarchical directory tree
            3. Journaling file systems and crash consistency
            4. Copy-on-write file systems (ZFS, btrfs)
            5. Mounting, namespaces and isolated views
            6. Page cache and buffer cache
            7. Locking and concurrency in file access
            8. POSIX permissions and extended ACLs
            9. Distributed / networked file systems
            10. FUSE and user-space file systems
        9. I/O management and drivers
            1. Kernel vs user-space drivers
            2. Interrupt handling and IRQ
            3. DMA and direct memory transfer
            4. Blocking vs non-blocking operations
            5. Polling, select, epoll, kqueue
            6. io_uring and modern async I/O
            7. Disk schedulers and I/O prioritization
            8. Buffering and I/O caching
            9. Hotplug and dynamic hardware detection
            10. Advanced network and storage device management
        10. Security and isolation
            1. User/kernel modes and privileges
            2. File permissions and access control
            3. User/group management and credentials
            4. Sandboxing (seccomp, pledge, capsicum)
            5. Namespaces and cgroups for isolation
            6. Mandatory access control (SELinux, AppArmor)
            7. Execute protection (NX / DEP)
            8. Memory isolation between processes
            9. KPTI and kernel vulnerability mitigations
            10. Signed binary verification
        11. Syscalls and execution modes
            1. Entry to the kernel (syscall/sysenter/trap)
            2. System call ABI
            3. User space → kernel space transition
            4. Emulation and syscall compatibility
            5. Blocking vs non-blocking calls
            6. Virtualization / containerization of syscalls
            7. libc / runtime as wrapper layer
            8. Mode switch costs and latency
            9. Traceability of system calls
            10. Security and filtering of sensitive syscalls
        12. Accounting, monitoring and metrics
            1. CPU, memory and I/O statistics per process
            2. Performance counters (perf, PMU)
            3. Kernel tracing (ftrace, eBPF)
            4. Security audit and critical events
            5. Resource control with cgroups and quotas
            6. Syscall telemetry and usage profiles
            7. Centralized kernel event logging
            8. Disk, CPU and memory quota enforcement
            9. Real-time observability for diagnostics
            10. Continuous profiling and postmortem analysis

    7. Virtualization and Containerization
        1. Virtualization concepts
            1. Full hardware virtualization
            2. Paravirtualization and reduced overhead
            3. Hardware acceleration (VT-x, AMD-V)
            4. Full platform emulation
            5. Unikernels and minimal specialized systems
            6. Nested virtualization
            7. Software-enforced sandboxing
            8. MicroVMs and ultra-lightweight environments
            9. Resource isolation and layered security
            10. Trade-offs between flexibility, overhead and density
        2. Hypervisors
            1. Type-1 (bare metal) hypervisors
            2. Type-2 (hosted) hypervisors
            3. KVM and Linux virtualization
            4. Xen and guest/control domain separation
            5. VMware ESXi and enterprise virtualization
            6. Hyper-V and Windows environments
            7. QEMU and full emulation
            8. Device passthrough (VFIO, SR-IOV)
            9. virtio and paravirtualized drivers
            10. Management of virtual devices and hotplug
        3. Hardware virtualization vs OS-level virtualization
            1. Full VMs (guest OS per VM)
            2. Kernel-shared containers
            3. Jail / chroot and basic isolation
            4. Zones / LDOMs and logical partitions
            5. MicroVMs (Firecracker, etc.)
            6. User/process-level sandboxing
            7. Namespace isolation
            8. cgroup-based resource isolation
            9. Security reinforced by policy
            10. Overhead and density trade-offs by type
        4. Containers
            1. Container runtimes (Docker, containerd, CRI-O)
            2. OCI standards and runtime compatibility
            3. Rootless containers and least privilege
            4. Pods and container grouping
            5. Volumes, mounts and state persistence
            6. Sidecar patterns and auxiliary containers
            7. Injection of configuration and secrets
            8. Immutable image deployment patterns
            9. Resource policies per container
            10. Reuse of common base images
        5. Namespaces and cgroups
            1. PID namespaces
            2. Network namespaces
            3. Mount namespaces
            4. UTS / hostname namespaces
            5. IPC namespaces
            6. User namespaces
            7. cgroups v1 and hierarchical control
            8. unified cgroups v2
            9. CPU / memory / I/O limits per group
            10. Prioritization and fair sharing of resources
        6. Image building and management
            1. Dockerfile and multi-stage builds
            2. Layers and union filesystems (overlayfs)
            3. Immutable and reproducible images
            4. Distroless images and minimal attack surface
            5. Image signing, attestation and integrity
            6. Registries (private / public)
            7. SBOM and supply chain security
            8. Versioning and tagging (tags / digests)
            9. Size reduction and surface minimization
            10. Managing common base-image dependencies
        7. Virtual networking and SDN
            1. Virtual bridges and software switches
            2. NAT, port forwarding and external connectivity
            3. Overlay networks (VXLAN, GRE, Geneve)
            4. Open vSwitch and programmable switching
            5. CNI (Container Network Interface) and plugins
            6. Service mesh and L7 control
            7. Internal L4 / L7 load balancing
            8. Network policies
            9. Ingress / egress control
            10. Multi-tenant segmentation and traffic isolation
        8. Orchestration
            1. Kubernetes and control plane
            2. Pod scheduler and node assignment
            3. Declarative resources (Deployment, StatefulSet, DaemonSet, Job, CronJob)
            4. Services, internal load balancing and cluster DNS
            5. ConfigMaps, Secrets and dynamic configuration
            6. Horizontal and vertical autoscaling
            7. Operators / CRDs and extensibility
            8. Affinity, tolerations and taints
            9. Control plane vs data plane separation
            10. Rolling updates, canary and safe rollback
        9. Multi-tenant security and isolation
            1. seccomp and syscall filtering
            2. SELinux / AppArmor and mandatory controls
            3. Linux capabilities and least privilege
            4. Rootless runtimes and user namespace isolation
            5. Admission controllers and policy enforcement
            6. gVisor / Kata and VM-backed sandboxing
            7. Image signing and cryptographic validation
            8. Prevention and detection of container escapes
            9. Network policies per tenant / namespace
            10. Confidential computing and hardware-backed isolation
        10. Observability and debugging in virtualized environments
            1. Centralized collection of container logs
            2. Resource metrics (CPU, memory, I/O, network)
            3. Distributed tracing between services
            4. eBPF for lightweight kernel inspection
            5. Continuous profiling (perf, pprof)
            6. Ephemeral debug / inspection containers
            7. Port forwarding and introspective access
            8. Health checks (liveness / readiness / startup)
            9. Scheduler / runtime event observation
            10. Auditing syscalls, policy changes and security events
    8. Distributed storage and file systems
        1. Storage models
            1. Direct-attached storage (DAS)
            2. Network-attached storage (NAS)
            3. Storage area network (SAN / block storage)
            4. Horizontally scalable distributed storage
            5. Software-defined storage (SDS)
            6. Temperature hierarchy (hot / warm / cold)
            7. Immutable storage and WORM
            8. Persistent vs ephemeral volumes
            9. Replicated storage for availability
            10. Retention policies and data lifecycle
        2. Local file systems
            1. Extended-type file systems (EXT family)
            2. XFS and high sequential performance
            3. Btrfs and copy-on-write
            4. ZFS and end-to-end integrity
            5. NTFS and the Windows ecosystem
            6. APFS and optimization for modern devices
            7. Quotas and user/group limits
            8. Extended attributes and rich metadata
            9. Local snapshots
            10. Fault tolerance and self-healing
        3. Distributed file systems
            1. NFS and traditional network sharing
            2. SMB/CIFS and mixed environments
            3. CephFS and unified distributed storage
            4. Lustre and high-performance HPC storage
            5. GlusterFS and horizontal scaling
            6. HDFS and batch processing of large data
            7. Parallel systems oriented to throughput
            8. Remote mounts with local caching
            9. Consistency between client and server
            10. Distributed concurrency control
        4. Block, file and object storage
            1. Virtual blocks and assignable volumes (LUN)
            2. File-system-like systems with POSIX semantics
            3. Object storage (S3-style)
            4. Addressing by block / path / object ID
            5. Object versioning and retention
            6. Snapshots and fast clones
            7. Thin provisioning and deferred allocation
            8. Deduplication and compression
            9. Encryption at rest and key management
            10. Transparent replication across locations
        5. Replication and durability
            1. Synchronous replication between nodes
            2. Asynchronous geo-replication
            3. Configurable replication factor
            4. Erasure coding and fault tolerance
            5. Tolerance to disk / node / rack / zone failures
            6. Repair processes and anti-entropy
            7. Data placement policies by failure domain
            8. Write / read quorum strategies
            9. Durability and recovery objectives (RPO / RTO)
            10. Trade-offs between durability and latency
        6. Partitioning and sharding
            1. Static vs dynamic sharding
            2. Consistent hashing for stable distribution
            3. Online shard rebalancing
            4. Partitioning by range / time / key
            5. Metadata directories vs implicit routing
            6. Data locality vs uniform distribution
            7. Hotspots and load imbalance
            8. Tolerance to uneven growth
            9. Tenant / client shard isolation
            10. Reassignment after failures or expansions
        7. Consistency and coherence
            1. Strong consistency
            2. Eventual consistency
            3. Causal consistency and partial ordering
            4. Linearizability and strict guarantees
            5. Serializability and equivalence to sequential execution
            6. Cache coherence among replicas
            7. Invalidation vs update protocols
            8. Repeatable reads and snapshot isolation
            9. Dirty reads and visibility control
            10. Configurable policies per operation (read/write quorum)
        8. Metadata and consensus
            1. Dedicated metadata nodes
            2. Global maps of blocks / distributed inodes
            3. Lock managers and distributed exclusion
            4. Leader election and authority maintenance
            5. Consensus protocols (Raft, Paxos)
            6. Logical clocks and vector clocks
            7. Globally consistent namespaces
            8. Journaling and metadata change logs
            9. Split-brain prevention
            10. Coordinated recovery after metadata failures
        9. Failure recovery and journaling
            1. Write-ahead logging (WAL)
            2. Data journaling vs metadata-only journaling
            3. Consistent snapshots and checkpoints
            4. Rollback / roll-forward after crash
            5. Reconstruction of failed nodes or disks
            6. Geo-replication for disaster recovery
            7. Split-brain detection and resolution
            8. Scrubbing and data integrity checking
            9. Rehydration of volumes on new nodes
            10. Periodic restore testing
        10. Caching and storage tiering
            1. Client-side cache and fast local reads
            2. Server / edge node caching
            3. RAM / NVMe / SSD / HDD tier hierarchy
            4. Write-back vs write-through policies
            5. Adaptive prefetch and read-ahead
            6. Automatic tiering by access pattern
            7. Nearline / archive / cold storage tiers
            8. Distributed cache coherence
            9. Reducing perceived client latency
            10. Cost optimization per usable GB
        11. I/O performance and latency
            1. Latency vs throughput as key metrics
            2. IOPS, I/O queues and queue depth
            3. Alignment and optimal block size
            4. Queue parallelism (multiqueue)
            5. Load balancing across data nodes
            6. Amortization of random writes
            7. Log-structured compaction and rewrite
            8. Costs of fsync / flush for durability
            9. Minimizing latency jitter
            10. Optimization for sequential vs random workloads
    9. Networks and Protocols
        1. Networking fundamentals (OSI and TCP/IP models)
            1. Reference models and layers
            2. OSI model (physical, data link, network, transport, session, presentation, application)
            3. TCP/IP model (link, internet, transport, application)
            4. Encapsulation and decapsulation
            5. Data units per layer (frames, packets, segments)
            6. MTU and fragmentation
            7. RFCs, standardization and protocol governance
            8. Interoperability between layers and modularity
            9. Separation of control plane and data plane
            10. Broadcast domain vs collision domain
            11. Latency, throughput and packet loss as key metrics
        2. Addressing and routing
            1. Addresses and network forwarding
            2. IPv4 addressing and CIDR notation
            3. IPv6 addressing and extended space
            4. Subnetting and VLSM
            5. NAT and PAT (address translation and multiplexing)
            6. DHCP and dynamic assignment
            7. Address resolution (ARP / NDP)
            8. Static routing
            9. Dynamic routing (RIP, OSPF, IS-IS, BGP)
            10. ECMP (Equal-Cost Multi-Path)
            11. Anycast / unicast / multicast / broadcast
            12. MPLS and label-based forwarding
        3. Data link layer
            1. Local link and medium access
            2. Ethernet (cabling and switched)
            3. CSMA/CD and collision control
            4. VLAN (802.1Q) and logical layer-2 segmentation
            5. Trunking and VLAN tagging
            6. STP / RSTP / MSTP to prevent loops
            7. PPP / HDLC and point-to-point links
            8. Point-to-point networks vs broadcast networks
            9. Link-level flow control (PAUSE frames)
            10. Link aggregation (LACP / bonding)
            11. Port-level security (port security / 802.1X)
        4. Network layer
            1. Forwarding and delivery between networks
            2. IP (IPv4 / IPv6) and logical addressing
            3. ICMP / ICMPv6 for diagnostics and control
            4. Routers and routing tables
            5. TTL / Hop Limit and loop prevention
            6. Fragmentation and packet reassembly
            7. IP-level QoS (DSCP / ToS)
            8. Tunnels (GRE, IP-in-IP)
            9. NAT traversal and firewall penetration
            10. Forwarding and filtering at layer 3
            11. Basic network-layer security (L3 filters)
        5. Transport layer
            1. End-to-end delivery: reliable or unreliable
            2. TCP and connection-oriented control
            3. UDP and lightweight connectionless transport
            4. Multiplexing by logical ports
            5. Connection establishment (3-way handshake)
            6. Window-based flow control
            7. Retransmission, ACKs and reliability
            8. Segmentation and reordering
            9. Integrity checks (checksums)
            10. Persistent connections and keepalive
            11. Congestion control coupled to the transport
        6. Application layer
            1. Application protocols and high-level services
            2. DNS and name resolution
            3. HTTP/1.1 and the request/response model
            4. HTTP/2 and stream multiplexing
            5. HTTP/3 and transport over QUIC
            6. TLS and end-to-end encryption
            7. SMTP / IMAP / POP3 for email
            8. gRPC and binary contracts over HTTP/2
            9. WebSockets and persistent communication
            10. NTP and clock synchronization
            11. DHCP as a network configuration service
        7. Congestion control and Quality of Service (QoS)
            1. Traffic management and prioritization
            2. TCP congestion algorithms (Reno, Cubic, BBR)
            3. Traffic shaping vs policing
            4. Classification and marking (DSCP / CoS)
            5. Queueing disciplines (PQ, WFQ, DRR)
            6. RED / ECN and early congestion signaling
            7. Rate limiting per flow / client / class
            8. Prioritization for low-latency / real-time traffic
            9. SLAs and dedicated queues per service class
            10. Adaptive buffer control (bufferbloat mitigation)
            11. Congestion telemetry for dynamic tuning
        8. Network security
            1. Protection of infrastructure and data in transit
            2. Firewalls (stateful / stateless)
            3. Access control lists (ACLs)
            4. TLS / mTLS and point-to-point encryption
            5. IPsec (AH / ESP) and secure tunnels
            6. Layer-2 / layer-3 VPNs
            7. Network segmentation and microsegmentation
            8. IDS / IPS (intrusion detection and prevention)
            9. Zero Trust and continuous authentication
            10. Protection against spoofing / hijacking / MITM
            11. Egress / ingress filtering and outbound control
        9. Software-Defined Networking (SDN) and network virtualization
            1. Programmable networks and centralized control
            2. Separation of control plane and data plane
            3. OpenFlow and forwarding control
            4. Centralized SDN controllers
            5. vSwitch (e.g., Open vSwitch)
            6. Encapsulation VXLAN / NVGRE / Geneve
            7. SDN in data centers and private clouds
            8. Service function chaining and service insertion
            9. NFV (Network Function Virtualization)
            10. Large-scale virtualized L2/L3 overlays
            11. Declarative network policies and security as code
        10. Observability and network troubleshooting
            1. Monitoring, diagnosis and analysis
            2. Ping / traceroute / mtr and hop tracing
            3. Packet capture (tcpdump, Wireshark)
            4. Inspecting sockets and open ports (netstat / ss / lsof -i)
            5. Network telemetry (SNMP / NetFlow / sFlow)
            6. Interface metrics (errors, drops, collisions)
            7. Latency, jitter and packet loss
            8. Active vs passive monitoring
            9. Firewall / IDS / load balancer logs
            10. Topology maps and service dependency graphs
            11. Early alerts and incident correlation
        11. Low-latency networks
            1. Extreme optimization of the data path
            2. Kernel bypass techniques (DPDK, RDMA)
            3. Jumbo frames and MTU tuning
            4. Interrupt coalescing and interrupt reduction
            5. IRQ affinity / NIC queue pinning
            6. NIC offloads (checksum offload, TSO, LRO)
            7. User-space networking and dedicated polling
            8. Fiber optics and low-latency direct links
            9. Deterministic, controlled routing (private peering)
            10. Minimizing intermediate queues (buffer tuning)
            11. Precise time synchronization between critical nodes
        12. SDN (Software Defined Networking)
            1. Logical central control of the network
            2. Centralized routing control
            3. Programmable network APIs
            4. Network slicing and logical segmentation
            5. Dynamic reconfiguration of paths
            6. Declarative, auditable security policies
            7. Multi-tenant virtual topologies
            8. Dynamic load balancing and failover automation
            9. Integration with orchestrators (Kubernetes / NFV MANO)
            10. Real-time telemetry for optimization
            11. On-demand QoS adjustment per application or flow
        13. Distributed networks
            1. Topologies without a single point of control
            2. Peer-to-peer (P2P) networks
            3. Gossip / epidemic dissemination protocols
            4. Eventual consistency in state dissemination
            5. Structured overlays (DHT)
            6. Unstructured overlays (flooding / random walk)
            7. Mesh routing and cooperative multi-hop
            8. Federations and autonomous domains
            9. Edge networks / distributed edge computing
            10. CDNs and content proximity
            11. Mitigating partitions and unstable links
        14. Delay-/disruption-tolerant networks and hostile environments
            1. Resilient networks under adverse conditions
            2. Disruption-tolerant routing (DTN)
            3. Store-and-forward intermediate storage
            4. Networks with intermittent / high-latency links
            5. Opportunistic protocols and delayed delivery
            6. Aggressive redundant replication
            7. Partition tolerance and partial reconnections
            8. Resilient multipath routing
            9. Satellite / RF / ad-hoc links
            10. Self-configuration without fixed infrastructure
            11. Robust security against untrusted nodes
        15. Modern transport
            1. Evolution of reliable and secure transport
            2. QUIC and encrypted transport over UDP
            3. HTTP/3 over QUIC
            4. Multipath TCP (MPTCP)
            5. SCTP and multistreaming
            6. Zero round trip initial (0-RTT / Zero-RTT)
            7. Latency-aware congestion control (BBR)
            8. Cryptographic offload in transport
            9. Multiplexed persistent connections
            10. Connection migration between interfaces/networks
            11. Prioritization of flows within a single connection
    10. Client-server and peer-to-peer models
        1. Traditional client-server architecture
            1. Classic components and basic deployments
            2. Thin client vs thick client
            3. Centralized monolithic server
            4. Front-end / back-end separation
            5. Load balancers in front of servers
            6. Vertical vs horizontal scaling
            7. Session management and server-side authentication
            8. Multi-tier architectures (presentation / logic / data)
            9. Fronting cache (reverse proxy)
            10. High availability with active replicas
            11. Centralized state persistence
        2. Stateless vs stateful
            1. Managing state between requests
            2. Persistent sessions in server memory
            3. Sticky sessions and instance affinity
            4. External session storage (distributed cache / KV store)
            5. Idempotency and safe retries
            6. Tolerance to restarts and instance rotation
            7. Persisting context in the client (signed tokens)
            8. Cookies / JWT as session transport
            9. Horizontal scalability of stateless services
            10. Consistency of shared state across nodes
            11. Gradual migration from stateful to stateless
        3. Microservices and decoupled services
            1. Domain-driven design and independent deployment
            2. Services with clear boundaries of responsibility
            3. API Gateway as unified façade
            4. Mutual authentication and encryption (mTLS between services)
            5. Service mesh for routing and security
            6. Circuit breakers and internal fault tolerance
            7. Independent deployment by service/team
            8. Observability per service (distributed tracing)
            9. Explicit contracts (OpenAPI / protobuf)
            10. Separate databases per service
            11. Independent versioning of each service
        4. Synchronous vs asynchronous communication
            1. Message exchange patterns
            2. Traditional HTTP request/response
            3. Synchronous gRPC and binary contracts
            4. Proprietary binary RPC
            5. Asynchronous messaging via queues
            6. Event-driven architectures and event sourcing
            7. Bidirectional streaming and real time
            8. Retries with exponential backoff
            9. Timeouts and propagated cancellation
            10. Delivery guarantees at-least-once / exactly-once
            11. Encapsulation of failures from slow services
        5. Pub/Sub and message queues
            1. Decoupled communication and reliable delivery
            2. Durable queues
            3. Topics with multiple subscribers
            4. Delivery guarantees (at-least-once / at-most-once / exactly-once)
            5. Topic partitioning and horizontal scalability
            6. Message ordering within a partition
            7. Historical retention and event replay
            8. Backpressure and consumer control
            9. Dead-letter queues for problematic messages
            10. Prioritization of critical flows
            11. Isolation by tenant or message type
        6. Peer-to-peer
            1. Distributed networks without central authority
            2. Serverless networks
            3. Distributed hash tables (DHT)
            4. Initial discovery (bootstrap peers)
            5. NAT traversal and hole punching
            6. Gossip / epidemic dissemination
            7. Distributed replication of data among peers
            8. Incentives and reputation among nodes
            9. Eventual consistency and reconciliation
            10. Privacy and anonymization in P2P
            11. Resistance to censorship and partitions
        7. Service discovery and coordination
            1. Mechanisms to locate and keep services available
            2. Service registries
            3. Heartbeats and health checks
            4. DNS-based discovery
            5. Sidecar / local agent-based discovery
            6. Leader election and dynamic roles (leader / follower)
            7. Distributed locks and mutual exclusion
            8. Dynamic distributed configuration
            9. Versioned configuration and gradual rollout
            10. Logical clocks and version control
            11. Automatic reconfiguration after failures
        8. Resilience patterns
            1. Strategies to withstand partial failures
            2. Circuit breaker
            3. Bulkhead isolation (resource isolation)
            4. Timeouts and controlled retries
            5. Fallbacks and graceful degradation
            6. Rate limiting and overload protection
            7. Reactive autoscaling under pressure
            8. Canary releases and blue-green deployments
            9. Chaos testing / fault injection
            10. Idempotent retries and deduplication
            11. Early telemetry for rapid rollback
        9. Versioning and compatibility of interfaces
            1. Safe evolution of contracts and APIs
            2. API versioning (v1, v2, etc.)
            3. Backward compatibility
            4. Forward compatibility
            5. Evolution of schemas and data contracts
            6. Feature flags and behavior toggles
            7. Gradual deprecation and removal windows
            8. Content negotiation
            9. Dual write / dual read strategies
            10. Beta / pre-release channels for selected clients
            11. Synchronization of changes between frontend and backend
    11. Consistency and fault tolerance
        1. CAP theorem and trade-offs
            1. Properties and limits in distributed systems
            2. Consistency (single coherent view of data)
            3. Availability (responding without error)
            4. Partition tolerance (survive network partitions)
            5. CA vs CP vs AP as design choices
            6. Impact of network partitions on availability
            7. Systems oriented to high availability
            8. Systems oriented to strict consistency
            9. Operational vs theoretical trade-offs
            10. Practical interpretation of CAP in real clouds
            11. Relation to PACELC (latency vs consistency)
        2. Consistency models
            1. Guarantees of visibility and update ordering
            2. Strong consistency
            3. Eventual consistency
            4. Causal consistency
            5. Read-your-writes
            6. Monotonic reads / monotonic writes
            7. Linearizability
            8. Sequential consistency
            9. Snapshot isolation
            10. Serializability
            11. Regional bias / preferential local reads
        3. Clocks and event ordering
            1. Time and causality in distributed systems
            2. Physical clocks
            3. Logical clocks (Lamport clocks)
            4. Vector clocks and partial order
            5. Multiversion concurrency control (MVCC)
            6. Total vs partial ordering of events
            7. Causality and the happens-before relation
            8. Clock skew and drift
            9. Distributed time synchronization (NTP/PTP)
            10. Logical timestamps in distributed storage
            11. Conflict resolution based on timestamps
        4. Consensus and replication
            1. Agreeing on a consistent state among multiple nodes
            2. Primary-secondary (leader-follower) replication
            3. Multi-leader (multi-master) replication
            4. Leaderless replication (gossip / eventual)
            5. Raft (log-replicated consensus)
            6. Paxos (fault-tolerant consensus)
            7. Read / write quorums
            8. Write-ahead log (WAL) and replay
            9. Consistency of critical metadata
            10. Leader re-election and service continuity
            11. Propagation of acknowledgements and distributed commit
        5. High availability and failover
            1. Design for operational continuity
            2. Automatic vs manual failover
            3. Active-active redundancy
            4. Active-passive redundancy
            5. Load balancing with health checks
            6. Geographic replication and multi-region
            7. Availability zones and failure domains
            8. Circuit breakers and selective dependency cutting
            9. Controlled graceful degradation
            10. Automatic scaling under degradation
            11. Scheduled disaster recovery (DR) exercises
        6. Byzantine fault tolerance
            1. Surviving malicious or arbitrary node behavior
            2. Byzantine model vs crash-stop model
            3. Byzantine Fault Tolerant replication (BFT)
            4. PBFT and consensus variants for Byzantine faults
            5. Cryptographic signatures and message authentication
            6. Byzantine quorums
            7. Authenticated, encrypted channels
            8. Detection of malicious / deviating nodes
            9. Dynamic reconfiguration under adversaries
            10. Computational and latency cost of BFT
            11. Critical use cases (finance, infrastructure control)
        7. Recovery strategies
            1. Returning to a healthy state after a failure
            2. Retries with exponential backoff
            3. Idempotency in retries
            4. Log replay (operation re-application)
            5. Periodic snapshots and checkpoints
            6. Coordinated rollback and roll-forward
            7. Re-synchronizing lagging replicas
            8. Reconciling divergent states
            9. Self-healing / autocorrection
            10. Automatic alerts and human escalation
            11. Planned recovery tests and drills
        8. Designing idempotent systems
            1. Repeatable operations without unwanted effects
            2. Operations without repeated side effects
            3. Unique operation identifiers (request ID)
            4. Exactly-once vs at-least-once as practical guarantees
            5. Distributed transactional processing
            6. Compensating actions
            7. Messaging with deduplication
            8. Write-once semantics
            9. Commutative states and CRDTs
            10. Event sourcing with safe replay
            11. Auditability and traceability of each mutation
    12. Distributed algorithms
        1. Communication models
            1. Synchronous systems
            2. Asynchronous systems
            3. Partially synchronous systems
            4. Reliable vs unreliable channels
            5. FIFO vs non-FIFO channels
            6. Message passing vs distributed shared memory
            7. Crash-stop failures
            8. Arbitrary / Byzantine failures
        2. Dissemination and broadcast
            1. Basic broadcast
            2. Reliable broadcast
            3. FIFO broadcast
            4. Causal broadcast
            5. Total order broadcast
            6. Gossip / epidemic broadcast
            7. Dissemination trees (spanning trees)
            8. Flooding and duplicate suppression
        3. Leader election
            1. Bully algorithm
            2. Ring election algorithm
            3. Timer-based election
            4. Priority / UID-based election
            5. Re-election after leader failure
            6. Election in partially connected networks
            7. Stable vs opportunistic election
        4. Clock synchronization
            1. Cristian’s algorithm
            2. Berkeley algorithm
            3. Distributed NTP
            4. Lamport logical clocks
            5. Vector clocks
            6. Hybrid logical clocks (HLC)
            7. Synchronization under variable latency
            8. Estimating and correcting skew and drift
        5. Distributed mutual exclusion
            1. Token ring
            2. Lamport mutual exclusion (timestamp messages)
            3. Ricart-Agrawala
            4. Centralized coordinator approach
            5. Hierarchical / tree-based control
            6. Quorum-based mutual exclusion
            7. Mutual exclusion tolerant to failures
        6. Distributed commit and consensus
            1. Two-Phase Commit (2PC)
            2. Three-Phase Commit (3PC)
            3. Paxos
            4. Raft
            5. Zab
            6. Read/write quorums
            7. Atomic broadcast and consensus
            8. Achieving linearizability via consensus
        7. Failure detection
            1. Perfect vs suspecting failure detectors
            2. Heartbeats
            3. Adaptive timeouts
            4. Accrual failure detectors / suspicion levels
            5. Marking a node slow vs down
            6. Distributed partition detection
            7. Reintegrating recovered nodes
        8. Global snapshotting
            1. Chandy-Lamport algorithm
            2. Consistent vs inconsistent snapshots
            3. Markers and communication channels
            4. Local state vs channel state
            5. Snapshot collection for recovery
            6. Periodic vs on-demand snapshots
            7. Coordinated vs uncoordinated checkpointing
        9. Consistent hashing and load partitioning
            1. Basic consistent hashing
            2. Ring of nodes
            3. Virtual replicas
            4. Incremental rebalancing
            5. Avoiding hotspots
            6. Rendezvous hashing
            7. Range-based vs hash-based partitioning
            8. Data affinity and locality-aware routing
        10. Byzantine-tolerant algorithms
            1. Byzantine failure model
            2. Byzantine replication (BFT)
            3. PBFT (Practical Byzantine Fault Tolerance)
            4. Byzantine quorums
            5. Byzantine agreement with digital signatures
            6. Resilience to malicious / dishonest nodes
            7. Partially synchronous Byzantine consensus
            8. Detection and exclusion of corrupt nodes
    13. Parallel and vectorized computing
        1. Parallelism models
            1. Flynn’s taxonomy (SISD / SIMD / MISD / MIMD)
            2. Instruction-level parallelism
            3. Data parallelism
            4. Task parallelism
            5. Pipeline parallelism
            6. Massive parallelism
            7. Bulk Synchronous Parallel (BSP)
            8. SPMD (Single Program Multiple Data)
            9. Dataflow computing
        2. Data-level parallelism (SIMD / SIMT)
            1. Vector registers and SIMD extensions
            2. Wide vector units
            3. Packed operations
            4. Masking / predication
            5. Warp / wavefront execution
            6. Branch divergence
            7. Memory coalescing
            8. Automatic vs manual vectorization
        3. Task-level parallelism (MIMD)
            1. Independent threads
            2. Asymmetric task processing
            3. Workers / thread pools
            4. Task DAGs
            5. Work stealing
            6. Heterogeneous pipeline stages
            7. Pipeline vs pure parallelism
            8. Dynamic load balancing
        4. Shared memory vs distributed memory
            1. Shared memory with cache coherence
            2. NUMA
            3. Distributed memory (cluster)
            4. Message passing (MPI)
            5. RDMA and remote direct access
            6. DSM (Distributed Shared Memory)
            7. Unified CPU–GPU memory
            8. Strong vs weak memory consistency
        5. Synchronization and coordination
            1. Barriers
            2. Locks and spinlocks
            3. Semaphores
            4. Futexes
            5. Critical sections
            6. Atomic operations and CAS
            7. Parallel reductions
            8. Prefetching and memory fences
            9. Deadlock / livelock / starvation
        6. GPU parallelism
            1. SIMT (Single Instruction Multiple Threads)
            2. Thread hierarchy (grid / block / warp)
            3. Memory hierarchy (global / shared / local / constant / texture)
            4. Coalescing of global memory accesses
            5. Occupancy and latency hiding
            6. Kernel launches
            7. CUDA / HIP programming
            8. Tensor cores / matrix accelerators
            9. Streams and kernel concurrency
            10. Unified Virtual Addressing
        7. Performance and scalability
            1. Amdahl’s Law
            2. Gustafson’s Law
            3. Strong vs weak scaling
            4. Fine vs coarse granularity
            5. Synchronization overhead
            6. Contention in shared memory
            7. Thread affinity / pinning
            8. Bandwidth vs compute (arithmetic intensity)
            9. Roofline model
        8. Common parallel patterns
            1. Map / Reduce
            2. Scatter / Gather
            3. Pipeline
            4. Stencil / convolution
            5. Reductions (sum, min, max)
            6. Prefetching and tiling / blocking
            7. Domain-partition parallelization
            8. Producer-consumer
            9. Task farm / master-worker
            10. All-reduce / broadcast / gather / scatter in clusters
        9. Tools and parallel programming environments
            1. OpenMP
            2. MPI
            3. CUDA
            4. OpenCL
            5. HIP / ROCm
            6. SYCL
            7. Threading Building Blocks (TBB)
            8. DSLs for scientific computing
            9. High-level parallel frameworks (Ray, Dask)
            10. Dependency-driven task schedulers
        10. Typical concurrency and performance issues
            1. Lock contention
            2. False sharing
            3. Cache thrashing
            4. Load imbalance
            5. Desynchronization and jitter
            6. NUMA effects
            7. Global memory latency vs local memory
            8. Context-switch overhead
            9. GPU control divergence
            10. Cloud computing and edge computing
    14. Networks and protocols
        1. Service models (IaaS, PaaS, SaaS, FaaS)
            1. IaaS (virtualized compute, networking, storage)
            2. PaaS (managed platforms for app deployment)
            3. SaaS (applications offered as a service)
            4. FaaS / serverless functions
            5. BaaS / MBaaS (Backend-as-a-Service / Mobile Backend-as-a-Service)
            6. DaaS (Data-as-a-Service)
            7. CaaS (Containers-as-a-Service)
            8. GPU / accelerators as a service
        2. Deployment models (public cloud, private, hybrid, multicloud)
            1. Public cloud
            2. Dedicated private cloud
            3. Hybrid cloud
            4. Active multicloud (workloads across multiple providers)
            5. DR in another cloud (multicloud disaster recovery)
            6. Cloud bursting
            7. Data sovereignty / geographic location
            8. Direct interconnect between clouds and on-prem
        3. Infrastructure as code and declarative infrastructure
            1. Declarative vs imperative
            2. Declarative templates
            3. Versioning infra alongside code
            4. Immutable infrastructure
            5. Configuration injection / parameterization
            6. Desired state reconciliation
            7. GitOps
            8. Secrets and credentials management in IaC
        4. Automation, orchestration and autoscaling
            1. Automatic resource provisioning
            2. Horizontal and vertical autoscaling
            3. Scaling based on load metrics
            4. Rolling update / rolling restart
            5. Canary deploy / blue-green deploy
            6. Container orchestrators
            7. CI/CD pipelines
            8. Self-healing infrastructures
            9. Management of service dependencies
        5. Observability in distributed clouds
            1. Metrics (CPU, memory, latency, throughput)
            2. Centralized logs
            3. Distributed tracing
            4. Service dependency maps
            5. Anomaly detection
            6. Alerts based on SLO/SLA
            7. Telemetry from edge / edge-to-cloud
            8. Infrastructure event auditing
        6. Serverless and FaaS
            1. Ephemeral on-demand functions
            2. Billing by execution / duration
            3. Cold start vs warm start
            4. Execution time limits
            5. Integration with queues, streams and events
            6. Function orchestration (state machines)
            7. External statefulness (external storage)
            8. Performance constraints vs dedicated VMs/containers
        7. Edge computing
            1. Processing close to the data source
            2. Ultra-low latency for real-time
            3. Partial offloading to the cloud
            4. Caching and local decision-making without contacting core cloud
            5. Deferred / eventual synchronization
            6. Edge nodes with limited resources
            7. ML inference at the edge
            8. Remote management of edge fleets
            9. Edge-to-edge local communication
        8. Security, compliance and governance
            1. Tenant isolation
            2. Multilevel access controls (IAM)
            3. Encryption in transit and at rest
            4. Key management (KMS / HSM)
            5. Regulatory compliance and auditing
            6. Traceability and data chain of custody
            7. Zero-trust network policies
            8. Continuous security posture (CSPM)
            9. Secrets management and credential rotation
            10. Access controls by workload identity (non-human)
        9. Cost management and optimization
            1. Instance rightsizing
            2. Shutting down idle resources
            3. Use of reserved / spot / preemptible instances
            4. Cost per environment (dev / stage / prod)
            5. Cost allocation by team / project
            6. On-demand scaling vs overprovisioning
            7. Compression / tiering of cold data
            8. Optimization of egress and inter-region transit
            9. Storage vs compute vs network costs
            10. FinOps
        10. Reliability and operational continuity
            1. Multi-zone / multi-region high availability
            2. Active-active geographic replication
            3. Tested backup and restore
            4. Disaster recovery policies (RTO / RPO)
            5. Design tolerant to regional failures
            6. Health checks and automatic failover
            7. Controlled degradation of functionality
            8. Chaos engineering / fault injection
            9. Failover and recovery testing
            10. Incident management and postmortems
    15. Embedded systems and RTOS
        1. Embedded systems fundamentals
            1. MCU vs MPU
            2. Integrated peripherals (GPIO, UART, SPI, I2C)
            3. Interrupt controllers
            4. Hardware clocks and timers
            5. Memory constraints and power consumption
            6. Bare-metal firmware
            7. Hardware initialization (boot, startup code)
            8. BSP (Board Support Package)
            9. Integration with sensors and actuators
        2. Real-time systems
            1. Hard real-time vs soft real-time
            2. Determinism and worst-case latency
            3. Real-time scheduling (Rate Monotonic, EDF)
            4. Deadlines and jitter
            5. Priority-based interrupt management
            6. Predictable execution vs throughput
            7. Real-time execution monitoring
            8. Worst-Case Execution Time (WCET) analysis
        3. Common RTOS and architecture
            1. Real-time scheduler core
            2. Tasks / threads in an RTOS
            3. ISR (Interrupt Service Routine) and threading
            4. Queues and mailboxes in RTOS
            5. Semaphores and mutexes with priority inheritance
            6. System timing and timers
            7. Monolithic RTOS vs embedded microkernel
            8. FreeRTOS / Zephyr / VxWorks / QNX
            9. RT‑Linux and low-latency patches
        4. Reliability and functional safety
            1. Watchdog timers
            2. Redundancy and fail-safe design
            3. Fault detection and recovery (self-check)
            4. Safety-certified systems (ISO 26262, DO-178C)
            5. Protected memory management
            6. Isolation of critical tasks
            7. Protection against transient faults (EMI, radiation)
            8. Secure and verified OTA updates
            9. Secure boot
            10. Hardware-based cryptography in embedded systems
        5. Integration with larger systems
            1. Communication with industrial buses (CAN, Modbus, extended SPI)
            2. Gateways to distributed control systems
            3. Telemetry and event logging
            4. Edge control and cloud reporting
            5. Synchronization with higher-level controllers (PLC, SCADA)
            6. Remote update protocols
            7. Remote diagnostics and predictive maintenance
            8. Security of the control channel (auth, encryption)
    16. Load balancing and content delivery networks (CDN)
        1. Load balancers (L4 / L7)
            1. Layer 4 load balancing (TCP/UDP)
            2. Layer 7 load balancing (HTTP/HTTPS)
            3. Hardware vs software load balancers
            4. Reverse proxies
            5. TLS termination / offload
            6. Ingress gateway
            7. Stateful vs stateless load balancing
            8. Internal (east-west) vs external (north-south) load balancing
        2. Traffic distribution strategies
            1. Round Robin
            2. Weighted Round Robin
            3. Least Connections
            4. Least Response Time
            5. Consistent hashing
            6. Sticky sessions / session affinity
            7. Routing by headers / path / HTTP method
            8. Traffic mirroring / shadow traffic
            9. Canary routing
            10. A/B testing based on balancing
        3. Health checks and failover
            1. Active vs passive health checks
            2. Port / protocol verification
            3. HTTP checks with application semantics
            4. Success / failure thresholds
            5. Automatic removal of unhealthy nodes
            6. Local failover vs cross-data-center failover
            7. Fencing / quarantine of unstable instances
            8. Detection of degraded latency
            9. Circuit breakers at the network layer
        4. Anycast and geographic routing
            1. Anycast IP
            2. BGP announcements across regions
            3. Redirecting to the nearest point (lower latency)
            4. GeoDNS / geo-routing
            5. Latency-based routing
            6. Weighted routing by region
            7. Active-active multi-region redundancy
            8. Containment of regional failures
            9. Traffic steering during incidents
        5. CDNs (Content Delivery Networks)
            1. Edge PoPs (Points of Presence)
            2. Edge cache servers
            3. Static caching (images, JS, CSS)
            4. Dynamic caching / generated content
            5. Origin server vs edge server
            6. Origin shielding
            7. Tokenization / signed URLs
            8. Origin offload
            9. Limiting origin egress
        6. Content delivery optimization
            1. Compression (gzip, brotli)
            2. Asset minification
            3. HTTP/2 push / server hints
            4. HTTP/3 / QUIC
            5. Cache-Control / ETag / Last-Modified
            6. Image resizing at the edge
            7. Adaptive video optimization
            8. Pre-caching / prefetching
            9. Cache by header variations (Vary)
            10. TTLs and expiration policies
        7. Attack mitigation and DDoS protection
            1. Rate limiting
            2. L3/L4 filtering (volumetric)
            3. L7 protections (HTTP floods)
            4. Scrubbing centers
            5. Challenges / client verification
            6. WAF (Web Application Firewall)
            7. Bot management
            8. Geo / ASN-based blocking
            9. Traffic pattern anomaly detection
            10. Controlled blackholing / sinkholing
        8. Observability and traffic control
            1. Metrics for latency, error rate and throughput
            2. Telemetry per route / service
            3. Access logs and distributed traces
            4. Real-time monitoring by zone / PoP
            5. Traffic heatmaps
            6. Adaptive rate limiting
            7. SLO-driven circuit breaking
            8. Dynamic route control
            9. Unified operational dashboard
        9. Service mesh and intelligent proxies
            1. Sidecar proxies per service
            2. mTLS encryption between services
            3. L7 policy-driven load balancing
            4. Retries, timeouts and backoff managed by the mesh
            5. Automatic distributed tracing
            6. Rate limiting by service / client
            7. Canary / blue-green traffic control
            8. Authorization policies between services
            9. Homogeneous observability across microservices
            10. Integrated fault injection / chaos testing
    17. Scalability models
        1. Vertical vs horizontal scaling
            1. Increasing resources on a single instance (CPU, RAM, IOPS)
            2. Physical and cost limits of vertical scaling
            3. Horizontal scaling via replicas / more nodes
            4. Load balancers to distribute traffic among replicas
            5. Sessions and state handling in horizontal environments
            6. Impact on availability and fault tolerance
            7. Compatibility with monolithic vs distributed architectures
            8. Database saturation as a common bottleneck
            9. Impact on local latency vs inter-node latency
            10. Hybrid strategies (vertical up to a limit, then horizontal)
        2. Elasticity and autoscaling
            1. Reactive scaling based on metrics (CPU, RPS, latency)
            2. Proactive / predictive scaling based on historical patterns
            3. Horizontal autoscaling of application instances
            4. Autoscaling of pods / containers in orchestrators
            5. Autoscaling of storage and I/O throughput
            6. Warm-up vs cold-start when scaling dynamically
            7. Cooldown rules to avoid scaling thrash
            8. Scale-to-zero for intermittent workloads
            9. Budget / quota limits for scaling
            10. Coordination between compute, database and queue scaling
        3. Decoupling via queues and events
            1. Natural buffering between producer and consumer
            2. Smoothing traffic spikes
            3. Asynchronous processing vs synchronous response
            4. Retries and idempotency for processed messages
            5. Backpressure controlled by queuing
            6. Dead-letter queues for problematic messages
            7. Prioritization by event type / separate queues
            8. Event sourcing as a source of truth
            9. Broadcast and fan-out to multiple consumers
            10. Risks: eventual latency, partial ordering and duplicates
        4. Sharding and data partitioning
            1. Horizontal partitioning by range / hash / geography
            2. Consistent hashing and minimal reassignment
            3. Shard catalog / router vs implicit routing
            4. Avoiding hotspots and hot keys
            5. Live shard rebalancing and gradual redistribution
            6. Isolation of noisy tenants in separate shards
            7. Independent read/write scaling
            8. Data migration between nodes with minimal downtime
            9. Monitoring shard size and uneven growth
            10. Impact on global aggregations and cross-shard queries
        5. Geographic replication and multi-region
            1. Active/active vs active/passive replicas
            2. Synchronous vs asynchronous replication between regions
            3. Inter-region latency and observable consistency
            4. Routing by geographic proximity (geo-routing / anycast)
            5. Operational continuity during regional failures
            6. Regulatory compliance and data sovereignty
            7. Multi-master write conflicts and reconciliation
            8. Automatic failover and disaster recovery policies
            9. Edge/ CDN distribution of content
            10. Egress costs and inter-region traffic optimization
        6. Multi-level caching
            1. Client / browser / local app cache
            2. Edge / CDN cache for static and semi-static content
            3. Application-layer cache (in-memory local)
            4. Shared distributed cache (e.g., KV cluster)
            5. Database caching (materialized views, precomputed results)
            6. TTL / expiration / selective invalidation strategies
            7. Cache warming and proactive prefetch
            8. Cache stampede mitigations (locking / request coalescing)
            9. LRU / LFU / ARC policies by access pattern
            10. Coherence between cache layers and the source of truth
        7. Resource isolation and multitenancy
            1. Logical isolation by tenant (namespaces / accounts)
            2. Physical / compute isolation (dedicated vs shared nodes)
            3. Rate limiting and quotas per tenant
            4. Noisy neighbor effects and fair usage
            5. Encryption at rest and in transit per tenant
            6. Data separation in storage (DB per tenant vs tagged rows)
            7. Traffic prioritization and differentiated QoS
            8. Auditability and traceability by tenant identity
            9. Fault isolation per tenant / reduced blast radius
            10. Gradual deployment control by customer segment
        8. Design without single points of failure
            1. Service instance redundancy (N+1, N+2)
            2. Highly available load balancers
            3. Critical data replication with write/read quorum
            4. Eliminating single critical master (auto-replaceable leader)
            5. Removing non-redundant dependencies (single DB, single queue)
            6. Automatic failover across zones / racks / regions
            7. Blue-green / canary deployments to avoid global outages
            8. Health checks and circuit breakers to isolate failures
            9. Fault domain segmentation (blast radius control)
            10. Chaos exercises to validate real tolerance
        9. Backpressure and flow control
            1. Early rejection / shed load under saturation
            2. Concurrency limits per queue / worker / endpoint
            3. Sliding windows and credits (windowing / credit-based flow control)
            4. Signaling availability to producers
            5. Pausing / throttling event producers
            6. Prioritizing critical traffic over best-effort
            7. Protecting against retry storms in cascade
            8. Dynamic rate adjustment by latency and backlog
            9. Timeouts and propagated cancellation mechanisms
            10. Avoiding large-scale deadlocks from circular pressure
        10. Observability and self-healing
            1. Metrics: latency, throughput, error rate and saturation
            2. Structured logs and distributed traceability by request ID
            3. Alerts based on SLOs (service level objectives) and SLIs
            4. Dependency maps and blast radius analysis
            5. Continuous health checks and automatic remediation
            6. Automatic restart / reschedule of defective workloads
            7. Early anomaly and degradation detection
            8. Automatic rollback for regressive deployments
            9. Auto-quarantine of sick nodes (quarantine / cordon)
            10. Postmortems and continuous learning integrated into the system
        11. Cost / performance optimization
            1. Rightsizing instances and tuning allocated resources
            2. On-demand scaling vs fixed overprovisioning
            3. Use of spot / preemptible instances / commitment savings
            4. Storage tiering (hot vs warm vs cold)
            5. Compression, deduplication and intelligent retention
            6. Reducing egress and inter-region traffic
            7. Offloading expensive compute to specialized accelerators
            8. Cache optimization to lower read costs
            9. Controlled degradation of high-cost features under saturation
            10. Financial visibility by service / team (FinOps)
        12. Architectural evolution at scale
            1. Migrating monolith to services / microservices / modules
            2. Progressive separation of functional domains (bounded contexts)
            3. Introducing queues/events where direct coupling existed
            4. Extracting dedicated storage per service (database per service)
            5. Canary / blue-green deployments for contract changes
            6. API versioning and backward compatibility
            7. Refactoring for multi-region and high availability
            8. Infrastructure automation and Infrastructure as Code
            9. Managing technical debt and removing single chokepoints
            10. Governance of performance, security and cost as the organization grows

2. Software Analysis and Design
    1. Software engineering processes
        1. Software requirements
            1. Functional requirements
            2. Non-functional requirements
            3. Quality attributes (performance, security, reliability, scalability)
            4. Technical and regulatory constraints
            5. Operational requirements
            6. Requirements prioritization
            7. Stakeholder expectation management
        2. Requirements analysis, specification and traceability
            1. User stories
            2. Use cases
            3. Business scenarios
            4. Formal requirements
            5. Domain models and shared vocabulary
            6. Traceability matrices
            7. Requirements change control
        3. Software design
            1. Architecture modeling
            2. Component and module design
            3. Structural and interaction diagrams
            4. Interface definition
            5. Test-driven design
            6. Design for observability
            7. Design for deployment and operations
        4. Construction and coding standards
            1. Style standards
            2. Naming conventions
            3. Code review
            4. Branching guidelines and version control
            5. Continuous integration
            6. Build automation
            7. External dependency management
            8. Secrets and configuration management
            9. Secure coding practices
            10. Technical debt policies
        5. Verification and validation
            1. Unit testing
            2. Integration testing
            3. Contract testing
            4. End-to-end testing
            5. Regression testing
            6. Performance and load testing
            7. Security testing
            8. Fuzzing
            9. Static code analysis
            10. Technical audits
            11. Deployment approvals
        6. Evolutionary and corrective maintenance
            1. Defect correction
            2. Continuous refactoring
            3. Technical debt management
            4. Extending existing features
            5. Technology migration
            6. Backward compatibility
            7. Risk management for changes
            8. End-of-life planning
        7. Configuration management
            1. Version control
            2. Branching strategies
            3. Semantic versioning
            4. Release management
            5. Traceability of production changes
            6. Infrastructure as code
            7. Environment management
            8. Audit and compliance
        8. Software quality engineering
            1. Quality assurance (QA)
            2. Quality control
            3. Automated testing strategies
            4. Test coverage
            5. Definition of acceptance criteria
            6. Definition of DoD (Definition of Done)
            7. Observability as part of quality
            8. Incident management and postmortems
            9. Continuous reliability review
            10. Vulnerability management
        9. Development processes
            1. Waterfall
            2. Evolutionary prototyping
            3. Iterative-incremental
            4. RUP / unified processes
            5. Agile / industrial Agile
            6. Scrum
            7. Kanban
            8. Lean software
            9. DevOps
            10. GitOps
            11. Continuous Delivery / Continuous Deployment
            12. Inner source and internal open collaboration
        10. Productivity and software quality metrics
            1. Delivery velocity
            2. Change lead time
            3. Mean time to recovery (MTTR)
            4. Deployment frequency
            5. Change failure rate
            6. DORA metrics
            7. Defect density
            8. Useful test coverage
            9. SLOs and SLIs
            10. Perceived availability and reliability
            11. Stability vs change velocity
            12. Total cost of ownership (TCO)
        11. Tools supporting the software lifecycle
            1. Version control systems
            2. CI/CD pipelines and continuous integration tools
            3. Issue tracking systems
            4. Requirements and specification management
            5. Architecture and documentation management
            6. Production monitoring and alerting
            7. Deployment traceability
            8. Incident management and on-call tooling
            9. Feature flags and progressive rollouts
            10. Ephemeral environments and isolated testing
            11. Observability (logs, metrics, traces)
            12. Secrets and secure configuration management
        12. Continuous process improvement and operational maturity
            1. Short feedback cycles
            2. Blameless postmortems
            3. Evolutionary architecture reviews
            4. Iteration on internal standards
            5. Systematic automation of manual tasks
            6. Reduction of unplanned work
            7. Active technical debt management
            8. Continuous training and knowledge transfer
            9. Organizational scaling of effective practices
            10. Operational maturity and reliability as product features
            11. Technical governance and shared accountability
            12. Security culture embedded in processes
    2. Software design and architecture
        1. Design principles for maintainability
            1. Low coupling and high cohesion
            2. Separation of concerns (SoC)
            3. Encapsulation and information hiding
            4. SOLID principles
            5. Stable interfaces and clear contracts
            6. Controlled evolution of components
            7. Testability and ease of testing
            8. Observability and debuggability
        2. Principles to avoid unnecessary repetition and keep simplicity
            1. DRY (Don’t Repeat Yourself)
            2. KISS (Keep It Simple, Stupid)
            3. YAGNI (You Aren’t Gonna Need It)
            4. Minimize accidental complexity
            5. Law of Demeter
            6. Principle of least surprise
            7. Minimize implicit dependencies
        3. Design patterns (creational, structural and behavioral)
            1. Creational patterns
                1. Factory Method
                2. Abstract Factory
                3. Builder
                4. Prototype
                5. Singleton
                6. Object Pool
                7. Dependency Injection
            2. Structural patterns
                1. Adapter
                2. Bridge
                3. Composite
                4. Decorator
                5. Facade
                6. Flyweight
                7. Proxy
                8. DTO (Data Transfer Object)
            3. Behavioral patterns
                1. Strategy
                2. Observer / Publish–Subscribe
                3. Command
                4. Chain of Responsibility
                5. State
                6. Template Method
                7. Iterator
                8. Mediator
                9. Memento
                10. Visitor
                11. Specification
                12. Null Object
            4. Concurrency patterns
                1. Producer–Consumer
                2. Reader–Writer
                3. Reactor
                4. Circuit Breaker
                5. Bulkhead
                6. Retry / Backoff
            5. Architectural patterns
                1. MVC / MVP / MVVM
                2. CQRS (Command Query Responsibility Segregation)
                3. Event Sourcing
                4. Pipes and Filters
        4. Layered architecture
            1. Presentation layer
            2. Application / service layer
            3. Domain / business layer
            4. Infrastructure / persistence layer
            5. Logical separation vs physical separation
            6. Dependencies directed inward
            7. Common pitfalls of traditional layered models
        5. Clean architecture
            1. Concentric circles and dependency toward the domain
            2. Entities and use cases
            3. Input and output interfaces
            4. Controllers and presenters
            5. Gateways / repositories
            6. Framework independence
            7. Testability and replaceable infrastructure
        6. Hexagonal architecture and ports/adapters separation
            1. Domain as an independent core
            2. Ports (interfaces oriented to the domain)
            3. Primary (driving) adapters
            4. Secondary (driven) adapters
            5. Swapping infrastructure (DB, queues, external APIs)
            6. Isolation of side effects
            7. Testing at the port level
        7. Domain-Driven Design (DDD)
            1. Ubiquitous language
            2. Bounded contexts
            3. Context mapping and relationships between contexts
            4. Explicit domain model
            5. Domain entities
            6. Value objects
            7. Domain services
            8. Aggregates and aggregate roots
            9. Repositories
            10. Domain events
            11. Anti-corruption layer
            12. Refactoring the model driven by business knowledge
        8. Modular monoliths and microservices
            1. Traditional monolith
            2. Modular monolith
            3. Internal module boundaries
            4. Microservices
            5. Criteria to extract a microservice
            6. Synchronous vs asynchronous communication
            7. Independent deployment
            8. Eventual consistency between services
            9. Distributed observability
            10. Versioning and lifecycle independence
            11. Service routing and discovery
            12. Management of cascading failures
        9. Event-driven architectures
            1. Event producers and consumers
            2. Event bus and message queues
            3. Event Sourcing
            4. CQRS and events as the source of truth
            5. Choreography vs orchestration
            6. Idempotence in event consumption
            7. Eventual consistency
            8. Retries and dead-letter queues
            9. Delivery guarantees (at-most-once, at-least-once, exactly-once)
        10. Interface versioning and API lifecycle
            1. Endpoint versioning
            2. Semantic versioning
            3. Backward compatibility
            4. Controlled contract deprecation
            5. Stability of public contracts
            6. API lifecycle management
            7. Breaking changes and internal/external communication
            8. Evolution of schemas and data models
            9. Capacity control and usage limits (rate limiting)
            10. Security and authentication policies
        11. Technical documentation for developers and maintenance
            1. Architecture documentation
            2. Component and dependency diagrams
            3. API specifications
            4. Internal service contracts
            5. ADRs (Architecture Decision Records)
            6. Deployment and operations guides
            7. Incident response manuals
            8. Documentation of limits and guarantees (SLO, SLA)
            9. Technical changelog
            10. Style standards and conventions
            11. Versioning the documentation
            12. Code-adjacent documentation vs external docs
        12. Modularization and packaging of reusable components
            1. Design of internal libraries
            2. Reusable packages by team/project
            3. Reuse vs localized copy
            4. Stability of internal interfaces
            5. Internal dependency control
            6. Version management of shared components
            7. Monorepos vs multi-repo strategies
            8. Plugins and extensions
            9. Internal compatibility-break policies
            10. Module ownership rules
            11. Internal service and library catalog
            12. Binary distribution vs source distribution

3. Programming and Software Development
    1. Linux, environments and automation
        1. Unix-like systems fundamentals
            1. Unix philosophy and modular design
            2. Hierarchical filesystem and absolute vs relative paths
            3. User, group and other permissions
            4. Owners, groups and file modes (r/w/x)
            5. Processes and user-space vs kernel-space
            6. Signals and process states
            7. Pipes and standard redirections (stdin, stdout, stderr)
            8. Executable scripts and the shebang (`#!/usr/bin/env ...`)
            9. Basic differences between Linux, macOS and WSL
            10. Mounted filesystems and mount points
        2. Essential command-line commands
            1. Filesystem navigation (`ls`, `cd`, `pwd`, `tree`)
            2. Inspecting content (`cat`, `less`, `head`, `tail`, `wc`)
            3. File and directory manipulation (`cp`, `mv`, `rm`, `mkdir`, `touch`)
            4. Finding files (`find`, `locate`)
            5. Searching inside files (`grep`, common flags and basic regex)
            6. Text transformation (`cut`, `sort`, `uniq`, `tr`, `sed`, `awk`)
            7. Compression and archiving (`tar`, `gzip`, `zip`, `unzip`)
            8. Downloading and transferring data (`curl`, `wget`, `scp`, `rsync`)
            9. Managing permissions and ownership (`chmod`, `chown`, `chgrp`)
            10. Getting help and manuals (`man`, `--help`, `info`)
            11. Wildcard expansion and globbing (`*`, `?`, `{}`)
            12. Command history and replay
        3. System package and environment management
            1. System package managers (apt, dnf, pacman, brew)
            2. Installing, upgrading and removing packages
            3. Official, extra and custom repositories
            4. System-level dependencies vs project dependencies
            5. Shared libraries and runtime versioning
            6. Isolation with lightweight containers and sandboxes
            7. Polyglot tool usage (`asdf`, `pyenv`, `nvm`, `rbenv`)
            8. Security policies when installing third-party software
            9. Package integrity auditing and signatures
            10. Reproducibility and system-level version locking
        4. System services, scheduled tasks and daemons
            1. Background vs foreground processes
            2. Managing services with `systemd` (`systemctl start/stop/status`)
            3. `systemd` units (service, timer, socket)
            4. Logging and automatic service restarts
            5. Scheduled tasks with `cron` and `crontab`
            6. Difference between cron jobs and systemd timers
            7. Custom daemons and supervision
            8. Execution at system boot
            9. Restart policies and watchdogs for critical services
            10. Managing and rotating logs for background services
        5. Environment variables and configuration
            1. Global and local environment variables
            2. Export and scope (`export`, subshells)
            3. Standard variables (`PATH`, `HOME`, `SHELL`, etc.)
            4. Executable search paths (`PATH`) and priority
            5. Shell startup files (`.bashrc`, `.zshrc`, `.profile`, etc.)
            6. `.env` files and environment-based configuration
            7. Separation of secrets and public configuration
            8. Injecting environment variables into processes and services
            9. Loading environment variables in CI/CD deployments
            10. Protecting secrets in shared environments / multiuser shells
        6. Process and resource monitoring
            1. Process listing (`ps`, `top`, `htop`)
            2. CPU, memory and disk usage
            3. Sending signals to processes (`kill`, `kill -9`, `kill -HUP`)
            4. Process tracing (`strace`, `lsof`)
            5. Monitoring IO and network consumption
            6. Detecting hung or runaway processes
            7. CPU affinity and resource limits
            8. Resource limits per process (`ulimit`)
            9. Isolation and control with cgroups / namespaces
            10. Detecting memory leaks and abnormal RSS growth
        7. Networking and ports
            1. Basic network concepts (IP, DNS, routing)
            2. Inspecting network interfaces and IP addresses
            3. Name resolution and DNS lookups
            4. Open connections and listening ports
            5. Connectivity testing (`ping`, `traceroute`, `nc`)
            6. Secure transfers (`ssh`, SSH tunnels, port forwarding)
            7. Local firewalls and access rules
            8. Local services vs publicly exposed services
            9. Scanning and verifying exposed ports (surface audit)
            10. Diagnosing blocks by firewall / NAT / asymmetric routing
        8. Security and access control
            1. Users and groups
            2. Privilege escalation (`sudo`, sudoers policy)
            3. SSH keys and passwordless authentication
            4. Least privilege (minimum necessary permissions)
            5. Private/public key management
            6. Secure secret storage
            7. Preventing arbitrary execution (don’t run scripts blindly)
            8. Process isolation and sandboxing
            9. Basic system hardening and attack surface reduction
            10. Access auditing and periodic credential rotation
        9. Command-line automation and scripting
            1. Aliases and shell functions
            2. Bash and POSIX-compatible shell scripting
            3. Variables, positional arguments and exit codes
            4. Conditionals and loops in shell
            5. Batch processing of files
            6. Chained pipelines and composition of small tools
            7. Idempotent and repeatable scripts
            8. Error handling and `set -euo pipefail`
            9. Interoperability between shell and other languages (Python, awk, etc.)
            10. Remote script execution
        10. Workspace customization
            1. Custom prompt and contextual realtime info
            2. Using `tmux` / terminal multiplexers
            3. Persistent history and incremental search
            4. Advanced autocompletion and contextual suggestions
            5. Reusable shell snippets
            6. Fast project navigation and path bookmarks
            7. Differences between shells (bash, zsh, fish)
            8. Global code/symbol search from the terminal
            9. Synchronizing and versioning dotfiles across machines
            10. Showing git branch/CI/deploy status in the prompt
        11. Performance diagnosis
            1. CPU bottlenecks
            2. Memory bottlenecks and swapping
            3. Disk latency and IOPS usage
            4. IO-bound vs network-bound blocking
            5. Perf counters and kernel tracing
            6. Reproducible benchmarks
            7. Latency analysis for background services
            8. Kernel and userland profiling (perf/ftrace/eBPF)
            9. Network throughput testing (iperf, etc.)
            10. Historical baseline for performance comparison
        12. System auditing and logs
            1. System logs (`journalctl`, `/var/log`)
            2. Log rotation and retention
            3. Severity levels and filtering
            4. Correlating system events and service failures
            5. Detecting recurring error patterns
            6. Access logs and suspicious activity records
            7. Traceability and evidence for post-mortems
            8. Early alerts and continuous monitoring
            9. Centralization and forwarding to SIEM systems
            10. Retention for compliance and forensic purposes
    2. Programming language fundamentals
        1. Suggested learning paths for programming languages
            1. Python
            2. JavaScript / TypeScript
            3. Rust
            4. Bash / shell scripting
            5. Go
            6. Java / JVM
            7. C / C++
            8. Kotlin
            9. SQL and query languages
            10. Languages aimed at distributed systems / high-performance backends
        2. Compilers, interpreters and language implementation
            1. Lexical analysis, parsing, semantic analysis
            2. Intermediate representation (IR) and optimization
            3. Code generation and backend
            4. Linking and loading
            5. Tree interpreters and virtual machines
            6. JIT vs AOT compilation
            7. Compiler bootstrapping
            8. Lexer/parser generators
            9. Architecture-specific optimizations (registers, cache, vectorization)
            10. Memory management and runtime GC
        3. Language design
            1. Operational, denotational and axiomatic semantics
            2. Scope: lexical vs dynamic
            3. Mutability vs immutability
            4. Strict evaluation vs lazy evaluation
            5. Referential transparency
            6. Side effects and controlled effects
            7. Type and memory safety
            8. Domain-specific languages (DSLs)
            9. Modules, encapsulation and explicit public interfaces
            10. Memory safety, isolation and sandboxing capabilities
        4. Syntax and basic constructs
            1. Expressions and operators
            2. Statements and blocks
            3. Precedence and associativity
            4. Literals and value construction
            5. Comments and directives
            6. Importing symbols and name scope
            7. Variable shadowing
            8. Variable declarations with different mutability (`const`, `let`, `var`)
            9. Literal syntaxes (objects, dicts, records)
            10. Rules for significant indentation (offside rule)
        5. Data types and data abstraction
            1. Scalar primitives (numbers, booleans, characters)
            2. Composite structures (records, structs, tuples)
            3. Collections (lists, arrays, dictionaries, maps)
            4. Algebraic types (sum and product)
            5. Tagged enumerations
            6. Abstract data types (ADT)
            7. Encapsulation of internal representation
            8. Option / Maybe types
            9. Parametric generics for reusable data structures
            10. Safe result/error types to signal failures
        6. Control flow (conditionals, loops, branching)
            1. if / else / switch / match
            2. while / for / foreach
            3. Structural pattern matching
            4. Logical short-circuiting
            5. Break / continue / return
            6. Goto and structured jumps
            7. Guard clauses and explicit branching
            8. Higher-level control like map/filter/reduce
            9. Exceptions as non-local jumps
            10. Pattern guards, backtracking and declarative branching
        7. Functions, closures and parameter passing
            1. First-class functions and anonymous functions
            2. Closures with lexical capture
            3. Call by value, reference, and by-name
            4. Currying and partial application
            5. Direct recursion and tail recursion
            6. Variadic functions
            7. Callbacks and higher-order functions
            8. Inlining and optimizing small functions
            9. Move semantics / borrow semantics
            10. Immutable vs controlled mutable parameter passing
        8. Functional paradigms
            1. Immutability
            2. Pure functions
            3. Lazy evaluation
            4. Pattern matching
            5. Algebraic types and sum types
            6. Monads, functors, applicatives
            7. Controlled effects and IO monads
            8. Transformations without shared state
            9. Persistent data structures
            10. Functional reactive programming and declarative streams
        9. Object-oriented programming
            1. Classes and objects
            2. Encapsulation and visibility
            3. Single and multiple inheritance
            4. Subtype polymorphism
            5. Interfaces and contracts
            6. Composition over inheritance
            7. Mixins and traits
            8. Virtual methods and dynamic dispatch
            9. Metaclasses and reflection
            10. Immutable objects and value semantics
        10. Modules and packaging
            1. Modules and namespaces
            2. Explicit imports/exports
            3. Public/private/internal visibility control
            4. Packaging and distribution
            5. Semantic versioning
            6. Dependency resolution
            7. Dependency trees and deduplication
            8. Logical separation by layer or domain
            9. Publishing to package registries (npm, PyPI, crates.io)
            10. Binary compatibility / ABI stability in shared libraries
        11. Static typing and type annotations
            1. Static vs dynamic typing
            2. Type inference
            3. Parametric polymorphism
            4. Ad-hoc polymorphism (overloading)
            5. Nominal vs structural typing
            6. Generics
            7. Dependent types
            8. Null-safety / optional types
            9. Mutability-typed vs immutability-typed systems
            10. Flow-sensitive typing and refinement types in analysis
        12. Error handling and exceptions
            1. Checked vs unchecked exceptions
            2. Exception propagation
            3. Result types (Result, Either)
            4. Sentinel values and error codes
            5. Panic / abort semantics
            6. Retries and recovery strategies
            7. Guaranteed cleanup after errors
            8. Retries with backoff and circuit breakers in business logic
            9. Structured logging of failures and traces
            10. Resilience and fault isolation policies
        13. Structured resource management (scopes and contexts)
            1. RAII
            2. Destructors / finalizers
            3. with / using / defer constructs
            4. Ownership and borrowing
            5. Lifetimes / region-based memory management
            6. Garbage collection
            7. Resource pools
            8. Reuse of connections and socket/DB pools
            9. Guaranteed release even on exceptions
            10. Deterministic vs non-deterministic GC
        14. Iterators, generators and consumable sequences
            1. Internal vs external iterators
            2. Generators with yield
            3. Cooperative coroutines
            4. Lazy sequences
            5. Streams and data pipelines
            6. Backpressure and incremental consumption
            7. Parallel iteration and concurrency
            8. Infinite iterators / unbounded streams
            9. Deferred materialization and batching
            10. Generators with flow control and cancellation
        15. Metaprogramming and reflection
            1. Compile-time macros
            2. AST transformations
            3. Runtime reflection
            4. Annotations and attributes
            5. Code generation
            6. Templates / generic metaprogramming
            7. Meta-objects and metaclasses
            8. `eval` and dynamic execution
            9. Aspect-oriented programming (AOP)
            10. Automatic SDK / client generation from contracts
        16. Serialization and deserialization
            1. JSON
            2. XML
            3. Binary formats (Protocol Buffers, MessagePack)
            4. Marshaling / unmarshaling
            5. Message schema versioning
            6. Schemas and validation
            7. Backward and forward compatibility
            8. Data normalization and canonical forms
            9. Compression and encryption of serialized payloads
            10. Evolving schemas without downtime or data loss
        17. Style, conventions and maintainability
            1. Naming conventions
            2. Auto-formatting and linters
            3. Integrated documentation and docstrings
            4. Unit and integration testing
            5. Contracts and assertions
            6. Code review practices
            7. Continuous refactoring
            8. Managing cyclomatic complexity
            9. Technical debt management
            10. Automated refactor and API migration for deprecated syntax
    3. Tools and technical productivity
        1. Isolated environments and dependency management
            1. Per-project virtual environments
            2. Lock files and version locking
            3. Reproducibility across machines
            4. Deterministic vs floating installs
            5. Interpreter and runtime isolation
            6. Lightweight containers for local testing
            7. System vs application dependencies
            8. Reproducibility in CI/CD and ephemeral environments
            9. Cross-platform version pinning
            10. Dependency vulnerability auditing and scanning
        2. Versioning configuration and data
            1. Versioning environment configuration (dotfiles)
            2. Traceable and reversible backups
            3. History of infrastructure changes
            4. Handling binary files and large data
            5. Parameterized configuration templates
            6. Secrets management outside repositories
            7. Versioning encrypted secrets (vaults)
            8. Retention and expiration policies for backups
            9. Drift control between declared infra and real state
            10. Auditing access/privilege changes
        3. Project templates and service skeleton generation
            1. Minimal recommended structures per project type
            2. Bootstrapping new repositories automatically
            3. Naming conventions and layout
            4. Initial metadata (license, README, basic CI)
            5. Initial linting and formatting configuration
            6. Standard logging and error handling patterns
            7. Initial versioning and base numbering
            8. Minimal instrumentation and observability (metrics, logs)
            9. Initial security checks (dependency scan)
            10. Test templates and minimum coverage expectations
        4. Task runners and repeatable automation
            1. Makefiles and conventional targets
            2. Development workflow automation scripts
            3. Local build/test/lint pipelines
            4. Orchestration of dependent steps
            5. Internal deployment automation
            6. Self-documenting rules (`make help`)
            7. Reproducible jobs across environments
            8. Local pipelines mirroring CI
            9. Packaging tasks in local containers
            10. Caching intermediate results to speed iteration
        5. Living, navigable documentation
            1. Docs generated from code
            2. Documentation validated by tests
            3. Reproducible installation and setup instructions
            4. Executable examples and demo notebooks
            5. Truth tables for expected behavior
            6. Architecture diagrams and data flow charts
            7. Versioning docs alongside code
            8. Docs versioned per release
            9. Internal service / API catalog
            10. Operational runbooks and SRE playbooks
        6. Building CLI tools for internal flows
            1. Consistent, self-describing interfaces
            2. Standards for flags, subcommands and `--help`
            3. Structured logging and output
            4. Exit codes and error handling
            5. Team-wide utility scripts
            6. Internal distribution of binaries and scripts
            7. Single-binary packaging
            8. Secure authentication and credential handling
            9. Cross-platform distribution and signed binaries
            10. Optional telemetry and internal usage metrics
        7. Advanced IDE/environment integration
            1. Editor configuration and critical extensions
            2. Integration with linters and formatters
            3. Debugger integration
            4. Integration with performance analyzers
            5. Snippet and automated refactor settings
            6. Integration with task managers / issue trackers
            7. Shared workspace standards for teams
            8. Synchronizing settings across devices / team
            9. Accessibility of dev environment (themes, contrast, readability)
            10. Onboarding scripts for new developers
        8. Profiling and interactive debugging
            1. Step-by-step debugging
            2. Inspecting runtime internal state
            3. Conditional breakpoints
            4. Memory inspection at runtime
            5. CPU profiling and hot path analysis
            6. IO / network profiling
            7. Collecting core dumps and post-mortems
            8. Heap dumps and leak diagnosis
            9. Safe/limited production tracing
            10. Historical profile comparisons to detect regressions
        9. Static type checking and static analysis
            1. Gradual typing and interface contracts
            2. Detection of unreachable code paths
            3. Early detection of common errors
            4. Automated style and convention checks
            5. Security analysis of unsafe use of external input
            6. Automated reports in CI
            7. Editor integration for static analysis
            8. Threat modeling for untrusted inputs
            9. Alerts for deprecated API usage
            10. Compliance and regulatory reporting
        10. Automatic formatting and pre-commit validations
            1. Automatic code formatters
            2. Style and consistency linters
            3. Naming convention validations
            4. Import, dependency and license checks
            5. Quick pre-push error checks
            6. Normalizing line endings and text encoding
            7. Shared local hooks (`pre-commit`)
            8. Secret scanning in commits
            9. Automated commit message format validation
            10. Local smoke tests before push
        11. Continuous integration and delivery templates
            1. Build and test pipelines
            2. Linting and static analysis in CI
            3. Automated security scans
            4. Automatic artifact publishing
            5. Automated deploy to staging environments
            6. Quality checks before merge
            7. Automatic versioning and release tagging
            8. Automated canary deployments
            9. Automatic rollback based on SLO alerts
            10. Auto-publishing changelogs / docs with releases
        12. Reproducible and remote development environments
            1. Development in containers
            2. Per-branch ephemeral environments
            3. Remote dev and cloud workspaces
            4. Local/remote state synchronization
            5. Isolation of heavy resources (GPU, DBs, queues)
            6. Local simulation of external services
            7. Consistency policies between dev / staging / prod
            8. Remote debugging with cloud breakpoints
            9. Access auditing and control for shared dev environments
            10. Automatic cleanup and rotation of old ephemeral environments
    4. Version control and collaboration
        1. Fundamentals of distributed version control
            1. Commits as immutable snapshots
            2. Commit graph and DAG history
            3. Remotes, clones and forks
            4. Staging area and index
            5. Tracking changes vs tracking new files
            6. Ignoring temporary files and secrets
            7. Local vs remote history rewriting
            8. Integrity via cryptographic hashes and signatures
            9. Local branches vs remote tracking branches
            10. Recovering past states (reflog / restore)
        2. Branching strategies
            1. Trunk-based development
            2. Feature branches
            3. Release branches and hotfix branches
            4. Long-term support branches
            5. Frequent integration vs late integration flows
            6. Stability control on critical branches
            7. Relation between branches and deployed environments
            8. Feature flags vs long-lived branches
            9. Release trains / fixed cadence deliveries
            10. Cleaning up zombie / orphan branches
        3. Rebase, merge, cherry-pick and parallel work
            1. Fast-forward merge vs merge commit
            2. Interactive rebase to clean history
            3. Rewriting messages and squashing commits
            4. Cherry-picking isolated changes
            5. Backporting fixes to old branches
            6. Synchronizing divergent branches
            7. Avoiding lost work in parallel development
            8. Avoiding very complex recursive merges by early division
            9. Preserving authorship and metadata
            10. Risks of rebasing shared branches vs traditional merge
        4. Conflict resolution
            1. Common conflict types
            2. Code conflicts vs config or lockfile conflicts
            3. Assisted merge tools
            4. Good practices for readable conflict resolution
            5. Verifying and testing after resolving conflicts
            6. Minimizing conflicts via small, focused changes
            7. Documenting decisions made during resolution
            8. Partial automation with custom merge drivers
            9. Decision policies for functional/semantic conflicts
            10. Validate build and tests before closing the conflict
        5. Commit conventions and semantic versioning
            1. Clear, structured commit messages
            2. Separate functional changes from cosmetic ones
            3. Atomic and reversible commits
            4. References to issues / tickets
            5. Refactor vs feature vs fix commit separation
            6. Prefix/convention categories for change types
            7. Relation between commits and release notes
            8. Signed / verifiable commits
            9. Separate functional changes and refactors into different PRs
            10. Traceability between commits and legal/compliance records
        6. Semantic versioning and release tagging
            1. Major / minor / patch
            2. Breaking changes and major releases
            3. Compatible changes and minor releases
            4. Urgent fixes and patch releases
            5. Pre-releases and stability tags
            6. Signed and verifiable tags
            7. Publishing changelogs
            8. Gradual API deprecation strategies
            9. Binary compatibility / ABI for libraries
            10. Automated bumping and tagging tools
        7. Submodules, monorepos and multi-repo management
            1. Submodules and versioned dependencies
            2. Synchronizing versions across repos
            3. Monorepos with multiple services
            4. Coordinating changes across multiple packages
            5. Tools to maintain internal consistency
            6. Trade-offs of monorepo vs multi-repo
            7. Permission and ownership strategies for code
            8. Synchronizing dependencies in large monorepos
            9. Coordinated versioning of internal contracts/APIs
            10. Visibility and permission policies per folder/module
        8. Hooks and workflow automation
            1. Local hooks (pre-commit, pre-push)
            2. Server-side hooks (remote validations)
            3. Enforcers for formatting and style
            4. Signature and security policy validation
            5. Rejecting invalid pushes automatically
            6. Auto-generating docs and changelogs
            7. Triggering CI/CD from repository events
            8. Dependency vulnerability scanning on push
            9. Enriching PRs with contextual information
            10. Continuous audit of internal policy compliance
        9. Integration with code review and CI
            1. Pull requests and merge requests
            2. Peer review and module ownership
            3. Automated checks on each PR
            4. Gatekeepers and approver responsibilities
            5. Policies for emergency changes
            6. Synchronization between branches and CI pipelines
            7. Security and compliance validation
            8. Rotating reviewers and balancing review load
            9. Metrics for lead time and review time
            10. Performance/load tests in critical PRs
        10. Review policies and protected branches
            1. Protected branches and push restrictions
            2. Minimum review requirements
            3. Mandatory approval rules
            4. Required signatures and author verification
            5. Pre-merge quality checks
            6. Recording who approved each change
            7. Approval conditioned on tests and coverage
            8. Policies by repository criticality
            9. Require reproducible / verifiable builds
            10. Auditing changes to sensitive configurations
        11. History audit and traceability
            1. Who changed what and when analysis
            2. Blame and line-level attribution
            3. Safe revert of specific versions
            4. Reconstructing the timeline of a bug
            5. Compliance and external audits
            6. Cryptographic footprints and GPG signatures
            7. Traceability between code, decisions and production
            8. Reconstructing security incidents from history
            9. Evidence for certifications and legal compliance
            10. Preservation and archiving of historical branches / stable snapshots

4. Backend development and services
    1. Web frameworks and API design
        1. Types and web architectures
            1. REST / RESTful
            2. HATEOAS
            3. GraphQL
            4. Binary RPC (gRPC / Thrift / Avro)
            5. WebSockets
            6. Long Polling
            7. Server-Sent Events (SSE)
            8. WebTransport
            9. WebRTC oriented to data channels
            10. SOA (Service-Oriented Architecture)
            11. SOAP / WSDL
            12. API Gateway and BFF (Backend for Frontend)
        2. Bidirectional communication and real time
            1. Persistent WebSocket channels
            2. Server-Sent Events for unidirectional notifications
            3. Long polling compatible with legacy environments
            4. Bidirectional gRPC streaming
            5. Real-time broadcasting via pub/sub
            6. Shared channels / rooms between clients
            7. Presence state and "user online" indicators
            8. Collaborative live synchronization (co-editing)
            9. Partial and progressive delivery of long results
            10. Prioritization of critical messages vs secondary messages
        3. Middleware, interceptors and filters
            1. Chain of composable middlewares
            2. Request / response interceptors
            3. Pre-handler validation
            4. Payload transformation and normalization
            5. Structured logging and traces
            6. Latency metrics and response-time metrics
            7. Centralized authentication
            8. Route-level access control
            9. Rate limiting and quotas per endpoint
            10. CORS management and security headers
        4. Validation and serialization of input and output data
            1. Consistent validation schemas
            2. Input sanitization and normalization
            3. Strong typing in DTOs / formal contracts
            4. Structured serialization (JSON / XML / YAML)
            5. Efficient binary serialization
            6. Normalization of dates, numbers and timezones
            7. Validation of sizes, limits and formats
            8. Standardized error responses
            9. Schema versioning with backward compatibility
            10. Evolving contracts without breaking existing clients
        5. Authentication and authorization at the service level
            1. Basic authentication and API Keys
            2. Signed tokens (JWT)
            3. OAuth2 / OpenID Connect
            4. Corporate SSO and identity federation (SAML / IdP)
            5. Management of delegated and external identities (identity providers)
            6. Passkeys / WebAuthn
            7. MFA (SMS, TOTP/HOTP, push, biometric, hardware tokens)
            8. Secure sessions and protected cookies
            9. Rotation, expiration and revocation of credentials
            10. Service-to-service identity (workload identity / service accounts)
        6. Role- and attribute-based authorization
            1. RBAC (Role-Based Access Control)
            2. ABAC (Attribute-Based Access Control)
            3. PBAC / policy-based centralized authorization
            4. Scopes and claims in tokens
            5. Hierarchical and delegated permission logic
            6. Controls by action, resource and context
            7. Policy evaluation at runtime
            8. Audit of authorization decisions
            9. Separation of duties (SoD)
            10. Conditional access based on risk / client posture
        7. Rate limiting, pagination and abuse control
            1. Global rate limiting
            2. Rate limiting by IP / user / API key
            3. Quotas (daily, hourly or per plan)
            4. Throttling and backpressure
            5. Offset/limit pagination
            6. Cursor-based pagination / "start from here"
            7. Detection of abusive patterns (scraping / anomalous bursts)
            8. Selective temporary blocking / cooldown
            9. Automation/bot detection and mitigation
            10. Honeypots / canary endpoints to identify abuse
        8. API versioning
            1. Explicit versioning in the route (v1, v2…)
            2. Versioning via negotiation headers
            3. Semantic contract versioning
            4. Backward compatibility
            5. Forward compatibility
            6. Gradual deprecation and planned removal
            7. Parallel coexistence of versions
            8. Beta / preview channels
            9. Automated schema compatibility tests
            10. Lifecycle management for public / internal / legacy APIs
        9. API specifications and documentation
            1. OpenAPI / Swagger
            2. IDL / protobuf for gRPC
            3. Documented GraphQL schemas
            4. Automatically generated documentation
            5. Examples of requests / responses and error codes
            6. Formal definition of error contracts
            7. SDKs and clients generated from the contract
            8. Consumer-driven contract testing
            9. Mock servers generated from the specification
            10. Contract validation in CI/CD
    2. Databases and persistence
        1. Structured query languages
            1. Declarative SQL
            2. DDL / DML / DQL / DCL
            3. Joins and complex combinations
            4. Subqueries and CTEs
            5. Aggregations and analytic windows
            6. Planner query optimization
            7. Index hints and query tuning
            8. Execution plans and cost analysis
            9. Prepared statements and parameter binding
            10. Injection prevention and safe queries
        2. Relational modeling
            1. Definition of tables and primary keys
            2. Foreign keys and referential constraints
            3. 1:1, 1:N, N:M relationships
            4. Strict referential integrity
            5. CHECK constraints and value domains
            6. Highly normalized models
            7. Strategic denormalization for fast reads
            8. Pivot tables and join tables
            9. Change traceability (audit columns, timestamps)
            10. Record versioning (soft history / temporal tables)
        3. Normalization and denormalization
            1. Normal forms (1NF, 2NF, 3NF, BCNF)
            2. Elimination of uncontrolled redundancy
            3. Balance between consistency and performance
            4. Precomputed derived fields
            5. Summary / materialized aggregated tables
            6. Wide tables optimized for reads
            7. Highly factorized tables optimized for writes
            8. Data duplication strategies by service
            9. Maintaining synchronization between duplicated copies
            10. Impact on cache and read latency
        4. Transactions, atomicity and isolation
            1. ACID properties
            2. Commit and rollback
            3. Configurable isolation levels
            4. Dirty reads, non-repeatable reads and phantom reads
            5. Pessimistic locks and row-level locks
            6. MVCC (multi-version concurrency control)
            7. Deadlock detection and resolution
            8. Transaction timeouts and retries
            9. Distributed transactions / 2PC
            10. Idempotency of critical operations
        5. Indexes, views and triggers
            1. B-Tree indexes
            2. Hash indexes and GIN/GiST
            3. Composite and partial indexes
            4. Functional / expression indexes
            5. Logical views
            6. Materialized views and incremental refresh
            7. BEFORE / AFTER triggers
            8. Auditing, logging and enforcement via triggers
            9. Indexes for full-text search
            10. Index maintenance and health checks
        6. Stored procedures and in-database logic
            1. User-defined functions (UDF)
            2. Transactional stored procedures
            3. Enforcing business rules at the SQL layer
            4. Data enrichment on insert / update
            5. Implementing simple queues inside the DB
            6. Granular access control in functions
            7. Encapsulation of critical centralized logic
            8. Versioning and deployment of SP/UDF changes
            9. Optimization and caching of function results
            10. Governance and security review of DB logic
        7. Object-relational mapping and data access layers
            1. ORMs
            2. Repositories / DAOs
            3. Typed query builders
            4. N+1 problem and batching techniques
            5. First-level cache (per session)
            6. Second-level cache (shared)
            7. Unit of Work pattern
            8. Mapping inheritance and complex polymorphism
            9. Gradual migration out of the ORM when it is a bottleneck
            10. Data-access tests with realistic fixtures
        8. Structured and controlled schema migrations
            1. Versioned incremental migrations
            2. Forward / backward safe migrations
            3. Transactional application of migrations
            4. Online migrations without downtime
            5. Renaming, splitting and merging large tables
            6. Audit and recording of schema changes
            7. Consistent seed / initial data
            8. Feature flags tied to schema changes
            9. Validation of migrations in staging
            10. Automated rollback on production failure
        9. Connection pools and concurrent access efficiency
            1. Pooling and connection reuse
            2. Maximum concurrent connection limits
            3. Reuse vs aggressive reconnect
            4. Timeouts and keepalive
            5. Balancing to read-only replicas
            6. Query queuing under saturation
            7. Prioritization of critical queries
            8. Circuit breakers for the database
            9. Pooling per service / tenant
            10. Telemetry of pool usage and dynamic tuning
        10. Non-relational storage
            1. Key-value stores
            2. Document stores
            3. Wide-column / columnar stores
            4. Graph databases
            5. Time-series databases
            6. TTL per record and automatic expiration
            7. Configurable eventual consistency
            8. Native horizontal sharding
            9. Secondary indexes and ad-hoc queries
            10. Replication policies per collection / bucket
        11. Search engines and full-text query
            1. Full-text indexing
            2. Configurable relevance ranking
            3. Tokenization, stemming and linguistic normalization
            4. Fuzzy search and typo tolerance
            5. Facets, filters and field aggregations
            6. Distributed inverted indexes
            7. Search at horizontal scale
            8. Enrichment / annotation of indexed documents
            9. Highlighting of matches
            10. Synonym control and semantic relevance
        12. Analytical storage and business query systems
            1. Columnar data warehouses
            2. OLTP vs OLAP distinction
            3. Precomputed aggregates and cubes
            4. Time-partitioned tables
            5. Data lakes and lakehouses
            6. ETL / ELT ingestion pipelines
            7. Fact tables and dimension tables
            8. Data catalog and lineage
            9. Incremental materialization of business metrics
            10. Governance of access to analytical data
        13. Replication, partitioning and high availability
            1. Read-only replicas and read scaling
            2. Horizontal sharding (by range / hash / geography)
            3. Automatic primary failover
            4. Multi-region geo-replication
            5. Load balancing across nodes
            6. Configurable consistency per operation (quorum)
            7. Recovery from node / rack / AZ failures
            8. Controlled promotion of replicas to primary
            9. Incremental synchronization based on logs
            10. Health and latency monitoring between replicas
        14. Referential integrity and eventual consistency
            1. Strong integrity in relational databases
            2. Soft deletes and logical consistency
            3. Asynchronous reconciliation between services
            4. Idempotent retries on writes
            5. Compensating events to revert changes
            6. Read-your-writes guarantees
            7. Materialized projections
            8. Partition-tolerant eventual consistency
            9. Write conflict resolution and semantic reconciliation
            10. Auditing and traceability of data mutations
    3. Integrations and inter-service communication
        1. Asynchronous messaging and message queues
            1. Persistent and durable queues
            2. Topics and multiple subscriptions
            3. Lag and throughput metrics
            4. Delivery guarantees (at-most-once / at-least-once / exactly-once)
            5. Deferred retries with backoff
            6. Dead-letter queues (DLQ)
            7. Backpressure and consumer rate control
            8. Partition/key-based ordering
            9. Prioritization of critical messages
            10. Queue isolation by service / tenant
        2. Efficient RPC and binary contracts
            1. gRPC and bidirectional streaming
            2. IDL and strongly-typed contracts
            3. Compact binary serialization (protobuf/avro)
            4. Timeouts and end-to-end cancellation
            5. Retries with exponential backoff and jitter
            6. Context propagation (tracing, auth)
            7. mTLS between services
            8. RPC contract versioning control
            9. Backward/forward compatibility via optional fields
            10. Automatic contract validation in CI
        3. Webhooks, notifications and external callbacks
            1. Outgoing HTTP delivery with signatures
            2. Retries with exponential policy
            3. Duplicate detection and suppression
            4. Delivery audit and tracking
            5. Temporary suspension when receiver is down
            6. Manual replay / safe re-delivery
            7. Receiver endpoint security (secrets, IP allowlist)
            8. Idempotency in callbacks
            9. External payload versioning
            10. Legal contracts / SLAs with third parties
        4. Integration with third-party services
            1. Consuming external APIs
            2. OAuth2 / delegated tokens
            3. Provider-imposed rate limits
            4. Use of third-party sandbox / staging environments
            5. Provider API versioning and migration
            6. Defensive caching of external responses
            7. Circuit breakers for degraded external services
            8. Integration-specific observability
            9. Compliance with terms of use / audits
            10. Fallback strategies if the third party fails
        5. Retry strategies and dead-letter queues
            1. Retries with progressive backoff
            2. Retries with random jitter
            3. Maximum retry limits per message
            4. DLQ (Dead-letter queue) for problematic messages
            5. Manual reprocessing and operational tooling
            6. Message correlation and unique identifiers
            7. Idempotency and deduplication in retries
            8. Isolation of toxic traffic
            9. Automatic alerts when failed message backlog accumulates
            10. Prioritization of reprocessing by criticality
        6. Binary serialization and compact formats
            1. Protocol Buffers
            2. Avro
            3. FlatBuffers / Cap’n Proto
            4. Optional and repeated fields
            5. Schema evolution without breaking compatibility
            6. Compression and message fragmentation
            7. Explicit message versioning
            8. Runtime schema validation
            9. Schema validation in CI/CD pipelines
            10. Cross-platform / multi-language compatibility
        7. Event-driven architectures and event sourcing
            1. Immutable events as the source of truth
            2. Distributed append-only log
            3. Materialized projections derived from the log
            4. Reconstructing state from events
            5. Replaying historical events
            6. Versioning of event types
            7. Eventual consistency via event propagation
            8. Integration with CQRS
            9. Total ordering vs partition ordering
            10. Delivery guarantees and event deduplication
        8. Publish/subscribe models
            1. Decoupled pub/sub producer-consumer
            2. Topic / tag / pattern filters
            3. Selective broadcast
            4. Durable subscriptions with historical retention
            5. Massive fan-out to multiple consumers
            6. Load balancing among consumers of the same topic
            7. Multiplexing events in logical channels
            8. Retries and explicit consumption acknowledgements
            9. Isolation by priority or criticality
            10. Payload versioning in shared topics
        9. Real-time data streaming and change capture
            1. Continuous record streaming
            2. Stream processing
            3. Time windows and live aggregations
            4. CDC (Change Data Capture) from the database
            5. Replication based on transaction logs
            6. Reactive subscriptions to state changes
            7. Near real-time alerts
            8. Prioritization of critical events
            9. Backpressure in streaming pipelines
            10. Persistence and replay of historical streams

5. Frontend development, graphical interfaces and usability
    1. Fundamentals of experience and flow
        1. Human–computer interaction
            1. Mental models and user expectations
            2. Affordances and usage cues
            3. Immediate feedback and visible responses
            4. Perceived latency and sense of control
            5. Direct mapping between action and impact
            6. Cognitive cost of use
            7. Preventable vs recoverable errors
            8. Fitts' Law and target distance
            9. Hick's Law and option overload
            10. Working memory and visual load
        2. User flows
            1. Primary task objective
            2. Happy path vs edge cases
            3. Mandatory vs optional steps
            4. Minimization of friction
            5. Drop-off points
            6. Prior and subsequent states (context before/after)
            7. Linear vs branching flows
            8. Recovery after interruption
            9. Continuity across devices
            10. Partial progress persistence
        3. Interface states
            1. Initial / empty state
            2. Loading state
            3. Data-present state
            4. No-results / meaningful empty state
            5. Error state and recovery
            6. Partially interactive / disabled state
            7. Confirmed / success state
            8. Pending / in-progress state
            9. Transient vs persistent states
            10. Local vs global app states
    2. Interaction and communication with the user
        1. Visual architecture
            1. Visual hierarchy (weight, size, contrast)
            2. Typography and modular scale
            3. Functional use of color
            4. Semantic iconography
            5. Spacing and visual rhythm
            6. Division into functional zones (navigation / content / actions)
            7. F/Z reading patterns
            8. Focus on actionable vs informational elements
            9. Visual accessibility cues
            10. Consistency across screens
        2. Interaction patterns
            1. Selection (click/tap/drag)
            2. Search and filtering
            3. Inline editing
            4. Explicit confirmation and undo
            5. Step-by-step forms (wizards)
            6. Tabular navigation / tabs / accordions
            7. Context menus
            8. Hover vs long-press vs right-click
            9. Touch gestures
            10. Bulk actions / batch editing
        3. Microinteractions and perception
            1. Small animations with functional intent
            2. Non-blocking loading indicators
            3. Hover states / pressed states
            4. Haptic vibration and tactile feedback
            5. Subtle sounds for confirmation or error
            6. “Typing…” or “sending…” indicators
            7. Immediate visual reactions to user input
            8. Non-modal confirmations (toasts)
            9. Smooth transitions between related views
            10. Contextual micro-help messages
        4. Notifications and attention management
            1. In-app local notifications
            2. Push notifications
            3. Urgency vs noise
            4. Visual prioritization (color, position, persistence)
            5. Historical notification center
            6. Silent / do-not-disturb mode
            7. Blocking vs non-blocking alerts
            8. Required confirmations vs informational
            9. User-customizable relevance
            10. Notification expiration
        5. Discoverability and search
            1. Clear labeling of actions
            2. Tooltips and inline help
            3. Global search in the interface
            4. Visible keyboard shortcuts
            5. Progressive tutorial (not front-loaded)
            6. Meaningful prefilled examples (placeholders)
            7. Guided demos (“try it” interactive)
            8. Educational initial state (instructional empty state)
            9. “What’s new” sections
            10. Highlight advanced features without blocking basics
        6. Content in the interface
            1. Clear, direct microcopy
            2. Inclusive language
            3. Avoid unnecessary technical jargon
            4. Avoid blaming the user in error messages
            5. Indicate cause and possible action
            6. Contextual text, not generic
            7. Tone consistent with the brand
            8. Avoid walls of text
            9. Empty states with actionable instructions
            10. Short, actionable button labels
        7. Onboarding and continuous learning
            1. Progressive and contextual, not a huge initial tutorial
            2. Interactive step-by-step guided mode
            3. Visual signaling of “new”
            4. Demo states with fictitious data
            5. First-steps checklist
            6. Gentle reminders of key features
            7. Role/permission-specific onboarding
            8. Re-onboarding after major redesigns
            9. Integrated help center
            10. Learning through guided repetition
    3. Presentation layer and UI composition
        1. Rendering and UI composition
            1. Node tree / view tree
            2. Responsive layout (viewport adaptation)
            3. Composition flow (layout → paint → composite)
            4. Reuse of views and subtrees
            5. Virtual DOM / reconciliation
            6. Server-Side Rendering (SSR)
            7. Static Site Generation (SSG)
            8. Partial / progressive hydration
            9. Islands architecture
            10. Incremental on-demand rendering
        2. Local UI state management
            1. Controlled vs uncontrolled state
            2. Controlled forms
            3. Ephemeral states (focus, hover, expanded)
            4. Derived state / memoization
            5. Immutable structures for predictable changes
            6. Local reducers / stores per component
            7. Syncing state with the URL
            8. State restoration on back navigation
            9. Temporary persistence in memory or local storage
            10. Visual rollback after an action error
        3. Visual stability
            1. Avoid unexpected layout shift (CLS)
            2. Reserve space for late-loading content
            3. Avoid jumps when injecting ads or banners
            4. Smooth animations instead of flicker
            5. Font loading without excessive flash (FOIT/FOUT)
            6. Keep keyboard focus stable
            7. Preserve scroll position between renders
            8. Loading indicators that do not block layout
            9. Avoid intrusive overlays that move content
            10. Understandable visual progression for the user
    4. Frontend application architecture
        1. Component modeling
            1. Presentational vs container components
            2. Props and explicit inputs
            3. Encapsulation of behavior
            4. Reusable and composable components
            5. Controlled vs uncontrolled components
            6. Isolation of side effects
            7. Separation between view and business logic
            8. Render props / slots / children-as-function patterns
            9. Atomic / molecular / organizational component design
            10. Versioning / deprecation of UI components
        2. Shared state management
            1. Global application state
            2. Centralized stores
            3. Context propagation
            4. Reducing renders via selective subscriptions
            5. Resource-cached states
            6. Client-side data normalization
            7. Coherent cache invalidation
            8. State synchronization across tabs
            9. Concurrency control in updates
            10. Selective persistence (localStorage / IndexedDB)
        3. Navigation and flow management
            1. Declarative routing
            2. URL / hash / memory-based routing
            3. Protected routes (auth)
            4. Nested routes
            5. Lazy-loaded routes
            6. Navigation guards (confirm exit, unsaved changes)
            7. Deep linking
            8. Syncing UI with URL (query params as state)
            9. Optimistic navigation (UI before real confirmation)
            10. Handling intermediate states between screens
        4. Integration with the design system
            1. Use of design tokens (color, spacing, typography)
            2. Shared component libraries
            3. Design system versioning
            4. Theming (dark mode / white-label)
            5. Visual compatibility across teams and products
            6. Consistency in interactions (hover, focus, active)
            7. Alignment with accessibility guidelines
            8. Approval processes for new patterns
            9. Early detection of visual drift
            10. Elimination of duplicated components
        5. UI DSL and templates
            1. Declarative components
            2. Reusable templates for repeated views
            3. Schema-driven UI configuration
            4. Forms generated from metadata
            5. Declarative conditional rendering
            6. Internal visual builders
            7. Parameterizable layouts
            8. Internationalization integrated in templates
            9. Snapshot testing of declarative views
            10. Controlled evolution without breaking existing screens
    5. Data, network and synchronization
        1. API consumption
            1. Fetch / XHR / gRPC-web
            2. Network error handling
            3. Retries with backoff
            4. Client-side caching
            5. Normalization of responses on the client
            6. Transforming wire formats to internal models
            7. Pagination handling
            8. Data streams vs one-off requests
            9. Per-request token/authorization security
            10. Payload signing / integrity verification
        2. Synchronization with backend
            1. Fresh reads vs cached reads
            2. Reactive invalidation
            3. Delta / patch updates
            4. Periodic synchronization
            5. On-demand synchronization
            6. Local queues of pending changes
            7. Concurrent write conflicts
            8. Client-side conflict resolution
            9. Optimistic confirmation and visual rollback
            10. Resource versioning
        3. Real-time and concurrency
            1. Subscribing to server events
            2. Presence indicators in real time
            3. Concurrent editing of the same entity
            4. “Someone is typing” states
            5. Parallel edit conflicts
            6. Soft locking vs hard locking of resources
            7. Broadcast by channel / shared room
            8. Distinguishing local vs remote changes
            9. Incremental view updates without reload
            10. Prioritizing critical events vs noise
        4. Offline mode and network resilience
            1. Local caching of critical data
            2. Queue of pending offline operations
            3. Retry upon reconnect
            4. Offline/online status indicator
            5. Disable actions that require connection
            6. Resolve inconsistencies when back online
            7. Persistence in IndexedDB / local storage
            8. Offline data expiration policies
            9. Use of Service Workers
            10. Degraded but usable experience
        5. Scalability with live data
            1. Incremental infinite pagination
            2. List virtualization
            3. Partial rendering of large tables
            4. Throttling and debouncing updates
            5. Batching of event groups
            6. Visual prioritization of recent changes
            7. “There are more new changes” indicators
            8. Avoid global rerender on local changes
            9. Selective subscription by channel / room / resource
            10. Avoid overloading the main thread
    6. Performance and perceived experience
        1. Rendering costs
            1. Layout thrashing
            2. Unnecessary reflows
            3. Excessive repainting
            4. Heavy computation on the main thread
            5. Use of memoization / memo / pure components
            6. Batching updates
            7. Suspense / deferred loading of expensive parts
            8. GPU-accelerated animations
            9. Use of Web Workers for heavy work
            10. Cleanup of listeners and timers
        2. Delivery and initial load
            1. Bundle splitting
            2. Lazy loading by route or component
            3. Selective preload / prefetch
            4. Resource compression
            5. Minification of CSS and JS
            6. Progressive image loading
            7. Efficient use of web fonts
            8. Prioritization of critical resources
            9. Avoid blocking JS in the head
            10. Edge caching / CDN
        3. Perceived interactivity
            1. Time to Interactive
            2. Immediate response to input
            3. Clear “processing” states
            4. Smooth transitions between screens
            5. Brief animations to avoid feeling frozen
            6. Minimize main-thread blocking time
            7. Optimistic feedback
            8. Avoid scroll jank
            9. Avoid “dead UI” after click
            10. Prioritize action responses over background tasks
        4. Performance budgets
            1. Bundle size limit
            2. Third-party scripts limit
            3. Main-thread blocking time limit
            4. Limits for CLS / LCP / INP
            5. CPU quotas on mobile devices
            6. Memory quotas on low-end devices
            7. Acceptable behavior on slow networks
            8. Minimum input-response metrics
            9. Maximum times for incremental render
            10. Automatic alerts when budgets are broken
    7. Accessibility, trust and ethics
        1. Accessibility and inclusion
            1. Full keyboard navigation
            2. Visible focus
            3. Alt text for images
            4. Sufficient contrast
            5. Appropriate roles and ARIA
            6. Screen reader support
            7. Avoid color-only dependencies
            8. Adjustable text size
            9. Reduced-motion / accessibility mode
            10. Properly labeled forms
        2. Internationalization and localization
            1. Multilanguage support
            2. Local formats (date, currency, separators)
            3. Plurals and genders
            4. LTR and RTL
            5. Text embedded in images
            6. Avoid rigid cultural assumptions
            7. Time zones and temporal context
            8. Regional legal and compliance adjustments
            9. Adapted copy, not just translated
            10. Avoid opaque anglicisms without explanation
        3. Security and trust
            1. Clear indicators for destructive actions
            2. Confirmations for critical operations
            3. Secure credential handling
            4. Visual indicators of encryption / secure session
            5. Prevent internal visual phishing
            6. Prevent clickjacking
            7. Lock UI after prolonged inactivity
            8. Feedback on permission requests
            9. Explanation of personal data usage
            10. Clear session and logout states
        4. Compliance and sensitive data
            1. Minimization of visible data
            2. Partial redaction / data masking
            3. Secure flows for personal or financial data
            4. User action history
            5. Reinforced identity confirmation for certain actions
            6. Explicit consent for storage
            7. Visible legal notices when applicable
            8. Audit of access to sensitive information
            9. Retention / expiration of visible data
            10. Download / portability of personal data
        5. Interaction ethics
            1. Avoid dark patterns
            2. Avoid emotional manipulation
            3. Clarity about the real cost of actions
            4. Respect the user's time
            5. Ask vs assume consent
            6. Avoid addictive gamification excess
            7. Avoid forcing unnecessary data sharing
            8. Transparency about AI / automation use
            9. Avoid biases in information presentation
            10. Respect cognitive and sensory limits
    8. Design system and experience governance
        1. Design system
            1. Design tokens
            2. Unified component library
            3. Standardized interaction patterns
            4. Color and typography usage guide
            5. Spacing and grid
            6. Standard iconography
            7. Consistent error / success states
            8. Standardized animations
            9. Accessible-by-default library
            10. System versioning and changelog
        2. Maintainability and experience debt
            1. Duplicated components
            2. Style inconsistencies
            3. Legacy patterns that are not accessible
            4. Experimental elements not consolidated
            5. Divergences across teams
            6. Dependence on ad-hoc overrides
            7. Layout fragmentation
            8. Lack of usage documentation
            9. Failure to remove obsolete patterns
            10. Accumulation of visual hacks
        3. Design governance
            1. Committee or role responsible for global design
            2. Proposal process for new patterns
            3. Cross-review between design and engineering
            4. Approval of changes affecting accessibility
            5. Brand consistency control
            6. Periodic experience audits
            7. Feedback mechanisms from satellite teams
            8. System evolution roadmap
            9. Communication of major changes
            10. Planned deprecation of old components
        4. Interface standards and guides
            1. Tone and voice guide
            2. Microcopy guide
            3. Forms and validation guide
            4. Error states guide
            5. Confirmation and dialog guide
            6. Keyboard interaction guide
            7. Minimum acceptable accessibility guide
            8. Navigation and information architecture guide
            9. Notifications guide
            10. Guide for critical reusable components
    9. Quality and validation
        1. Testing
            1. Unit tests for components
            2. Integration tests for full views
            3. End-to-end tests in real browser
            4. Visual snapshots / visual regression
            5. Automated accessibility tests
            6. Client-side performance tests on real devices
            7. Contract tests with mocked backend
            8. Deterministic tests for edge cases
            9. Simulation of latency / network failure
            10. Cross-browser / cross-device tests
        2. Experience and usability testing
            1. Moderated user testing
            2. Unmoderated user testing
            3. A/B testing
            4. Heatmaps and click maps
            5. Session recordings with consent
            6. In-product surveys
            7. Task success rate measurement
            8. Time to complete critical task
            9. Flow abandonment rate
            10. Perceived friction and qualitative feedback
        3. Versioning and maintainability of changes
            1. Gradual rollouts
            2. Feature flags
            3. Canary release by user segment
            4. Metrics before / after change
            5. Fast reversibility (rollback)
            6. Compatibility with already-saved local data
            7. Versioning of internal visual contracts
            8. Documentation of notable changes for support
            9. Communication of changes to end users
            10. Risk audit prior to merge
    10. Collaboration and multi-user
        1. Real-time presence (who is viewing/editing)
            1. Remote cursor indicators
            2. Avatars for simultaneous presence
            3. “User is typing…” states
            4. Entry/exit notifications for rooms
            5. Distinguish viewing vs active editing
            6. Reserved work zones
            7. Connection status of each collaborator
            8. Ephemeral co-editing sessions
            9. Contextual live annotations
            10. Visual scaling with many concurrent users
        2. Resolution of simultaneous edit conflicts
            1. Optimistic locking
            2. Pessimistic locking
            3. Automatic field-level merge
            4. CRDTs
            5. Per-user change history
            6. Real-time conflict alerts
            7. Preview remote content before accepting
            8. “Last write wins” vs intelligent reconciliation
            9. Revert unwanted remote changes
            10. Intermediate reconciliation state
        3. Shared history and attribution by person / role
            1. Timeline of changes
            2. Visible authorship per element
            3. Inline comments and discussion
            4. Formal review and approval
            5. Roles (viewer / commenter / editor / approver)
            6. Traceable responsibility
            7. Restore previous versions
            8. Visual diff between versions
            9. Auditability for compliance
            10. Flagging critical changes pending review
    11. Operation and evolution of the frontend
        1. Observability and metrics
            1. Real User Metrics (RUM)
            2. Perceived interaction latency
            3. Initial load and internal navigation timings
            4. Client-side crash reporting
            5. JS error logs
            6. Alerts for perceived degradation
            7. Accessibility metrics in production
            8. Conversion and flow abandonment metrics
            9. Performance tracking by device/network
            10. Segmentation by deployed version
        2. Evidence-driven improvement
            1. Prioritization based on real user impact
            2. Iteration on highest friction points
            3. Removal of unused features
            4. Fine-tuning microinteractions
            5. Staged changes tested with cohorts
            6. Roadmap driven by data and qualitative feedback
            7. Observe post-change behavior
            8. In-product feedback mechanisms
            9. Ethical telemetry with consent
            10. Cross-team review design–product–engineering

6. Mobile and embedded development
    1.

7. Scientific computing and HPC
    1. Fundamentals of numerical analysis
        1. Floating-point arithmetic and numerical error
            1. IEEE-754 formats (single, double and extended precision)
            2. Representation of subnormal / denormal numbers
            3. Rounding modes: upward / downward / to-nearest
            4. Loss of significance and catastrophic cancellation
            5. Overflow and underflow
            6. Accumulated errors in long sums and compensated summation (Kahan)
            7. Numerical comparisons with tolerance (machine epsilon)
            8. Extended precision and arbitrary multiprecision computing
            9. Impact on reproducibility across different architectures
            10. Sensitivity of results to small input perturbations
        2. Numerical conditioning and condition number
            1. Absolute vs relative conditioning
            2. Condition number of a function or problem
            3. Well-conditioned vs ill-conditioned problems
            4. Classic ill-conditioned examples (Hilbert matrices)
            5. Effect of conditioning on final result accuracy
            6. Relation between conditioning and need for extended precision
            7. Rescaling techniques to improve conditioning
            8. Practical estimation of the condition number
            9. Propagation of uncertainty in ill-conditioned problems
            10. Impact on stability of iterative methods
        3. Algorithmic stability and numerical stability
            1. Numerically stable vs unstable algorithms
            2. Forward error vs backward error
            3. Backward error analysis
            4. Numerical cancellation in nearly-equal subtractions
            5. Algebraic reordering to improve stability
            6. Choosing equivalent formulations that are more stable
            7. Methods that amplify vs damp rounding error
            8. Stability in presence of noise in input data
            9. Stability in repetitive / cumulative operations
            10. Empirical evaluation of stability with synthetic data
        4. Consistency, convergence and order of numerical methods
            1. Definition of method consistency
            2. Convergence to the exact solution as the step is refined
            3. Order of convergence and error rate
            4. First-order vs high-order methods
            5. Consistency + stability ⇒ convergence (Lax theorem)
            6. Mesh / time-step refinement in simulations
            7. Global vs local convergence
            8. Error estimation and adaptive step control
            9. Cost vs desired accuracy trade-offs
            10. Comparison of explicit vs implicit methods in convergence
        5. Propagation and accumulation of rounding errors
            1. Independent vs correlated errors
            2. Error amplification in repeated operations
            3. Long sums and error compensation
            4. Reordering operations to minimize accumulated error
            5. Effect of data type (float32 vs float64 vs float128)
            6. Impact of parallelization on sums/reductions (non-associativity)
            7. A priori vs empirical estimation of error accumulation
            8. Interval arithmetic techniques for error bounds
            9. Precision control on vector/GPU hardware
            10. Bitwise reproducibility between runs
        6. Scaling and nondimensionalization of physical equations
            1. Dimensionless variables and normalized units
            2. Reducing extreme magnitudes to avoid overflow/underflow
            3. Rescaling of ill-conditioned matrices
            4. Nondimensionalization to improve temporal stability
            5. Choice of characteristic scales (time, length, energy)
            6. Rewriting differential equations in nondimensional form
            7. Comparability between simulations with different physical scales
            8. Estimation of expected ranges of simulated variables
            9. Avoiding cancellation due to differences of magnitude
            10. Physical interpretation of nondimensional results
        7. Sensitivity and perturbation analysis
            1. Output sensitivity to small input changes
            2. Linear and nonlinear perturbation analysis
            3. Sensitivity derivatives and numerical differentiation
            4. Detection of critical / stiff parameters
            5. Identification of variables dominant in global behavior
            6. Robustness of a model to experimental uncertainty
            7. Propagation of stochastic noise in simulations
            8. Manufacturing / measurement tolerances in engineering models
            9. Parametric sensitivity for calibration and inverse problems
            10. Use in optimal control and design assistance
        8. Numerical chaos and dependence on initial conditions
            1. Chaotic dynamical systems
            2. Exponential sensitivity to initial conditions
            3. Useful prediction horizon
            4. Numerical divergence due to rounding errors
            5. Lyapunov exponents (chaos indicators)
            6. Physical chaos vs numerical chaos induced by discretization
            7. Methods to bound probable trajectories vs exact ones
            8. Importance of statistical sampling instead of single trajectories
            9. Monte Carlo simulations in chaotic systems
            10. Implications in climate, turbulence, astrophysics and fluid dynamics
    2. Fundamental numerical methods
        1. Interpolation and polynomial approximation
            1. Lagrange interpolation
            2. Newton interpolation (divided differences)
            3. Cubic splines and smooth splines
            4. Piecewise interpolation and C¹ / C² continuity
            5. Runge phenomenon with high-degree polynomials
            6. Chebyshev points to minimize oscillations
            7. Multivariate interpolation
            8. Local vs global fitting
            9. Efficient polynomial evaluation (Horner)
            10. Estimation of interpolation error
        2. Curve fitting and numerical regression
            1. Linear least squares
            2. Nonlinear least squares
            3. Polynomial fitting of varying degree
            4. Regularization (L2 / ridge, L1 / LASSO)
            5. Robust fitting against outliers
            6. Logarithmic / exponential / power law fitting
            7. Ill-conditioning in high-order regression
            8. Cross-validation and overfitting control
            9. Normal equation vs QR decomposition for stability
            10. Physical interpretation of fitted parameters
        3. Numerical differentiation
            1. Forward / backward / centered finite differences
            2. Truncation error order in finite differences
            3. Choice of step h optimal vs rounding error
            4. Numerical higher-order derivatives
            5. Automatic differentiation vs numerical differentiation
            6. Noise in experimental data and prior smoothing
            7. Gradient estimation for optimization
            8. Spectral techniques for differentiation (FFT)
            9. Directional derivatives in high-dimensional spaces
            10. Computational cost of repeated differentiation
        4. Numerical integration
            1. Trapezoidal and Simpson rules
            2. Composite quadrature over subintervals
            3. Adaptive methods with local refinement
            4. Gaussian quadrature
            5. Integration of highly oscillatory functions
            6. High-dimensional integration (curse of dimensionality)
            7. Monte Carlo integration
            8. Importance of change of variables and normalization
            9. Error estimation from multiple rules
            10. Parallelization by integrating independent subdomains
        5. Numerical solution of nonlinear equations
            1. Bisection method (interval search)
            2. Newton–Raphson method
            3. Secant and quasi-Newton methods
            4. Local convergence conditions
            5. Choice of initial guess and multiple roots issues
            6. Divergence detection and fallback to more robust methods
            7. Globally convergent vs locally fast methods
            8. Physical constraints to discard invalid roots
            9. Coupled systems of nonlinear equations
            10. Parallelization of root searches over different ranges
        6. Deterministic numerical optimization
            1. Classical gradient descent
            2. Newton and quasi-Newton methods (BFGS, L-BFGS)
            3. Trust-region methods
            4. Line-search methods with backtracking
            5. Optimality conditions (KKT, zero gradient)
            6. Quadratic / convex programming
            7. Handling constraints (penalties, Lagrange multipliers)
            8. Local vs global optimum detection
            9. Stopping criteria (gradient norm, energy change)
            10. Scalability in very high-dimensional problems
        7. Stochastic numerical optimization
            1. Simulated annealing
            2. Guided random restart search
            3. Genetic algorithms and differential evolution
            4. Particle swarm optimization (PSO)
            5. Stochastic gradient methods (SGD)
            6. Thermal / Gaussian noise to escape local minima
            7. Exploration vs exploitation balance
            8. Hyperparameter sensitivity and tuning
            9. Parallelization of objective evaluations
            10. Use in calibration of complex physical models
        8. Monte Carlo methods and random sampling
            1. Generation of high-quality pseudorandom numbers
            2. Uniform sampling vs importance sampling
            3. Acceptance-rejection methods
            4. Markov Chain Monte Carlo (MCMC)
            5. Statistical estimation of integrals and expectations
            6. Variance and Monte Carlo errors
            7. Variance reduction (stratification, control variates)
            8. Quasi-Monte Carlo and low-discrepancy sequences
            9. Massive parallelization of independent simulations
            10. Applications in statistical physics, quantitative finance and reliability
        9. Adaptive quadrature and composite methods
            1. Recursive subdivision of intervals based on estimated error
            2. Local refinement where the function is complex
            3. Global control of absolute and relative error
            4. Piecewise integration using simple rules per subinterval
            5. Handling local singularities
            6. Mixing rules (trapezoid, Simpson) according to local smoothness
            7. Parallelization by independent blocks
            8. Estimation of incremental computational cost
            9. Adaptive stopping criteria
            10. Use in problems with peaks, boundary layers or irregular boundaries
        10. Energy minimization and variational methods
        11. Formulation of physical problems as free-energy minimization
        12. Variational methods and energy functionals
        13. Principle of least action / minimal potential energy
        14. Spatial discretization (finite elements) for continuous energy
        15. Iterative relaxation methods for energy minimization
        16. Hard physical constraints (incompressibility, geometric limits)
        17. Projected gradient descent methods
        18. Multiscale techniques to relax large physical systems
        19. Numerical stability of energy relaxation
        20. Applications in structural mechanics, elasticity, materials and fluids
    3. Advanced numerical linear algebra
        1. LU, Cholesky, QR, SVD decompositions
            1. LU factorization to solve Ax = b
            2. Cholesky decomposition for symmetric positive-definite matrices
            3. QR decomposition for stable least squares
            4. Singular value decomposition (SVD)
            5. Numerical stability of each factorization
            6. Computational complexity and FLOP cost
            7. Use of partial / complete pivoting for stability
            8. Rank reduction and compression with truncated SVD
            9. Overdetermined and underdetermined problem solving
            10. Use in regression, compression, PCA and noise filtering
        2. Direct solution of linear systems
            1. Forward and backward substitution
            2. Classical Gaussian elimination
            3. Partial pivoting for numerical stability
            4. Block factorizations to exploit cache
            5. Dense vs sparse systems
            6. O(n³) costs and practical limits for large n
            7. Reuse of the same factorization for multiple RHS
            8. Effect of A's conditioning on accuracy of x
            9. Impact of rounding errors on final result
            10. Optimized implementations with BLAS/LAPACK
        3. Iterative methods for linear systems
            1. Jacobi and Gauss–Seidel
            2. Successive Over-Relaxation (SOR)
            3. Krylov subspace methods
            4. Convergence conditioned on spectral properties of A
            5. Stopping criteria (residual, relative norm)
            6. Preconditioning to accelerate convergence
            7. Scalability to very large sparse systems
            8. Natural parallelization of iterative methods
            9. Storage efficiency vs direct methods at large scale
            10. Applications in field, fluid and structural simulation
        4. Conjugate gradient and variants
            1. Conjugate gradient for SPD (symmetric positive-definite)
            2. Relation to minimization of a quadratic form
            3. Preconditioned CG (PCG)
            4. Convergence estimates from matrix spectrum
            5. Limitations for non-SPD matrices
            6. Flexible CG and practical adaptations
            7. Reuse of preconditioners between simulation steps
            8. Parallel CG on clusters and GPUs
            9. Reducing communication between nodes in HPC
            10. Numerical stability in long iterations
        5. GMRES, BiCGSTAB and general Krylov methods
            1. GMRES for nonsymmetric systems
            2. Restarted GMRES (GMRES(m)) to limit memory
            3. BiCGSTAB for accelerated convergence on nonsymmetric problems
            4. Growing Krylov subspace methods
            5. Sensitivity to chosen preconditioner
            6. Storage costs of Krylov bases
            7. Strategies to avoid loss of orthogonality
            8. Distributed parallelization and collective communications
            9. Trade-off between cheap iterations and robust iterations
            10. Use in CFD and electromagnetics simulations
        6. Eigenvalue and eigenvector problems
            1. Power and inverse power methods
            2. Iterative QR for eigenvalues
            3. Subspace methods for dominant eigenvalues
            4. Lanczos methods for large symmetric matrices
            5. Arnoldi methods for large nonsymmetric matrices
            6. Computing modal shapes in physical systems (vibration, normal modes)
            7. Extracting a few relevant eigenvalues without full spectrum
            8. Shift-and-invert spectral transformation
            9. Numerical stability with clustered spectra
            10. Parallelization of spectral computations in HPC
        7. Spectral decompositions and modal analysis
            1. Spectral decomposition of symmetric matrices
            2. Modal representation of linear dynamical systems
            3. Modal decomposition in structural vibrations
            4. Eigenmodes in quantum mechanics / wave equations
            5. Modal filtering for reduced-order modeling
            6. Selection of dominant modes and modal truncation
            7. Stability analysis via eigenvalues with positive/negative real part
            8. Spectrum-guided dimensionality reduction
            9. Construction of reduced bases (ROMs)
            10. Galerkin projection and subspace approximations
        8. Sparse matrices and storage formats
            1. CSR / CSC (Compressed Sparse Row / Column)
            2. COO and DIA (diagonal) formats
            3. Block sparse formats (Block CSR / BCSR)
            4. Impact on memory access and cache
            5. Efficient sparse matrix-vector multiply (SpMV)
            6. GPU loading and coalesced access for sparse data
            7. Assembly of sparse matrices in finite element methods
            8. Node reordering to improve locality (RCM, etc.)
            9. Compression and trade-offs between memory and speed
            10. Serialization / exchange of sparse matrices between HPC nodes
        9. Preconditioners and convergence improvement
            1. Diagonal / Jacobi scaling preconditioners
            2. ILU(0) and incomplete factorization variants
            3. Multigrid / algebraic multigrid (AMG) preconditioners
            4. Block-based preconditioners
            5. Domain-specific preconditioners
            6. Trade-off between preconditioner build cost and iteration gain
            7. Reuse across transient simulation steps
            8. Distributed implementation via domain decomposition
            9. Effect of preconditioner on global numerical stability
            10. Adaptive tuning of preconditioner during runs
        10. Multigrid and multiscale methods
            1. Relaxation on fine meshes and correction on coarse meshes
            2. V, W and F cycles
            3. Restriction and prolongation between mesh levels
            4. Smoothing high-frequency errors
            5. Convergence nearly independent of problem size
            6. Geometric vs algebraic multigrid
            7. Use in Poisson / diffusion / elasticity equations
            8. Extension to nonlinear problems (Full Approximation Scheme)
            9. Natural parallelization by levels and domains
            10. Combination with Krylov solvers as preconditioners
        11. Low-rank factorizations
            1. Approximating large matrices by low-rank factors
            2. Truncated SVD and numerical PCA
            3. CUR decomposition
            4. Low-rank approximation for operator compression
            5. Randomized methods for low-rank approximation
            6. Reduced storage and computational cost
            7. Application in reduced-order models for large physical systems
            8. Signal/noise separation via dominant modes
            9. Use in high-dimensional simulations (fluid dynamics, climate)
            10. Trade-off between lost accuracy and computational savings
    4. Methods for ordinary differential equations (ODE)
        1. Single-step explicit methods
            1. Explicit Euler
            2. Low-order Taylor methods
            3. Basic explicit Runge–Kutta methods (RK2, RK4)
            4. Stability conditioned on step size
            5. Local vs global error propagation
            6. Advantages for non-stiff, well-behaved problems
            7. Low per-step computational cost
            8. Simple parallelization of derivative evaluations
            9. Limitations for stiff equations
            10. Use in real-time simulations where speed outweighs fine accuracy
        2. Single-step implicit methods
            1. Implicit Euler (backward Euler)
            2. Implicit trapezoidal methods
            3. A-stability and L-stability
            4. Solving nonlinear systems at each step
            5. Requirement of Jacobians or Jacobian approximations
            6. Suitability for stiff ODEs
            7. Higher per-step computational cost
            8. Newton methods to close implicit steps
            9. Good damping control in dissipative systems
            10. Use in highly stiff simulations (chemistry, circuits, fast reactions)
        3. Multistep methods
            1. Adams–Bashforth (explicit)
            2. Adams–Moulton (implicit)
            3. Backward Differentiation Formulas (BDF)
            4. Use of past-step history to accelerate computation
            5. Stability and stiffness: BDF for very stiff problems
            6. Variable-order control
            7. Startup with single-step methods before applying multistep
            8. Error control via embedded estimators
            9. Difficulties with events/discontinuities (history reset)
            10. Efficiency in long-time simulations
        4. Classical and high-order Runge–Kutta methods
            1. Classic RK4 as a general-purpose standard
            2. Embedded adaptive Runge–Kutta (Fehlberg, Cash–Karp, Dormand–Prince)
            3. Explicit vs implicit Runge–Kutta methods
            4. Diagonally implicit RK for stiffness
            5. High-order RK (order 5,6,7+) trade-offs in cost/accuracy
            6. Local error control in embedded pairs
            7. Partitioned methods (for coupled stiff/non-stiff parts)
            8. Implementation simplicity vs analytical complexity
            9. Extensive use in physical simulation and scientific animation
            10. Partial parallelization of intermediate derivative evaluations
        5. Adaptive methods with step control
            1. Local error estimation at each step
            2. Dynamic adjustment of step size (step size control)
            3. Absolute vs relative tolerance criteria
            4. Rejection and repetition of steps when error too large
            5. Handling regions with rapid vs smooth changes
            6. Avoiding wasted work in smooth regions using large steps
            7. Avoiding instability in stiff regions with small steps
            8. Embedded pairs (p / p-1) to estimate error cheaply
            9. Detection of numerical blow-up and integration halting
            10. Relevance in general-purpose "solve ODE" routines
        6. Stiff systems and methods for stiffness
            1. Definition of stiffness in ODEs
            2. Severe step restrictions for explicit methods
            3. BDF methods for severe stiffness
            4. L-stable implicit Runge–Kutta methods
            5. Local linearization and solving internal linear systems
            6. Need for Jacobians or numerical Jacobian approximations
            7. Preconditioning for internal system solves
            8. Numerical stability against highly damped fast modes
            9. Typical stiff problems: chemical kinetics, circuits, nuclear reactions
            10. Automatic stiffness detection and solver switching at runtime
        7. Conservation of invariants and geometric integrators
            1. Symplectic integrators for Hamiltonian systems
            2. Long-term energy conservation in conservative systems
            3. Conservation of momentum and other invariants
            4. Action-angle methods and preservation of phase-structure
            5. Split-step methods for separable dynamics
            6. Rotation / rigid-body integrators preserving constraints
            7. Use in celestial mechanics and molecular dynamics
            8. Avoiding numerical drift in long simulations
            9. Lie–Trotter and Strang splitting
            10. Constraint-preserving methods for holonomic constraints
        8. Linearized methods and shooting methods
            1. Local linearization around time trajectories
            2. First-order approximations for weakly nonlinear systems
            3. Shooting method for boundary value problems
            4. Iteratively adjusting initial conditions to meet final conditions
            5. Extreme sensitivity to initial guess in direct shooting
            6. Subinterval decomposition to improve stability
            7. Coupling with optimization methods to satisfy boundary constraints
            8. Multiple shooting variants
            9. Use in optimal control and ballistic trajectory design
            10. Relation to collocation-type boundary methods
        9. Boundary value problem solution
            1. ODEs with conditions at more than one point (BVPs)
            2. Single and multiple shooting methods
            3. Collocation methods and basis-function approximations
            4. Global solution adjustment over the whole domain
            5. Incremental linearization and iterative solution
            6. Stability and sensitivity to small boundary perturbations
            7. Use of splines / piecewise polynomials to enforce conditions
            8. Galerkin-type methods for boundary value problems
            9. Conversion of BVP to a large algebraic system
            10. Applications in beams, 1D elasticity, stationary heat transfer
    5. Methods for partial differential equations (PDE)
        1. Finite difference discretization
            1. Approximation of spatial derivatives by forward/backward/centered differences
            2. Explicit time schemes (forward Euler for PDE)
            3. Implicit schemes (backward Euler, Crank–Nicolson)
            4. Spatial and temporal truncation order
            5. Conditional stability and CFL in explicit schemes
            6. Handling boundary conditions (Dirichlet, Neumann, mixed)
            7. Uniform vs nonuniform meshing
            8. Discretization of elliptic, parabolic and hyperbolic operators
            9. Treatment of convective terms and numerical diffusion
            10. Efficient implementation on regular meshes (stencil computation)
        2. Finite element discretization
            1. Weak / variational formulation of the problem
            2. Local basis functions (linear, quadratic elements, etc.)
            3. Assembly of global stiffness / mass matrix
            4. Handling complex geometries and irregular domains
            5. Local mesh adaptation where strong gradients appear
            6. Isoparametric elements and curved mapping
            7. Natural vs essential boundary conditions
            8. Mixed methods and hybrid formulations
            9. FEM for elasticity, thermal, flow, electromagnetics
            10. Use of FEM-specific preconditioners in HPC
        3. Finite volume discretization
            1. Conservation of fluxes across control volumes
            2. Integral balance over each cell
            3. Computation of numerical fluxes on cell faces
            4. Suited for conservation laws (mass, momentum, energy)
            5. Handling discontinuities (shock capturing)
            6. High-resolution schemes with slope limiters
            7. Structured vs unstructured meshes
            8. Global conservation by construction
            9. Extensive use in computational fluid dynamics (CFD)
            10. Physically intuitive local balance interpretation
        4. Spectral and pseudospectral methods
            1. Expansion of the solution in global basis functions (Fourier, Chebyshev)
            2. High accuracy with few degrees of freedom for smooth problems
            3. Fast transforms (FFT) to accelerate computation
            4. Complicated treatment of complex geometries
            5. Aliasing and dealiasing in nonlinear terms
            6. Pseudospectral methods evaluating derivatives in physical space
            7. Natural periodic boundary conditions in box domains
            8. Capturing dominant modes in turbulence and instabilities
            9. Parallel scalability via spectral domain decomposition
            10. Use in incompressible fluid and wave simulations
        5. Boundary integral and boundary element methods
            1. Reformulation of a PDE as an integral over the domain boundary
            2. Dimensionality reduction (e.g., 3D → 2D)
            3. Use of Green's functions
            4. Very efficient for infinite / semi-infinite domains
            5. Handling complex boundary conditions (acoustics, electromagnetics)
            6. Dense matrices resulting and need for accelerators (FMM, etc.)
            7. Difficulty with strong nonlinearities
            8. High accuracy for stationary potential problems
            9. Coupling with volumetric methods for interior domains
            10. Applications in wave scattering and elliptic problems
        6. Conservative schemes and conservation laws
            1. Discretizations that respect conservation of mass, momentum, energy
            2. Riemann-solver-type numerical fluxes
            3. Upwind and Godunov methods
            4. High-order schemes with TVD / ENO / WENO limiters
            5. Shock capturing without spurious oscillations
            6. Numerical entropy and physical stability
            7. Treatment of contact discontinuities and shock waves
            8. Prevention of nonphysical values (negative density/pressure)
            9. Methods for relativistic hydrodynamics and MHD
            10. Exact cellwise conservation as a validity criterion
        7. Numerical stability and the CFL condition
            1. Definition of the Courant–Friedrichs–Lewy (CFL) condition
            2. Relation between time step, characteristic speed and cell size
            3. Conditional stability of explicit hyperbolic schemes
            4. Choice of safe time step in transient simulations
            5. Implicit schemes that relax CFL restriction
            6. CFL impact on accuracy vs computational cost
            7. Adaptive time-step control based on local CFL
            8. Global vs local CFL in nonuniform meshes
            9. CFL in multiphysics problems (waves + diffusion)
            10. Typical failures when CFL is violated (numerical blow-up)
        8. Implicit vs explicit schemes for PDEs
            1. Explicit schemes: simpler and more parallelizable but require small steps
            2. Implicit schemes: more stable but require solving large systems
            3. Semi-implicit / IMEX (implicit-explicit) hybrid methods
            4. Differences for diffusive vs convective problems
            5. Cost of assembling and factoring large matrices in implicit methods
            6. Use of preconditioners in implicit solves
            7. Trade-off between cost per step and allowed step size
            8. Practical choice according to stiffness and temporal scales
            9. Physics-partitioned methods (treating different terms with different schemes)
            10. Memory and communication considerations in HPC
        9. Adaptive mesh refinement (AMR)
            1. Local spatial refinement where high variation occurs
            2. Coarsening where the solution is smooth
            3. Hierarchical nested mesh levels
            4. Refinement criteria based on gradient / curvature / estimated error
            5. Load balancing across HPC nodes with locally refined meshes
            6. Interpolation between refinement levels
            7. Conservation when refining / coarsening
            8. Dynamic adaptation in time (refinement that moves with a wave/shock)
            9. AMR in 2D vs 3D and memory costs
            10. Integration with multigrid and iterative solvers
        10. Particle methods and SPH (Smoothed Particle Hydrodynamics)
            1. Lagrangian representation: fluid as particles
            2. Smoothing kernel to estimate continuous fields
            3. Natural handling of large deformations and free surfaces
            4. Mesh-free (no fixed mesh required)
            5. Treatment of boundaries and boundary conditions in SPH
            6. Stability and artificial numerical viscosity
            7. Conservation of mass and momentum via particle interactions
            8. Use in astrophysics, free-surface flows, impacts and fragmentation
            9. GPU scalability with local neighbor searches
            10. Difficulty capturing highly compressible phenomena with high accuracy
        11. Immersed boundary methods
            1. Representing solid objects immersed in a fluid without meshing solids explicitly
            2. Distributed fluid forces to impose solid-fluid interaction on the fluid mesh
            3. Handling moving / complex geometries without full remeshing
            4. Use in biomechanics (heart valves, swimming organisms)
            5. Decoupling between fluid and solid resolution
            6. Approximate enforcement of no-slip conditions
            7. Possible numerical leakage near the interface if insufficiently refined
            8. Additional computational cost to impose immersed boundary conditions
            9. Extension to non-Newtonian and multi-component flows
            10. Coupling with deformable elastic structures
        12. Numerical treatment of discontinuities and shocks
            1. Capturing shocks without introducing spurious numerical oscillations
            2. Slope limiters to avoid overshoot/undershoot
            3. Godunov methods and approximate Riemann solvers
            4. ENO / WENO techniques for high resolution without oscillations
            5. Explicit shock tracking vs diffuse shock capturing
            6. Physical entropy and selection of physically correct solution
            7. Prevention of nonphysical values (negative density, negative pressure)
            8. Interaction of multiple shocks and wall reflections
            9. Relativistic shocks and magnetized shock waves in MHD
            10. Validation against analytic reference solutions / standard test problems (Sod, blast wave)
    6. Scientific simulation by physical domain
        1. Computational Fluid Dynamics (CFD)
            1. Solution of the Navier–Stokes equations (incompressible and compressible)
            2. Turbulence models (RANS, LES, DNS)
            3. Numerical stability in high-speed flows (high Mach)
            4. Capturing boundary layers, flow separation and drag
            5. Pressure-velocity coupling methods (projection, SIMPLE, PISO)
            6. Multiphase flow and interface tracking (VOF, Level Set)
            7. Reactive flows and numerical combustion
            8. Cavitation simulation and vortex-induced erosion
            9. Fluid-structure interaction (FSI)
            10. Massive parallelization on high-resolution 3D meshes
        2. Solid mechanics and structural analysis
            1. Linear and nonlinear elasticity
            2. Plasticity and hardening
            3. Large deformations and geometric nonlinearity
            4. Finite elements for stress and strain
            5. Modal analysis of structural vibrations
            6. Structural stability and buckling
            7. Contact and friction between bodies
            8. Fatigue and lifetime under cyclic loading
            9. Composite materials and anisotropy
            10. Topology optimization of structures
        3. Fracture, plasticity and damage mechanics
            1. Linear elastic fracture mechanics (LEFM)
            2. Crack initiation and propagation criteria
            3. Cohesive zone fracture models
            4. History-dependent plasticity
            5. Accumulated damage and stiffness degradation
            6. Dynamic fracture and rapid fragmentation
            7. Thermal and thermo-mechanical effects on crack propagation
            8. Multiscale models (microstructure → macroscopic behavior)
            9. Impact, penetration and ballistics simulation
            10. Lifetime assessment and damage tolerance in safety-critical engineering
        4. Computational electromagnetics
            1. Numerical solution of Maxwell’s equations
            2. FDTD methods (Finite-Difference Time-Domain)
            3. Finite element methods for electromagnetics
            4. Boundary methods for electromagnetic scattering
            5. Wave propagation in complex media
            6. Waveguides, antennas and resonant cavities
            7. High-frequency electromagnetic coupling and radiation effects
            8. Interference, diffraction and absorption in real materials
            9. Electromagnetic compatibility / EMI simulation (EMC/EMI)
            10. Optimization of RF / microwave / integrated photonics devices
        5. Plasma physics and magnetohydrodynamics
            1. Coupled MHD (magnetohydrodynamics) equations
            2. Frozen-in magnetic field dynamics in fluids
            3. Magnetic reconnection and energy release
            4. Plasma instabilities (Rayleigh–Taylor, Kelvin–Helmholtz, kink)
            5. Kinetic models vs fluid models for plasmas
            6. Particle-in-cell (PIC) methods for collisionless plasmas
            7. Magnetized shock waves and MHD shock structures
            8. Magnetic confinement in nuclear fusion
            9. Anisotropic heat transport in magnetized plasmas
            10. Simulation of space and astrophysical plasmas
        6. Computational astrophysics and numerical relativity
            1. Self-gravitating N-body gravitational evolution
            2. Gravitational collapse and formation of cosmic structures
            3. Cosmological hydrodynamics with universe expansion
            4. Coupled radiation-hydrodynamics simulations
            5. Numerical general relativity (discretized Einstein equations)
            6. Gravitational waves and compact object mergers
            7. Accretion models around black holes
            8. Relativistic jet ejection and extreme magnetic fields
            9. Tracking chemical species in stellar evolution and interstellar media
            10. Adaptive mesh refinement across enormous astronomical scales
        7. Classical molecular dynamics
            1. Simulation of particle motion under classical forces
            2. Empirical interatomic potentials (Lennard-Jones, Morse, etc.)
            3. Symplectic integrators to conserve long-term energy
            4. Periodic boundary conditions (periodic boxes)
            5. Thermostats and barostats (NVT, NPT)
            6. Computation of thermodynamic properties (free energy, diffusivity)
            7. Trajectory analysis and time correlation functions
            8. Simulation of diffusion, mixing, self-assembly
            9. Coarse-grained vs detailed atomistic models
            10. GPU acceleration and spatial domain decomposition across nodes
        8. Ab initio molecular dynamics
            1. Forces derived directly from electronic structure calculations
            2. DFT (Density Functional Theory) coupled to atomic dynamics
            3. Extremely high computational cost per time step
            4. Short time scales but high quantum fidelity
            5. Simulation of chemical reactions and bond formation/breaking
            6. Electronic properties under extreme conditions (high P, high T)
            7. Comparison with fitted classical potentials
            8. Hybrid QM/MM (quantum–molecular mechanics) methods
            9. Structure optimization and search for metastable states
            10. Use in novel materials, catalysis and surface chemistry
        9. Statistical physics and Monte Carlo simulation
            1. Simulation of canonical, microcanonical, grand-canonical ensembles
            2. Metropolis–Hastings method
            3. Simulation of spin systems (Ising, Potts)
            4. Phase transitions and critical phenomena
            5. Simulated annealing techniques
            6. Histogram reweighting and rare-state analysis
            7. Random walks and Brownian diffusion
            8. Advanced sampling methods (cluster updates, parallel tempering)
            9. Computation of statistically averaged observables
            10. Estimation of statistical uncertainty and autocorrelation
        10. Climate models and geo-simulation
            1. Coupled ocean–atmosphere models
            2. Transport equations for heat, moisture and momentum at planetary scale
            3. General atmospheric circulation dynamics
            4. Ice models, cryosphere and glacier dynamics
            5. Carbon cycle and biogeochemical models
            6. Subgrid parameterizations for clouds and precipitation
            7. Data assimilation of observational data into numerical models
            8. Simulation of extreme events (hurricanes, heatwaves)
            9. Scalability on supercomputers for long-term projections
            10. Uncertainty analysis and ensemble projections
        11. Seismology and wave propagation
            1. Elastic wave equations in heterogeneous media
            2. 3D seismic wave propagation modeling
            3. Spectral and finite-element methods for seismic waves
            4. Geologic interface discontinuities and faults
            5. Realistic seismic source modeling (dynamic ruptures)
            6. Attenuation, dissipation and dispersion of seismic pulses
            7. Seismic inversion to infer Earth's internal structure
            8. Earthquake scenario simulation for seismic engineering
            9. Tsunami propagation and ocean–ground coupling
            10. Need for adaptive meshes in urban/coastal regions
        12. Computational biophysics and protein dynamics
            1. Protein folding simulation
            2. Protein–ligand interactions and binding affinity
            3. Ion channels and transport across membranes
            4. DNA/RNA models and conformational dynamics
            5. Coarse-grained methods for large biological systems
            6. Simulation of cellular membranes and lipid microdomains
            7. Slow conformational dynamics and rare-event sampling
            8. Prediction of mutation stability effects
            9. Coupling with experimental data (cryo-EM, X-ray)
            10. Exploration of transition pathways between functional states
        13. Nuclear reactor simulation and radiation transport
            1. Neutron transport equations in material media
            2. Neutron diffusion and multigroup energy methods
            3. Reactivity calculation and multiplication factors
            4. Coupled thermohydraulics (flow + fuel heating)
            5. Fuel management and burnup calculations
            6. Gamma/radiation photon transport
            7. Monte Carlo methods for particle trajectories
            8. Shielding and radiological protection
            9. Transient accident simulation and SCRAM (rapid shutdown)
            10. Validation against experiments and standard benchmarks
    7. Scientific programming
        1. Dominant languages and ecosystems (modern Fortran, C/C++, Julia)
            1. Modern Fortran (Fortran 90+ with modules, n-dimensional arrays, parallelism)
            2. C for low-level compute and explicit memory control
            3. C++ for metaprogramming, generics and zero-cost abstractions
            4. Modern C++ (C++17/C++20) with templates and compile-time evaluable constants
            5. Julia as a high-level language with performance close to C
            6. Interoperability between languages (e.g., C/Fortran → Python)
            7. Manual memory management vs controlled garbage collection
            8. Numerical stability and reproducibility across implementations
            9. Native parallelism support in languages
            10. Portability across architectures (CPU, GPU, accelerators)
        2. Low-level numerical libraries (BLAS, LAPACK)
            1. BLAS levels 1/2/3 (vector, matrix-vector, matrix-matrix operations)
            2. Hardware-optimized implementations (MKL, OpenBLAS, BLIS)
            3. LAPACK for dense linear algebra solvers
            4. LU, QR, Cholesky factorizations via standard calls
            5. Eigenvalue/eigenvector computations
            6. Procedural interfaces and memory layout conventions (column-major)
            7. Use in HPC without reimplementing core algebra
            8. Focus on dense matrices vs need for sparse extensions
            9. Calls from higher-level languages
            10. Static vs dynamic linking and ABI concerns
        3. Higher-level scientific libraries (FFTW, PETSc, Trilinos)
            1. FFTW for multidimensional fast Fourier transforms
            2. PETSc for scalable sparse linear algebra and iterative solvers
            3. Trilinos for multipurpose solvers in parallel environments
            4. Mesh handling, discretizations and discretized differential operators
            5. Solving coupled PDEs in parallel
            6. Advanced preconditioners implemented out of the box
            7. Support for domain decomposition and distributed computation
            8. Integration with MPI and OpenMP
            9. Abstractions for vectors and matrices with varying internals
            10. Reuse in complex multi-physics simulation
        4. Programming with controlled precision
            1. Choice among float32, float64, float128
            2. Trade-off between cost and physically required precision
            3. Accumulation of sums in extended precision
            4. Fixed-point types in embedded scientific hardware
            5. Rounding control and IEEE-754 modes
            6. Rescuing numerical stability via mixed precision
            7. Bitwise reproducibility strategies
            8. Minimizing catastrophic cancellation in near-equal subtractions
            9. Impact of reduced precision on GPU performance
            10. Mixed-precision iterative methods with refinement
        5. Explicit vector programming and SIMD extensions
            1. SIMD on CPUs (AVX, NEON, SVE)
            2. Automatic compiler vectorization vs manual vectorization
            3. Data alignment and contiguous layouts
            4. Loop unrolling to improve throughput
            5. Fused multiply-add (FMA) instructions
            6. Minimizing data dependencies in loops
            7. AoS vs SoA layouts (Array of Structs vs Struct of Arrays)
            8. Architecture-specific intrinsics usage
            9. Portability of vectorized code between architectures
            10. Interaction between vectorization and cache hierarchies
        6. Use of templates and metaprogramming for performance
            1. C++ metaprogramming to generate compile-time specialized kernels
            2. Zero-cost abstractions by removing abstraction layers at compile time
            3. Expression templates for linear algebra expressions
            4. Aggressive inlining and elimination of virtual calls
            5. Selecting optimized code paths by type/dimension
            6. Static code generation for known block sizes
            7. Partial specialization for target architectures
            8. Templates to fuse loops and reduce memory passes
            9. Codegen for problem-specific kernels
            10. Compile-time cost and maintainability vs performance gain
        7. Distributed scientific compute models (MPI)
            1. Explicit point-to-point message passing
            2. Collective communications (broadcast, scatter, gather, all-reduce)
            3. Spatial domain partitioning among processes
            4. 1D / 2D / 3D mesh decomposition
            5. Edge synchronization (halo exchange)
            6. Blocking vs non-blocking communications
            7. Minimizing inter-node latency
            8. Overlap of computation and communication
            9. Scaling to thousands or millions of processes
            10. Fault tolerance for long runs
        8. Parallel directives (OpenMP, OpenACC)
            1. Parallelization via pragmas in code
            2. Automatic thread creation and management
            3. Loop distribution across CPU threads
            4. Thread affinity and core binding control
            5. Safe parallel reductions
            6. Critical regions and atomic sections
            7. Incremental parallelization without rewriting the codebase
            8. OpenACC for GPU offload via directives
            9. Trade-off between directive simplicity and fine control
            10. Interaction with vectorization and NUMA hierarchies
        9. Accelerated compute models (CUDA, HIP, OpenCL)
            1. Massively executed kernels on GPUs
            2. Thread, block and grid hierarchies
            3. Global vs shared memory vs registers
            4. Coalesced memory accesses and alignment
            5. Latency hiding via thread oversubscription
            6. Portability across vendors (CUDA vs HIP vs OpenCL)
            7. CPU↔GPU transfer and overlap with computation
            8. Use of accelerated libraries (cuBLAS, cuFFT, rocBLAS)
            9. Kernel fusion to reduce memory traffic
            10. Tuning occupancy and register limits
        10. Domain-specific languages (DSLs) and DSLs
            1. DSLs for partial differential equations
            2. Declarative languages for meshes and discretizations
            3. DSLs for sparse linear algebra
            4. Symbolic languages that generate numeric kernels
            5. Automatic code generation for GPU/CPU
            6. Simulation templates for domains (CFD, FEM, EM)
            7. Hardware abstraction without losing efficiency
            8. Reducing human error in complex discretizations
            9. Rapid exploration of new physical models
            10. Scientific reuse across research teams
        11. Scientific Python wrappers and native bindings
            1. Python as orchestration and analysis layer
            2. Calling kernels in C/C++/Fortran from Python
            3. Use of ctypes, cffi, pybind11
            4. NumPy as standard numerical array representation
            5. SciPy as wrapper of native algebra and optimization libraries
            6. Just-in-time compilation (Numba) to accelerate critical loops
            7. Managing the GIL in compute-intensive workloads
            8. GPU interoperability (CuPy, PyCUDA)
            9. Rapid prototyping before porting to C++/Fortran
            10. Reproducible environments with complex scientific dependencies
        12. Interactive scientific exploration environments
            1. Interactive notebooks for numerical experimentation
            2. Immediate visualization of partial results
            3. Parameter exploration and sensitivity analysis
            4. Recording experimental decisions alongside code
            5. Step-by-step reproducibility of calculations
            6. Integration with scientific plotting libraries
            7. Remote cluster interaction from interactive environments
            8. Post-processing of large HPC simulations
            9. Visual comparison of runs/configurations
            10. Communicating results to non-specialists within the team
    8. HPC architectures and extreme performance
        1. Supercomputers and HPC clusters
            1. Dedicated compute nodes interconnected at high speed
            2. Login node vs compute nodes
            3. Queue hierarchies and allocation by project
            4. Balance between CPU compute and accelerators (GPU, TPU)
            5. Dedicated low-latency internal networks
            6. Parallel shared file systems
            7. Massive cooling and electrical power requirements
            8. Scalability to hundreds of thousands of cores
            9. Health checks of clusters in continuous operation
            10. Planned maintenance and downtime windows
        2. High-performance interconnect topologies
            1. Mesh topology
            2. 2D/3D torus topology
            3. Fat-tree / fat-tree networks
            4. Dragonfly / HyperX
            5. Clos networks
            6. Topology impact on inter-node latency
            7. Traffic balancing and hotspots
            8. Task affinity according to physical proximity
            9. Topology scalability as cluster grows
            10. Resilience of topology to link failures
        3. Low-latency, high-bandwidth networks
            1. Minimizing communication overhead between nodes
            2. RDMA (Remote Direct Memory Access)
            3. Avoiding CPU intervention in data transfers
            4. Sustained aggregated bandwidth vs peak
            5. Latency jitter and its impact on parallel synchronization
            6. Aligning network buffers with user memory
            7. Protocol offload on intelligent NICs
            8. Batching small messages into larger bursts
            9. Prioritization of critical traffic
            10. Compatibility with high-performance MPI libraries
        4. Interconnect technologies (InfiniBand, Omni-Path)
            1. InfiniBand as de facto HPC standard
            2. Omni-Path and proprietary alternatives
            3. Sub-microsecond latency
            4. RDMA for direct remote access
            5. QoS and logical partitioning of the fabric
            6. Scaling the fabric to thousands of nodes
            7. Integration with GPU Direct (GPU↔GPU across nodes)
            8. Cost of specialized hardware vs optimized Ethernet
            9. Congestion management in very high-performance networks
            10. Diagnosis and monitoring of fabric health
        5. Memory hierarchies in HPC (HBM, NUMA, NVRAM)
            1. Local memory per CPU (NUMA domains)
            2. High-bandwidth memory (HBM) alongside CPU/GPU
            3. Multilevel shared caches
            4. Fast persistent memory (NVRAM / PMem)
            5. Latency variability by NUMA proximity
            6. Explicit data placement to minimize remote jumps
            7. Spillover to fast storage as “near-RAM”
            8. Explicit management of memory near GPUs
            9. Tiling/blocking techniques for spatial/temporal locality
            10. Strategies to minimize data movement as a bottleneck
        6. Manycore architectures and vector engines
            1. CPUs with tens or hundreds of lightweight cores
            2. Specialized vector accelerators (vector engines)
            3. GPUs oriented to massive throughput
            4. Co-processors dedicated to linear algebra
            5. Hybrid CPU+vector engine architectures in the same node
            6. Schedulers assigning kernels to the most suitable device
            7. Exploiting extreme data parallelism
            8. Challenges of shared memory when scaling many cores
            9. Internal bandwidth limitations as cores scale
            10. Portable programming for heterogeneous architectures
        7. Strong and weak scaling
            1. Strong scaling: solve the same problem faster with more resources
            2. Weak scaling: solve larger problems with more resources while keeping time constant
            3. Ideal speedup vs real speedup
            4. Parallel efficiency (speedup / number of processes)
            5. Amdahl’s law and sequential fraction limits
            6. Gustafson’s law for weak scaling
            7. Communication overhead when increasing processes
            8. Load imbalance among processes
            9. Scaling to thousands of nodes vs tens of nodes
            10. Metrics to justify hardware cost
        8. Compute/memory balance models (roofline model)
            1. Roofline model as visualization of theoretical performance limits
            2. Arithmetic intensity (operations per byte transferred)
            3. Compute-bound vs bandwidth-bound limits
            4. Detecting memory-bound kernels
            5. Optimizing to increase arithmetic intensity
            6. Using roofline to prioritize optimizations
            7. Comparing target architectures
            8. Application to sparse linear algebra kernels
            9. Identifying memory-shared bottlenecks
            10. Tracing improvements after code changes
        9. Exascale computing and exascale architectures
            1. Goal: ≥10^18 sustained operations per second
            2. Requirements for massive parallelism
            3. Fault tolerance as a core requirement (frequent failures expected)
            4. Energy and cooling as physical limits
            5. Deeper and more specialized memory hierarchies
            6. Extreme heterogeneity (CPU+GPU+specialized accelerators)
            7. New programming models resilient to faults
            8. Data locality as dominant performance factor
            9. Rethinking algorithms to reduce global communication
            10. Hardware–software–algorithm co-design
        10. Energy efficiency and green computing
            1. Performance per watt as a key metric
            2. DVFS (Dynamic Voltage and Frequency Scaling) in HPC nodes
            3. Selective shutdown of unused units
            4. Data locality to minimize energy from data movement
            5. Job packing to optimize cooling and thermal use
            6. Reuse of waste heat
            7. Energy-aware scheduling
            8. Trade-offs between precision and energy cost (reduced precision)
            9. Dynamic selection of the most efficient accelerator per kernel
            10. Sustainability metrics for infra design justification
        11. CPU/GPU/FPGA heterogeneity in compute nodes
            1. Nodes with multiple specialized processor types
            2. Dynamic task assignment according to workload type (dense compute, streaming, IO-bound)
            3. FPGAs for acceleration of specific kernels
            4. Programming reconfigurable FPGA kernels
            5. Direct GPU↔GPU and GPU↔NIC communication
            6. Memory balancing across heterogeneous devices
            7. Multi-device scheduling strategies
            8. Code portability across architectures
            9. Overlapping compute on several accelerators simultaneously
            10. Debugging and profiling complexity in heterogeneous environments
        12. Reducing data movement as a physical limit
            1. The energy/cost of moving data can exceed the cost of computing
            2. Compute “where the data is” to minimize transfer
            3. Kernel fusion to avoid intermediate writes/reads
            4. Tiling/blocking to reuse cache data
            5. Intermediate storage near the accelerator
            6. On-the-fly reductions instead of collecting everything
            7. In-situ computation on scientific data without moving to host
            8. Deduplication of shared data between nearby processes
            9. Fast in-memory/registry compression before sending data
            10. Algorithmic changes explicitly designed to minimize communication
    9. HPC cluster administration and operation
        1. Shared multiuser resource management
            1. Allocation of CPU/GPU/RAM among users/groups
            2. Fair-share policies
            3. Isolation between concurrent jobs
            4. Storage quotas and IO limits
            5. Managing saturation of critical nodes
            6. Queue administration by scientific or contractual priority
            7. Coordination for large simulation campaigns
            8. User account and access management
            9. Monitoring misuse or accidental abuse
            10. Usage reports for funding/projects
        2. Batch schedulers and job queues
            1. Submitting batch jobs with specification scripts
            2. Advance reservation of full nodes
            3. Maximum runtime per queue
            4. Prioritization by size/urgency/project
            5. Preemption of low-priority jobs
            6. Backfilling to fill idle slots with short jobs
            7. Grouping similar jobs for energy efficiency
            8. Managing job dependencies
            9. Automatic retries on transient failures
            10. Policies for interactive vs long-running jobs
        3. Queue systems (SLURM, PBS, LSF)
            1. SLURM as a common standard in HPC centers
            2. PBS/Torque and LSF in legacy/industrial environments
            3. Resource requests (nodes, CPUs, GPUs, memory, time)
            4. NUMA affinity and thread binding control
            5. Array jobs for massive parameter sweeps
            6. Collection of job logs and stdout/stderr
            7. Access limits to special queues (GPU, high-memory)
            8. Integration with HPC containers (Singularity/Apptainer)
            9. Automatic compute-hour accounting
            10. Integration with monitoring and dashboards
        4. Module and build environment management
            1. Environment modules (`module load`) to select toolchains
            2. Multiple compiler versions (gcc, clang, Intel, NVHPC)
            3. Multiple MPI and BLAS/LAPACK versions
            4. Avoiding global library conflicts in /usr/lib
            5. Reproducible builds via fixed module environments
            6. Documentation of modules to load per workflow
            7. Central deployment of scientific libraries
            8. GPU/CUDA-specific modules
            9. User environment isolation vs system environment
            10. Cleanup and audit of obsolete modules
        5. Dependency and toolchain management
            1. Optimized compilation with CPU-specific flags
            2. Consistent toolchains (compiler + MPI + BLAS)
            3. ABI control and compatible binaries
            4. Proprietary vs open-source math libraries
            5. Reproducible builds (Spack, EasyBuild)
            6. Parallel versioning of the same library for different users
            7. Minimizing mass recompilation after system updates
            8. Performance regression testing after updates
            9. Cryptographic integrity of installed toolchains
            10. Documentation of officially supported combinations
        6. Parallel file systems (Lustre, GPFS, BeeGFS)
            1. Shared storage across thousands of nodes
            2. Very high aggregate read/write throughput
            3. Distribution of files across multiple data servers
            4. Distributed metadata and dedicated metadata servers
            5. Striped large files across many disks/nodes
            6. Latency limitations for many small files
            7. Quota policies per user/project
            8. Recovery from storage node failures
            9. Optimization of sequential vs random IO
            10. Periodic cleanup of temporary simulation data
        7. Priority and fairness policies
            1. Prioritization by funded project / research group
            2. Dynamic fair-share (lower priority after heavy usage)
            3. Special reservations for deadlines
            4. Urgent jobs for emergency scientific/industrial needs
            5. Balance between long and short jobs
            6. Reuse of spare slot time via backfilling
            7. Preventing hoarding of high-end GPUs
            8. Transparency of queues and wait reasons
            9. Negotiation between teams for exclusive windows
            10. Auditing internal SLA compliance
        8. Accounting and compute-hour usage
            1. Recording CPU-hours / GPU-hours consumption
            2. Associating compute cost to projects/grants
            3. Budget limits per period
            4. Automated reports for billing internal/external
            5. Penalties for repeatedly failing jobs
            6. Priority adjustment by historical consumption
            7. Efficiency analysis (reserved time vs actual use)
            8. Approximate energy cost attribution
            9. Metrics to justify capacity expansion
            10. Historical traceability for audits
        9. Monitoring and telemetry of the cluster
            1. Real-time CPU, GPU and memory usage per node
            2. Node temperature and thermal health
            3. State of high-speed network links
            4. IO load on the parallel file system
            5. Early detection of unstable or slow nodes
            6. Automatic alerts on degradations
            7. Aggregated operational dashboards
            8. Performance history to detect trends
            9. Correlation of hardware failures with extreme loads
            10. Integration with ticketing / incident systems
        10. Security and user isolation in HPC
            1. Centrally authenticated user accounts
            2. Isolation of processes and jobs between users
            3. Access control to sensitive research data
            4. Encryption at rest and in internal transit
            5. Restriction of external connectivity from compute nodes
            6. Auditing of access and binary execution
            7. Scanning for malicious loads or unauthorized mining
            8. SSH key and internal certificate management
            9. Compliance with regulations (e.g., biomedical data)
            10. Containing incidents without shutting down the entire cluster
        11. Predictive maintenance and node failure management
            1. Monitoring of temperature, fans, power
            2. Alerts on recurring ECC memory errors
            3. Proactive replacement of unstable nodes
            4. Job migration away from suspect nodes
            5. Planned downtime by rack/row
            6. Remote hardware diagnosis without immediate physical intervention
            7. Management of critical spares (NICs, GPUs, PSUs)
            8. MTBF analysis and component reliability
            9. Historical failure logs by hardware batch
            10. Minimizing loss of long simulations on unexpected outages
        12. Capacity planning and physical scaling
            1. Projecting future demand (CPU, GPU, memory, IO)
            2. Power and cooling requirements
            3. Physical rack space and thermal density
            4. Evaluating new architectures (new GPUs, IA accelerators)
            5. Balance between “big” nodes vs many small nodes
            6. Planning upgrades without breaking software compatibility
            7. Total cost of ownership (TCO) for additional hardware
            8. Impact on parallel file system and central network
            9. Risks of rapid technological obsolescence
            10. Budget justification and prioritization among user groups
    10. Optimization of scientific performance
        1. Profiling and tracing performance
            1. CPU profiling (time per function / line)
            2. GPU profiling (time per kernel)
            3. Memory profiling (allocs, frees, leaks)
            4. FLOP counts and bandwidth usage
            5. Timeline traces of parallel execution
            6. Manual instrumentation vs statistical sampling
            7. Analysis of critical regions with high blocked time
            8. Specific tools (perf, VTune, Nsight, TAU)
            9. Reproducible measurement (same input, same environment)
            10. Identifying run-to-run variability
        2. Hotspot and kernel analysis
            1. Detect functions consuming most of the total time
            2. Grouping time into repetitive operations (inner loops)
            3. Determine if hotspot is compute-bound or memory-bound
            4. Isolate the critical kernel as a testable unit
            5. Microbenchmarks of the isolated kernel
            6. Manual kernel rewriting
            7. Evaluate impact of a local optimization on total runtime
            8. Avoid optimizing non-dominant sections
            9. Use the roofline model to guide effort
            10. Iterate: re-profile after each improvement
        3. Automatic and manual vectorization
            1. Review compiler vectorization reports
            2. Use `restrict` / no-aliasing to help the compiler
            3. Restructure loops to eliminate false dependencies
            4. Align data in memory
            5. Use architecture-specific SIMD intrinsics
            6. Change AoS → SoA for contiguous access
            7. Loop unrolling
            8. Fuse operations into FMA instructions
            9. Verify numerical results after vectorization
            10. Fall back to scalar-safe routes on SIMD-less architectures
        4. CPU affinity and thread pinning
            1. Pin threads to specific cores (CPU pinning)
            2. Avoid thread migration between cores
            3. Consider NUMA topology when assigning threads
            4. Align memory access with the local NUMA node
            5. Balance threads across physical sockets
            6. Separate compute threads from IO threads
            7. Minimize contention for shared core resources
            8. Adjust affinity for mixed CPU/GPU jobs
            9. Measure effects on latency and jitter
            10. Use affinity tools (numactl, taskset)
        5. Cache optimization and data locality
            1. Improve spatial locality (sequential memory access)
            2. Improve temporal locality (fast reuse of same data)
            3. Tiling / blocking of nested loops
            4. Avoid repeatedly bringing cold data from RAM
            5. Loop fusion for accesses to the same memory regions
            6. Separate loops that destroy locality across different data
            7. Avoid false sharing among threads
            8. Explicit or compiler-assisted prefetching
            9. Minimize critical L1/L2 cache misses
            10. Tune block size to actual cache sizes
        6. Loop blocking and tiling
            1. Divide large domains into smaller tiles
            2. Tune tiles to fit L1/L2 cache
            3. Apply tiling in spatial (x,y,z) and temporal (t) dimensions
            4. Avoid repeatedly fetching cold data from RAM
            5. Fuse loops accessing the same regions
            6. Separate loops that harm locality for different data
            7. Swap iteration order for contiguous access
            8. Hierarchical tiling across cache levels
            9. Tiling specialized for linear algebra kernels
            10. Evaluate impact on vectorization
        7. Reducing communication cost
            1. Minimize frequent MPI point-to-point calls
            2. Use efficient collective communications (tree-based all-reduce)
            3. Aggregate small messages into larger buffers
            4. Avoid unnecessary synchronizations between processes
            5. Reorganize domain to reduce halo exchange surface
            6. Compute more locally before communicating
            7. Keep derived data cached locally
            8. Avoid “chatter” between distant nodes
            9. Map processes to physical topology appropriately
            10. Use algorithms with lower global communication complexity
        8. Overlap communication / computation
            1. Non-blocking communication (MPI Isend/Irecv)
            2. Compute on interior regions while halos arrive
            3. Pre-post receives before computing
            4. Pipelines between compute and transfer stages
            5. Offload communication to smart NICs
            6. Use asynchronous streams on GPU
            7. Decouple communication threads from compute threads
            8. Mask network latency with useful work
            9. Overlap disk IO ↔ CPU ↔ GPU
            10. Validate data coherence before using freshly arrived results
        9. Minimize global synchronizations
            1. Avoid unnecessary global barriers
            2. Replace frequent global reductions with hierarchical reductions
            3. Use asynchronous algorithms when physics permits
            4. Latency-tolerant algorithms
            5. Decouple advancement steps for slow processes
            6. Relax strict synchrony between subdomains
            7. Eventual-communication techniques in iterative methods
            8. Reduce global all-reduce frequency in large linear solvers
            9. Isolate slow nodes without stalling the simulation
            10. Metrics for synchronization overhead vs pure compute
        10. Parallel scalability and efficiency
            1. Empirical measurement of strong vs weak scaling
            2. Speedup and parallel efficiency vs process count
            3. Detect efficiency loss due to communication
            4. Dynamic load balancing among processes/threads
            5. Analysis of spatial imbalance in physical domains
            6. Performance sensitivity to problem size
            7. Shared memory saturation as a limiting factor
            8. Scaling to thousands of cores without abrupt drop
            9. Find the “sweet spot” of scaling
            10. Comparable reports across different architectures
        11. Portability of performance across architectures
            1. Code that performs well on CPU and GPU
            2. Use portable abstraction layers (Kokkos, RAJA)
            3. Avoid rigid dependence on a single vector ISA
            4. Adapt to different SIMD widths
            5. Tune block sizes per backend
            6. Minimize calls to non-portable proprietary libraries
            7. Autotuning per target architecture
            8. Dynamic selection of specialized kernels at runtime
            9. Maintain a single codebase
            10. Cross-target numerical validation
        12. Auto-tuning and generation of optimal kernels
            1. Automatic search for block/tile parameters
            2. Systematic variation of compilation flags
            3. Adaptive algorithm selection by problem size
            4. Empirical measurements to pick best variant
            5. Generate hardware-specialized kernels
            6. Runtime (JIT) dynamic tuning
            7. Store optimal profiles for reuse
            8. Heuristic/genetic exploration of configurations
            9. Metaprogramming that produces multiple implementation candidates
            10. Integration with CI pipelines to re-evaluate after hardware changes
    11. Heterogeneous computing and accelerators
        1. General-purpose GPUs
            1. SIMT-style massively parallel execution
            2. Thousands of lightweight threads in parallel
            3. Global memory with high latency hidden by concurrency
            4. Fast per-block shared memory
            5. Use of specialized kernels for dense and sparse linear algebra
            6. Optimized libraries (cuBLAS, cuFFT, cuSPARSE)
            7. Host↔device transfer overhead
            8. Streams and overlapped concurrency of kernels
            9. Fine-tuning occupancy and register usage
            10. Multi-GPU scaling and peer-to-peer communication
        2. Specialized matrix accelerators
            1. Tensor cores / matrix cores
            2. Massive multiply-accumulate units
            3. Extreme performance on dense matrix multiplication
            4. Reduced precision (FP16, BF16, INT8) as a performance lever
            5. Application beyond AI: classical scientific linear algebra
            6. Mapping scientific kernels to blocked matrix operations
            7. Limitations when matrices are sparse / unstructured
            8. Data layout tuning to exploit block width
            9. Impact on energy efficiency (GFLOP/s per watt)
            10. Rapid hardware evolution between generations
        3. FPGAs for scientific compute
            1. Problem-oriented reconfigurable logic
            2. Fully customized data pipelines
            3. Ultra-low latency for certain operations
            4. Spatial parallelism rather than temporal
            5. Use in signal filtering, massive correlations, specialized computations
            6. Arbitrary word widths (optimized fixed precision)
            7. Complex development (HDL, HLS) and long synthesis times
            8. Harder maintenance vs programmable GPUs
            9. Excellent performance/consumption for well-defined kernels
            10. Integration in specialized HPC nodes
        4. Selective kernel offloading
            1. Identify highly parallelizable kernels
            2. Measure whether transfer cost justifies acceleration
            3. Split the pipeline into CPU vs GPU/FPGA stages
            4. Overlap data transfer with compute
            5. Avoid offloading routines with little parallelism
            6. Keep data resident on the accelerator across multiple stages
            7. Design clear call interfaces (host → device → host)
            8. Reuse buffers on the accelerator
            9. Runtime selection of which accelerator to send each kernel to
            10. Balance numerical precision when migrating sensitive kernels
        5. Unified memory models and memory pooling
            1. Unified CPU/GPU memory (UMA / UVA)
            2. Shared access to the same virtual address space
            3. Automatic/transparent migration of memory pages
            4. Reduce overhead of explicit copies
            5. Risk of remote accesses with high latency
            6. Common memory pool across multiple GPUs
            7. Coordinating large datasets on heterogeneous nodes
            8. Preferred location placement policies
            9. Manual tuning when the runtime makes poor decisions
            10. Interaction with NUMA and accelerator-local memory
        6. Dynamic CPU/GPU load balancing
            1. Split work between CPU and GPU based on current load
            2. Detect imbalances between devices
            3. Migrate kernels between CPU and GPU during long runs
            4. Adapt work granularity for better overlap
            5. Coordinate use of shared memory and caches
            6. Avoid GPU idling waiting for the CPU (and vice versa)
            7. Runtime models predicting kernel execution time
            8. Scheduling aware of data transfer cost
            9. Prioritize critical stages on the fastest accelerator
            10. Hot adjustments based on performance telemetry
        7. Co-scheduling multiple accelerators
            1. Nodes with several GPUs working in coordinated parallelism
            2. Stage-by-stage pipelines (GPU A → GPU B)
            3. Partition spatial subdomains across accelerators
            4. Direct GPU↔GPU communication without routing through the CPU
            5. Minimize interconnect bus congestion
            6. Lightweight synchronization between accelerators
            7. Replicate common data across multiple GPUs
            8. Load balancing across heterogeneous GPUs (different generations)
            9. Avoid starving a slow accelerator that stalls the whole chain
            10. Multinode telemetry to adjust work distribution
        8. NUMA-aware strategies in heterogeneous nodes
            1. Understand internal NUMA domains of the node (multiple sockets)
            2. Place threads near the memory they use
            3. Place GPU buffers in memory closest to that GPU
            4. Avoid inter-socket high-latency hops
            5. IRQ/network affinity toward the correct socket
            6. “First touch” policy to initialize memory on the appropriate node
            7. Dynamic migration of poorly placed NUMA memory
            8. Monitor NUMA miss counters
            9. Adjust MPI process topology within the node
            10. Combine NUMA-awareness with thread pinning and GPU affinity
        9. Hardware-software co-design
            1. Adapt numerical algorithms to available hardware
            2. Change discretization to favor contiguous data access
            3. Reformulate kernels to use matrix accelerators
            4. Specialize numeric precision to save energy
            5. Integrate emerging hardware (neuromorphic, photonic) into scientific flows
            6. Iterative feedback between hardware team and simulation team
            7. Automate generation of platform-specific kernels
            8. Minimize data movement as a primary design goal
            9. Design reusable libraries parameterized by architecture
            10. Anticipate scaling to exascale heterogeneous architectures
    12. Stochastic methods and massive sampling
        1. Classical Monte Carlo
            1. Independent random sampling of configurations/states
            2. Estimation of high-dimensional integrals
            3. Law of large numbers as convergence basis
            4. Statistical error ~ 1/sqrt(N)
            5. Variance reduction (control variates, antithetic sampling)
            6. Importance of high-quality random number generators
            7. Trivial parallelization by distributing different seeds
            8. Applications in radiation transport, quantitative finance, diffusion
            9. Detect stable convergence of estimators
            10. Storage and reproducibility of initial seeds
        2. Markov chain Monte Carlo (MCMC)
            1. Construct a chain that converges to the target distribution
            2. Metropolis-Hastings methods
            3. Gibbs sampling
            4. Mixing and autocorrelation time
            5. Burn-in and discarding initial samples
            6. Convergence diagnostics across multiple chains
            7. Parallel MCMC: independent chains and combined analysis
            8. Hamiltonian / Hybrid Monte Carlo to traverse low-probability regions
            9. Use in Bayesian inference for complex parameters
            10. Cost of evaluating the target likelihood function
        3. Importance sampling and reweighting
            1. Sample from an easy-to-simulate proposal distribution
            2. Reweight (weights) to estimate the true target distribution
            3. Variance reduction by focusing on relevant regions
            4. Weight degeneracy (few weights dominate)
            5. Numerically stable weight normalization
            6. Use in high-dimensional integration with heavy tails
            7. Sequential Importance Sampling (SIS)
            8. Particle filters in dynamical systems
            9. Stratified / systematic resampling
            10. Applications in probabilistic state tracking
        4. Quasi-Monte Carlo and low-discrepancy sequences
            1. Deterministic sequences (Sobol, Halton)
            2. More uniform coverage of the integration domain
            3. Potentially faster convergence than 1/sqrt(N)
            4. Importance of the effective dimension of the problem
            5. Random scrambling to estimate statistical error
            6. Axis alignment and correlations between dimensions
            7. Performance in financial pricing and smooth problems
            8. Limitations in highly discontinuous problems
            9. Parallelization while preserving low-discrepancy properties
            10. Interaction with classical variance reduction techniques
        5. Rare-event sampling and rare-event methods
            1. Estimation of extremely low probabilities
            2. Splitting/branching promising trajectories
            3. Importance sampling targeting extreme tails
            4. Accelerated Monte Carlo for very unlikely events
            5. Trajectory genealogy techniques
            6. Applications in structural reliability and extreme risk
            7. Estimation of failure times in engineering
            8. Simulation of rare natural or nuclear catastrophes
            9. Strict control of statistical error in tails
            10. Validation against approximate analytical methods
        6. Uncertainty analysis and propagation of statistical errors
            1. Propagate input parameter uncertainty
            2. Statistical sensitivity sweeps of parameters
            3. Non-intrusive sampling-based methods
            4. Confidence interval estimation for physical outputs
            5. Estimate correlations between inputs and output metrics
            6. Generalized Polynomial Chaos (gPC) methods
            7. Dimensionality reduction in uncertainty space
            8. Visualization of probabilistic response surfaces
            9. Compare numerical uncertainty vs physical uncertainty
            10. Use in model certification
        7. Large-scale computational Bayesian inference
            1. Posterior evaluation in complex models with massive data
            2. Distributed large-scale MCMC
            3. Variational Inference as a deterministic approximation
            4. Laplace and Gaussian approximations around the mode
            5. SMC (Sequential Monte Carlo) for dynamic inference
            6. Amortized inference with neural networks approximating posteriors
            7. Use of GPUs to evaluate likelihoods and massive gradients
            8. Factorization of likelihood for partitioned data
            9. Evidence / Bayes factor computation
            10. Traceability of uncertainty in inferred parameters
        8. Ensemble simulation and replica methods
            1. Simultaneous simulation of multiple system copies (replicas)
            2. Replica-exchange / parallel tempering to cross energy barriers
            3. Canonical, isobaric, grand-canonical ensembles run concurrently
            4. Explore rugged energy landscapes
            5. Controlled exchange of temperature/pressure between replicas
            6. Accelerate sampling of metastable rare states
            7. Robust estimation of global thermodynamic properties
            8. Identify phase transitions and intermediate states
            9. Intensive parallelism (each replica on a separate node)
            10. Joint post-analysis to average observables across replicas
    13. Large-scale mathematical optimization
        1. Linear programming
            1. Standard form linear problems (minimize cᵀx subject to Ax = b, x ≥ 0)
            2. Simplex method and revised variants for high dimension
            3. Interior-point methods applied to linear programming
            4. Scaling and normalization of constraints for numerical stability
            5. Dantzig–Wolfe and Benders decomposition for structured large problems
            6. Linear relaxations of integer/mixed problems
            7. Use in logistics, resource planning and network flows
            8. Distributed and parallel solving of giant LPs (millions of variables)
            9. Warm start between successive iterations
            10. Sensitivity and duality analysis (shadow prices)
        2. Quadratic programming
            1. Convex quadratic objectives with linear constraints
            2. Strictly convex vs indefinite QP
            3. Active-set methods
            4. Interior-point methods specialized for QP
            5. QP in model predictive control (MPC)
            6. Quadratic penalization and L2 regularization
            7. Use in portfolio optimization, control, curve fitting
            8. Reduce large QPs to relevant active subsets
            9. SQP (Sequential Quadratic Programming) for local nonlinear approximations
            10. Hardware-accelerated solutions (GPU/FPGA) for real-time control
        3. Interior-point methods
            1. Logarithmic barrier functions to maintain strict feasibility
            2. Central path and tracking the optimal curve
            3. Repeated solution of KKT-type linear systems
            4. Preconditioners for ill-conditioned linear systems
            5. Scalability to problems with millions of variables and constraints
            6. Parallelization of internal factorizations
            7. Primal-dual convergence metrics
            8. Warm start between nearby problems in iterative simulations
            9. Numerical stability with very tight constraints
            10. Application in energy planning, telecoms, routing
        4. Unconstrained nonlinear optimization
            1. Classical gradient descent methods
            2. Gradient descent with adaptive step (line search, backtracking)
            3. Second-order methods (pure Newton)
            4. Damped Newton / Levenberg–Marquardt
            5. Quasi-Newton methods without explicit Hessian
            6. Conjugate direction search
            7. Detecting local minima vs saddle points
            8. Problem conditioning and variable scaling
            9. Parallelization of gradient computation in HPC
            10. Massive evaluation of objective functions in physical simulations
        5. Constrained optimization
            1. Formulation with equality and inequality constraints
            2. Lagrange multipliers
            3. Penalty and barrier methods
            4. Augmented Lagrangian methods
            5. Sequential Quadratic Programming (SQP)
            6. Projection onto the feasible set
            7. Handling hard physical constraints (mass, energy conservation)
            8. Numerical infeasibility and soft relaxation
            9. Distributed Lagrangians in HPC
            10. Scalability with many coupled constraints
        6. Large-scale gradient descent methods
            1. Plain gradient with small steps
            2. Momentum methods
            3. Nesterov accelerated gradient
            4. Stochastic gradient and mini-batch for massive datasets
            5. Adaptive learning rates (RMSProp, Adam in scientific contexts)
            6. Preconditioning of the gradient
            7. Reduce communication in distributed gradient (efficient all-reduce)
            8. Quantization / compression of gradients
            9. Gradient methods under memory constraints
            10. Numerical stability when using reduced precision on GPUs
        7. Quasi-Newton and limited-memory BFGS
            1. BFGS as an iterative approximation to the inverse Hessian
            2. L-BFGS for very high-dimensional problems (bounded memory)
            3. Rank-1 / rank-2 updates of Hessian approximations
            4. Avoid cost of exact Hessian computation
            5. Superlinear convergence properties
            6. Common use in scientific parameter fitting
            7. Tolerance to noise in gradient evaluations
            8. Distributed implementations of L-BFGS
            9. Acceleration combining L-BFGS with physical preconditioners
            10. Comparison with pure gradient methods in stiff problems
        8. Block decomposition and alternating coordinates
            1. Optimize subsets of variables while fixing others
            2. Cyclic vs random coordinate methods
            3. Block Coordinate Descent (BCD) for grouped variables
            4. Alternating Direction Method of Multipliers (ADMM)
            5. Natural separation in spatial or physical-structured problems
            6. Distributed computation assigning blocks to different nodes
            7. Convergence in convex and nonconvex problems
            8. Use in imaging, tomography, inverse reconstruction
            9. Incremental tuning in large iterative pipelines
            10. Easy parallelization when blocks are weakly coupled
        9. Distributed and consensus methods
            1. Decompose a global problem into local subproblems
            2. Iterative consensus among nodes to agree on shared variables
            3. Exchange partial information (avoid sharing everything)
            4. Distributed ADMM on HPC clusters
            5. Robustness to partial node failures
            6. Reduce latency of global synchronization
            7. Horizontal scaling with more compute nodes
            8. Decentralized approximations without a single coordinator
            9. Methods tolerant to noisy or delayed communication
            10. Applications in power networks, traffic optimization, distributed control
        10. Numerical optimal control
            1. Formulation of continuous and discrete optimal control problems
            2. Temporal and spatial discretization of the dynamical system
            3. Pontryagin and optimality conditions
            4. Model Predictive Control (MPC) solved online
            5. Repeated QP/LP solves at each control step
            6. Control of rigid and nonlinear systems
            7. Adjoint methods to obtain gradients w.r.t. control inputs
            8. Closed-loop optimization with critical physical constraints
            9. Hardware-accelerated solvers for real-time control
            10. Integration with high-fidelity physical simulators
        11. Inverse problems and physical parameter fitting
            1. Estimate unknown parameters from experimental observations
            2. Fit PDE/EDP models to real-world data
            3. Adjoint methods for efficient gradient computation
            4. Regularization (L2, L1, Tikhonov) to stabilize solutions
            5. Seismic inversion, medical tomography, image reconstruction
            6. Identification of unknown initial/boundary conditions
            7. Sensitivity and nonuniqueness of solutions
            8. Bayesian methods to quantify uncertainty
            9. Iterative coupling of simulation ↔ optimization
            10. Scaling to high spatial and temporal dimensionality
    14. Large-scale data science in HPC
        1. Massive preprocessing of scientific data
            1. Cleaning raw data from sensors / simulations
            2. Detect and remove outliers / corrupt values
            3. Temporal synchronization of multiple measurement sources
            4. Resampling and spatial alignment of meshes / grids
            5. Normalization of physical units and scales
            6. Handling missing data and reconstruction
            7. Conversion between scientific formats (NetCDF, HDF5, Parquet)
            8. Parallelize scientific ETL on the cluster
            9. Version control of intermediate datasets
            10. Traceability of transformations (data lineage)
        2. Cleaning and normalization of experimental data
            1. Instrument and sensor calibration
            2. Background noise subtraction
            3. Correction of drift and systematic bias
            4. Fusion of data from different experiments / runs
            5. Removal of numerical or measurement artifacts
            6. Range scaling, z-score, physical normalization
            7. Spatial/temporal alignment of heterogeneous data
            8. Automated quality validation
            9. Reliable metadata labeling
            10. Generation of curated reusable datasets
        3. Dimensionality reduction and compression
            1. PCA / SVD to capture dominant modes
            2. Eigenvectors and spectral decompositions of physical fields
            3. Lossy compression with controlled error in volumetric simulations
            4. Domain-specific compression (e.g., wavelets)
            5. Low-dimensional maps for scientific visualization
            6. Autoencoders trained on HPC
            7. Signal/noise separation via principal modes
            8. Store reduced snapshots for later analysis
            9. Trade-off between compression and induced error
            10. Stream compressed data between nodes for distributed analysis
        4. High-resolution time-series analysis
            1. Multichannel signals at high sampling frequency
            2. Spectral filtering and frequency/wave analysis
            3. Cross-correlation and cross-spectral analysis between sensors
            4. Detection of rare transient events
            5. Multivariate autoregressive and VAR models
            6. Short-term prediction with RNNs / Transformers
            7. Automatic segmentation into phases/regimes
            8. Detect slow drift vs abrupt changes
            9. Parallelize temporal analysis in sliding windows
            10. Time-indexed storage for fast access
        5. Batch and streaming scientific analysis pipelines
            1. Batch processing of completed simulations
            2. Near real-time processing of partial results
            3. Flows: simulate → analyze → decide → feed back to simulation
            4. Fault tolerance and resume for long pipelines
            5. Distributed orchestration on HPC clusters
            6. Chain heterogeneous stages (Fortran simulation, Python analysis)
            7. High-speed shared memory buffers
            8. Minimal intermediate persistence to lower latency
            9. Alerts/thresholds on detecting critical behaviors
            10. Auditable steps and intermediate results
        6. High-performance scientific visualization
            1. Parallel rendering of 3D volumes / vector fields
            2. Scientific ray tracing for complex structures
            3. In-situ visualization (avoid writing all data to disk)
            4. Remote interactive exploration of massive results
            5. Smart subsampling and adaptive refinement
            6. Extract isosurfaces and streamlines
            7. Multi-scale visualization (zoom macro → micro)
            8. GPU pipelines for post-processing visuals
            9. Export high-fidelity images/animations
            10. Collaborative visual analysis across users
        7. Managing massive datasets and data movement
            1. Organize petabytes of simulation outputs
            2. Hierarchical storage (fast vs cold archive)
            3. Cataloging and searchable metadata
            4. Minimize transfers between compute centers
            5. Retention and expiration policies for old data
            6. Bandwidth planning to move experiment data to HPC
            7. Prefetch data needed for next stages
            8. Geographic replication for resilience
            9. Encryption and compliance during transit
            10. IO costs vs recomputation costs
        8. Efficient indexing of simulation results
            1. Multidimensional indexing of physical fields (x,y,z,t)
            2. Hierarchical spatial indexing (octree / kd-tree)
            3. Catalogs queryable by parameter ranges
            4. Fast search of snapshots with specific properties
            5. Rich metadata (initial conditions, physical constants)
            6. Semantic tagging of regions of interest (shock, fracture)
            7. Indexing compatible with interactive visualization
            8. Self-contained formats (HDF5 with metadata)
            9. Precompute aggregates per spatial block
            10. Query APIs for collaborative team analysis
        9. Interactive exploration in supercomputing environments
            1. Remote access to visualization nodes with GPUs
            2. Scientific notebooks connected to the HPC cluster
            3. Live parameter exploration without relaunching the full sim
            4. Near-real-time dashboards for simulation evolution
            5. Adaptive sampling of interesting domain regions
            6. Side-by-side comparison of different runs/configurations
            7. Multiuser collaboration viewing the same dataset
            8. Immediate statistical summaries when exploring regions
            9. Protect sensitive data in interactive sessions
            10. Fast generation of reproducible technical reports
    15. Accelerated machine learning in HPC
        1. Distributed training of deep models
            1. Gradient synchronization across many nodes (data parallel)
            2. Optimized hierarchical all-reduce
            3. Training on clusters with tens or hundreds of GPUs
            4. Fault-tolerant distributed checkpointing
            5. Resume after node failures
            6. Use low-latency networks for synchronization
            7. Mixed precision training (FP16/BF16) to speed computation
            8. Overlap gradient communication with forward/backward compute
            9. Control imbalance across heterogeneous GPUs
            10. Scale to models with billions of parameters
        2. Data parallelism
            1. Each model replica processes a different batch subset
            2. Aggregate gradients among replicas
            3. Very large batch sizes to exploit the cluster
            4. Adjust learning rate with batch size
            5. Bias correction when scaling batch size
            6. Minimize statistical variability in giant batches
            7. Efficient sharding of training data
            8. Distributed data loading without IO bottlenecks
            9. Parallel data augmentation
            10. Reproducibility across massive runs
        3. Model parallelism
            1. Split the model across multiple devices (model parallel)
            2. Partition by consecutive deep layers
            3. Partition by internal dimension (tensor/model parallel)
            4. Synchronize activations and gradients between partitions
            5. Minimize communication volume between partitions
            6. Align physical network topology with model partitioning
            7. Handle layers that do not fit in a single GPU
            8. Train very large-scale models (huge transformers)
            9. Balance load among model fragments
            10. Debugging forward/backward in distributed settings
        4. Pipeline parallelism
            1. Split the model into sequential stages like an assembly line
            2. Microbatches flow through the pipeline
            3. Streaming execution of forward and backward passes
            4. Minimize bubbles (idle time between stages)
            5. Precise timing coordination across stages
            6. Combine with data and model parallelism
            7. Dynamic microbatch size tuning
            8. Recovery after a pipeline stage failure
            9. Measure end-to-end pipeline throughput
            10. Scale to pipelines with many stages across multiple nodes
        5. Hybrid parallelism techniques
            1. Combine data + model + pipeline parallelism
            2. Design logical meshes of GPUs/NICs for efficient sync
            3. Shard parameters alongside data parallelism
            4. Partial replication of critical layers
            5. Mix numerical precisions by layer
            6. Fuse communications to reduce overhead
            7. Partial checkpointing per parallel group
            8. Scale foundation-model-like architectures
            9. Trade off operational complexity vs speed gain
            10. Automate hybrid strategies in modern frameworks
        6. Graph compilers and kernel optimizers
            1. Auto-fuse operators to minimize memory traffic
            2. Reorder operations for better locality
            3. Generate hardware-specialized kernels (codegen)
            4. Reduce kernel launch overhead on GPUs
            5. Schedule to maximize GPU occupancy
            6. Integrated quantization and pruning in the graph
            7. Auto-tune block sizes and tiling
            8. Auto-select optimal BLAS primitives
            9. Tune for specific matrix accelerators
            10. Export to lightweight runtimes for inference
        7. Physics-informed machine learning
            1. Neural networks that incorporate physical laws (conservation, symmetries)
            2. Penalize PDE violations in the loss
            3. Speed up simulations by learning approximations
            4. Estimate continuous fields (pressure, velocity, temperature)
            5. Learn closures in turbulence models
            6. Incorporate physical invariants (energy, mass, momentum)
            7. Validate physics in addition to statistical metrics
            8. Reduce cost of high-fidelity simulations
            9. Use in inverse problems with partial data
            10. Bidirectional coupling simulation ↔ neural network
        8. Surrogates and emulators for costly simulations
            1. Surrogate models that replace full simulations
            2. Supervised training on expensive simulator outputs
            3. Ultra-fast evaluation for parameter exploration
            4. Optimization/calibration using surrogates instead of solvers
            5. Statistical emulation with Gaussian Processes / deep models
            6. Reduced-order networks approximating complex dynamics
            7. Validate fidelity vs the base simulator
            8. Quantify surrogate uncertainty
            9. Use in design of experiments and online control
            10. Incrementally update surrogates with new data
        9. Low-latency optimized inference
            1. Compile models for inference (TensorRT, XLA, etc.)
            2. Low-precision quantization to speed inference
            3. Pruning weights and structured compression
            4. Small-batch vs large-batch depending on latency target
            5. Distributed inference across multiple GPUs for throughput
            6. Edge/near-edge HPC inference pipelines
            7. Minimize CPU↔GPU transfers during inference
            8. Optimal model placement on accelerator-equipped nodes
            9. Latency monitoring in mission-critical environments
            10. Dynamic runtime reconfiguration based on load
        10. AutoML and architecture search in HPC
            1. Large-scale hyperparameter search
            2. Distributed neural architecture search (NAS)
            3. Massive parallel evaluation of candidate configurations
            4. Weight-sharing to speed up NAS
            5. Multi-criteria selection (accuracy, compute cost, energy)
            6. Intermediate checkpointing of promising candidates
            7. Intelligent prioritization using bandit/Bayesian methods
            8. Use GPUs/TPUs at scale to sweep the architecture space
            9. Persistent historical comparison of tested architectures
            10. Generate models tailored to specific physical domains
    16. Verification, validation and scientific reproducibility
        1. Numerical verification of solvers
            1. Compare with known analytical solutions
            2. Expected order of convergence under mesh/time refinement
            3. Conservation of physical invariants (mass, energy, momentum)
            4. Stability analysis in time integration
            5. Detect numerical drift in long simulations
            6. Sensitivity checks to small timestep variations
            7. Compare single vs double precision
            8. Cross-check equivalent formulations of the same operator
            9. Use synthetic controlled problems for debugging
            10. Automated numerical regression tests
        2. Physical validation against experimental data
            1. Direct comparison simulation vs measurement
            2. Calibrate free physical parameters
            3. Adjust boundary conditions to match experiments
            4. Quantify relative and absolute error
            5. Compare experimental uncertainty vs numerical uncertainty
            6. Evaluate predictions beyond measured ranges
            7. Cross-validation between laboratories/experiments
            8. Iterative cycle: predict → measure → refine model
            9. Identify missing physics (e.g., unmodeled dissipation)
            10. Accept a model for engineering/regulatory use
        3. Cross-code comparisons
            1. Run the same physical case with different codes/solvers
            2. Ensure consistency of key results (curves, stresses, fields)
            3. Evaluate numerical differences from discretization choices (FEM vs FDM vs FV)
            4. Analyze mesh dependency
            5. Benchmark against community reference codes
            6. Find bugs via systematic divergences
            7. Use for validation of new numerical methods
            8. Document acceptable discrepancies
            9. Create canonical cases for future regression
            10. Jointly publish comparative results
        4. Community benchmarks and reference suites
            1. Standard discipline cases (lid-driven cavity, turbulent channel, etc.)
            2. Community-approved baseline data
            3. Agreed error metrics and figures of merit
            4. Repeatable setup, mesh, and parameters
            5. Performance and numerical efficiency rankings
            6. Historical benchmark evolution for new physics
            7. Use in funding proposals / code validation
            8. Include extreme cases (high Re, strong nonlinearities)
            9. Compare across hardware (CPU vs GPU vs accelerators)
            10. Curate open, accessible benchmarks
        5. Version control for simulations and parameters
            1. Version input decks / configuration files
            2. Record exact source code version
            3. Hashes/cryptographic verification of executed binaries
            4. History of physical and numerical parameters
            5. Trace each result to its commit/tag
            6. Manage gradual changes in the physical model
            7. Branches specific to scientific studies
            8. Freeze configurations for publications
            9. Temporal reproducibility (rerun months later)
            10. Integrate with Git and scientific metadata
        6. Random seed and initial state management
            1. Explicit recording of RNG seeds
            2. Reproducibility of stochastic runs
            3. Deterministic sequences in parallel environments
            4. Control RNG streams per MPI process / GPU
            5. Avoid seed collisions between nodes
            6. Traceability of randomly generated initial states
            7. Statistical repeatability to validate findings
            8. Estimate variance between runs differing only by RNG
            9. Validate robustness against different seeds
            10. Publish seeds used in final results
        7. Experimental logs and full traceability
            1. Structured run logs (input, version, time, node)
            2. Hardware and execution topology metadata
            3. Environment logs (modules loaded, env vars)
            4. Automatic capture of performance and resource usage
            5. Record failures and restarts
            6. Link runs to subsequent analyses
            7. Digital “laboratory” notebook queryable later
            8. Auditable evidence for scientific articles
            9. Compliance with lab/HPC center policies
            10. Support for external reviewers
        8. Publishing reproducible datasets
            1. Release simulated fields / raw experimental measurements
            2. Attach post-processing scripts
            3. Document format, units and meshes
            4. Licensing and open/restricted access policies
            5. DOIs and academic citability
            6. Version the published dataset
            7. Provide reduced subsets for practical download
            8. Include associated uncertainty
            9. Curate in institutional / community repositories
            10. Promote reusability by other research groups
        9. Replication of published results
            1. Independent re-execution of the original numerical experiment
            2. Reproduce the statistical/graphical analysis
            3. Compare key metrics and scientific conclusions
            4. Identify hidden dependencies or undeclared assumptions
            5. Validate claims before building further work on them
            6. Academic incentives for replication
            7. Reproducibility reports as supplementary material
            8. Culture of verifiable results over “flashy” outcomes
            9. Share CI pipelines that regenerate figures
            10. Reinforce trust in high-impact predictive simulations
    17. Scientific software development methodologies
        1. Modular design oriented to physical components
            1. Separate physical phenomena (fluid, heat, chemistry) into clear modules
            2. Explicit interfaces between coupled modules
            3. Replace submodels without rewriting the whole solver
            4. Reuse modules across different projects
            5. Avoid circular dependencies between physical components
            6. Version modules by physical component
            7. Clear distinction between “physical model” and “numerical infrastructure”
            8. Enable isolated testing of each module
            9. Decouple physics from hardware-specific code
            10. Facilitate contributions from domain experts
        2. Separation between physics, discretization and solver
            1. Continuous physics layer (PDE / EDP)
            2. Discretization layer (FEM, FDM, FV)
            3. Algebraic resolution layer (linear / nonlinear solvers)
            4. Swap solvers without changing base physics
            5. Objective comparison between discretizations
            6. Independent tuning of algebraic components
            7. Conceptual clarity for debugging
            8. Portability of the solver to new architectures
            9. Incremental improvement of each layer without breaking others
            10. Reuse of solvers across multiple physical domains
        3. Automated testing for numerical kernels
            1. Unit tests for critical mathematical kernels
            2. Numerical regression tests (compare to previous results)
            3. Conservation / invariant tests
            4. Convergence order tests
            5. Stability tests under extreme steps
            6. Single vs double precision tests
            7. CPU and GPU equivalence tests
            8. Deterministic tests for reproducibility
            9. Minimum acceptable performance tests
            10. CI integration of numerical tests
        4. Continuous validation and scientific CI pipelines
            1. CI that runs reduced reference simulations
            2. Automatic comparison with expected results within tolerance ε
            3. Alerts on stability or conservation regressions
            4. Generate artifacts (figures, metrics) as part of CI
            5. Publish CI reports accessible to the scientific team
            6. Use containers/fixed environments for reproducible CI
            7. Control numerical dependencies (BLAS/MPI)
            8. Version virtualized/emulated hardware in CI
            9. CI with GPU/accelerator tests
            10. Block merges that degrade key physical validation
        5. Performance-driven refactoring
            1. Identify kernel bottlenecks before refactoring
            2. Clean code oriented to vectorization/parallelization
            3. Remove abstractions that block critical optimizations
            4. Preserve scientific clarity despite micro-optimizations
            5. Set measurable performance targets
            6. Iterate guided by profiling, not intuition
            7. Document impact of each refactor on performance
            8. Avoid numerical regressions after refactor
            9. Balance readability and extreme speed
            10. Minimize “performance debt”
        6. Technical documentation and scientific user manuals
            1. Document physical assumptions and validity ranges
            2. Document discretized equations exactly used
            3. Input/output manual (input decks, result formats)
            4. Build and installation guides for different clusters
            5. Minimal reproducible examples
            6. Dependency tree (MPI, BLAS, etc.)
            7. Warnings about delicate boundary conditions
            8. Best practices for post-processing
            9. Release notes with scientific-relevant changes
            10. FAQ on numerical stability and tuning
        7. Reproducible notebooks and executable documents
            1. Use notebooks (Jupyter, etc.) linked to concrete data and code
            2. Step-by-step documented execution
            3. Capture parameters and intermediate results
            4. Auto-generate publication figures
            5. Visual comparison between runs
            6. Reproducible environment specification (requirements, environment.yml)
            7. Shareable without recompiling entire codebase
            8. Version notebooks as scientific artifacts
            9. Convert to PDF/HTML reports for dissemination
            10. Beware “mutable code” risks and lock versions
        8. Automation of simulation campaigns
            1. Systematic parameter sweeps
            2. Massive job submission to HPC queues
            3. Automatic collection of results and key metrics
            4. Automatic retries on node failure
            5. Trace which job corresponds to which parameter point
            6. Adaptive optimization guided by prior results
            7. Dynamically prioritize “interesting” regions
            8. Generate phase maps / parametric diagrams
            9. Auto-clean corrupted partial results
            10. Executive progress reports for campaigns
        9. Configuration management and parameter sweeps
            1. Clearly define physical vs numerical parameters
            2. Template configurations with placeholders
            3. Version each parameter set tested
            4. Structured storage (YAML/JSON) for reproducibility
            5. Auto-compare nearby configurations
            6. Track sensitivity of each parameter
            7. Avoid physically invalid combinations
            8. Reuse historically validated configurations
            9. Reanalyze old configurations quickly on new hardware
            10. Auto-generate documentation for sweeps
        10. Portability between on-premise supercomputers and research environments
            1. Package solvers and dependencies in reproducible containers
            2. Adapt to different schedulers (SLURM vs PBS vs LSF)
            3. Ensure code scales on smaller academic hardware
            4. Maintain reasonable performance without exotic hardware
            5. Synchronize datasets across sites
            6. Standardize build modules and toolchains
            7. Support heterogeneous accelerators depending on center
            8. Port scientific CI/CD pipelines to restricted environments
            9. Document proprietary dependencies / licenses
            10. Share optimized binaries with external collaborators
    18. Mixed and Approximate Precision Computing
        1. Single, double and extended precision
            1. Trade-off between computational cost and numerical precision
            2. Use of single precision (FP32) vs double (FP64) in different physical domains
            3. Extended precision for extremely stiff problems
            4. Impact on stability of iterative methods
            5. Changes in accumulated rounding error
            6. Regulatory or scientific requirements for minimum precision
            7. Compatibility with optimized BLAS/LAPACK libraries
            8. Acceptable error metrics according to the simulated phenomenon
            9. Choice of precision when producing publishable results
            10. Strategic use of high precision only in critical steps
        2. Mixed precision in iterative solvers
            1. Low-precision preconditioner + high-precision refinement
            2. Iterative refinement
            3. Matrix-vector products computed in low precision
            4. Accumulation of sums in higher precision for stability
            5. Use of half / BF16 in accelerated kernels
            6. Final correction in double precision
            7. Leveraging tensor cores / matrix accelerators
            8. Controlling loss of orthogonality in Krylov methods
            9. Validation of true residual vs reduced-precision residual
            10. Automatic detection of when to increase precision
        3. Precision reduction in critical kernels
            1. Identify kernels that dominate total cost
            2. Measure physical sensitivity of the result to local errors
            3. Lower precision only where scientific impact is minor
            4. Generate alternative versions of the same kernel per precision
            5. Evaluate gains in FLOP/s and energy savings
            6. Validate that scientific conclusions do not change
            7. Use in near-real-time computing
            8. Integration with auto-tuning to select ideal precision
            9. Documentation of introduced fidelity loss
            10. Rollback mechanisms to high precision in unstable regions
        4. Approximate and error-tolerant computing
            1. Accept controlled-error results in exchange for large acceleration
            2. Approximate algorithms for linear kernels / partial solvers
            3. Probabilistic methods as substitutes for exact deterministic computation
            4. Use of statistical sampling as an estimator instead of exact calculation
            5. Techniques for spatial/temporal precision trimming in simulations
            6. Dynamic adjustment of approximation level according to simulation phase
            7. Monitoring deviations against a high-fidelity baseline
            8. Suitable for exploratory analysis and parameter screening
            9. Risks in final or certifiable studies
            10. Balance between exploratory science and regulated science
        5. Numerical rescaling strategies
            1. Normalize variables to avoid overflow/underflow
            2. Nondimensional scaling of physical equations
            3. Rewriting equations to improve conditioning
            4. Centering and shifts for extremely large or small values
            5. Avoid catastrophic cancellation in nearly-equal subtractions
            6. Keep magnitudes similar among summed terms
            7. Rescale physical fields into convenient units
            8. Explicit tracking of scale changes in postprocessing
            9. Dynamic scale adjustment during long simulations
            10. Rigorous documentation of applied rescaling
        6. Controlled error propagation
            1. Model how numerical errors amplify step by step
            2. Estimate upper bounds of total error
            3. Detect when accumulated error invalidates the simulation
            4. Adaptive methods that refine precision when error grows
            5. Adjust timestep / mesh size according to estimated error
            6. Compare successive solutions to measure drift
            7. Report error bars on scientific results
            8. Separate real physical uncertainty from numerical error
            9. Validate robustness of conclusions against error propagation
            10. Use in decision-making based on simulation
        7. Stochastic arithmetic and instability detection
            1. Inject controlled random noise into arithmetic operations
            2. Identify extreme sensitivity to small perturbations
            3. Statistical estimation of numerical stability
            4. Detect catastrophic cancellation via random perturbation
            5. Quantify confidence in final results
            6. Compare runs with different noise realizations
            7. Use as a tool to validate numerical robustness
            8. Integrate with uncertainty analysis
            9. Prioritize stability improvements where most needed
            10. Pre-publication evaluation of critical results

    19. Resilience and Fault Tolerance in HPC
        1. Checkpointing and restart
            1. Save the complete simulation state periodically
            2. Resume after failure without restarting from t=0
            3. Checkpoint size and frequency as a cost/risk trade-off
            4. Consistent checkpoints across multiple MPI processes
            5. Compressed / differential checkpoints
            6. Fault-tolerant distributed storage
            7. Automation of dump and restore process
            8. Integrity validation of checkpoints
            9. Incremental vs full checkpoints
            10. Impact on overall performance
        2. Incremental and differential checkpointing
            1. Save only differences since last full checkpoint
            2. Reduce bandwidth and storage usage
            3. Track modified pages/variables
            4. Reconstruct state by combining base + deltas
            5. Selective encryption and compression of deltas
            6. Lower impact for ultra-long simulations
            7. Checkpoint tiering (fast local vs cold storage)
            8. Adaptive checkpointing based on physical criticality
            9. Coordination with the job scheduler
            10. Fast recovery after brief outages
        3. Fault-tolerant algorithms (ABFT)
            1. Insert mathematical redundancy into computations (checksums)
            2. Detect silent errors in linear algebra
            3. Partial correction without restarting the entire computation
            4. ABFT for distributed matrix multiplication
            5. ABFT in iterative solvers
            6. Trade-off between computational overhead and resilience
            7. Early detection of data corruption in RAM/GPU
            8. Integration with ECC-capable hardware
            9. Extension to complex communication topologies
            10. Use in exascale environments with frequent faults
        4. Active replication of critical tasks
            1. Run the same task in parallel on different nodes
            2. Compare results to detect silent corruption
            3. Immediate fallback to the healthy result if one fails
            4. Selective replication: only for critical or irreproducible stages
            5. Costs of duplicating/triplicating compute
            6. Detection of transient hardware faults
            7. Fast recovery without long retries
            8. Consistency validation in time (similar latency)
            9. Use in simulations that feed real-time control
            10. Integration with HPC queues that allocate redundant nodes
        5. Detection and correction of bit flips
            1. Single-bit errors in memory (soft errors from cosmic radiation)
            2. Use ECC memory for automatic correction
            3. Monitor per-node error rates
            4. Rerun suspect numerical kernels
            5. Validate integrity of critical data on GPUs
            6. Identify degraded hardware
            7. Preventive node cleaning / reboot
            8. Quarantine policies for “noisy” nodes
            9. Logging for long-term reliability analysis
            10. Prioritize more reliable nodes for sensitive simulations
        6. Recovery after partial node failures
            1. Continue execution with fewer active resources
            2. Dynamically redistribute spatial domain among remaining nodes
            3. Reinitialize failed processes without killing the whole job
            4. Rebalance load after the failure
            5. Preserve in-memory data from the rest of the cluster
            6. Coordinate with scheduler (SLURM, PBS) to reassign nodes
            7. Reconstruct lost halos/boundaries
            8. Safeguard partial results produced up to the failure
            9. Record the failure event as part of scientific traceability
            10. Application-level resilience metrics
        7. Elasticity under large-scale failures
            1. Jobs that survive frequent failures in exascale systems
            2. Dynamic adjustment of MPI process counts
            3. Reassign tasks to healthy nodes on the fly
            4. Maintain parallel efficiency despite node loss
            5. Temporarily scale down to stabilize
            6. Prevent cascading failures
            7. Integration with execution-runtime fault tolerance
            8. Automatic “graceful degradation” policies
            9. Decision-making based on scientific criticality vs rescue cost
            10. Metrics of effective availability of useful compute
        8. Dynamic reconfiguration of jobs mid-run
            1. Change process layout without restarting
            2. Migrate subdomains between active nodes
            3. Adjust timestep / mesh size according to available resources
            4. Shutdown noncritical stages to save the main experiment
            5. Preserve data coherence after reassignment
            6. Hot update of simulation parameters
            7. Change queue priorities live
            8. Continuous telemetry to decide reconfiguration
            9. Validate that simulated physics remains valid
            10. Automatic documentation of reconfiguration for traceability

    20. Real-time and High-Fidelity Scientific Computing
        1. Online simulation for experimental control
            1. Run predictive simulation alongside an ongoing physical experiment
            2. Adjust experiment parameters live according to predictions
            3. Require minimal latency and deterministic computation
            4. Zero tolerance for prolonged failures
            5. Need for reduced-order models or ultra-fast surrogates
            6. Strict temporal synchronization with data acquisition
            7. Continuous monitoring of deviations between prediction and measurement
            8. Near-real-time alarms
            9. Logging for scientific and safety audits
            10. Use in plasma physics, particle accelerators, reactors
        2. Digital twins of complex physical systems
            1. Operational numerical replica of a real physical system
            2. Continuous update with sensed data
            3. Predict failures and enable preventive maintenance
            4. Evaluate hypothetical scenarios without intervening in the real system
            5. Continuous model adjustment with ML + physics
            6. Integration of multiple coupled physical domains
            7. Near-live compute requirements
            8. Scale from single devices to industrial infrastructures
            9. Cybersecurity issues for connected digital twins
            10. Traceability for critical operational decisions
        3. Simulation-based predictive control
            1. Use numerical models to predict future state
            2. Optimize control actions under physical constraints
            3. Continuous Model Predictive Control (MPC)
            4. Model order reduction to meet time windows
            5. Fusion with sensors in a closed loop
            6. Rapid reaction to external disturbances
            7. Stability guarantees under uncertainty
            8. Safety validation before applying control
            9. Co-execution on dedicated plant/lab hardware
            10. Compliance with operational safety regulations
        4. Live assimilation of experimental data with models
            1. Data assimilation in near real time
            2. Kalman filters / EnKF / particle filters for state estimation
            3. Continuous correction of simulated states
            4. Reconstruction of fields not directly measured
            5. Use in climate, nuclear fusion, in-vivo biology
            6. Strict latency requirements for data ingestion
            7. Balance statistical robustness vs speed
            8. Control noise and outliers in experimental signals
            9. Plausibility validation after assimilation
            10. Scale to distributed sensor networks
        5. Edge processing for scientific instruments
            1. Compute near the data-generating device (beamlines, telescopes, microscopes)
            2. Filtering and compression at the edge to reduce bandwidth
            3. Early detection of interesting events
            4. Decide which data to store vs discard
            5. Ultra-low latency for costly beam-time experiments
            6. Integrate with central HPC clusters for deep postprocessing
            7. Energy/space constraints at the edge
            8. Robustness to intermittent disconnections
            9. Physical and logical security of the edge node
            10. Regulatory compliance for sensitive scientific instrumentation
        6. Automatic data reduction under strict latency
            1. Immediate postprocessing of raw data in real time
            2. Extract relevant features live
            3. Remove redundant or low-value scientific data
            4. Prioritize rare / critical events
            5. Use accelerated inference (GPU/FPGA) for immediate classification
            6. Adaptive retention policies based on experimental context
            7. Minimize IO to slow storage
            8. Ensure nothing important is discarded without review
            9. Log criteria used to discard data
            10. Ability to “replay” recent temporal windows
        7. Early warning systems based on simulation
            1. Predict dangerous or unstable conditions before they occur
            2. Combine physical models + ML to identify critical thresholds
            3. Automatic operational alerts for human responders
            4. Continuous validation to avoid harmful false alarms
            5. Prioritize alerts by severity
            6. Integrate with industrial/lab safety protocols
            7. Logging and audit of emitted alerts
            8. Post-event evaluation of alert effectiveness
            9. Fine-tune thresholds under new conditions
            10. Use in seismology, reactor operation, extreme weather

    21. Ethics, Management and Scientific Policy in HPC
        1. Prioritization of access to supercomputing resources
            1. Policies for allocation of compute hours among projects
            2. Evaluate scientific merit vs applied urgency (e.g., extreme climate)
            3. Balance basic research and industrial projects
            4. Fair access for small / emerging teams
            5. Transparency in prioritization criteria
            6. Appeal / peer-review mechanisms
            7. Impact on careers and publication opportunities
            8. Incentives to share results and tools
            9. Emergency reserves for critical immediate use
            10. Minimize resource capture by a few dominant actors
        2. Quotas and governance of shared clusters
            1. CPU/GPU/storage quotas per group
            2. Priority limits in job queues
            3. Fairness among concurrent users
            4. Penalties for abuse or inefficient use
            5. Near-real-time consumption monitoring
            6. Accounting reports for sponsors / agencies
            7. Compliance audits with institutional agreements
            8. Long-term capacity planning
            9. Transparency in internal cost allocation
            10. Policies for multi-institution collaborative projects
        3. Transparency and traceability of numerical results
            1. Require full reporting of configuration and parameters
            2. Require publishing postprocessing scripts
            3. Document assumed physical hypotheses
            4. Report uncertainty and sensitivity
            5. Include hardware and library details used
            6. Ensure results are auditable by third parties
            7. Avoid “black box” findings with public impact
            8. Ensure minimal interpretability in AI applied to physics
            9. Maintain temporal traceability (when the result was generated)
            10. Declare technological / commercial conflicts of interest
        4. Reproducibility as a publication criterion
            1. Require data and code (or verifiable executables) with the paper
            2. Require seeds and exact configurations
            3. Require execution instructions
            4. Peer review that includes replication attempts
            5. Encourage open repositories and persistent DOIs
            6. Penalize irreproducible practices in journals/conferences
            7. Declare reproducibility metrics in the article
            8. Culture of “reliable results” over “flashy results”
            9. Facilitate reproducibility badges / certifications
            10. Avoid dependence on proprietary infrastructure inaccessible to reviewers
        5. Energy sustainability of supercomputing
            1. Energy consumption of HPC centers at MW scale
            2. FLOP/J efficiency as a key metric
            3. Recovery and reuse of waste heat
            4. Geographic siting with access to clean energy
            5. Schedule intensive loads during lower-energy-cost hours
            6. Dynamic frequency/voltage scaling (DVFS) to reduce consumption
            7. Migrate workloads to more energy-efficient hardware
            8. Assess environmental cost of giant simulations
            9. Report carbon footprint associated with scientific publications
            10. Institutional incentives for computational efficiency
        6. Carbon footprint of large-scale model training
            1. Training huge models (thousands of GPUs) and their consumption
            2. Compare scientific benefit vs environmental cost
            3. Use efficiency techniques (pruning, distillation)
            4. Continuous training vs incremental fine-tuning
            5. Reuse pretrained models instead of training from scratch
            6. Transparency about declared energy cost in papers
            7. Schedule optimization for cleaner energy windows
            8. Design more efficient network architectures
            9. Balance marginal precision gains vs exponential energy cost
            10. Institutional policies to limit compute waste
        7. Responsible handling of sensitive and confidential data
            1. Biomedical, strategic climate, or proprietary industrial data
            2. Strict access controls in HPC storage
            3. Anonymization / pseudonymization of data
            4. Encryption in transit and at rest
            5. Access audits for sensitive datasets
            6. Regulatory compliance (privacy, export controls)
            7. Limit copying / exfiltration of data
            8. Isolated environments for secure analysis
            9. Secure deletion procedures for expired data
            10. Balance openness in science with ethical/legal protection
        8. Technology transfer to industry
            1. Bring advanced simulation and HPC from lab to real applications
            2. Regulatory validation of numerical models for industrial use
            3. Create engineering tools based on HPC solvers
            4. Intellectual property and licensing
            5. Public–private collaborations in supercomputing
            6. Train transferable specialized technical personnel
            7. Democratize HPC capabilities via managed services
            8. Economic and competitive impact of advanced simulation
            9. Responsibility for automated decisions based on simulation
            10. Standards of safety, reliability and ethics in industrial adoption

8. Data and ML
    1. Mathematical and computational fundamentals
        1. Linear algebra for data and models
            1. Vectors, matrices and tensors
            2. Linear operations and matrix products
            3. Linear dependence and rank
            4. Vector spaces and column/row subspaces
            5. Eigenvalue and eigenvector decomposition
            6. SVD decomposition and dimensionality reduction
            7. Orthogonal projections and least squares
            8. Overdetermined systems and pseudoinverse
            9. Numerical stability in linear algebra
            10. Sparse representation and efficient computation
        2. Differential calculus and introduction to continuous optimization
            1. Partial derivatives and gradient
            2. Chain rule in high-dimensional spaces
            3. Hessian and local curvature
            4. Local optima and stationarity
            5. Basic convexity and conditions for global minimum
            6. Differentiable loss functions
            7. Basic gradient descent
            8. Learning rate and stability
            9. Ill-conditioned problems
            10. Regularization as a term in the objective function
        3. Convex optimization and duality (Lagrange, KKT)
            1. Convex functions and convex sets
            2. Quadratic and linear programs
            3. Lagrange multipliers
            4. KKT conditions
            5. Primal-dual duality
            6. Economic interpretation of dual variables
            7. Soft constraints vs hard constraints
            8. L1/L2 regularization as constraints
            9. Sparsity induced by L1
            10. Guaranteed convergence in convex problems
        4. Numerical optimization methods (gradient, Newton, quasi-Newton, Adam)
            1. Stochastic gradient descent (SGD)
            2. Momentum and acceleration
            3. Second-order methods and Newton
            4. Quasi-Newton methods (BFGS, L-BFGS)
            5. Adam and adaptive variants
            6. Learning rate decay
            7. Batch vs mini-batch vs online
            8. Early stopping as overfitting control
            9. Nonconvex landscapes and flat local minima
            10. Numerical stability in deep training
        5. Basic probability and random variables
            1. Probability spaces and events
            2. Discrete and continuous random variables
            3. Density and distribution functions
            4. Expectation, variance and covariance
            5. Law of large numbers
            6. Central limit theorem
            7. Common distributions (Bernoulli, Normal, Poisson, Exponential)
            8. Independence and correlation
            9. Conditional probability and Bayes
            10. Basic Monte Carlo sampling
        6. Elementary statistical inference (sampling, estimation, bias/variance)
            1. Sample vs population
            2. Point and interval estimators
            3. Properties of a good estimator
            4. Bias vs variance
            5. Bootstrap resampling
            6. Confidence intervals
            7. Hypothesis testing as a binary decision
            8. p-value and Type I/II error
            9. Multiple-comparison correction
            10. Uncertainty and communicating error
        7. Information theory (entropy, divergence)
            1. Shannon entropy
            2. Mutual information
            3. KL divergence
            4. Cross-entropy as a loss function
            5. Optimal coding and compression
            6. Redundancy and attribute correlation
            7. Feature selection by mutual information
            8. Information-based regularization
            9. Maximum entropy
            10. Relation between entropy and uncertainty in models

    2. Data foundations and quantitative analysis
        1. Data types and formats (structured, semi-structured, unstructured)
            1. Relational tabular
            2. JSON, logs and events
            3. Free text
            4. Images and signals
            5. Time series data
            6. Sensors and telemetry
            7. Geospatial data
            8. Labeled vs unlabeled data
            9. Synthetic data
            10. Sensitive and regulated data
        2. Data manipulation and transformation
            1. Joins and merges
            2. Filtering and column selection
            3. Aggregations and group-by
            4. Pivoting and reshaping
            5. Unit and scale normalization
            6. Duplicate detection
            7. Enrichment with external sources
            8. Batch vs streaming processing
            9. Construction of derived features
            10. Documentation of transformations
        3. Cleaning, imputation, normalization and validation
            1. Detection of missing values
            2. Numerical and categorical imputation
            3. Outliers and winsorizing
            4. Standardization and scaling
            5. Categorical encoding
            6. Range and format validation
            7. Schema drift detection
            8. Label quality
            9. Data quality auditing
            10. Traceability of changes to critical data
        4. Data versioning, lineage and dataset reproducibility
            1. Column lineage (source-transformation-destination)
            2. Versioning of tables and snapshots
            3. Versioning of schemas and contracts
            4. Access control to historical datasets
            5. Metadata and data catalog
            6. “Golden” certified datasets
            7. Reproducibility of reports
            8. Retention and expiration policies
            9. Lifecycle of critical datasets
            10. Audit and compliance
        5. Basic time series: aggregations, time windows, seasonality
            1. Moving and cumulative windows
            2. Downsampling and resampling
            3. Daily / weekly / yearly seasonality
            4. Trend and level
            5. Exponential smoothing
            6. User retention with moving windows
            7. Peak and anomaly detection
            8. Lag features and lead features
            9. Short-term vs long-term forecasting
            10. Forecast error metrics
        6. Business metrics and KPI definition
            1. Acquisition, activation and retention metrics
            2. Conversion and funnel metrics
            3. Lifetime value (LTV)
            4. Churn and customer retention
            5. Operational SLA / SLO
            6. Risk and fraud metrics
            7. Satisfaction metrics / NPS
            8. Operational efficiency and cost metrics
            9. Regulatory metrics
            10. Alignment between metrics, teams and leadership
        7. Segmentation, cohorts and user behavior
            1. Cohorts by signup / acquisition date
            2. Segmentation by feature usage
            3. Economic value by segment
            4. User lifecycle
            5. RFM (recency, frequency, monetary)
            6. Multi-stage funnels
            7. Drop-off and choke points
            8. Geographic segmentation
            9. Contextual / seasonal segmentation
            10. Real-time dynamic segmentation
        8. Product analytics and usage telemetry
            1. Event instrumentation
            2. Definition of product events
            3. Event properties (metadata)
            4. Feature usage funnels
            5. Friction detection in the experience
            6. Impact of new features
            7. Alerts on drops in usage
            8. Experiments for UI/UX changes
            9. Engagement metrics
            10. Early activation metrics
        9. Geospatial analysis and location data
            1. Coordinates and projections
            2. Map matching and geofencing
            3. Spatial density and heatmaps
            4. Routes, trajectories and mobility
            5. Spatial clustering
            6. Localized demand
            7. Geographic risk and coverage
            8. Logistics optimization
            9. Satellite data and remote sensors
            10. Privacy in location data
        10. Risk, fraud and anomaly analysis
            1. Unusual transactional patterns
            2. Dynamic vs static thresholds
            3. Heuristic rules vs statistical models
            4. Unsupervised anomaly models
            5. Aggregated signals by user / device
            6. Alert escalation
            7. Human validation of fraud
            8. Expected cost of false positives
            9. Adversarial evasion
            10. Internal reporting / compliance
        11. Exploratory data analysis (EDA)
            1. Distributions and percentiles
            2. Bivariate relationships
            3. Correlations and preliminary multicollinearity
            4. Outliers and heavy tails
            5. Subpopulation breakdowns
            6. Temporal variable drift
            7. Labeling quality
            8. Candidate variables for features
            9. Model assumptions detectable by inspection
            10. Early actionable findings
        12. Visualization, data storytelling and executive communication
            1. Choice of appropriate visualization
            2. Minimalism and signal vs noise
            3. Charts for trends vs snapshots
            4. Single metrics vs comparative dashboards
            5. Causal narrative vs descriptive narrative
            6. Communication to non-technical audiences
            7. Visual alerts and executive traffic lights
            8. Annotations and historical context
            9. Metrics that matter to the business
            10. Evidence-driven decision making

    3. Statistics, inference and causality
        1. Estimators, bias and variance
            1. Consistency of the estimator
            2. Unbiasedness vs low variance
            3. Mean squared error
            4. Bias/variance trade-off
            5. Regularization as controlled bias increase
            6. Error intervals for business metrics
            7. Empirical vs parametric estimation
            8. Low-data regimes
            9. Variance in complex models
            10. Communicable uncertainty to stakeholders
        2. Confidence intervals and hypothesis testing
            1. Null and alternative hypotheses
            2. Test statistic
            3. Null distribution
            4. p-value and its interpretation
            5. Type I and Type II errors
            6. Confidence intervals vs tests
            7. Multiple-testing correction
            8. Equivalence and non-inferiority tests
            9. One-sided vs two-sided tests
            10. Robustness to violated assumptions
        3. Group comparison (t-test, χ², ANOVA)
            1. Comparison of means
            2. Comparison of proportions
            3. Variances between groups
            4. Contingency tables and χ²
            5. One-way ANOVA
            6. Multifactor ANOVA
            7. Interactions between factors
            8. Practical vs statistical significance
            9. Post-hoc correction
            10. Choice of comparison metric
        4. Statistical significance, power and sample size
            1. Statistical power
            2. Minimum sample size calculation
            3. Detection of small effects
            4. Statistical ROC of an experiment
            5. Cost/benefit of experimenting
            6. Minimum experiment duration
            7. Peeking and look-ahead bias
            8. Sequential testing
            9. Stopping rules
            10. Scientific validity vs business speed
        5. Linear and multiple regression (interpretation of coefficients)
            1. Classical linear model
            2. Assumptions of the linear model
            3. Coefficients as marginal effects
            4. Confidence intervals for coefficients
            5. Interactions and cross terms
            6. Categorical variables and dummies
            7. Multicollinearity in practice
            8. Heteroskedasticity
            9. Correlated errors over time
            10. Interpretability for executive audiences
        6. Multicollinearity and variable selection
            1. Correlation matrix
            2. VIF (Variance Inflation Factor)
            3. Backward / forward elimination
            4. L1 penalties and sparsity
            5. Selection based on mutual information
            6. Selection based on validated performance
            7. Redundant variables
            8. Proxy variables for bias
            9. Cost to obtain each variable
            10. Stability of selection over time
        7. Statistical regularization (ridge, lasso)
            1. Ridge and coefficient shrinkage
            2. Lasso and sparsity
            3. Elastic Net
            4. Geometric interpretation of L1 vs L2
            5. Avoiding overfitting in high dimensions
            6. Automatic variable selection with L1
            7. Penalty as complexity control
            8. Cross-validation for optimal λ
            9. Relation to Bayes (Gaussian / Laplace priors)
            10. Impact on interpretability
        8. Applied Bayesian inference
            1. Priors and posteriors
            2. Likelihood
            3. Bayesian updating with new evidence
            4. Credible intervals vs confidence intervals
            5. MAP vs MCMC
            6. Approximate and variational inference
            7. Bayes in online experimentation
            8. Informative vs noninformative priors
            9. Bayesian mixture of experts
            10. Probabilistic communication to business
        9. Causal analysis (confounders, instrumental variables, correlation vs causation)
            1. Cause vs correlation
            2. Confounders and omitted variable bias
            3. Causal diagrams (DAGs)
            4. Instrumental variables
            5. Propensity score matching
            6. Inverse propensity weighting
            7. Difference-in-differences
            8. Structural causal models
            9. Identification vs estimation
            10. Practical limitations of causal inference
        10. Impact evaluation and uplift
            1. Individual uplift metrics
            2. Treatment population segmentation
            3. Heterogeneous treatment effects
            4. Conversion lift
            5. Incremental ROI
            6. Selection of target population
            7. Regulatory risk in differential targeting
            8. Fairness in treatment allocation
            9. Operational prioritization of campaigns
            10. Post-launch measurement (observational vs experimental)

    4. Theory of machine learning
        1. Formulation of supervised, unsupervised and semi-supervised learning
            1. Objectives: prediction vs structure discovery
            2. Strong labels vs weak labels
            3. Dependence on training signal
            4. Assumptions about data distribution
            5. Transductive vs inductive learning
            6. Empirical risk vs true risk
            7. Typical objective functions by task type
            8. Scenarios with limited or costly data
            9. Relation to active learning
            10. Transfer between paradigms (pseudo-labeling)
        2. Loss functions and statistical meaning
            1. Quadratic loss and Gaussian assumptions
            2. Cross-entropy and probabilistic classification
            3. Hinge loss and margins
            4. Robust losses to outliers (Huber)
            5. Asymmetric and cost-sensitive losses
            6. Ranking losses / AUC-oriented losses
            7. Multiclass vs multilabel losses
            8. Regularization as a loss term
            9. Business-customized losses
            10. Probabilistic interpretation of loss
        3. Generalization: bias-variance, model capacity and overfitting
            1. Learning curves (train vs valid)
            2. Underfitting vs overfitting
            3. Model capacity vs dataset size
            4. Effective model complexity
            5. Regularization to reduce variance
            6. Data augmentation to improve generalization
            7. Early stopping as overfitting control
            8. Cross-validation as out-of-sample error estimator
            9. Detection of information leakage
            10. Out-of-distribution generalization
        4. VC dimension, margins and complexity control
            1. VC dimension as capacity measure
            2. Linear separability and maximum margin
            3. L2 regularization as margin control
            4. Margin vs empirical error trade-off
            5. Generalization bounds dependent on margin
            6. Complexity of nonlinear classifiers
            7. Kernel functions and high-dimensional spaces
            8. Effective capacity of deep models
            9. Overcapacity and memorization
            10. Geometric interpretation of overfitting
        5. PAC learning (conceptual overview)
            1. Probably Approximately Correct
            2. Empirical vs true error
            3. Tolerance ε (accuracy) and δ (confidence)
            4. Sample size needed to learn
            5. Hypothesis families and complexity
            6. PAC consistency
            7. Relation to VC dimension
            8. Learnability in the PAC sense
            9. Practical limitations of PAC framework
            10. Connections to modern deep-learning bounds
        6. Regularization seen as complexity constraint
            1. L2 penalty (weight decay)
            2. L1 penalty (sparsity and feature selection)
            3. Elastic Net as compromise
            4. Dropout as structured noise
            5. Data augmentation as implicit regularization
            6. Batch normalization and training stability
            7. Early stopping as capacity limit
            8. Weight sharing in convolutional nets
            9. Quantization/pruning as effective complexity reduction
            10. Bayesian interpretation of regularization
        7. Nonconvex optimization landscapes in deep nets
            1. Local minima vs saddle points
            2. Flat vs sharp minima
            3. Robustness of flat minima to noise
            4. Effect of batch size
            5. Sensitivity to initialization
            6. Ruggedness of the loss landscape
            7. Parameter symmetries (neuron permutation)
            8. Gradient vanishing/explosion
            9. Descent trajectories in high dimensions
            10. Practical convergence with heuristic optimizers
        8. Training stability and noise
            1. Stochastic noise in SGD
            2. Noise as exploration of the loss landscape
            3. Robustness to noisy data
            4. Incorrect labels and their effect
            5. Label smoothing
            6. Normalization and scale control
            7. Example mixing (mixup, cutmix)
            8. Sensitivity to adversarial perturbations
            9. Stability across random seeds
            10. Stability vs reproducibility in real environments

    5. Classical Machine Learning (Traditional ML)
        1. Linear and Logistic Regression
            1. Closed-form formulation vs iterative training
            2. Interpretation of coefficients
            3. Calibrated probabilities in classification
            4. Ridge / lasso regularization
            5. Multicollinearity and numerical conditioning
            6. Interactions and polynomial terms
            7. Outlier detection in residuals
            8. Penalized regression for high-dimensional data
            9. Multinomial logistic regression
            10. Limitations for non-linear decision boundaries
        2. k-NN and Distance-Based Methods
            1. Definition of neighborhood
            2. Choice of k
            3. Distance metrics (Euclidean, cosine)
            4. Effect of high dimensionality
            5. Approximate nearest neighbor search
            6. Classification by weighted voting
            7. Regression by local averaging
            8. Sensitivity to noise and outliers
            9. Scaling / normalization beforehand
            10. Use in similarity-based recommendation
        3. Support Vector Machines (SVM)
            1. Maximum margin
            2. Soft margin and parameter C
            3. Kernel functions (linear, RBF, polynomial)
            4. Binary and multiclass classification
            5. SVM for regression (SVR)
            6. Geometric interpretation of support vectors
            7. Feature scaling
            8. Computational cost for large datasets
            9. Hyperparameter selection (C, gamma)
            10. Robustness in high-dimension with few samples
        4. Decision Trees
            1. Split criteria (gini, entropy, mse)
            2. Maximum depth and overfitting
            3. Visual interpretability
            4. Handling categorical variables
            5. Handling missing values
            6. Regression vs classification trees
            7. Pruning
            8. Instability to small input variations
            9. Leakage via poorly constructed splits
            10. Trees as base learners for ensembles
        5. Random Forests
            1. Bootstrap aggregating (bagging)
            2. Random feature selection per split
            3. Variance reduction
            4. Variable importance (feature importance)
            5. Robustness to noise
            6. Out-of-bag error estimation (OOB)
            7. Control of depth and number of trees
            8. Detection of residual overfitting
            9. Handling high dimensionality
            10. Limitations in continuous extrapolation
        6. Ensembles and Gradient Boosting (XGBoost, LightGBM)
            1. Boosting vs bagging
            2. Weak trees as base learners
            3. Learning rate
            4. Tree depth in boosting
            5. Regularization in boosting
            6. Feature importances by gain
            7. Handling class imbalance
            8. Partial interpretability (partial dependence)
            9. Overfitting from aggressive boosting
            10. Industrial use in tabular prediction
        7. Feature Selection and Feature Engineering
            1. Creation of aggregated features
            2. Feature crosses
            3. Log, Box-Cox transformations, binning
            4. Categorical encoding (one-hot, target encoding)
            5. Selection based on model importance
            6. Selection based on temporal stability
            7. Removal of leakage
            8. Temporal feature engineering (lags, rolling stats)
            9. Normalization / standardization
            10. Documentation and feature governance
        8. Class Balancing and Handling Extreme Imbalance
            1. Class reweighting (class weights)
            2. Undersampling the majority class
            3. Oversampling the minority class
            4. SMOTE and variants
            5. Metrics robust to imbalance (PR AUC)
            6. Decision threshold tuning
            7. Cost-sensitive learning
            8. Regulatory risk of false negatives/positives
            9. Evaluation by subpopulations
            10. Monitoring imbalance over time
        9. Clustering (k-means, Hierarchical, DBSCAN)
            1. k-means and its objective
            2. Choosing k (inertia, silhouette)
            3. Initialization (k-means++)
            4. Hierarchical clustering and dendrograms
            5. Distances and linkage methods
            6. DBSCAN and density-based clustering
            7. Noise and border points
            8. Clusters of arbitrary shape
            9. Scaling to large datasets
            10. Use in customer segmentation
        10. Mixture Models and Probabilistic Clustering
            1. Gaussian mixture models
            2. Expectation-Maximization (EM)
            3. Soft clustering vs hard clustering
            4. Density estimation
            5. Choosing number of components (BIC/AIC)
            6. Probabilistic interpretation of membership
            7. Non-Gaussian mixtures
            8. Mixtures for categorical data
            9. Mixtures in time series
            10. Limitations in high dimension
        11. Dimensionality Reduction (PCA, t-SNE, UMAP)
            1. Linear PCA and explained variance
            2. Interpretable principal components
            3. Effect of prior scaling
            4. t-SNE for visualization
            5. UMAP and preservation of local structure
            6. Noise vs signal in high dimension
            7. Feature compression
            8. Preprocessing for clustering
            9. Reduction for executive visualization
            10. Loss of interpretability
        12. Anomaly Detection and Outliers
            1. Univariate statistical models
            2. Distance in feature space
            3. Isolation Forest
            4. Local Outlier Factor
            5. Density-based models
            6. Anomalies in time series
            7. Use in fraud and security
            8. Sensitivity vs false alarm trade-off
            9. Human validation of alerts
            10. Adaptation to new attack patterns
        13. Time Series with Traditional ML (ARIMA, SARIMA, Holt-Winters, VAR)
            1. Stationarity and differencing
            2. Seasonality and SARIMA
            3. Holt-Winters (trend and smooth seasonality)
            4. VAR for multivariate series
            5. Lag selection
            6. Forecasting metrics (MAPE, sMAPE, MASE)
            7. Rolling vs global training
            8. Behavior drift over time
            9. Forecasting with external interventions
            10. Operational interpretation of forecasts
        14. Demand Forecasting and Multi-Horizon Prediction
            1. Short-term vs long-term prediction
            2. Rolling horizon
            3. Forecast by segment / category
            4. Calendar effects (holidays, campaigns)
            5. Prediction uncertainty
            6. Probabilistic forecasting (quantile forecasting)
            7. Cost of overstock vs stockout
            8. Hierarchical forecast aggregation
            9. Financial evaluation of error
            10. Integration with operational planning
        15. AutoML and Hyperparameter / Architecture Search
            1. Random search vs grid search
            2. Bayesian hyperparameter optimization
            3. Automatic selection of candidate models
            4. Automatic feature selection
            5. Automatic pipeline assembly
            6. Neural Architecture Search (NAS)
            7. Meta-learning
            8. Internal quality benchmarks
            9. Computational cost and practical limits
            10. Risks of black-boxing and reproducibility
        16. Semi-Supervised and Weakly Supervised Learning
            1. Pseudo-labeling
            2. Consistency regularization
            3. Iterative self-training
            4. Weak supervision with heuristic rules
            5. Noisy but massive datasets
            6. Reducing human labeling costs
            7. Domain transfer
            8. Detecting contradictory labels
            9. Evaluation without a perfect gold standard
            10. Industrial use in fraud and moderation

    6. Model Evaluation and Experimental Design
        1. Train/validation/test split and cross-validation
            1. Simple hold-out
            2. K-fold cross-validation
            3. Stratified sampling
            4. Time series split
            5. Nested cross-validation
            6. Temporal leakage in series
            7. User-level leakage
            8. Blocked test sets
            9. Improper reuse of the test set
            10. Reproducibility of splits
        2. Regression, classification and ranking metrics (ROC, PR, F1, calibration)
            1. RMSE / MAE for regression
            2. Accuracy and its limitations
            3. Precision, recall and F1
            4. ROC curve and AUC
            5. PR curve and usefulness for rare classes
            6. Probability calibration
            7. Top-K and ranking metrics
            8. Business-oriented metrics (expected cost)
            9. Subgroup metrics (fairness)
            10. Real-time vs batch metrics
        3. Decision thresholds and expected cost
            1. False positive / false negative trade-off
            2. Threshold optimization by business metric
            3. Precision-recall curve as threshold guide
            4. Expected value of a prediction
            5. Cost-sensitive classification
            6. Dynamic thresholds by context
            7. Regulatory risk for certain error types
            8. Segment-dependent calibration
            9. Human approval for borderline cases
            10. Explaining thresholds to the business
        4. Local and global interpretability (feature importance, SHAP/LIME)
            1. Global variable importance
            2. Partial dependence plots (PDP)
            3. SHAP for local attribution
            4. LIME for local approximate explanations
            5. Counterfactual explanations
            6. Feature interactions
            7. Transparency vs performance trade-offs
            8. Explanations for auditors / regulators
            9. Real-time explainability to end users
            10. Risk of revealing sensitive information
        5. Data Leakage and Information Leaks
            1. Variables using future information
            2. Label-derived variables
            3. Variables nearly duplicated from the label
            4. Mixing users across train and test
            5. Mixing historical periods
            6. Highly aggregated variables without temporal control
            7. Leaks in shared feature stores
            8. Leaks between training and production environments
            9. How to detect with feature audits
            10. Impact on artificially inflated metrics
        6. Robustness to noise, missing data and distribution shifts
            1. Evaluation under controlled perturbations
            2. Robustness to outliers
            3. Robustness to aggressive imputation
            4. Evaluation on rare subpopulations
            5. Domain shift
            6. Concept drift
            7. Basic adversarial noise
            8. Stability across model replicas
            9. Uncertainty estimation in predictions
            10. Mitigation plans for model degradation
        7. A/B Testing and Controlled Experimentation
            1. Control vs treatment groups
            2. Randomization and stratification
            3. Minimum experiment duration
            4. Peeking and temporal bias
            5. Primary and secondary metrics
            6. Spillover between treatments
            7. Multivariate testing (A/B/n)
            8. Effects in subsegments
            9. Opportunity cost of a bad variant
            10. Rollout decision based on evidence
        8. Descriptive / Diagnostic / Predictive / Prescriptive Models
            1. What happened (descriptive)
            2. Why it happened (diagnostic)
            3. What will happen (predictive)
            4. What should we do (prescriptive)
            5. Early warning systems
            6. Prioritization of leads / cases
            7. Next-action suggestion
            8. Optimization under resource constraints
            9. Measuring real impact of actions
            10. Integration with daily operations
        9. Applied Causal Analysis and Uplift Modeling in Product
            1. Individual uplift models
            2. Differential treatment assignment
            3. Heterogeneous treatment effects
            4. High-impact incremental segments
            5. Avoid targeting users who would convert anyway
            6. Ethical risk in selective targeting
            7. Retrospective evaluation (post-hoc)
            8. Validation with A/B experiments
            9. Communicating incremental impact to the business
            10. Use in marketing, retention and pricing
        10. Early Detection of Degradation (Data Drift and Concept Drift)
            1. Monitoring input distribution
            2. Monitoring output distribution
            3. Label drift detection
            4. Performance alarm thresholds
            5. Localized degradation in a segment
            6. Automatic operational alerts
            7. Retraining triggered by drift
            8. Pre-deploy validation
            9. Safe rollback
            10. Documenting model incident
        11. Online Learning and Continuous Adaptation
            1. Incremental training
            2. Weight updates without full retraining
            3. Streaming feature stores
            4. Handling changing concepts
            5. Models that evolve with the user
            6. Risk of drifting into biases
            7. Near-real-time metrics
            8. Security against malicious data injection
            9. Retaining useful old knowledge
            10. Continuous validation in production
        12. Active Learning (model requests labels where uncertain)
            1. Uncertainty-based sampling strategies
            2. Disagreement-based sampling between models
            3. Prioritization of “hard” examples
            4. Reducing human labeling cost
            5. Human-in-the-loop workflows
            6. Targeted improvement on critical metrics
            7. Focus on rare classes / fraud
            8. Progressive dataset curation
            9. Evaluating marginal benefit of each new label
            10. Risk of biasing the dataset with iterative feedback

    7. Deep Learning: Fundamentals
        1. Artificial Neurons and the Perceptron
            1. Linear neuron and activation function
            2. Simple perceptron and linear separability limit
            3. Multilayer perceptron (MLP)
            4. Hidden layers and universal approximation capacity
            5. Layer size vs model capacity
            6. Fully connected architectures
            7. Input normalization
            8. Saturation of classic activations (sigmoid/tanh)
            9. Vanishing gradient in deep networks
            10. Relation to logistic regression and softmax
        2. Dense Feed-Forward Networks
            1. Chained linear layers
            2. Linear + non-linear block as basic unit
            3. Depth vs width
            4. Modern activations (ReLU and variants)
            5. Batch-wise training
            6. Regularization with dropout in dense layers
            7. Between-layer normalization
            8. Proper initialization for deep nets
            9. Memorization vs generalization capacity
            10. Limits on structured/tabular data
        3. Activation Functions and Normalization
            1. Sigmoid and saturation
            2. tanh and zero-centering
            3. ReLU and variants (LeakyReLU, GELU)
            4. Softmax for multiclass classification
            5. Batch Normalization
            6. Layer Normalization
            7. Normalization as gradient stabilizer
            8. Effect on convergence speed
            9. Normalization as implicit regularization
            10. Normalization vs residual connections
        4. Backpropagation of the Gradient
            1. Derivatives in chained layers
            2. Chain rule in high dimension
            3. Forward pass vs backward pass
            4. Efficient computation with computational graphs
            5. Vanishing / exploding gradients
            6. Gradient clipping
            7. Backpropagation in recurrent networks
            8. Backpropagation in architectures with skip connections
            9. Autograd and modern frameworks
            10. Computational and memory cost
        5. Weight Initialization and Numerical Stability
            1. Uniform vs normal random initialization
            2. Xavier/Glorot initialization
            3. He initialization for ReLU
            4. Breaking symmetry between neurons
            5. Proper scaling per layer
            6. Depth and gradient degradation
            7. Initialization effect on convergence speed
            8. Random seeds and reproducibility
            9. Numerical precision (float32, float16, bfloat16)
            10. Stability on accelerated hardware (GPU/TPU)
        6. Regularization in Neural Networks (dropout, weight decay)
            1. Dropout as structured noise
            2. Weight decay as L2 penalty
            3. Early stopping
            4. Data augmentation
            5. Label smoothing
            6. Mixup and variants
            7. Normalization as implicit regularization
            8. Induced sparsity
            9. Overfitting control on small datasets
            10. Impact on interpretability
        7. Hyperparameter Tuning in Deep Networks
            1. Learning rate and schedulers
            2. Batch size
            3. Choice of optimizer (SGD, Adam, AdamW)
            4. Network depth and width
            5. Dropout rate and regularization
            6. Number of epochs
            7. Learning rate warmup
            8. Grid search vs Bayesian search
            9. Task-specific tuning (vision, NLP)
            10. Tuning under compute constraints
        8. Loss Functions for Classification and Regression
            1. Cross-entropy (multiclass classification)
            2. Binary cross-entropy (binary classification)
            3. Softmax + NLLLoss
            4. MSE / MAE (regression)
            5. Huber / Smooth L1
            6. Triplet loss and contrastive loss
            7. Focal loss for imbalanced classes
            8. Ranking-oriented losses
            9. Multitask losses
            10. Business-customized loss functions

    8. Advanced deep architectures
        1. Convolutional neural networks (CNN) for vision
            1. Convolution as local pattern extraction
            2. Filters / kernels and channels
            3. Receptive field and depth
            4. Translational invariance
            5. Classic architectures (LeNet, AlexNet)
            6. Modern architectures (ResNet, EfficientNet)
            7. BatchNorm in vision
            8. Data augmentation in vision
            9. Training with large vs small datasets
            10. Transfer learning in vision
        2. Pooling, padding and ResNet-like blocks
            1. Max pooling vs average pooling
            2. Stride and spatial downsampling
            3. Padding and size preservation
            4. Gradient problems in very deep networks
            5. Residual skips (skip connections)
            6. Basic blocks and bottleneck blocks
            7. Normalization within the residual block
            8. Extreme depth (50+ layers)
            9. Computational and memory efficiency
            10. Training stability with residuals
        3. Recurrent networks (RNN, LSTM, GRU)
            1. Explicit sequential modeling
            2. Exploding/vanishing gradients in classic RNNs
            3. LSTM cells and gates
            4. GRU as a simplified variant
            5. Hidden state as memory
            6. Step-by-step processing vs batching
            7. Many-to-one / many-to-many models
            8. Limitations on very long sequences
            9. Regularization in RNNs (recurrent dropout)
            10. Applications in time series and text
        4. Temporal Convolutional Networks
            1. Causal convolutions
            2. Dilated receptive fields
            3. Parallelism vs sequential RNNs
            4. Gradient stability on long sequences
            5. Multi-horizon prediction
            6. Use in temporal forecasting
            7. Application in industrial signals
            8. Comparison with LSTM
            9. Limitations with very long dependencies
            10. TCN + attention hybrids
        5. Attention mechanisms and self-attention
            1. Attention as contextual weighting
            2. Query, Key, Value
            3. Scaled dot-product attention
            4. Multi-Head Attention
            5. Attending to long sequences
            6. Causal vs bidirectional attention
            7. Cross-attention
            8. Quadratic cost and efficient variants
            9. Interpretability of attention maps
            10. Attention in vision and audio
        6. Transformers and encoder-decoder architectures
            1. Pure encoder (BERT-like)
            2. Pure decoder (GPT-like)
            3. Encoder-decoder (T5, modern seq2seq)
            4. Positional encoding
            5. Layer normalization
            6. Attention masks and context control
            7. Completion and translation tasks
            8. Scaling laws and model size
            9. Fine-tuning vs prompting
            10. Context window limitations
        7. Generative models (autoencoders, GANs, diffusion models)
            1. Classical autoencoder (reconstruction)
            2. Variational autoencoder (VAE)
            3. Continuous latent space
            4. GANs: generator vs discriminator
            5. Training instability in GANs
            6. Forward and reverse diffusion (denoising diffusion)
            7. Style control and conditioning
            8. Image and audio generation
            9. Deepfakes and ethics of generation
            10. Generative quality metrics (FID, IS)
        8. Multimodal models (image-text, audio-text, sensor fusion)
            1. Alignment between modalities (CLIP-style)
            2. Shared representations between text and image
            3. Audio-text and neural ASR
            4. Video + text + temporal context
            5. Sensor fusion (image + LiDAR)
            6. Multimodal contrastive learning
            7. Grounding in the physical world
            8. Capturing situational context
            9. Modal bias limitations
            10. Applications in robotics and autonomous perception

    9. Transfer learning, self-supervision and foundational models
        1. Classical transfer learning (pretrain and adapt)
            1. Full fine-tuning vs frozen layers
            2. Reuse of visual features
            3. Adapting text models to specific domains
            4. Reuse on small datasets
            5. Catastrophic forgetting when over-adapting
            6. Selection of cutoff layer
            7. Adapting the output (head) to a new task
            8. Data required vs model size curve
            9. Overfitting risks in niche domains
            10. Metrics to validate successful transfer
        2. Self-supervised learning (contrastive, masked, next-part prediction)
            1. Pretext tasks without human labels
            2. Masked language modeling
            3. Contrastive learning (SimCLR, InfoNCE)
            4. Predict-the-next-token
            5. Bootstrap without explicit negatives
            6. Unsupervised pretraining in vision
            7. Representations invariant to augmentations
            8. Reducing labeling cost
            9. Generalization to multiple downstream tasks
            10. Limitations due to corpus biases
        3. Foundational models and LLMs as generalist bases
            1. Scaling parameters and data
            2. Emergent capabilities
            3. In-context learning
            4. Chain-of-thought reasoning (high-level)
            5. Use as a general semantic engine
            6. Adaptation to multiple tasks without retraining
            7. Risks of hallucination
            8. Risks of leaking sensitive training data
            9. Dependence on large infrastructure
            10. Impact on product development cycles
        4. Efficient fine-tuning (LoRA, adapters, distillation)
            1. LoRA and low-rank updates in attention matrices
            2. Adapters as insertable layers
            3. Few-parameter updates (PEFT)
            4. Teacher-student distillation
            5. Compressing large models to lightweight ones
            6. Reduced inference cost
            7. Fast adaptation per client / vertical
            8. Frequent retraining with low compute
            9. Preserving base knowledge
            10. Risks of quality degradation
        5. Continual learning and catastrophic forgetting
            1. Catastrophic forgetting in sequential adaptation
            2. Regularization to retain prior knowledge
            3. Rehearsal and episodic memory
            4. Parameter-importance based methods
            5. Incremental domain adaptation
            6. Lifelong learning
            7. User-personalizable learning
            8. Control of semantic drift
            9. Temporal bias risks
            10. Metrics to measure retention vs adaptation

    10. Natural language, retrieval-augmented systems and agents
        1. Text representations (TF-IDF, embeddings)
            1. Bag-of-words and term counts
            2. TF-IDF as relevance weighting
            3. Dense word embeddings (word2vec, GloVe)
            4. Subword embeddings
            5. Contextual embeddings (transformers)
            6. Semantic spaces and cosine similarity
            7. Dimensionality reduction in text
            8. Synonym / semantic relation detection
            9. Limitations with polysemy
            10. Linguistic biases in embeddings
        2. Language models (n-grams, RNNs, Transformers)
            1. n-gram models and conditional probability
            2. Smoothing in n-grams
            3. Recurrent models for text
            4. Attention for long sequences
            5. Autoregressive transformers
            6. Masked models like BERT
            7. Perplexity as quality metric
            8. Generative models vs classifiers
            9. Style / tone control
            10. LM training costs
        3. Large language models (LLMs) and basic alignment
            1. Instruction tuning and human feedback
            2. RLHF (reinforcement learning from human feedback) overview
            3. Output safety and filtering
            4. Mitigating toxicity and bias
            5. Institutional / compliance tone control
            6. Controlling hallucinations
            7. Use as specialized internal assistant
            8. Risk of leaking confidential information
            9. Qualitative vs quantitative evaluation
            10. Human panel evaluation
        4. Domain adaptation and instruction fine-tuning
            1. Specialization to a vertical (legal, health, finance)
            2. Adapting technical vocabulary
            3. Adjusting output style and format
            4. Incorporating internal policies
            5. Injecting proprietary documentation
            6. Controlling tone for clients
            7. Personalization by user segment
            8. Mitigating internal contradictions
            9. Evaluation with domain data
            10. Legal risks with sensitive data
        5. Summarization, QA, NER and information extraction
            1. Extractive vs abstractive summarization
            2. Factual question answering
            3. Open-domain vs corpus-restricted QA
            4. Named entity recognition (NER)
            5. Relation extraction (RE)
            6. Event extraction
            7. Intent classification
            8. Sentiment / toxicity detection
            9. Factual accuracy evaluation
            10. Use in operational automation
        6. Retrieval-augmented generation (semantic search, RAG)
            1. Vector indexing
            2. Semantic similarity
            3. Retrieving relevant context
            4. Injecting context into the prompt
            5. Grounding in internal data
            6. Updating without retraining the base model
            7. Controlling hallucination via retrieved evidence
            8. Privacy and access control to the corpus
            9. Retrieval latency vs response latency
            10. Traceability and citability of answers
        7. Orchestrating agents that use external tools (tool-use)
            1. LLM as high-level planner
            2. Calling external APIs
            3. Step-by-step reasoning conditioned by feedback
            4. Iterative information retrieval
            5. Autonomous actions with human confirmation
            6. Routing queries to the right tool
            7. Short-term memory of the agent
            8. Long-term memory of the agent
            9. Traceability of agent decisions
            10. Risks of unauthorized actions
        8. Safety and hallucination
            1. Factual hallucination
            2. Confidently fabricated responses
            3. Malicious prompt injection
            4. Jailbreaks and extraction of internal instructions
            5. Filtering sensitive outputs
            6. Compliance controls in regulated environments
            7. Scope limitation of the agent
            8. Reducing leakage of internal data
            9. Output safety metrics
            10. Continuous human auditing

    11. Computer vision and graph learning
        1. Image augmentation and preprocessing
            1. Pixel normalization and standardization
            2. Geometric augmentation (rotate, scale, crop)
            3. Photometric augmentation (brightness, contrast, noise)
            4. Domain-specific augmentation (industrial defects, weather)
            5. Class balancing via augmentation
            6. Consistent resizing and cropping
            7. Cleaning corrupt data / dubious labels
            8. Preprocessing for real-time inference
            9. Aggressive data augmentation vs model stability
            10. Standardization of preprocessing pipelines
        2. Classification, detection and segmentation
            1. Full-image classification
            2. Localization with bounding boxes
            3. Object detection (one-stage vs two-stage)
            4. Semantic segmentation
            5. Instance and panoptic segmentation
            6. Metrics like IoU / mAP
            7. Handling rare classes and small objects
            8. Real-time inference (cameras, mobile)
            9. Use in industrial vision / inspection
            10. Persistent object tracking
        3. 3D vision, point clouds and video tracking
            1. Point clouds (LiDAR, depth cameras)
            2. Approximate 3D reconstruction
            3. 3D pose estimation
            4. Optical flow and motion estimation
            5. Multi-object tracking in video
            6. Perception for autonomous driving / robotics
            7. Voxel vs point-based representations
            8. Sensor noise cleaning
            9. Frame and sensor synchronization
            10. Temporal stability metrics
        4. Sensor fusion (image + LiDAR)
            1. Calibration between sensors
            2. Multi-sensor temporal synchronization
            3. Projecting point clouds into image space
            4. Late fusion vs early fusion
            5. Shared multimodal representations
            6. Handling missing / degraded sensors
            7. Robust detection in adverse conditions (night, rain)
            8. Redundancy for safety
            9. Use in mobile robotics and autonomous vehicles
            10. Edge compute cost
        5. Graph representations (nodes, edges, attributes)
            1. Homogeneous and heterogeneous graphs
            2. Directed vs undirected graphs
            3. Node and edge attributes
            4. Subgraphs and k-hop neighborhoods
            5. Paths, cycles and connectivity
            6. Initial node embeddings
            7. Dynamic / temporal graphs
            8. Degree imbalance and hubs
            9. Structural normalization
            10. Cost of sampling large neighborhoods
        6. Graph neural networks (message passing, GCN, GAT)
            1. Message passing neural networks
            2. GCN (Graph Convolutional Networks)
            3. GAT (Graph Attention Networks)
            4. Graph pooling
            5. Global graph readout
            6. Graphs induced by similarity
            7. Spatio-temporal graphs
            8. Scalability to giant graphs
            9. Over-smoothing in deep layers
            10. Structural regularization
        7. Applications in chemistry, fraud, social networks and recommendation
            1. Molecular property prediction
            2. Drug discovery
            3. Transactional fraud detection
            4. Community and collusion detection
            5. User-item graph-based recommendation
            6. Social influence analysis
            7. Moderation and platform safety
            8. Bot and coordinated activity detection
            9. Critical connectivity analysis (infrastructure)
            10. Network-contextualized ranking

    12. Advanced time series and signals
        1. Seasonality, trend and decomposition
            1. Additive vs multiplicative decomposition
            2. Long-term trend
            3. Fixed and moving seasonal effects
            4. Calendar effects (weekends, holidays)
            5. Structural changes and breaks
            6. Saturation / maturity signals
            7. Seasonal adjustment before modeling
            8. Trend reversal (cycles)
            9. Business interpretation of seasonality
            10. Comparison between segments or regions
        2. Probabilistic and multi-horizon forecasting
            1. Point prediction vs full predictive distribution
            2. Prediction intervals and quantiles
            3. Forecasts at multiple horizons (1h, 24h, 7d)
            4. Hierarchical forecasting (category → product)
            5. Aggregatable forecasts by region / channel
            6. Penalties for overestimation vs underestimation
            7. Metrics (MAPE, sMAPE, MASE)
            8. Model ensembles for forecasting
            9. Rolling-origin temporal validation
            10. Financial evaluation of forecast error
        3. Real-time anomaly detection
            1. Context-dependent dynamic thresholds
            2. Prediction + residual-based models
            3. Correlated multivariate signals
            4. Early alerts vs operational noise
            5. Human-in-the-loop confirmation
            6. Prioritization by impact
            7. Reducing false alarms
            8. Persistence vs isolated spikes
            9. Expected seasonal anomalies
            10. Continuous labeling and audit of rare events
        4. Temporal transformers and multivariate sequential prediction
            1. Attention on long series
            2. Handling multiple variables simultaneously
            3. Temporal / positional encoding for continuous time
            4. Multi-horizon prediction with a single model
            5. Capturing complex nonlinear dependencies
            6. Handling missing data in streams
            7. Regularization for low-history tasks
            8. Transfer between similar series
            9. Real-time inference cost
            10. Interpretability of temporal attention
        5. Operational monitoring in streaming (alerts, detection SLA)
            1. Live data ingestion
            2. Online feature extraction
            3. Low-latency inference
            4. Automatic alerts and escalation
            5. Detection and response SLAs
            6. Incident traceability
            7. Versioning rules / production models
            8. Continuous retraining with recent data
            9. Near-real-time business metrics
            10. Integration with dashboards and on-call

    13. Reinforcement learning and control
        1. MDP formulation (states, actions, rewards)
            1. State, observation and partial observability
            2. Policy as decision function
            3. Discounted return
            4. Sparse vs dense rewards
            5. Finite vs infinite horizon
            6. Exploration vs exploitation
            7. Deterministic vs stochastic
            8. Simulated vs real environments
            9. Off-policy vs on-policy methods
            10. Reward engineering
        2. Tabular methods (Q-Learning, SARSA)
            1. Q-table as action-value approximation
            2. Incremental Q updates
            3. ε-greedy exploration
            4. SARSA vs Q-Learning
            5. Convergence in small spaces
            6. Limitations in large/continuous spaces
            7. Speed vs exploration trade-offs
            8. ε decay variants
            9. Noise in value estimation
            10. Classic problems like gridworld
        3. Deep Q-Networks (DQN)
            1. Neural approximation of Q-value
            2. Replay buffer
            3. Target network
            4. Training stability
            5. Generalization between similar states
            6. Discrete vs continuous actions
            7. DQN extensions (Double DQN, Dueling DQN)
            8. Sample efficiency
            9. Scaling to complex environments (games, control)
            10. Risks of overfitting to the simulator
        4. Policy Gradient and actor-critic (PPO)
            1. Optimize the policy directly
            2. Gradient of expected return
            3. High variance of the estimator
            4. Baselines and variance reduction
            5. Actor-critic (actor updates policy, critic evaluates)
            6. PPO (Proximal Policy Optimization)
            7. Update constraints for stability
            8. Continuous control and continuous actions
            9. Sample efficiency in physical tasks
            10. Robustness to small perturbations
        5. Continuous control and robotics
            1. Continuous action spaces
            2. Fine motor control
            3. Reactive policies vs planning
            4. Imitation learning / behavioral cloning
            5. Sim2Real (simulator → real world transfer)
            6. Physical safety and force limits
            7. Noisy sensory feedback
            8. Latency and real-time control
            9. Catastrophic failures and safe fallback
            10. Energy optimization and mechanical efficiency
        6. Multi-agent and coordination
            1. Zero-sum vs cooperative games
            2. Independent vs coordinated policies
            3. Explicit communication between agents
            4. Stable equilibria and strategies
            5. Policy transfer between agents
            6. Scaling with agent count
            7. Misaligned incentives (collusion, abuse)
            8. Multi-agent credit assignment
            9. Emergence of specialized roles
            10. Applications in logistics and distributed systems
        7. Safety, controlled exploration and alignment in RL
            1. Safe exploration in physical environments
            2. Hard constraints (safety constraints)
            3. Penalty for dangerous actions
            4. Protection against poorly-specified rewards
            5. Catastrophic actions and kill-switches
            6. Interpretability of learned policies
            7. Human-in-the-loop supervision
            8. Specification of aligned objectives
            9. Ethical failures in simulated social environments
            10. Transfer to real regulated environments

    14. Recommendation systems and personalization
        1. User segmentation and applied clustering
            1. Demographic segmentation
            2. Segmentation by usage behavior
            3. Segmentation by economic value
            4. Segmentation by risk / churn
            5. Classical clustering (k-means) applied to users
            6. Temporal cohorts
            7. Dynamic micro-segmentation
            8. Periodic vs online updating
            9. Privacy and indirect identification
            10. Use for campaigns and targeting
        2. Collaborative filtering and matrix factorization
            1. User–item matrix
            2. Filling missing entries
            3. Decomposition into latent factors
            4. SVD and implicit variants
            5. Cold start for new users
            6. Cold start for new items
            7. Popularity biases
            8. Regularization of factors
            9. Evaluation for top-N recommendations
            10. Scaling to large catalogs
        3. Content-based models and contextual signals
            1. Item profiling (tags, text, metadata)
            2. User profiling (history, preferences)
            3. Temporal context (time of day, seasonality)
            4. Spatial / geographic context
            5. Device / channel context
            6. Contextualized recommendation
            7. Attribute-based explainability
            8. Exposure bias (what you show conditions what is clicked)
            9. Situation-aware personalization
            10. Risks of filter bubbles
        4. Ranking, CTR prediction and top-K metrics
            1. Click-through rate prediction models (CTR)
            2. Relevance scoring
            3. Ordering results as a ranking problem
            4. Top-K metrics (recall@K, precision@K)
            5. Diversity vs pure precision
            6. Serendipity and novelty
            7. Calibration of click probability
            8. Positional bias and correction
            9. Learning from implicit feedback
            10. Online vs offline evaluation in recommendation
        5. Sequential and real-time recommenders
            1. Modeling the sequence of interactions
            2. RNN / Transformers for user sessions
            3. Next-item prediction
            4. Live contextual recommendation
            5. Extreme latency (ms-level)
            6. Continuous updating of user embeddings
            7. Multi-armed bandits for exploration
            8. Protection against self-reinforcing loops
            9. Fraudulent behavior detection
            10. Scaling to massive catalogs and fast turnover
        6. Product-level dynamic personalization
            1. Dynamic content per user
            2. UI reordering / personalized feed
            3. Personalized offers / pricing
            4. Prioritization of alerts / notifications
            5. Adaptive experiences (intelligent onboarding)
            6. Contextual recommendation across surfaces (web, mobile, email)
            7. User controls (opt-out, manual tuning)
            8. Regulatory risks in personalization
            9. Impact on retention and conversion metrics
            10. Bias and differential treatment auditing
        7. Interpretability and explainability for business teams
            1. “We recommend this because…”
            2. Highlight relevant item attributes
            3. Regulatory transparency (why I received this offer)
            4. Explain ranking to non-technical stakeholders
            5. Health metrics of the recommendation system
            6. Fairness across user segments
            7. Audit of self-reinforcement of content
            8. Reputational risk from poor suggestions
            9. Human controls over critical recommendations
            10. Documentation and accountability of the recommender engine

    15. Data engineering and data platforms
        1. Business-oriented analytical modeling
            1. Identification of key business metrics
            2. Data models centered on real questions
            3. Single source of truth definition
            4. Operational vs strategic KPIs
            5. Derived metrics vs fundamental metrics
            6. Traceability from metric to source table
            7. Design with non-technical stakeholders in mind
            8. Semantic versioning of metrics
            9. Alignment between analytics and financial reporting
            10. Governance of metric definitions
        2. Dimensional modeling (facts and dimensions)
            1. Fact tables (transactions, events)
            2. Dimension tables (who, what, where)
            3. Slowly changing dimensions (SCD)
            4. Granularity of facts
            5. Additive, semi-additive and non-additive metrics
            6. Conformed dimensions across domains
            7. Standard join patterns
            8. Minimize duplication in data marts
            9. Documentation of business keys
            10. Impact of dimensional modeling on BI performance
        3. Data warehouse, data lakes and lakehouses
            1. Structured warehouse vs raw repository
            2. ETL to warehouse vs ELT in lake
            3. Lakehouse as a unified layer
            4. Governed tables vs “raw” zones
            5. Schema management in raw zones
            6. Storage costs vs query costs
            7. Security and access by layer
            8. Analytical use vs ML use
            9. Central catalog of production datasets
            10. Historical evolution: warehouse → lake → lakehouse
        4. Columnar formats and analytics-oriented storage
            1. Columnar vs row-oriented
            2. Formats like Parquet / ORC
            3. Compression and partitioning
            4. Column pruning for analytical queries
            5. Z-Ordering / physical clustering
            6. Cold vs hot storage
            7. Cost/latency trade-offs for access
            8. Secondary indexing
            9. Time-partitioned tables
            10. Impact on ad-hoc exploration costs
        5. Data catalog, lineage and discoverability
            1. Technical and business metadata
            2. Who uses which table
            3. Column-level lineage
            4. Semantic search for datasets
            5. Sensitivity classification
            6. Owners and data stewards
            7. Declared vs measured quality
            8. Deprecation and controlled archiving
            9. Access audit
            10. Self-service discovery for analysts
        6. Access governance and permission control
            1. Role-based access control
            2. Masking of sensitive columns
            3. Segmentation by domain/business area
            4. Separation between environments (dev / prod)
            5. Auditing of sensitive queries
            6. Temporary / Just-In-Time access
            7. Automated revocation
            8. Compliance records
            9. Controlled internal data sharing
            10. External data sharing (partners, customers)
        7. Retention, archiving and data lifecycle
            1. Legal retention policies
            2. Secure deletion / right to be forgotten
            3. Cold/historical vs active data
            4. Low-cost archival layers
            5. Historical snapshots for audit
            6. Frozen versions for reproducibility
            7. Cleaning of obsolete data
            8. Regulatory risks from over-retention
            9. Long-term storage cost impact
            10. Restore strategies after incidents
        8. Integration with BI tools and executive dashboards
            1. Operational vs executive dashboards
            2. Single, consistent metric across dashboards
            3. Access control to sensitive dashboards
            4. Automatic alerts and thresholds
            5. Dashboard versioning
            6. Catalog of official reports
            7. Self-service for analysts
            8. Visual storytelling for directors
            9. Regulatory / audit dashboards
            10. Near-real-time business metrics
        9. Exposing data as a service (analytical APIs)
            1. APIs for internal analytical consumption
            2. Avoid heavy client-side filtering
            3. Precomputed aggregations
            4. Access control by token / role
            5. Quotas and rate limiting
            6. Endpoint versioning
            7. Contract stability of responses
            8. Usage auditing of APIs
            9. Response latency targets
            10. Exposing features to online ML systems
        10. Reproducible, declarative ETL / ELT pipelines
            1. Extraction from heterogeneous sources
            2. Deterministic transformations
            3. Declarative vs imperative scripting
            4. Infrastructure-as-code for pipelines
            5. Version control of pipelines
            6. Idempotent tasks
            7. Dependency management between steps
            8. Rollback of defective pipelines
            9. Execution auditing
            10. Automated testing of transformations
        11. Large-scale batch processing
            1. Nightly / periodic ingestion
            2. Cutoff windows (close of business)
            3. Historical reprocessing
            4. Cost control in heavy batch jobs
            5. Intermediate failures and retries
            6. Horizontal parallelization
            7. Ordering of dependent jobs
            8. SLA for batch data availability
            9. Integrity validation at job end
            10. Publish results ready for consumption
        12. Streaming processing and continuous data flows
            1. Real-time ingestion (event buses)
            2. Stream transformations
            3. Fixed / sliding window computation
            4. Stateful operators in streaming
            5. Deduplication in real time
            6. Exactly-once vs at-least-once guarantees
            7. End-to-end latency
            8. Immediate alerts and early detection
            9. Enrichment with reference data
            10. Publishing to live dashboards
        13. Orchestration and flow scheduling
            1. Dependency DAGs
            2. Declarative schedulers
            3. Retries and exponential backoff
            4. Execution priorities
            5. Failure alerts
            6. Execution history auditing
            7. Controlled deploy of new flow versions
            8. Separation of environments (dev / staging / prod)
            9. Governance of who can edit what
            10. Horizontal scaling of workers
        14. Pipeline optimization and profiling
            1. Profiling costly steps
            2. I/O bottlenecks
            3. Optimization of expensive joins
            4. Reduce shuffle / data movement
            5. Prune unused columns
            6. Proper indexing / partitioning
            7. Reuse of intermediate cached results
            8. Costing per pipeline / job
            9. Alerts on performance degradation
            10. Compute budgeting per team
        15. Data quality tests, contracts and SLAs
            1. Schema tests (types, nullability)
            2. Range / valid-domain tests
            3. Uniqueness and key tests
            4. Minimum completeness tests
            5. Alerts on quality drops
            6. Data contracts between teams
            7. Freshness and availability SLAs
            8. Incompatible column versioning
            9. Breaking change management
            10. Weekly data health reports
        16. Data observability (freshness, completeness, anomalies)
            1. Ingestion latency monitoring
            2. Event arrival rate monitoring
            3. Detection of data gaps
            4. Statistical outlier detection on key metrics
            5. Trend-break alarms
            6. Health dashboard for critical tables
            7. Unexpected access auditing
            8. Alerts for PII in wrong places
            9. Data incident management
            10. Postmortems and corrective actions
        17. Data mesh and data domains
            1. Data domain as an internal “product”
            2. Distributed ownership by business team
            3. Common quality and access standards
            4. Data SLAs per domain
            5. Federated discoverability
            6. Interoperability between domains
            7. Federated vs centralized governance
            8. Reduce bottlenecks from a central data team
            9. Organizational scaling and autonomy
            10. Risk of metric inconsistency across domains

    16. Big Data and distributed computing
        1. The concept of big data (volume, velocity, variety, veracity, value)
            1. Volume: massive datasets
            2. Velocity: near real-time ingestion
            3. Variety: heterogeneous sources
            4. Veracity: noisy and questionable quality
            5. Value: actual economic usefulness
            6. Structured data vs raw logs
            7. Limitations of traditional tools
            8. Latency vs cost trade-offs
            9. Cases that truly require big data
            10. Anti-patterns of “big data for fashion”
        2. Distributed data architectures
            1. Horizontally scalable clusters
            2. Parallel processing map/shuffle/reduce
            3. Compute/storage separation
            4. Elasticity on demand
            5. Fault tolerance and replication
            6. Load balancing
            7. High availability
            8. Eventual vs strong consistency
            9. Multi-region scaling
            10. Costing of shared infrastructure
        3. Distributed file systems
            1. Replicated block storage
            2. Centralized vs distributed metadata
            3. Massive concurrent access
            4. Node fault tolerance
            5. Data locality and task affinity
            6. Storage hierarchies (SSD/HDD/object)
            7. Integration with compute engines
            8. Evolution from HDFS to object storage
            9. Permission control in distributed storage
            10. Secure deletion and regulatory compliance
        4. Distributed query engines and distributed SQL
            1. Parallel query processing
            2. Pushdown of filters/projections
            3. Execution plan optimization
            4. Distributed joins and shuffle
            5. Intermediate caching
            6. Cost-based optimization
            7. Federated query across multiple sources
            8. Latency vs throughput
            9. Workload isolation
            10. Multitenancy and resource fairness
        5. Event buses and messaging queues
            1. Publish/subscribe
            2. Partitioning by key
            3. Relative ordering per partition
            4. Retention by time window
            5. Reprocessing event history
            6. Backpressure and flow control
            7. Delivery guarantees (at-most-once, at-least-once, exactly-once)
            8. Consumer lag monitoring
            9. Isolation of noisy producers
            10. Integration with streaming pipelines
        6. Real-time processing for operational decisions
            1. Enrich incoming events with context
            2. Live scoring with ML models
            3. Automatic operational alerts
            4. Early fraud / intrusion detection
            5. Automatic reaction (block, throttle)
            6. SLA monitoring for operations
            7. Live dashboards for operations shifts
            8. Auditable logging of online decisions
            9. Low-latency systems (<100 ms)
            10. Precision vs immediacy trade-off
        7. Integration of product telemetry and business metrics at scale
            1. Instrumentation of massive usage events
            2. Reliable client-side delivery
            3. Align product data with financial data
            4. Enrichment with user/account attributes
            5. Live product health metrics
            6. Correlate technical performance with business metrics
            7. Detect regressions after deploys
            8. Alerts on engagement drops
            9. Unified visibility for product/data/operations
            10. Prioritize incidents by economic impact

    17. Model deployment (MLOps / LLMOps)
        1. Model lifecycle: training, validation, deployment, rollback
            1. Reproducible training
            2. Pre-deployment validation
            3. Publication to an inference environment
            4. Canary release / gradual rollout
            5. Safe and fast rollback
            6. Versioning of deployed models
            7. Environment management (dev/staging/prod)
            8. Dependency and library control
            9. Documentation of model changes
            10. Full traceability of which model made which decision
        2. Experiment tracking and artifact versioning
            1. Record hyperparameters and metrics
            2. Compare runs
            3. Record datasets used
            4. Version training code
            5. Model checkpoints
            6. Preprocessing artifacts
            7. Retention of obsolete models
            8. Scientific reproducibility / audit
            9. Signing and certification of approved models
            10. Access control to sensitive models
        3. Feature stores management
            1. Single reusable feature definitions
            2. Batch vs online computation
            3. Train/serve consistency (offline vs online)
            4. Feature versioning
            5. Catalog of approved features
            6. Access control for sensitive features
            7. Semantic documentation of each feature
            8. Drift monitoring per feature
            9. Read latency in production
            10. Reuse across teams/models
        4. Serving models in batch and real time
            1. Scheduled batch scoring
            2. On-demand scoring (online inference)
            3. Prediction endpoints
            4. Latency targets per use case
            5. Horizontal scaling / autoscaling
            6. Fault tolerance of the service
            7. Versioning and routing of models
            8. Request/response logging
            9. Security and access control for inference
            10. Cost per prediction / per request
        5. Low-latency inference and cost per prediction
            1. Model quantization
            2. Compilation / optimization for specific hardware
            3. Internal batching for throughput
            4. Caching frequent results
            5. Edge / on-device deployment
            6. Balance between precision and latency
            7. Cloud vs on-prem cost trade-offs
            8. Timeouts and controlled degradation
            9. Elasticity for traffic spikes
            10. Prioritization policies for critical requests
        6. Monitoring drift and model degradation
            1. Input data drift
            2. Prediction distribution drift
            3. Input→output relationship drift (concept drift)
            4. Live performance metrics
            5. Threshold-based alarms
            6. Subpopulation evaluation
            7. Fairness metrics in production
            8. On-call alerts for model incidents
            9. Incident logging and RCA
            10. Response and containment plan
        7. Continuous retraining and feedback loops
            1. Automatic collection of newly labeled data
            2. Curation of hard examples
            3. Scheduled vs on-demand retraining
            4. Automated post-retraining validation
            5. Human approval before redeploy
            6. Version management of successive models
            7. Avoid drift toward unwanted biases
            8. Clean toxic / adversarial data
            9. Documentation of behavior changes
            10. Impact evaluation after redeploy
        8. Pre-rollout testing and safety validation
            1. Unit tests for preprocessing
            2. Feature consistency tests
            3. Numerical stability tests
            4. Load/performance tests
            5. Fairness / bias tests
            6. “Do not break key metrics” tests
            7. Evaluation on synthetic adversarial data
            8. Red teaming of prompts / language models
            9. Legal / compliance validation
            10. Approval signing before production
        9. A/B testing in production and impact measurement
            1. Traffic splitting between models
            2. Primary success metric
            3. Live experiment monitoring
            4. Detect side effects
            5. Spillover between variants
            6. Minimum reliable duration
            7. Adopt / rollback decision
            8. Experiment result documentation
            9. Communicate impact to the business
            10. Reuse learnings for future launches
        10. Operational observability (latency, throughput, errors)
            1. Infrastructure metrics (CPU, memory, GPU)
            2. Latency p50 / p95 / p99
            3. Sustained throughput vs peak
            4. Error / timeout rates
            5. Queue saturation
            6. External dependency failures
            7. Real-time alerts
            8. On-call dashboards
            9. Historical logging for audits
            10. Prioritization of critical incidents
        11. SLOs and SLAs for inference services
            1. Technical SLO definition (latency, uptime)
            2. Contractual SLA definition
            3. Alerts when SLOs are violated
            4. Penalties for SLA breaches
            5. Different SLOs for internal vs external clients
            6. Isolation of critical workloads
            7. Contingency plans
            8. Graceful degradation and backoff
            9. Formal operational escalation
            10. Executive compliance reporting
        12. Documentation and model cards
            1. Description of model purpose
            2. Training dataset(s) and their biases
            3. Populations where it works well / poorly
            4. Declared performance metrics
            5. Known risks and limitations
            6. Ethical and legal considerations
            7. Post-deployment monitoring requirements
            8. Required human controls
            9. Version history of the model
            10. Responsible contact / clear ownership

    18. Scaling, efficiency and edge deployment
        1. Distributed training (data parallelism, model parallelism, sharding)
            1. Data parallelism vs model parallelism
            2. Sharding parameters and activations
            3. All-reduce and gradient synchronization
            4. Decoupling communication / compute
            5. Training across multiple GPUs / nodes
            6. Worker load balancing
            7. Fault-tolerant distributed checkpointing
            8. Elastic training (resources joining/leaving)
            9. Batch size scaling strategies
            10. Network costs as a bottleneck
        2. Mixture of experts and scalable architectures
            1. Sparse mixture-of-experts (MoE)
            2. Conditional routing of tokens / inputs
            3. Scale parameters without scaling compute per token
            4. Load balancing between experts
            5. Structured sparsity
            6. Domain specialization of experts
            7. Expert collapse and mitigations
            8. MoE in vision, text and multimodal models
            9. Distributed inference with MoE
            10. Cost impact of serving giant LLMs
        3. Quantization, pruning and model compression
            1. Lower-precision quantization (fp16, int8, int4)
            2. Structured and unstructured pruning
            3. Pruning channels / less-useful neurons
            4. Low-rank weight factorization
            5. Distillation (teacher-student)
            6. Minimize memory in inference
            7. Minimize latency on edge devices
            8. Compression vs quality trade-offs
            9. Post-training vs in-training techniques
            10. Fine-tuning after compression
        4. Compilers and runtimes optimized (GPU / TPU / ASIC)
            1. Graph compilers and computational graph optimization
            2. Operator fusion (op fusion)
            3. Reordering operations for memory locality
            4. Hardware-specific kernel tuning
            5. Specialized accelerators (TPU / NPU / ASIC)
            6. Heterogeneous CPU+GPU scheduling
            7. Ahead-of-time vs just-in-time compilation
            8. Auto-tuning based on profiling
            9. Memory bottlenecks vs FLOP bottlenecks
            10. Portability across hardware vendors
        5. Edge inference (edge AI, TinyML, microcontrollers)
            1. Ultra-lightweight models
            2. Extremely limited memory (KB/MB)
            3. Hard real-time latency
            4. Offline execution without network
            5. Minimum energy consumption (battery / IoT)
            6. On-device security and privacy
            7. Inference in industrial sensors / robots
            8. Remote model updates in the field
            9. Local detection of critical events
            10. Validation and certification in regulated environments
        6. Memory, energy and hard-latency limitations
            1. Energy budget per inference
            2. Maximum tolerable latency per application
            3. Maximum allowed model size
            4. Thermal management in embedded hardware
            5. Precision vs energy consumption trade-offs
            6. Deterministic inference and guaranteed timing
            7. Controlled degradation under overload
            8. Prioritization of critical edge tasks
            9. Local caching of frequent results
            10. Trade-offs between server-side and local decisioning
        7. Energy costs and sustainability of AI compute
            1. Energy footprint of training large models
            2. Cooling and data center costs
            3. Use efficient hardware vs generic hardware
            4. Reuse models vs training from scratch
            5. Compression to reduce inference energy at scale
            6. Balance batch offline vs online scoring
            7. Energy-efficiency metrics per prediction
            8. Environmental reporting and regulations
            9. Economic incentives for smaller models
            10. Responsible design of intensive workloads

    19. Ética, seguridad, privacidad y gobernanza
        1. Privacidad de datos personales y minimización de uso
            1. Minimización de retención de PII
            2. Principio de “necesidad de conocer”
            3. Anonimización y seudonimización
            4. Riesgo de reidentificación
            5. Separación de datos personales y operacionales
            6. Propósito declarado vs uso real
            7. Transparencia frente al usuario
            8. Derecho al olvido y borrado selectivo
            9. Restricciones de uso secundario de datos
            10. Auditorías de acceso
        2. Privacidad diferencial y aprendizaje federado
            1. Ruido calibrado a nivel estadístico
            2. Garantías formales de privacidad
            3. Ataques de reconstrucción de datos
            4. Membership inference attacks
            5. Entrenamiento en el dispositivo del usuario
            6. Agregación segura de gradientes
            7. No compartir datos crudos entre nodos
            8. Riesgos de fuga mediante el modelo
            9. Trade-off privacidad / performance
            10. Uso en salud y finanzas
        3. Gobernanza, trazabilidad y auditoría de datos y modelos
            1. Linaje de datos crítico (origen → transformación → decisión)
            2. Quién entrenó el modelo y con qué datos
            3. Historial de versiones del modelo en producción
            4. Registro de cambios de features
            5. Auditoría externa regulatoria
            6. Auditoría interna de cumplimiento
            7. Evidencia para peritaje legal
            8. Firma / certificación de modelos aprobados
            9. Control de acceso basado en rol
            10. Responsables claros (“owner” del modelo)
        4. Cumplimiento normativo y marcos legales
            1. Regulaciones sectoriales (finanzas, salud, etc.)
            2. Restricciones de uso de datos sensibles
            3. Reportabilidad obligatoria de decisiones automáticas
            4. Explicabilidad legalmente exigible
            5. Limitaciones al profiling individual
            6. Retención mínima / máxima legal
            7. Transferencia internacional de datos
            8. Consentimiento informado vs interés legítimo
            9. Sanciones por incumplimiento
            10. Actualización continua por cambios regulatorios
        5. Control de acceso, clasificación de datos y dominios de seguridad
            1. Clasificación por sensibilidad
            2. Segmentación de entornos (prod vs analítica)
            3. Enmascaramiento dinámico de campos sensibles
            4. Accesos temporales / justificados
            5. Registro de accesos privilegiados
            6. Hardening de entornos de inferencia
            7. Gestión de llaves y secretos
            8. Aislamiento de workloads regulados
            9. Cumplimiento de políticas internas
            10. Detección de abuso interno
        6. Sesgos algorítmicos, equidad y no discriminación
            1. Bias en datos históricos
            2. Variables proxy de atributos sensibles
            3. Métricas de fairness por subgrupos
            4. Disparidad de falsos positivos/negativos
            5. Impacto distributivo en poblaciones vulnerables
            6. Auditoría periódica de sesgos
            7. Mitigación de sesgos en entrenamiento
            8. Mitigación en post-procesamiento
            9. Obligación ética de corrección
            10. Documentación del riesgo residual
        7. Explicabilidad y justificabilidad de decisiones automatizadas
            1. Explicar por qué se tomó una decisión
            2. Explicabilidad global vs local
            3. Explicaciones contrafactuales (“qué habría pasado si…”)
            4. Interpretabilidad para auditores/autoridades
            5. Interpretabilidad para usuarios finales
            6. Límites técnicos de interpretabilidad en deep learning
            7. Transparencia de criterios de scoring
            8. Riesgos de revelar demasiado (gaming del sistema)
            9. Trazabilidad de la decisión hasta el input
            10. Registro accesible para defensa legal
        8. Riesgo reputacional y deepfakes / desinformación sintética
            1. Generación de contenido engañoso
            2. Suplantación de identidad
            3. Manipulación de audio/video
            4. Atribución de autoría falsa
            5. Detección de contenido sintético
            6. Watermarking y firmas de procedencia
            7. Moderación de contenido automatizada
            8. Riesgo de viralización y daño reputacional
            9. Uso malicioso interno vs externo
            10. Políticas de respuesta a incidentes públicos
        9. Transparencia frente a usuarios y stakeholders
            1. Declarar uso de IA en decisiones críticas
            2. Explicar límites y posibles errores
            3. Canales de apelación humana
            4. Control del usuario sobre sus datos
            5. Visibilidad de métricas de calidad
            6. Disclosure ante clientes corporativos
            7. Comunicación de incidentes de datos
            8. Lenguaje claro no técnico
            9. Requerimientos de confianza en sectores regulados
            10. Expectativas éticas de clientes y sociedad
        10. Reproducibilidad científica y versionado de datasets/modelos
            1. Versionado de datasets de entrenamiento
            2. Congelamiento de snapshots de datos
            3. Versionado de código y configuración
            4. Fijación de seeds y determinismo
            5. Documentación de ambiente de ejecución
            6. Comparación justa entre modelos
            7. Evidencia de replicabilidad
            8. Auditoría post-mortem de fallos
            9. Portabilidad entre entornos
            10. Conservación de experimentos históricos
        11. Gobernanza del ciclo de vida completo del dato y del modelo
            1. Flujo dato → feature → modelo → predicción → acción
            2. Dueños claros para cada etapa
            3. Políticas de aprobación en cada cambio
            4. Monitoreo continuo post-despliegue
            5. Evaluación de impacto social antes del lanzamiento
            6. Retiro responsable de modelos obsoletos
            7. Controles de rollback ético
            8. Gestión de deuda técnica y deuda ética
            9. Documentación para auditoría externa
            10. Apoyo ejecutivo / comité de riesgo
        12. Políticas internas de aprobación y revisión humana obligatoria
            1. Casos donde no se permite decisión 100% automática
            2. Umbrales que gatillan revisión humana
            3. Registro de intervenciones humanas
            4. Trazabilidad de overrides
            5. Revisión ética de nuevos casos de uso
            6. Revisión legal / compliance previa al despliegue
            7. Aprobación ejecutiva en casos críticos
            8. Revocación de modelos ante mal uso
            9. Mecanismos de denuncia interna
            10. Accountability final explícito
        13. Continuidad operativa y resiliencia ante fallos del modelo en producción
            1. Modos degradados seguros
            2. Fallback a reglas heurísticas
            3. Rollback inmediato a versión anterior
            4. Plan de contingencia ante ataque adversario
            5. Desconexión rápida ante comportamiento tóxico
            6. Alertas on-call 24/7 para servicios críticos
            7. Simulacros de desastre algorítmico
            8. Comunicación de incidentes a stakeholders
            9. Plan de remediación y mejora
            10. Gestión reputacional post-incidente

    20. Aplicaciones verticales y casos de uso
        1. Analítica de negocio y optimización operacional
            1. Medición de eficiencia operativa
            2. Identificación de cuellos de botella
            3. Priorización de iniciativas de mejora
            4. Scorecards y accountability interno
            5. Automatización de reporting operativo
            6. Alertas sobre SLAs rotos
            7. Optimización de pricing/promociones
            8. Predicción de demanda de capacidad interna
            9. Detección de ineficiencias de procesos
            10. Soporte de decisiones tácticas diarias
        2. Detección de fraude, scoring de riesgo y cumplimiento financiero
            1. Scoring crediticio
            2. Señales de comportamiento atípico
            3. Alertas de fraude en tiempo real
            4. Clasificación de transacciones sospechosas
            5. Modelos antifraude adaptativos
            6. Explicabilidad requerida por cumplimiento regulatorio
            7. Revisión humana de alertas de alto riesgo
            8. Prevención de lavado de dinero (AML)
            9. Auditoría y trazabilidad de decisiones de riesgo
            10. Balance falso positivo vs costo de fraude
        3. Personalización, recomendación y priorización de leads
            1. Lead scoring comercial
            2. Priorización automática de outreach
            3. Ofertas y mensajes personalizados
            4. Recomendación de producto / contenido
            5. Retención de usuarios en riesgo de churn
            6. Up-selling / cross-selling inteligente
            7. Secuencias de contacto multicanal
            8. Optimización de funnel de conversión
            9. Evaluación incremental (uplift en ventas)
            10. Riesgos éticos de segmentación agresiva
        4. Salud y biomedicina asistida por IA
            1. Ayuda al diagnóstico clínico asistido
            2. Análisis de imágenes médicas
            3. Alarmas tempranas en UCI
            4. Priorización de casos críticos
            5. Modelos de riesgo de rehospitalización
            6. Descubrimiento de fármacos y screening molecular
            7. Privacidad y datos altamente sensibles
            8. Validación clínica y regulación sanitaria
            9. Toma de decisión asistida, no autónoma
            10. Responsabilidad legal y ética del soporte de IA
        5. Retail, demanda y logística predictiva
            1. Forecast de demanda por tienda / SKU
            2. Optimización de inventario
            3. Prevención de quiebre de stock
            4. Optimización de reposición
            5. Ruteo de entrega y última milla
            6. Detección de fraude en devoluciones
            7. Segmentación de clientes por valor de vida útil
            8. Personalización de promociones
            9. Pricing dinámico según demanda
            10. Evaluación del impacto en margen
        6. Industria y mantenimiento predictivo (gemelos digitales)
            1. Sensores IoT industriales
            2. Modelos de fallo inminente
            3. Mantenimiento preventivo vs predictivo
            4. Gemelos digitales de equipos críticos
            5. Optimización energética de planta
            6. Seguridad industrial y fallos catastróficos
            7. Programación automática de mantención
            8. Priorización de alertas operativas
            9. Diagnóstico remoto en terreno
            10. Trazabilidad completa de eventos de falla
        7. Ciencia y simulación asistida por datos (clima, materiales, física)
            1. Modelado climático / pronóstico de variables ambientales
            2. Descubrimiento de nuevos materiales
            3. Modelos de dinámica molecular asistidos por ML
            4. Aceleración de simulaciones numéricas costosas
            5. Ajuste de parámetros físicos vía optimización bayesiana
            6. Fusión de datos experimentales + simulación
            7. Reducción de modelos complejos a emuladores rápidos
            8. Cuantificación de incertidumbre científica
            9. Reproducibilidad científica
            10. Uso ético en modelamiento de riesgo climático
        8. Agentes autónomos, robótica y control continuo
            1. Percepción integrada (visión + sensores)
            2. Navegación y evitación de obstáculos
            3. Manipulación robótica con feedback sensorial
            4. Control en bucle cerrado en tiempo real
            5. Aprendizaje por refuerzo en simulación
            6. Transferencia Sim2Real
            7. Coordinación multi-robot
            8. Seguridad operacional y “botón rojo”
            9. Cumplimiento normativo en entornos humanos
            10. Responsabilidad en caso de accidente
        9. Asistentes conversacionales y copilotos para trabajo humano
            1. Asistencia al flujo de trabajo (resúmenes, drafting)
            2. Recuperación aumentada de contexto interno
            3. Razonamiento paso a paso guiado
            4. Integración con herramientas corporativas
            5. Automatización de tareas repetitivas
            6. Soporte en atención al cliente
            7. Riesgo de alucinación en dominios críticos
            8. Escalamiento del humano (augmentación, no reemplazo)
            9. Medición de valor real (tiempo ahorrado, calidad mejorada)
            10. Supervisión humana obligatoria en decisiones sensibles
        10. Automatización de decisiones en línea dentro del flujo de negocio
            1. Scoring en tiempo real dentro del producto
            2. Priorización automática de casos operativos
            3. Control dinámico de riesgo
            4. Moderación y filtrado de contenido en vivo
            5. Prevención de abuso y spam
            6. Detección temprana de incidentes operativos
            7. Ajuste automático de precios / límites / acceso
            8. Integración con sistemas transaccionales
            9. Auditoría de cada decisión automatizada
            10. Estrategia de rollback rápido ante decisiones dañinas

9. Security
    1. Application and service security
        1. Attack surface in web applications and microservices
            1. Endpoint enumeration and discovery
            2. Exposure of metadata and sensitive information in responses
            3. Misconfiguration and insecure defaults
            4. Leaks in error messages and stack traces
            5. External dependencies and third-party libraries
            6. Unsafe management of versions and patches
        2. Main attack vectors in web applications
            1. Code and command injection
            2. Cross-Site Scripting (XSS)
            3. Cross-Site Request Forgery (CSRF)
            4. Unsafe deserialization
            5. Abuse of authentication and brute force
            6. Directory traversal and arbitrary file read
            7. Exploitation of poorly defined or over-permissive APIs
            8. Privilege escalation via internal endpoints
        3. Practical cryptography and secure hashing
            1. Password hashing with resistant algorithms (bcrypt, scrypt, Argon2)
            2. Digital signatures and integrity verification
            3. Symmetric vs. asymmetric keys
            4. Authenticated encryption (AEAD)
            5. Secure key derivation (KDF)
            6. Rotation and expiration of cryptographic keys
            7. Avoid obsolete and insecure cryptographic algorithms
        4. Secure channels and certificates
            1. Encryption in transit (TLS)
            2. Valid certificates and rotation plans
            3. Certificate pinning and MITM mitigation
            4. End-to-end encryption in critical services
            5. Strict HTTPS use and secure redirects
            6. Security in public and private APIs
        5. Protection against common web attacks
            1. Strict validation of user input
            2. Sanitization and output escaping
            3. Anti-forgery and intent tokens (CSRF tokens)
            4. Content policies (Content Security Policy)
            5. Rate limiting and protection against brute force
            6. Avoid arbitrary code execution on the server
            7. Protection against replay attacks
            8. Restriction of dangerous HTTP methods
        6. Authentication and authorization
            1. Password-based authentication models
            2. Multi-factor authentication and contextual factors
            3. Session tokens and signed tokens (JWT, PASETO)
            4. Token expiration and renewal
            5. Role-based authorization models (RBAC)
            6. Attribute-based authorization models (ABAC)
            7. Object-level and field-level authorization
            8. Identity federation (OAuth2, OpenID Connect, SAML)
            9. Single sign-on in corporate environments
        7. Secure handling of credentials, keys and secrets
            1. Storing secrets in secure vaults
            2. Injecting secrets at runtime
            3. Avoid secrets in code repositories
            4. Automatic rotation of access keys
            5. Segmentation of secrets by environment
            6. Use of machine identities vs static secrets
        8. Database security and access control for sensitive data
            1. Least privilege access to tables and views
            2. Separation of credentials per service
            3. Parameterized queries and secure ORM
            4. Masking, tokenization and data anonymization
            5. Encryption of sensitive fields
            6. Protection of personal and identifiable data
            7. Logging of accesses and queries to critical data
        9. Security event logging and traceability
            1. Logging of authentication attempts
            2. Logging of permission changes
            3. Logging of access to sensitive data
            4. Logging of administrative actions
            5. Retention and protection of logs
            6. Correlation of logs with user or service identity
        10. Input sanitization and validation
            1. Whitelists vs. blacklists
            2. Validation of types, ranges and formats
            3. Input normalization to avoid bypasses
            4. Prevent execution of user input as code
            5. Cleaning HTML, JSON and binary payloads
            6. Limiting input size
        11. Threat modeling and basic penetration testing
            1. Analysis of critical assets
            2. Identification of relevant threat actors
            3. STRIDE and DREAD models
            4. Prioritization of attack scenarios
            5. Internal penetration testing
            6. Manual review of sensitive endpoints
        12. Session management and session hijacking mitigation
            1. Secure cookies and protection flags
            2. Expiration time and revocation
            3. Protection against session fixation
            4. Detection of anomalous simultaneous use
            5. Secure session reassignment after privilege escalation
        13. Principle of least privilege in internal components
            1. Separation of responsibilities between services
            2. Run with low-privilege technical identities
            3. Limiting resources accessible by process
            4. Restriction of operating system commands
            5. Minimization of permissions in internal calls
            6. Access control between microservices

    2. Infrastructure and platform security
        1. Isolation between services and environments
            1. Separation between production, staging and development
            2. Isolation of real data vs test data
            3. Limitation of cross-environment access
            4. Ephemeral environments and isolated test environments
        2. Hardening of operating systems, containers and runtimes
            1. Reduction of the base system attack surface
            2. Removal of unnecessary packages
            3. Non-root users in containers
            4. Seccomp, AppArmor and SELinux policies
            5. Immutable containers with verifiable signatures
            6. Kernel capability control
        3. Network security
            1. Internal network segmentation
            2. Firewalls between zones of different criticality
            3. Trust zones and high-sensitivity networks
            4. Restriction of public access to internal services
            5. Outbound traffic filtering and restricted ingress
        4. Internal traffic control between services
            1. Mutual authentication between services (mTLS)
            2. Declarative network policies
            3. Service mesh and service identity control
            4. Detection of unusual traffic between microservices
            5. Limitation of unauthorized lateral calls
        5. Cloud security
            1. Secure configuration of managed resources
            2. Isolation of accounts and projects by environment
            3. Access policies based on service identity
            4. Protection of buckets and object storage
            5. Controlled and explicit public exposure
            6. Monitoring of configuration drift
        6. Protection of data at rest
            1. Volume-level disk encryption
            2. File- or object-level encryption
            3. Centralized encryption key management
            4. Segmentation of highly sensitive data
            5. Secure and verifiable data deletion
        7. Software supply chain security
            1. Verification of dependency integrity
            2. Signing of build artifacts
            3. Build provenance control
            4. Validation of container images
            5. Review of third-party libraries and precompiled binaries
            6. Prevention of malicious dependency injection
        8. Vulnerability scanning of dependencies, images and artifacts
            1. Analysis of known vulnerable dependencies
            2. Container image scanning before deploy
            3. Recurring scanning of production environments
            4. Prioritization based on criticality and exposure
            5. Remediation and tracking of CVEs
        9. Patch and security update management
            1. Patch application schedule
            2. Out-of-cycle critical patches
            3. Compatibility testing before deployment
            4. Automation of infrastructure updates
            5. Documentation of exceptions and technical justifications
        10. Secure backups and disaster recovery
            1. Periodic backup policies
            2. Encryption of backups at rest and in transit
            3. Offline or cross-region storage
            4. Regular restoration tests
            5. Disaster recovery plan
            6. Continuity of critical services in case of total los
    3. Identity, access and privilege control
        1. Identity and access management (IAM)
            1. Human identities vs service identities
            2. Centralized permission control
            3. Scoped access policies
            4. Avoid shared accounts
            5. Periodic review of assigned permissions
        2. Multifactor authentication (MFA)
            1. Possession, inherence and knowledge factors
            2. MFA required for administrative access
            3. Risk-based adaptive MFA
            4. Registration and renewal of factors
        3. Periodic rotation of credentials and keys
            1. Expiration policy for privileged passwords
            2. Automatic rotation of API keys
            3. Active revocation after incidents
            4. Removal of orphaned credentials
        4. Delegation of permissions and granular roles
            1. Minimal roles specific to tasks
            2. Temporary privilege delegation
            3. Separation of read and write permissions
            4. Controlled access to destructive actions
        5. Just-in-time access and controlled emergency access
            1. Temporary elevation of privileges on request
            2. Approval and justification workflow
            3. Automatic closure of temporary access
            4. Audited channels for emergency access
        6. Audit of who accessed what and when
            1. Logging of administrative actions
            2. Logging of access to sensitive data
            3. Tracking of privileged accesses
            4. Post-event review of unusual access
        7. Separation of critical duties (segregation of duties)
            1. Division between development and deployment
            2. Division between operations and audit
            3. Restriction of self-approval for changes
            4. Independence for financial or regulated data controls
        8. Governance of service accounts and API keys
            1. Service account lifecycle
            2. Minimum-permission assignment for technical accounts
            3. Rotation and secure storage of API keys
            4. Revocation of unused service accounts
        9. Revocation and secure deactivation of access
            1. Immediate deprovisioning of departing personnel
            2. Closure of compromised keys
            3. Deactivation of expired temporary roles
            4. Verification that no residual access remain
    4. Monitoring, detection and early response
        1. Detection of anomalous behavior and abuse
            1. Detection of user patterns outside the expected
            2. Analysis of call volume and frequency
            3. Identification of automated or aggressive scraping patterns
            4. Signals of robotic activity or malicious scripts
        2. Alerts on suspicious authentication and API usage
            1. Repeated failed login attempts
            2. Access from unexpected locations
            3. Use of expired or revoked tokens
            4. Sudden privilege changes
        3. Correlation of security events in centralized logs
            1. Aggregation of logs from multiple services
            2. Normalization and tagging of events
            3. Temporal and causal context between events
            4. Enrichment with identity and permission data
            5. Creation of timelines for investigation
        4. Protection against data leakage and exfiltration
            1. Monitoring of unusual mass downloads
            2. Control of export of sensitive data
            3. Alerts on data movements to external destinations
            4. Blocking of unauthorized extraction channels
        5. Full traceability of high-risk actions
            1. Logging of destructive administrative operations
            2. Explicit confirmation for irreversible operations
            3. Association between action and verifiable actor
            4. Temporary sealing and integrity of the record
        6. Incident simulation (fire drills)
            1. Security war games
            2. Roles and responsibilities during simulated attacks
            3. Validation of reaction times
            4. Evaluation of internal communication plans
        7. Detection of internal lateral escalation
            1. Misuse of internal credentials
            2. Unexpected access to collateral services
            3. Unauthorized creation of new technical identities
            4. Detection of lateral tunnels and pivoting
        8. Early signs of compromise in critical environments
            1. Configuration changes without record
            2. Activation of advanced or experimental capabilities in production
            3. New unknown binaries or processes
            4. Unauthorized persistence in critical services
            5. Changes to network or firewall rules without justificatio
    5. Incident response and business continuity
        1. Security incident response plan
            1. Formal definition of an incident
            2. Severity criteria and prioritization
            3. Responsible team and escalation chain
            4. Documented step-by-step procedures
        2. Containment, eradication and recovery
            1. Isolation of compromised systems
            2. Cutting active malicious access
            3. Removal of attacker persistence
            4. Secure restoration to a trusted state
            5. Post-restoration validation
        3. Forensic analysis and preservation of technical evidence
            1. Memory and disk capture
            2. Preservation of relevant logs
            3. Chain of custody for technical evidence
            4. Reconstruction of the attack timeline
            5. Identification of initial entry point
        4. Security postmortems without blame culture
            1. Incident documentation and root cause
            2. Technical and organizational findings
            3. Corrective and preventive actions
            4. Tracking of committed improvements
            5. Lessons shared with the team
        5. Internal and external communication during incidents
            1. Internal emergency channels
            2. Communication with leadership and management
            3. Communication with customers and users
            4. Coordination with relevant external teams
            5. Management of public messaging and reputation
        6. Business continuity and recovery plans
            1. Definition of critical services
            2. Recovery time objectives
            3. Recovery point objectives for data
            4. Alternative manual or degraded procedures
            5. Partial and total loss scenarios
            6. Execution of failover to secondary infrastructure
        7. Coordinated management with legal, compliance and stakeholders
            1. Notification requirements to authorities
            2. Contractual obligations to customers
            3. Management of legal and reputational liability
            4. Involvement of compliance in impact assessment
            5. Coordination with executive leadership and boar
    6. Compliance and organizational risk
        1. Internal security and acceptable use policies
            1. Definition of expected conduct on internal systems
            2. Rules for handling sensitive information
            3. Deployment and production operation rules
            4. Control of external tools and shadow IT
            5. Disciplinary procedures for misuse
        2. Classification and handling of sensitive data
            1. Identification of personal and critical data
            2. Labeling of sensitivity levels
            3. Retention and disposal rules
            4. Copy and export restrictions
            5. De-identification and anonymization for analysis
        3. Applicable regulatory and compliance requirements
            1. Data protection regulations
            2. Privacy and consent obligations
            3. Restrictions on geographic data storage
            4. Applicable industry standards
            5. Traceability and audit requirements
        4. Periodic review of risks and exposures
            1. Updated attack surface assessment
            2. Analysis of new critical dependencies
            3. Identification of single points of failure
            4. Maturity assessment of existing controls
            5. Prioritization of mitigation efforts
        5. Third-party and vendor assessment
            1. Supply chain risk
            2. Security assessment of critical external services
            3. Validation of compliance with minimum standards
            4. Operational dependency and vendor lock-in
            5. Contingency plan for vendor failure
        6. Preventive controls and compensating controls
            1. Technical preventive controls
            2. Organizational and process controls
            3. Documented compensating controls when ideal control is missing
            4. Evaluation of applied control effectiveness
        7. Traceability, reporting and notification obligations
            1. Recording of security incidents
            2. Severity thresholds that require reporting
            3. Timelines for notification to customers and authorities
            4. Tests of organizational response capability
            5. Preservation of evidence and legally required documentation
        8. Security culture
            1. Continuous awareness and team training
            2. Secure practices embedded in the development cycle
            3. Open channels to report internal vulnerabilities
            4. Avoid normalization of temporary security deviations
            5. Incentives aligned with operational security

10. Quality and auditing
    1. Formal verification and formal methods
        1. Formal specification
            1. Temporal logics (LTL, CTL)
            2. Safety vs liveness properties
            3. Modeling of concurrent systems
            4. TLA+ and specification languages for distributed systems
        2. Model checking
            1. Exhaustive state-space exploration
            2. Verification of concurrent and distributed protocols
            3. Abstraction to reduce state-space
            4. Automatic detection of invariant violations
        3. SMT/SAT-assisted testing
            1. SMT solvers (Z3, CVC4)
            2. Satisfiability with theories for integers, arrays, memory
            3. Automatic checking of pre/post-conditions
            4. Bounded model checking
        4. Interactive theorem proving (proof assistants)
            1. Coq / Isabelle / Lean
            2. Proofs of functional correctness for critical algorithms
            3. Extraction of certified code
            4. Verification of cryptographic properties
        5. Practical applications of formal methods
            1. Hardware verification (circuits, buses)
            2. Cryptographic and consensus protocols
            3. Industrial control systems and automotive
            4. Infrastructure-critical software (aviation, healthcare, nuclear)
    2. Testing and quality assurance
        1. Unit testing
            1. Tests for pure functions and local business logic
            2. Dependency isolation using mocks and stubs
            3. AAA structure (Arrange / Act / Assert)
            4. Edge cases and invalid inputs
            5. Test-Driven Development (TDD)
        2. Integration testing
            1. Integration between internal modules
            2. Integration with real or simulated external services
            3. Tests with a database in a controlled environment
            4. Schema migrations and data compatibility
            5. Configuration, seeds and data cleanup between tests
        3. End-to-end testing
            1. Full user flows
            2. Validation of functional requirements
            3. Critical business scenarios
            4. Environments as close to production as possible
            5. Automation of repeatable journeys
        4. Contract testing between services
            1. Producer vs consumer
            2. Contract versioning and backward compatibility
            3. Schema and payload validation
            4. Failures on unauthorized API changes
            5. Publication and automatic validation in CI
        5. Snapshot and expected-state testing
            1. Capture of complex expected outputs
            2. Regression control for visual/structural changes
            3. Intentional review and update of snapshots
            4. Limitations and false positives
        6. Simulation of external dependencies and test doubles
            1. Stubs, mocks, spies and fakes
            2. Simulation of remote errors, timeouts and latency
            3. Emulation of queues, storage, external services
            4. Test harnesses for decoupled components
        7. Property-based testing
            1. Random input generation
            2. Invariants and laws that must always hold
            3. Minimization of failing cases (shrinking)
            4. Detection of unexpected classes of behavior
        8. Coverage metrics and quality criteria
            1. Line, branch, logical path and mutation coverage
            2. Minimum acceptable thresholds
            3. Useful coverage vs artificial coverage
            4. Detection of dead or unexercised code
        9. Static analysis and linters
            1. Syntactic analysis and style enforcement
            2. Semantic analysis and type checking
            3. Early detection of common errors
            4. Custom rules aligned with internal guidance
            5. Integration with the development workflow
        10. Automated security analysis
            1. Scanning for vulnerable dependencies
            2. Detection of secrets in repositories
            3. Validation of authentication and authorization policies
            4. Dynamic Application Security Testing (DAST)
            5. Hardening the attack surface in CI/CD
        11. Automated test execution in delivery pipelines
            1. Quality gates before deploy
            2. Environment/version/configuration matrices
            3. Parallelization and reduction of feedback time
            4. Automatic reports and blocking on failures
            5. Selective re-execution of relevant suites
    3. Quality and audit processes
        1. Continuous integration and continuous delivery
            1. Automatic validation per commit / merge request
            2. Branch policies, versioning and tagging
            3. Progressive deployments, canary and blue/green
            4. Controlled rollbacks and safe reversibility
        2. Version control of external dependencies
            1. Version pinning
            2. Audit of changes in libraries and SDKs
            3. Renewal and expiration of dependencies
            4. Management of SBOM (Software Bill of Materials)
        3. Structured code review and internal guidelines
            1. Technical and functional review standards
            2. Minimum approval rules and responsible roles
            3. Actionable, traceable comments
            4. Prevention of introduced technical debt
        4. Security audits and regulatory compliance
            1. Review of the attack surface
            2. Management of access, keys and secrets
            3. Threat modeling and risk assessment
            4. Verification of processes against applicable regulations
        5. Quality assurance (QA) and quality control (QC)
            1. QA as defect prevention
            2. QC as defect detection
            3. Manual and exploratory validation strategies
            4. Prioritization of defects by impact
        6. Operational quality metrics
            1. Defect density
            2. Failure rate per deployment
            3. MTTR (mean time to recovery)
            4. Availability and SLO/SLA compliance
        7. Acceptance and regression testing
            1. Validation against agreed business criteria
            2. Automated regression suites
            3. Prevention of recurrence of historical bugs
            4. Validation prior to release milestones
        8. Coding standards and approval criteria
            1. Style and formatting conventions
            2. Minimum documentation rules per change
            3. Logging and error-handling policy
            4. Limits on cyclomatic complexity and coupling
        9. Non-functional testing
            1. Performance and latency testing
            2. Load, stress and scalability testing
            3. Resilience and fault-tolerance testing
            4. Resource usage and cost testing
        10. Quality documentation and traceability
            1. Record of technical decisions (ADR)
            2. History of functional and infrastructure changes
            3. Evidence of validation and certification
            4. Mapping requirement → test → result
        11. Compliance with frameworks and industry certifications
            1. Applicable controls and regulatory requirements
            2. Security and data privacy standards
            3. Reevaluation cycles and recertification
            4. Legal responsibilities and external auditability
        12. Post-release assessments and preventive maintenance
            1. Postmortems and incident analysis
            2. Management of accumulated technical debt
            3. Planning of routine patches and updates
            4. Continuous observability and early alerts

11. Operation in production
    1. Concurrency and performance
        1. Asynchronous models and event loops
            1. Structure of the event loop
            2. Cooperative tasks and awaitables
            3. Non-blocking I/O programming
            4. Multiplexing of sockets and file descriptors
            5. Single-thread limit of the event loop
            6. Integrating synchronous code inside an asynchronous context
            7. Cancellation of asynchronous tasks and cleanup
        2. Parallelism with threads and processes
            1. CPU-bound vs I/O-bound parallelism
            2. Operating-system thread scheduling
            3. Thread pools and process pools
            4. Interpreter contention and impact of a global lock
            5. Memory isolation between processes
            6. Data sharing and message-passing between processes
            7. Thread synchronization and race conditions
        3. Deferred tasks and background work
            1. Execution outside the request critical path
            2. Scheduling periodic jobs
            3. Automatic retries and delayed retry queues
            4. High-latency jobs and batch pipelines
            5. Task prioritization and service levels
            6. Explicit acknowledgement of completed work
        4. Futures, promises and asynchronous work units
            1. States of a promise (pending, fulfilled, rejected)
            2. Chaining callbacks and composition
            3. Collecting concurrent results
            4. Synchronization via waiting on multiple tasks
            5. Error propagation through futures
            6. Cancellation and timeouts on futures
        5. In-memory and distributed caching
            1. Local in-process caches
            2. Caches shared between replicas
            3. Expiration strategies and TTL
            4. Cache invalidation and data coherence
            5. Memoization of expensive computations
            6. Caching results of external queries
            7. Cache effects on perceived latency
        6. CPU and memory profiling
            1. Statistical sampling of CPU usage
            2. Tracing memory allocations
            3. Identifying memory leaks
            4. Cost of boxing, copying and serialization
            5. Impact of data structures on consumption
            6. Hot paths and critical functions
            7. Optimization guided by real profiles
        7. I/O-bound vs compute bottlenecks
            1. Disk saturation
            2. Network saturation
            3. Blocking on external service calls
            4. Limitations of vector/SIMD CPU operations
            5. RAM and cache (L1/L2/L3) latency
            6. Balancing I/O-bound and CPU-bound load in mixed architectures
        8. Performance measurement and benchmarking
            1. Microbenchmarks of critical functions
            2. End-to-end throughput and latency benchmarks
            3. Cold-start vs warm processes testing
            4. Statistical variability and repeatability
            5. Sustainable limits vs transient spikes
            6. Degradation under prolonged stress
        9. Horizontal and vertical scaling strategies
            1. Vertical scaling by resource (CPU, RAM)
            2. Horizontal scaling by identical replicas
            3. Load balancers and uniform distribution
            4. Sticky sessions vs shared state
            5. Logical sharding by key
            6. Active-active and active-passive replication
        10. Work queues and task orchestrators
            1. Decoupled producers and consumers
            2. Explicit acknowledgement of processed messages
            3. Retries with exponential backoff
            4. Detection of poisoned messages
            5. Dead-letter queues and quarantine
            6. Load balancing between workers
        11. Rate limiting and pressure relief mechanisms
            1. Limiting requests per unit of time
            2. Sliding windows and token counters
            3. Prioritization by client type
            4. Early rejection and degraded responses
            5. Controlled waiting queues
            6. Circuit breaking under overload
        12. Locks, semaphores and synchronization primitives
            1. Mutual exclusion and critical sections
            2. Readers-writer locks and concurrent access
            3. Counting semaphores and limited-resource control
            4. Synchronization barriers and computation phases
            5. Deadlocks, livelocks and starvation
            6. Lock-free and wait-free design

    2. Infrastructure and operations
        1. Advanced strategies for version control and branching
            1. Long-lived branches and ephemeral branches
            2. Trunk-based strategies and release branches
            3. Semantic versioning and release tagging
            4. Controlled cherry-pick and backporting
            5. Review policies and branch protection
            6. Change lineage and commit auditing
        2. Continuous integration / continuous delivery in real environments
            1. Automated build and test pipelines
            2. Security validations in the pipeline
            3. Quality gates and coverage checks
            4. Versioned artifacts and promotion between environments
            5. Continuous deploy vs deploy with approval
            6. Automated rollback on failures
        3. Containers and portable environment definitions
            1. Isolation of dependencies and system libraries
            2. Reproducible and deterministic images
            3. Reducing attack surface in the image
            4. Layer caching and image versioning
            5. Immutable packaged runtime
            6. Cross-platform compatibility and CPU architecture
        4. Deploying multiple coordinated services
            1. Independent versioning per service
            2. API contracts and backward compatibility
            3. Orchestration of dependent deployments
            4. Synchronization of data schema changes
            5. Transitional migrations and maintenance windows
            6. Gradual deployment strategies per service
        5. Container orchestration and workload scheduling
            1. Schedulers and pod/task placement
            2. Node affinity and anti-affinity
            3. Liveness and readiness probes
            4. Metric-driven autoscaling
            5. Rolling updates and canary deployments
            6. Managing stateful workloads
        6. Infrastructure monitoring and dashboards
            1. CPU, memory, disk and network metrics
            2. Node, container and pod health status
            3. Capacity and saturation alarms
            4. Real-time and executive dashboards
            5. Historical performance for trend analysis
            6. Correlation between infrastructure events and failures
        7. Infrastructure as code
            1. Declarativity and convergence to desired state
            2. Versioning and auditing infrastructure changes
            3. Template validation and testing
            4. Reuse of modules and components
            5. Managing multiple environments from the same code
            6. Controlled destruction and resource cleanup
        8. Cloud platforms (compute, networking, storage)
            1. Virtual machines and reserved capacity
            2. Virtual networks, subnets and ingress rules
            3. Managed load balancers and gateways
            4. Block storage and shared file systems
            5. Cross-zone and cross-region replication
            6. Policies for geographic high availability
        9. Object storage, serverless execution, managed monitoring
            1. Object buckets and retention policies
            2. On-demand functions and serverless compute
            3. Execution time and memory limits per invocation
            4. Integration with queues and events
            5. Managed logging and metrics services
            6. Eventual persistence and read-after-write consistency
        10. Configuration and centralized secret management
            1. Environment variables and external configuration
            2. Dynamic injection of secrets at runtime
            3. Key and credential rotation
            4. Role-based access control
            5. Configuration versioning and rollback
            6. Separating configuration by environment and region
        11. Active monitoring and operational alerts
            1. Synthetic probes for availability
            2. SLA and SLO verification
            3. Alerts on latency and error rates
            4. Alerts on queue backlog and congestion
            5. Cost and overspend alerts
            6. Escalation paths and on-call
        12. Cost optimization and auto-scaling
            1. Rightsizing instances and containers
            2. Using reserved and spot/preemptible instances
            3. Business-metric-driven scaling
            4. Scheduled shutdown of resources
            5. Compression and storage lifecycle
            6. Reducing data duplication and unnecessary traffic

    3. Observability, logs and metrics
        1. Structured and contextualized logging
            1. Key/value fields and request traceability
            2. Correlation with session, user and transaction IDs
            3. Severity levels and filtering
            4. Log retention, rotation and archiving
            5. Masking of sensitive data
            6. Search and aggregation at large scale
        2. Application performance monitoring (APM)
            1. Latency metrics per endpoint
            2. Throughput and saturation metrics
            3. Errors by type and frequency
            4. Dependency tracking of external services
            5. Progressive degradation under load
            6. Early detection of performance regressions
        3. Distributed end-to-end tracing
            1. Context propagation between services
            2. Nested spans and request timeline
            3. Identifying the slow service in the chain
            4. Inter-service bottlenecks
            5. Trace sampling and retention
            6. Analysis of user-perceived latency
        4. Custom metrics and health checks
            1. Technical metrics (queue, memory, GC)
            2. Functional metrics (orders/minute, failed payments)
            3. Internal and public healthcheck endpoints
            4. Early degradation signals
            5. Alerts on relative change, not only absolute
            6. Metrics of perceived availability
        5. Threshold and trend-based alerts
            1. Static vs dynamic thresholds
            2. Anomaly-detection alerts
            3. Growth trends in error rates
            4. Imminent saturation alerts
            5. Prioritization and alert severity
            6. Managing alert fatigue and noise
        6. Audit and incident reconstruction
            1. Immutable record of relevant actions
            2. Incident timeline
            3. Evidence for post-mortem analysis
            4. Identifying the breaking point
            5. Access to consistent historical data
            6. Continuous improvement based on lessons learned

    4. Resilience
        1. Fault tolerance and isolation
            1. Isolation by service and functional domain
            2. Isolation of critical shared resources
            3. Active and passive redundancy
            4. Controlled degradation of non-critical features
            5. Limiting blast radius on failures
            6. Automated failover between replicas
        2. Latency control and timeouts
            1. Timeouts per operation and per dependency
            2. Latency budgets per request
            3. Proactive cancellation of slow operations
            4. Partial responses under pressure
            5. Fast-fail when resources are saturated
            6. Avoid cascading blocking due to waits
        3. Safe retries
            1. Idempotency of operations
            2. Exponential backoff and random jitter
            3. Detecting transient vs permanent errors
            4. Avoiding coordinated retry storms
            5. Maximum retry limits and early cutoffs
            6. Logging retries for audit
        4. Protection against overload
            1. Circuit breakers and circuit opening
            2. Controlled rejection of traffic during spikes
            3. Bounded queues and load shedding
            4. Degraded service modes
            5. Client- or tenant-level quotas
            6. Protection against malicious or anomalous spikes
        5. Service health and self-healing
            1. Automatic detection of unhealthy instances
            2. Automatic restart and replacement of replicas
            3. Reconciliation with declared state
            4. Rotation of unhealthy nodes
            5. Cleanup of hung or zombified resources
            6. Self-recovery without human intervention
        6. Recovery and continuity
            1. Consistent and verified backups
            2. Proven and documented restoration
            3. Crisis recovery plans
            4. Chaos engineering

12. Technical Management
    1. Technical culture and team management
        1. Effective and empathetic code review
            1. Objectives of code review
                1. Functional quality and correctness
                2. Security and compliance
                3. Readability and maintainability
                4. Consistency with internal guidelines
            2. Feedback styles and professional tone
            3. Approval and PR blocking criteria
            4. Reviewer rotation and load distribution
            5. Use of automated tools in PRs
            6. Early detection of architectural issues
            7. Security and compliance review
        2. Technical debt management
            1. Cataloguing and visibility of technical debt
                1. Record in a technical backlog
                2. Tagging in tickets and PRs
                3. Risk maps by service
                4. Remediation owners
            2. Prioritization based on impact and risk
            3. Planned refactors vs opportunistic refactors
            4. Architectural debt vs implementation debt
            5. Technical health metrics and internal tech radar
            6. Hardening and stabilization windows
        3. Mentoring and technical leadership
            1. One-on-one coaching
            2. Transfer of historical system context
            3. Development of architectural judgement
                1. Internally accepted patterns
                2. Common antipatterns and early warnings
                3. Systemic impact assessment
            4. Growing juniors toward higher autonomy roles
            5. Responsible delegation and progressive ownership
            6. Constructive feedback and technical improvement plans
        4. Production incident response
            1. Roles during an incident (commander, communications, scribe, resolvers)
            2. Internal and external communication channels
            3. Technical escalation and decision-making under pressure
            4. Temporary containment vs root cause fix
            5. Chronological recording of the incident
            6. Severity and priority criteria
                1. User impact
                2. Data loss or security
                3. Direct financial impact
                4. Reputational risk
            7. Handling repeated incidents
        5. Postmortems and blameless root-cause analysis
            1. Postmortem structure
                1. Incident timeline
                2. Measured impact
                3. Technical causes
                4. Organizational causes
                5. Next steps
            2. Root-cause trees and contributing factors
            3. Corrective actions and clear owners
            4. Prioritization of follow-up actions
            5. Review of effectiveness of previous actions
            6. Sharing learnings across the organization
            7. Avoiding a blame culture and fostering psychological safety
        6. Internal code standards and guides
            1. Style and formatting guides
                1. Automatic formatting and linters
                2. Folder structure
                3. Naming of variables, classes and modules
                4. Standards for in-code documentation
            2. Security rules and secret handling
            3. Approved design patterns
            4. Recommended use of libraries and frameworks
            5. Supported versions and deprecation policies
            6. Naming conventions and repository structure
            7. Internal API contracts
        7. Communication with product and other teams
            1. Translating business needs into technical requirements
            2. Realistic expectations for timelines and risks
                1. Hidden technical costs
                2. Future operational costs
                3. Trade-offs between quality and speed
            3. Handling scope and last-minute changes
            4. Transparency on blockers and dependencies
            5. Managing conflicting priorities
            6. Basic technical education for non-technical stakeholders
            7. Coordination with QA, data, security and support
        8. Iteration and release planning
            1. Designing milestones and clear objectives
            2. Defining minimum viable scope
            3. Feature freeze control before release
            4. Coordination across multiple teams for a common release
            5. Branch management and merge windows
            6. Gradual rollout strategies and feature flags
                1. Percentage-based user rollout
                2. Canary and shadow environments
                3. Controlled rollback
                4. Kill switches
            7. Criteria for ready for production
        9. Evaluation of technical decisions and trade-offs
            1. Cost of future complexity vs immediate speed
            2. Assessment of technological lock-in
            3. Impact on observability and operability
            4. Long-term maintainability sustainability
            5. Compatibility with global architectural vision
            6. Reversibility of the decision
                1. Exit costs
                2. Estimated migration time
                3. Rollback impact on users
        10. Technical roadmap and platform vision
            1. Baseline of the current architecture
            2. Technological evolution objectives
            3. Consolidation plan and complexity reduction
            4. Investment in reusable internal platforms
            5. Plans to retire legacy systems
                1. Identification of critical components
                2. Gradual migration without downtime
                3. Freeze of changes in legacy
                4. Target retirement date
            6. Interoperability standards between services
            7. Observability strategy and technical governance
        11. Living documentation culture
            1. Technical documentation as part of delivery
            2. Continuous documentation update processes
            3. Single sources of truth (runbooks, ADRs, diagrams)
                1. ADRs (Architecture Decision Records)
                2. Service and dependency maps
                3. Level-1 support runbooks
                4. Escalation flows
            4. Versioning and traceability of decisions
            5. Operational documentation for on-call and incidents
            6. Onboarding documentation for new hires
        12. Inclusion, collaboration and psychological safety
            1. Respectful collaboration practices
            2. Safe spaces to ask technical questions
            3. Normalizing asking for help
            4. Managing technical conflict without personal confrontation
            5. Equity in distribution of visible vs invisible tasks
                1. Maintenance and support work
                2. Innovation and key feature work
                3. Recognition and internal visibility
            6. Preventing burnout and excessive cognitive load
        13. Knowledge management and context rotation
            1. On-call and support rotations
                1. Coverage schedules and fair distribution
                2. Documented handovers
                3. Training before rotation
            2. Structured shadowing and pairing
            3. Internal knowledge-transfer sessions
            4. Record of historical decisions
            5. Reducing single human points of failure
            6. Backup plans for critical expertise
    2. Management and technical leadership
        1. Project management
            1. Defining scope and measurable objectives
            2. Structuring into incremental deliverables
            3. Tracking milestones and progress
                1. Roadmaps with explicit dates
                2. Burndown and burnup charts
                3. Status of critical blockers
            4. Managing scope changes
            5. Coordination across multiple squads
            6. Formal project closure and retrospective
        2. Effort estimation and technical planning
            1. Estimation models (story points, t-shirt sizing)
                1. Relative vs absolute estimation
                2. Collective planning sessions
                3. Common estimation biases
            2. Technical complexity analysis
            3. Validation of technical assumptions
            4. Uncertainty ranges and buffers
            5. Continuous review and adjustment of estimates
        3. Risk and dependency management between teams
            1. Early identification of critical dependencies
            2. Impact analysis for external delays
            3. Technical contingency plans
                1. Alternative implementation routes
                2. Feature flags to isolate impact
                3. Controlled degradation strategies
            4. Prioritization based on operational risk
            5. Managing inter-team blockers
        4. Prioritizing technical debt versus features
            1. Argumentation based on future risk
            2. Accumulated operational costs
                1. Unplanned support time
                2. Recurrent incidents
                3. Deployment complexity
            3. Opportunity cost of not addressing debt
            4. Negotiation with product on what enters each iteration
            5. Impact metrics on team velocity
        5. Release management and change control
            1. Branching and merge policies
            2. Semantic versioning and tagging
            3. Freeze windows and release cut
            4. Pre-release checklist
                1. Minimum test coverage
                2. Reviewed database migrations
                3. Alert configuration ready
                4. Updated operational documentation
            5. Rollback and post-release monitoring
            6. Multi-service coordination in coupled releases
        6. Cross-cutting communication (product, QA, operations, data)
            1. Formal coordination channels
            2. Technical alignment rounds
            3. Managing external expectations
            4. Translating technical risks to business impact
                1. Potential financial impact
                2. Impact on user experience
                3. Legal or reputational impact
            5. Support agreements with non-technical areas
        7. Professional development and technical mentorship
            1. Individual technical growth plans
            2. Career tracks: IC vs management
                1. Staff / Principal Engineer
                2. Engineering Manager
                3. Tech Lead / Lead Engineer
            3. Assessment of specific technical skills
            4. Access to challenging projects
            5. Strategic rotation to broaden experience
            6. Preparing future technical leaders
        8. Technical performance evaluation
            1. Objective criteria for technical impact
                1. Measurable production results
                2. Risk reduction
                3. Acceleration of other teams
            2. Contribution to quality and reliability
            3. Collaboration and professional behaviour
            4. Innovation and continuous improvement
            5. 360° evaluation and cross feedback
        9. Recording and documenting architectural decisions
            1. ADRs (Architecture Decision Records)
                1. Problem context
                2. Decision made
                3. Expected consequences
                4. Date and responsible parties
            2. Evaluated alternatives and explicit discard rationale
            3. Technical and organizational impact analysis
            4. Decision reversibility
            5. Internal dissemination and alignment
        10. Technical presentations to non-technical audiences
            1. Executive communication oriented to outcomes
            2. Architecture and flow visualization
                1. High-level diagrams
                2. Simplified dependency maps
                3. Data flows and privacy
            3. Translating technical risk to business risk
            4. Narrative of technical value and differentiation
            5. Technical storytelling for leadership and clients
        11. Engineering culture based on continuous learning
            1. Post-release feedbacks
                1. What went well
                2. What went wrong
                3. What to change next time
            2. Internal technical sessions like tech talks
            3. Group technical readings and RFC reviews
            4. Cross-training between teams
            5. Safe spaces and sandboxes for experimentation
        12. Continuous improvement practices after incidents
            1. Systematic elimination of error classes
            2. Automation of preventive checks
                1. Regression tests
                2. Synthetic monitors
                3. Pre-deploy validations
            3. Adjustment of alerts and thresholds
            4. Operational retraining of the team
            5. Integration of learnings into runbooks
        13. Capacity management and resource allocation
            1. Balance between maintenance and feature development
            2. Operational load of the team
                1. On-call rotation
                2. Work outside working hours
                3. Unplanned interruptions
            3. Commitment decisions based on real capacity
            4. Managing individual bottlenecks
            5. Prioritizing high-leverage initiatives
        14. Hiring strategy and technical onboarding
            1. Defining required technical profiles
            2. Designing technical interview processes
            3. Practical evaluation and technical exercises
            4. Quality of onboarding and initial ramp
                1. Initial documentation of critical systems
                2. First guided tasks
                3. Assigned mentor
            5. Cultural integration and engineering values
            6. Retention of key talent
        15. Organizational scaling and delegation
            1. Role of Tech Lead vs Engineering Manager
            2. Technical multipliers and distributed leadership
            3. Effective delegation of decision-making
            4. Clear ownership by service or domain
                1. Primary technical owner
                2. Operational on-call owner
                3. Map of incoming and outgoing dependencies
            5. Defining interfaces between teams
            6. Designing autonomous cells or squads
    3. Operations, reliability and delivery excellence
        1. Internal SRE and service ownership
            1. End-to-end responsibility for the service
                1. Design
                2. Deployment
                3. Operation
                4. Support
            2. Clear definition of service owners
            3. Reliability objectives aligned with the business
            4. Resilience engineering and fault tolerance
            5. Minimum operational training for development teams
        2. Organizational observability
            1. Metrics, logs and distributed traces
            2. Standardized dashboards per service
                1. Health of external dependencies
                2. Errors per endpoint
                3. 95/99 percentile response time
            3. Actionable, low-noise alerts
            4. End-to-end request traceability and latency
            5. End-user experience metrics
        3. SLA, SLO and SLI management
            1. Defining availability objectives
            2. Error budgets and pace of change
                1. Release freeze policy
                2. Prioritization of stabilization
                3. Shared responsibility between teams
            3. Aligning SLOs with business impact
            4. Communicating compliance to stakeholders
            5. Dynamic adjustment of objectives according to maturity
        4. Alert management and alert fatigue
            1. Severity and priority criteria for alerts
            2. Routing alerts to the correct team
            3. Reducing false positives
                1. Threshold tuning
                2. Correlation of multiple signals
                3. Synthetic health checks
            4. On-call rotation and load balancing
            5. Periodic review of alerting policies
        5. Safe deployment cycles
            1. Continuous integration and automated tests
            2. Continuous delivery and quality gates
                1. Automatic validations before deploy
                2. Manual reviews for high-risk changes
                3. Separate approvals for sensitive changes
            3. Incremental and canary deployments
            4. Fast and safe rollback
            5. Production change auditing
        6. Environment management (dev, staging, prod)
            1. Parity between environments
                1. Equivalent configuration
                2. Simulated dependencies
                3. Performance tests before promotion to production
            2. Test data and anonymization
            3. Isolation of shared services
            4. Infrastructure versioning
            5. Governance of configuration changes
        7. Change control and operational audit
            1. Record of who changed what and when
            2. Authorization and approval of sensitive changes
            3. Separation of operational functions
                1. Developer
                2. Operations
                3. Security
                4. Internal audit
            4. Temporary and just-in-time access policies
            5. Log retention for audit
        8. Continuity exercises and DRP
            1. Disaster recovery plan
            2. Periodic failover tests
            3. Verified backups and restoration
                1. Backup frequency
                2. Backup retention
                3. Real restoration tests
                4. Encrypted backups
            4. Partial vs total loss scenarios
            5. Communication plans during major outages
        9. Security incident management
            1. Early detection of anomalous activity
            2. Immediate containment and isolation
                1. Revocation of compromised keys
                2. Disabling affected accounts
                3. Blocking compromised endpoints
            3. Internal communication and regulatory obligations
            4. Forensic analysis and learning
            5. Responsible disclosure policies
        10. Communication during critical incidents
            1. Single official information channel
            2. Periodic updates to stakeholders
            3. External messages to customers and users
                1. Current status
                2. Known impact
                3. Estimated next update
                4. Suggested mitigation steps
            4. Coordination with legal and compliance
            5. Avoid overwhelming technical teams
        11. DevSecOps process maturity
            1. Security integrated into the development cycle
            2. Continuous vulnerability scanning
            3. Secrets and credential management
                1. Automatic key rotation
                2. Centralized encrypted storage
                3. Removal of secrets from code repositories
            4. Least-privilege access policies
            5. Secure infrastructure-as-code
            6. Compliance automation
13. Compliance and improvement
    1. Ethics, legality and professional practice
        1. Professional responsibility in software engineering
            1. Quality and reliability of delivered product
            2. User and data security
                1. Handling sensitive data
                2. Preventing platform abuse
                3. Response to discovered vulnerabilities
            3. Transparency of technical limitations
            4. Due diligence for high-impact changes
            5. Duty to escalate when critical risk exists
        2. Privacy and responsible data handling
            1. Data minimization principles
            2. Secure retention and deletion
                1. Retention policies by data type
                2. Verifiable deletion
                3. Deletion records
                4. Legally mandated retention
            3. Informed consent and revocability
            4. Internal access with minimum privilege
            5. Anonymization and pseudonymization of data
            6. Ethical use of user data
        3. Intellectual property and software licensing
            1. Open-source licenses and compatibility
                1. Permissive licenses
                2. Copyleft licenses
                3. Redistribution restrictions
                4. Attribution obligations
            2. Use of third-party dependencies
            3. Internal contributions to OSS
            4. Reuse of internal code across projects
            5. Protection of strategic know-how
        4. Regulatory compliance and industry standards
            1. Information security standards
            2. Sector-specific regulations
            3. Quality norms and certifications
                1. Documented processes
                2. Verifiable evidence
                3. Recurring audits
            4. External audit requirements
            5. Traceability and compliance logging
        5. Risk of dependency on a single vendor and technological shutdown
            1. Assessing provider lock-in in infrastructure
            2. Portability of data and services
                1. Standard formats
                2. Exportable APIs
                3. Active replication
            3. Multi-cloud or multi-vendor strategies
            4. Exit and migration costs
            5. Continuity plans if a provider fails
        6. Algorithmic bias and transparency in automated systems
            1. Identifying biases in training data
            2. Impact assessment on user groups
            3. Explainability of automated decisions
            4. Continuous auditing of models in production
                1. Drift detection
                2. Tracking fairness metrics
                3. Alerts for anomalous behavior
            5. Appeals and correction mechanisms
        7. Accessibility and inclusion in design and UX
            1. Accessibility guidelines in interfaces
                1. Keyboard navigation
                2. Appropriate visual contrast
                3. Screen reader support
                4. Text alternatives for visual content
            2. Inclusive design of critical flows
            3. Multiplatform and multichannel support
            4. Usability tests with diverse groups
            5. Clear and understandable language
        8. Governance of free software and open collaboration
            1. Community governance models
            2. Policies for internal contributions to public projects
                1. Internal approval beforehand
                2. Legal review
                3. Protecting sensitive information
            3. Publishing reusable internal tools
            4. Managing vulnerabilities in open dependencies
            5. Relationships with external maintainers
        9. Protection of personal data and access traceability
            1. Role-based access control
            2. Logging accesses to sensitive data
                1. Who accessed
                2. When accessed
                3. Purpose of access
                4. Periodic access review
            3. Alerts on unusual access
            4. Separation of personal and operational data
            5. Principle of least privilege
    2. Technical and scientific reproducibility
        1. Versioning of code and data
            1. Controlled execution environments
                1. Declarative infrastructure
                2. Versioned containers
                3. Frozen dependencies
            2. Verifiable experimental evidence
            3. Deterministic and repeatable pipelines
            4. Internal publication of replicable results
        2. Honest and responsible communication with stakeholders
            1. Clear reporting of risks and limitations
            2. Early communication of relevant incidents
                1. Who to inform
                2. When to inform
                3. Level of detail to share
            3. Unvarnished status reports
            4. Coordinated messages with leadership
            5. Transparency about security failures
        3. Social and environmental impact of software
            1. Energy footprint of infrastructure
                1. Energy consumption per workload
                2. Compute efficiency
                3. Optimization of idle resources
            2. Responsible use of computational resources
            3. Social effects of automation
            4. Impact on human labor and the job market
            5. Non-technical negative externalities
        4. Data sovereignty and regional compliance
            1. Geographic data localization
                1. Allowed regions
                2. Geographic redundancy
                3. Applicable jurisdiction
            2. International legal restrictions
            3. Cross-border processing requirements
            4. State audit requirements
            5. Data export limitations
        5. Responsible management of generative AI
            1. Approved use of internal and external models
            2. Protecting confidential information when using AI
            3. Mandatory human review in critical decisions
                1. Regulatory decisions
                2. Financial decisions
                3. Decisions affecting end users
            4. Managing IP generated by AI
            5. Logging of sensitive prompts and outputs
    3. Innovation, research and continuous improvement
        1. Critical evaluation of new technologies
            1. Technical and business feasibility
            2. Risk of immature technology
                1. Community maturity
                2. API stability
                3. Long-term support
            3. Operational and adoption costs
            4. Replacement of current solutions
            5. Time horizon for return on investment
        2. Rapid prototypes and proofs of concept
            1. Clear hypothesis definition to validate
            2. Narrow, focused scope
            3. Time-boxed experimentation
            4. Clear success criteria
                1. Objective technical metrics
                2. Business metrics
                3. Validation with real users
            5. Exit plan if no value is added
        3. Comparative measurement and technical benchmarking
            1. Controlled performance tests
                1. Definition of dataset or synthetic load
                2. Reproducible conditions
                3. Consistently collected metrics
            2. Memory and CPU consumption
            3. Latency and throughput
            4. Horizontal and vertical scalability
            5. Associated infrastructure costs
        4. Monitoring technological trends and state of the art
            1. Continuous technology watch
            2. Mapping of relevant emerging technologies
            3. Evaluation of potential disruptions
            4. Relationship with academia and applied research
                1. Formal collaborations
                2. Joint publications
                3. Early access to research results
            5. Identifying internal capability gaps
        5. Participation in technical communities and open projects
            1. Contribution to open source projects
                1. Bug fixes
                2. New features
                3. Documentation and examples
                4. User support
            2. Presentations at meetups and conferences
            3. Publication of technical articles
            4. Reviewing external proposals (public RFCs)
            5. Technical recruitment based on community reputation
        6. Internal knowledge management and shared documentation
            1. Internal knowledge bases
                1. Central technical wiki
                2. Service catalog
                3. Incident history and learnings
            2. Libraries of reusable patterns
            3. Best-practice guides by domain
            4. Formalized knowledge-transfer sessions
            5. Discoverability mechanisms for information
        7. User-centered design to solve real problems
            1. Discovering real user needs
            2. Mapping critical journeys
                1. Main flow steps
                2. Current friction points
                3. Abandonment risks
            3. Prioritizing pain points
            4. Testable prototypes with end users
            5. Measuring perceived impact
        8. Continuous learning and training plans
            1. Internal technical training programs
                1. Hands-on workshops
                2. Guided labs
                3. Recorded internal courses
            2. Training budget and certifications
            3. Rotation through strategic projects
            4. Peer coaching
            5. Advanced specialization tracks
        9. Controlled experimentation and gradual rollouts
            1. A/B testing and controlled experiments
                1. Hypothesis definition
                2. Cohort selection
                3. Statistical analysis
            2. Feature toggles and segmented activation
            3. Experiments on limited user segments
            4. Evaluating impact on key metrics
            5. Progressive rollout to the entire user base
        10. Responsible, safe and sustainable innovation
            1. Evaluation of ethical and legal risks
            2. Security by design from prototype stage
            3. Environmental impact and resource consumption
            4. Abuse and malicious-use controls
                1. Acceptable use limits
                2. Fraud prevention
                3. Monitoring of toxic behaviour
            5. Governance of experiment lifecycle
        11. Patent strategy and scientific disclosure
            1. Identifying patentable results
            2. Protecting key intellectual property
            3. Decision to publish or patent
                1. Competitive advantage
                2. Disclosure obligations
                3. Time-to-market considerations
            4. Coordination with legal and compliance
            5. Academic dissemination and reputation
        12. Technology transfer and scaling to production
            1. Moving prototype to maintainable product
                1. Refactoring experimental code
                2. Minimum automated tests
                3. Initial operational documentation
            2. Hardening security and compliance
            3. Observability from day one
            4. Costing and sustainable operating model
            5. Training the team that will operate the solution
        13. Internal culture of experimentation and hack time
            1. Protected spaces for technical exploration
            2. Hackathons and innovation weeks
                1. Definition of strategic themes
                2. Presenting results to leadership
                3. Selection of ideas for production
            3. Rotation of challenging technical problems
            4. Incentives for learning and calculated risk-taking
            5. Internal publication of notable experiments
    4. Audit, metrics and process optimization
        1. Delivery and workflow metrics
            1. Lead time for change to production
                1. Time from code commit to deploy
                2. PR review time
                3. Time in QA and validation
            2. Cycle time per feature
            3. Team throughput
            4. Work in progress (WIP) and healthy limits
            5. Recurrent blockers and external waits
        2. Reliability and availability metrics
            1. Perceived uptime by the user
            2. MTTR (mean time to recovery)
                1. Initial diagnosis
                2. Containment
                3. Definitive resolution
            3. MTTD (mean time to detection)
            4. High-severity incidents
            5. SLO breaches
        3. Code quality metrics
            1. Automated test coverage
                1. Coverage of critical units
                2. Coverage of error paths
                3. Coverage of sensitive business logic
            2. Cyclomatic complexity
            3. Code duplication
            4. Statically detected vulnerabilities
            5. Average time to fix critical bugs
        4. Security and compliance audit
            1. Scanning for vulnerable dependencies
            2. Patch management
                1. Maximum exposure windows
                2. Prioritization by criticality
                3. Tracking applied patches
            3. Access control evaluation
            4. Verification of encryption in transit and at rest
            5. Regulatory compliance validation
        5. Access audit and traceability
            1. Centralized access logging
            2. Alerts for unusual accesses
            3. Periodic privilege review
                1. Validity of current access
                2. Operational necessity
                3. Date of last review
            4. Account lifecycle (create, modify, revoke)
            5. Exportable audit evidence
        6. Kaizen-style continuous improvement processes
            1. Identifying process waste
                1. Rework
                2. Waiting
                3. Excess process
                4. Repetitive manual movements
            2. Standardization of good practices
            3. Small, frequent iterations
            4. Short feedback loops
            5. Empowering the team to propose changes
        7. Feedback loop with customers and stakeholders
            1. Structured capture of complaints and incidents
            2. Post-release feedback processing
                1. Classification by problem type
                2. Assignment to responsible team
                3. Follow-up until resolution
            3. Identifying friction patterns
            4. Prioritization based on perceived severity
            5. Communicating delivered improvements
        8. Organizational health checks and technical maturity
            1. Health of the development process
            2. Health of code quality
            3. Operational and on-call health
                1. Off-hours interruption load
                2. Average incident severity
                3. Perceived burnout
            4. Cultural health of the team
            5. Prioritized improvement plan
        9. Backlog management for operational improvements
            1. Centralized register of pending technical improvements
            2. Joint prioritization with technical leadership
                1. Operational risk
                2. Business impact
                3. Cost of not acting
            3. Clear assignment of owners
            4. Target remediation deadlines
            5. Executive visibility of open risks
        10. Automation of controls and reportability
            1. Automatic generation of compliance reports
            2. Preventive alerts for process deviations
            3. Security validations integrated into the pipeline
                1. Static code scanning
                2. Dependency analysis
                3. Dynamic security tests
            4. Audit-ready evidence
            5. Orchestration of repeatable flows
        11. Internal transparency and executive reporting
            1. Technical dashboards for leadership
            2. Platform reliability reports
                1. Incident trend
                2. Availability by service
                3. SLO compliance
            3. Visibility of operational costs
            4. Status of prioritized technical debt
            5. Risk mitigation roadmap
        12. Preparation for external audits and certifications
            1. Early collection of mandatory evidence
            2. Audit drills
                1. Scope evaluated
                2. Gaps found
                3. Corrective actions
            3. Remediation plans for findings
            4. Internal owners per control area
            5. Certification renewal cycle
