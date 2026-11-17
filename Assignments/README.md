# Mobile Computing (ITA03-MP) – Comprehensive Frontend Implementation & Execution Suite

This workspace contains **complete frontend implementations and standalone executions** for every assignment and every question from the course syllabus and specification document.

---

## 🗂️ Workspace Architecture

```
Assignments_Final/
├── index.html                           # 🏠 Master Navigation & Execution Portal
├── README.md                            # Comprehensive Documentation & Execution Guide
│
├── Assignment_1/                        # CO1: Hexagonal Cellular Network Planning & Spectrum Allocation (50 Marks)
│   ├── Task_01/index.html               # Task 01: Alternative Frequency-Planning Strategies (5M)
│   ├── Task_02/index.html               # Task 02: Identify Governing Design Parameter (2M)
│   ├── Task_03/index.html               # Task 03: Derive Capacity & SIR Functions Mathematically (6M)
│   ├── Task_04/index.html               # Task 04: Best, Average & Worst-Case Behaviour (4M)
│   ├── Task_05/index.html               # Task 05: Scaling and Sensitivity Analysis (3M)
│   ├── Task_06/index.html               # Task 06: Recurrence for Repeated Cell Splitting (3M)
│   ├── Task_07/index.html               # Task 07: Solve Recurrence & Interpret Result (4M)
│   ├── Task_08/index.html               # Task 08: Monte-Carlo Simulator & Correctness Checks (4M)
│   ├── Task_09/index.html               # Task 09: Record & Present Experimental Performance (3M)
│   ├── Task_10/index.html               # Task 10: Compare Theory with Simulation (4M)
│   ├── Task_11/index.html               # Task 11: Recommend and Defend Final Design (4M)
│   └── Task_12/index.html               # Task 12: Day-4 Stadium Convocation Design Challenge (8M)
│
├── Assignment_2/                        # CO2: Mobile Telecommunications & Multiple Access Techniques (50 Marks)
│   ├── Question_01/index.html           # Q01: Mobile Comm vs Mobile Computing (Store & Forward) (5M)
│   ├── Question_02/index.html           # Q02: Sharing Channel – FDMA vs TDMA Under Traffic (6M)
│   ├── Question_03/index.html           # Q03: CDMA – Orthogonality, Spreading & Near-Far (7M)
│   ├── Question_04/index.html           # Q04: OFDMA – Subcarrier Allocation & Jain's Fairness (6M)
│   ├── Question_05/index.html           # Q05: SDMA – Directional Antennas & Toll Plaza (6M)
│   ├── Question_06/index.html           # Q06: Multiple-Access Selection & Sensitivity Matrix (7M)
│   └── Question_07/index.html           # Q07: Day-4 Bottleneck Redesign: Dynamic PRMA Hybrid (13M)
│
├── Assignment_3/                        # CO3: Wireless Networks, Mobile IP & Routing (Pair Work - 50 Marks)
│   ├── Question_01/index.html           # Q01: Architecture & Mobility RSSI Handoff (6M)
│   ├── Question_02/index.html           # Q02: Mobile IP Entities, Tunneling & Triangular Routing (7M)
│   ├── Question_03/index.html           # Q03: Cellular vs Ad-Hoc Networks in Disasters (7M)
│   ├── Question_04/index.html           # Q04: Mobile IP Healthcare Connected Ambulance (7M)
│   ├── Question_05/index.html           # Q05: Proactive Routing (DSDV Sequence Numbers) (6M)
│   ├── Question_06/index.html           # Q06: Reactive Routing (AODV vs DSDV) (7M)
│   └── Question_07/index.html           # Q07: Day-4 Collaborative Emergency Disaster Network (10M)
│
├── Assignment_4A/                       # CO4 Part I: Mobile App Development – Architectural Reasoning (50 Marks)
│   ├── Task_01/index.html               # Task 01: OS Architecture Review & Layered Specification (6M)
│   ├── Task_02/index.html               # Task 02: Platform Comparison & Screen-Off Push Trace (8M)
│   ├── Task_03/index.html               # Task 03: Runtime Analysis: Cold vs Warm Launch Sequence (9M)
│   ├── Task_04/index.html               # Task 04: Security Forensics: SecureNotes Audit & Repair (7M)
│   ├── Task_05/index.html               # Task 05: Power Management & 15% Battery-Saver Policy (7M)
│   └── Task_06/index.html               # Task 06: RuralCare Field-Data Collection Platform Strategy (13M)
│
├── Assignment_4B/                       # CO4 Part II: Mobile Systems Engineering (50 Marks)
│   ├── Task_01/index.html               # Task 01: OS Resource-Management Engine & oom_adj (8M)
│   ├── Task_02/index.html               # Task 02: Architecture Assumptions vs Reality (Threading) (9M)
│   ├── Task_03/index.html               # Task 03: ART Compilation Modes & Memory Leak Failure (10M)
│   ├── Task_04/index.html               # Task 04: Secure Mobile App Audit Workbench (STRIDE) (7M)
│   ├── Task_05/index.html               # Task 05: Three Power Engineers (DVFS, Doze, Wakelocks) (7M)
│   └── Task_06/index.html               # Task 06: Battery-Aware Secure Field Tracker Prototype (9M)
│
└── Assignment_5/                        # CO5: Android Features & Performance Engineering (50 Marks)
    ├── Task_A1/index.html               # Task A1: Constraint-Aware Intent & Service Architecture (7M)
    ├── Task_A2/index.html               # Task A2: Safe Incremental Data Replication & Pruning (5M)
    ├── Task_A3/index.html               # Task A3: Generic Mobile-Background Design Pattern (5M)
    ├── Task_A4/index.html               # Task A4: Tractability: Local vs Cloud Processing Classes (4M)
    ├── Task_A5/index.html               # Task A5: UI Scrolling Heuristic & Approximation (4M)
    ├── Task_B1/index.html               # Task B1: Instrumented Background Pipeline (FIFO vs Priority) (7M)
    ├── Task_B2/index.html               # Task B2: Adversarial Workload Engineering & Churn (5M)
    ├── Task_B3/index.html               # Task B3: Exact vs Approximate UI Benchmark (8M)
    └── Task_B4/index.html               # Task B4: Multimedia Framework Selection Decision Note (5M)
```

---

## 🚀 How to Execute

### Option 1: Direct Browser Launch
Each question is **100% self-contained** with zero external network or build dependencies.
Simply navigate into any question folder in Windows Explorer and double-click `index.html`.

### Option 2: Master Navigation Hub
Open `index.html` at the root of `Assignments_Final/` in any modern web browser to access the central dashboard:
- Instant search and filtering across all 47 modules.
- One-click launch into any assignment task.
- Breadcrumb navigation (`⬅️ Previous`, `Next ➡️`, `🏠 Master Hub`) embedded in every single page.

### Option 3: Local HTTP Server
Run a local Python server:
```powershell
python -m http.server 8000
```
Then visit: `http://localhost:8000`

---

## 🌟 Key Technical Highlights

1. **Exact Mathematical and Algorithmic Fidelity:**
   - **Assignment 1:** Dynamic Hexagonal lattice generator, Erlang-B numerical solvers, co-channel reuse distance ($D = R\sqrt{3N}$), Monte Carlo path-loss SIR calculation with 18.7 dB sanity check.
   - **Assignment 2:** Walsh-Hadamard code generation, CDMA near-far power disparity simulation, OFDMA subcarrier Rayleigh fading allocator with Jain's Fairness Index, ULA smart antenna beam steering ($AF(\theta)$).
   - **Assignment 3:** Live RSSI handoff trajectory simulator, Mobile IP triangular routing and IP-in-IP tunneling visualizer, DSDV sequence-number routing table updater, AODV on-demand route discovery.
   - **Assignment 4A & 4B:** Deep Android OS resource management (`dumpsys meminfo`, `oom_score_adj`), ART compilation mode comparative profiler, single vs multi-threaded lock contention counter-examples, STRIDE security audit engine, and battery-aware state policy $P[Battery][Network][Motion]$.
   - **Assignment 5:** Android Intent/Service constraint pruning engine, FIFO vs Priority background schedulers, exact vs greedy scrolling feed heuristic benchmark, and production video transcoding optimizer.

2. **SIMATS-Standard Algorithmic Pseudocode:**
   - Every algorithm strictly conforms to the SIMATS Engineering standard defined in pages 35-62 of the specification: `ALGORITHM ...`, `INPUT:`, `OUTPUT:`, `BEGIN`, `END`, `←`, explicit state names, and zero reliance on programming-language shortcuts.

3. **Data Export & Reporting:**
   - Every simulation includes CSV export and JSON trace generation for submission verification.
