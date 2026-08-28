# StructuredText

Tutorial to learn Structured Text from zero

Part 1: Laptop as an IPC & Environment Setup

1.1: Installing TwinCAT 3 XAE & Understanding the Architecture (IDE vs. Runtime)
1.2: Configuring your laptop as a local Software PLC (IPC runtime, core isolation, 7-day renewable trial licenses)  
1.3: Git workflow setup: Repository structure, branch management, and PR protocol for PLC projects

Part 2: Structured Text (ST) Foundations

2.1: PLC cyclic execution model (Scan cycles, Inputs $\rightarrow$ Logic $\rightarrow$ Outputs)  
2.2: Program Organization Units (POUs) & Declaration vs. Implementation areas
2.3: Basic Data Types (BOOL, INT, DINT, REAL, TIME, STRING)
2.4: Operators & Expressions (Arithmetic, Logical, Comparison, Precedence)
2.5: Conditional Execution (IF...THEN...ELSE, CASE...OF)
2.6: Loops in real-time systems (FOR, WHILE, PLC watchdog protection)  
2.7: Standard IEC Function Blocks:Edge Detection (R_TRIG, F_TRIG)Timers (TON, TOF, TP)Counters (CTU, CTD)

Part 3: Modular Architecture & Control Patterns

3.1: Complex Data Types: Arrays, Structures (STRUCT), Enumerations (ENUM)
3.2: Functions (FUN) vs. Function Blocks (FB) & Variable Scopes (VAR_INPUT, VAR_OUTPUT, VAR_IN_OUT, GVL)
3.3: Industrial Finite State Machines (FSM design pattern)3.4: Diagnostics: TwinCAT online monitoring, forcing variables, and Scope View

Part 4: TwinCAT HMI Programming

4.1: Introduction to TwinCAT HMI (Server, Client, and Web-based UI concepts)
4.2: Building your first HMI view (Buttons, Indicators, Text boxes, Gauges)
4.3: ADS Data Binding: Connecting UI elements to PLC Structured Text variables
4.4: HMI Event Handling & Actions (On-click triggers, setpoint entry, alarms)

Part 5: Integrated Hands-On Capstone Projects

Project 1: Industrial Tank Level & Pump ControlPLC: Automatic level control, hysteresis, pump duty cycling, alarm limits.HMI: Live tank level gauge, start/stop station, manual override, fault banner.

Project 2: Multi-State Traffic Intersection & Pedestrian CrossingPLC: FSM sequencer, crosswalk request logic, emergency flash mode.HMI: Visual intersection display, live countdown timers, mode selector.

Project 3: Automated Batch Mixing & Recipe SystemPLC: Recipe array management, sequential valve sequencing, batch timers.HMI: Recipe selector, live batch progress bar, temperature trend display.