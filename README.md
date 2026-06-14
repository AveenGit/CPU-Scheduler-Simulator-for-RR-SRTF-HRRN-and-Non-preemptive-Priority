# CPU-Scheduling Algorithm-Simulator-for-RR-SRTF-HRRN-and-Non-preemptive-Priority

A Java Swing-based desktop application that simulates and compares four CPU scheduling algorithms.

Built for CSF3213 — Operating System, University Malaysia Terengganu.

---

## Algorithms Implemented

| Algorithm | Type |
|---|---|
| Round Robin (RR) | Preemptive |
| Shortest Remaining Time First (SRTF) | Preemptive |
| Highest Response Ratio Next (HRRN) | Non-Preemptive |
| Non-Preemptive Priority | Non-Preemptive |

---

## Features

- Enter your own processes (PID, Arrival Time, Burst Time)
- Priority field appears only when Non-Preemptive Priority is selected
- Quantum field appears only when Round Robin is selected
- Visual Gantt chart drawn automatically after running
- Results table showing WT, TAT, RT per process
- Summary metrics — Average WT, Average TAT, Average RT, Throughput

---

## How to Run

1. Make sure Java is installed (JDK 17 or above)
2. Clone or download this repository
3. Open the project in IntelliJ IDEA
4. Run `Main.java`

Or compile and run manually:
```bash
cd src
javac cpuscheduler/**/*.java cpuscheduler/Main.java
java cpuscheduler.Main
```

---

## Project Structure
