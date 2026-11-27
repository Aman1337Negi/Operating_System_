# Operating Systems Lab: Python Implementations

A collection of Python programs that simulate core **Operating Systems** concepts. The programs cover CPU scheduling, deadlock avoidance, memory management, synchronization, file allocation, disk scheduling, and process and thread handling. They were written for learning and lab practice.

---

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Programs Included](#programs-included)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Concepts Covered](#concepts-covered)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

---

## Overview

This repository contains Python simulations of fundamental OS algorithms and classic synchronization problems. Each program is a standalone script. You can run any of them on its own to see how the algorithm behaves.

---

## Project Structure

```text
OS/
├── bankers_algorithm.py
├── cpu_scheduling.py
├── dining_philosophers.py
├── disk_scheduling.py
├── file_allocation.py
├── memory_allocation.py
├── page_replacement.py
├── process_creation.py
├── producer_consumer.py
├── readers_writers.py
├── thread_sum.py
└── README.md
```

---

## Programs Included

| File | Topic | Description |
|------|-------|-------------|
| `bankers_algorithm.py` | Deadlock Avoidance | Banker's Algorithm to check for a safe state and a safe sequence |
| `cpu_scheduling.py` | CPU Scheduling | Process scheduling algorithms such as FCFS, SJF, Priority and Round Robin |
| `dining_philosophers.py` | Synchronization | The Dining Philosophers problem, with deadlock-free resource sharing |
| `disk_scheduling.py` | Disk Management | Disk scheduling algorithms such as FCFS, SSTF, SCAN and C-SCAN |
| `file_allocation.py` | File Systems | File allocation strategies such as sequential, indexed and linked |
| `memory_allocation.py` | Memory Management | Allocation strategies such as First Fit, Best Fit and Worst Fit |
| `page_replacement.py` | Virtual Memory | Page replacement algorithms such as FIFO, LRU and Optimal |
| `process_creation.py` | Process Management | Creating and managing processes |
| `producer_consumer.py` | Synchronization | The Producer-Consumer (bounded buffer) problem |
| `readers_writers.py` | Synchronization | The Readers-Writers problem |
| `thread_sum.py` | Multithreading | Computing a sum using multiple threads |

> **Note:** The algorithms listed for each topic are typical examples. Edit the table to match what each script actually implements.

---

## Prerequisites

- **Python 3.8 or higher**
- A terminal or command prompt
- No external libraries are required unless a script says otherwise. Most programs use only the Python standard library, such as `threading`, `multiprocessing` and `os`.

Check your Python version:

```bash
python --version
```

---

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/[your-username]/[your-repository-name].git
   ```

2. **Move into the project folder**

   ```bash
   cd [your-repository-name]
   ```

---

## Usage

Run any program with Python:

```bash
python <filename>.py
```

Examples:

```bash
python cpu_scheduling.py
python bankers_algorithm.py
python page_replacement.py
```

Some programs ask for input, such as the number of processes, burst times or resource matrices. Follow the on-screen prompts.

> **Note:** `process_creation.py` may use `os.fork()`, which is available only on Unix-based systems (Linux and macOS). On Windows, run it with **WSL** or use `multiprocessing` instead.

---

## Concepts Covered

- **Process Management:** process creation, scheduling and execution
- **Concurrency and Synchronization:** semaphores, mutexes and classic synchronization problems
- **Deadlock Handling:** the safe-state check in the Banker's Algorithm
- **Memory Management:** contiguous allocation and page replacement
- **Storage Management:** file allocation methods and disk scheduling
- **Multithreading:** parallel computation with threads

---

## Contributing

Contributions and suggestions are welcome.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## Author

**[Your Name]**
GitHub: [@your-username](https://github.com/your-username)

---

## License

This project is licensed under the [MIT License](LICENSE). It is intended for educational use.
