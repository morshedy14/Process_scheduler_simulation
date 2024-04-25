# Multiprocessor Scheduling Simulation

## Project Overview
This project simulates a multiprocessor system scheduler, demonstrating dynamic scheduling with multiple algorithms and processor interactions to optimize task management.

## Features
- **Multiple Processors**: Simulates multiple processors, each with its own queue and one of three scheduling algorithms: FCFS, SJF, and RR.
- **Dynamic Process States**: Processes transition through states including New, Ready, Running, Blocked, Terminated, and Orphan.
- **Advanced Scheduling Features**:
  - **Process Migration**: Allows processes to migrate between processors.
  - **Work-Stealing**: Balances load by moving tasks from busier to less busy processors.
  - **Process Control**: Supports forking, killing (SIGKILL), and managing orphan processes.

## Getting Started

### Prerequisites
- C++ compiler (e.g., GCC, Clang)
  


## Input and Output
- **Input**: A structured text file specifying processor types and detailed process attributes.
- **Output**: Outputs logs detailing process states, processor status, and scheduling outcomes.
