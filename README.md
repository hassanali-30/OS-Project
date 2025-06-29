# Secure Operating System Simulator 🚀

A C++ project that simulates core OS functionalities including Hybrid CPU Scheduling, Deadlock Avoidance, Memory Management, and Secure Inter-Process Communication (IPC). Built for CS-303 Operating Systems at HITEC University.

## 👨‍💻 Authors
- Hassan Ali (23-CYS-035)
- Muneeb Ahmed (23-CYS-004)
- Shayan Latif (23-CYS-041)
- Syed Haider Abbas (23-CYS-038)

## 📌 Features

- 🧠 **Hybrid CPU Scheduler** (Round Robin + SRTF)
- 🔐 **Deadlock Avoidance** using Banker’s Algorithm
- 💾 **Memory Management** with Best Fit and LRU Paging
- 🔄 **Inter-Process Communication** (Shared Memory, Semaphores, Message Passing)
- 📈 **Performance Metrics** (Turnaround Time, Waiting Time, Throughput, CPU Utilization)

## 🗂️ Project Structure

os-simulator/
├── src/ # Source code files (.cpp)
├── include/ # Header files (.h)
├── Report/ # Final project report
├── screenshots/ # Output snapshots
├── sim_results.txt # Logged performance output
├── Makefile or build script (optional)
└── README.md

bash
Copy
Edit

## 🧑‍🏭 How to Compile & Run

```bash
# Compile
g++ -o os_sim src/*.cpp -pthread

# Run
./os_sim
