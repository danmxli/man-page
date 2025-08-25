## About
- Third year Computer Engineering student at the University of Waterloo, focused on distributed systems, operating systems, and performance optimization.
- **Relevant Coursework**:
    - **ECE252: Systems Programming and Concurrency**
        - About
            - Semaphore, mutex, monitors, and barrier synchronization.
            - Performance and correctness of concurrent systems.
            - Deadlock detection and recovery.
        - Projects
            - Image processing tool, implementing the bounded buffer producer-consumer pattern for inter-process communication.
            - Web crawler design and implementation. Benchmarked completion time and resource consumption of multithreaded blocking I/O vs. non-blocking I/O approach.
    - **ECE208: Discrete Mathematics and Logic 2**
        - About
            - Formal logics and methods, and their applications in verifying computer systems.
            - Formal models of computation.
            - Predicate logic, temporal logic, relational logic. Set theory, proof theory, model theory, graph theory.
        - Projects
            - Boolean satisfiability solver using the DPLL algorithm.
    - **ECE250: Algorithms and Data Structures**
        - About
            - Data structures and algorithms.
            - Abstract data types.
            - Algorithm analysis.
        - Projects
            - Symbolic classifier program, implementing prefix tree for hierarchical knowledge organization and LLM-based evaluation per node for intelligent path selection.
            - Network topology analyzer program, modelling relational data as weighted graphs to analyze connection patterns and resource distribution.
    - **ECE224: Embedded Microprocessor Systems**
        - About
            - Embedded microprocessor systems.
            - Microprocessor system architecture.
            - Data transfer, synchronization, error detection/correction, testing and debugging.
        - Projects
            - Audio waveplayer built using the Altera toolchain. Implements FAT32 MicroSD card streaming.
    - **ECE222: Digital Computers**
        - About
            - Computer organization and architecture.
            - Memory units, arithmetic logic units, control units, and I/O operations.
            - Assembly language programming, translation, and loading.
        - Projects
            - Morse code encoder and decoder program using RISC-V assembly language.

---

## Experience

### Voltra Energy - Software Developer Intern (Jan 2025 - Apr 2025)
- Delivered concurrent, fault-tolerant systems powering IoT services, and pipelines for CI/CD and telemetry.
    - **IoT Action Layer**
        - An Elixir-based messaging fabric for Open Charge Point Protocol remote commands.
        - Implements the actor model for concurrent computing.
        - Zero message loss in chaos tests and process restarts due to automatic state reconstruction of process handlers.
    - **Traffic Management Layer**
        - A cloud-native policy enforcement gateway, built using Apache APISIX.
        - Features load-balancing, per-tenant rate-limiting, and header-based API-key auth for protected routes.
        - Features an observability pipeline to stream gateway events into Clickhouse for real-time billing and analytics.

### Voltra Energy - Software Developer Intern (May 2024 - Aug 2024)
- Developed data infrastructure for route planning and EV management features.
    - **Data Pipeline**
        - A Go-based service that ingests, transforms, and loads station metadata from distributed sources into a PostgreSQL database.
        - Leverages concurrent worker pools with idempotent processing for consistent data ingestion.
    - **Proto3 Schema Repository**
        - A centralized repository that enforces typed gRPC service contracts for route planning and station discovery.
        - Features schema versioning and codegen pipelines to eliminate serialization mismatches during rolling updates.

### Onlia Insurance - Automation QA Intern (May 2023 - Aug 2023)
- Led the development of a web automation project for regression testing workflows.
    - **Selenium WebDriver Automation Framework**
        - Implements Java-based Page Object Model design to encapsulate web elements, allowing for a wide scope of testing.

---

## Open Source Projects

- **SQL Database Migration Visualizer (C, C++)**
    - [Source code](https://github.com/danmxli/pg_migration_graph) 
    - PostgreSQL migration visualizer program.
    - Transforms SQL schema changes into weighted directed graphs using AST parsing and graph theory.

---

## Links
- **LinkedIn**: [linkedin.com/in/danli591](https://www.linkedin.com/in/danli591/)
- **GitHub**: [github.com/danmxli](https://github.com/danmxli)
