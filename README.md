# CPU-Scheduling-Algorithms-Simulator
🧠 A Python-based simulator for various CPU Scheduling Algorithms including First-Come-First-Serve (FCFS), Shortest Job First (SJF), Round Robin, and Priority Scheduling. Ideal for operating systems coursework, this tool visualizes process execution and computes essential metrics like turnaround time and waiting time.


Great! You've uploaded your project file `cpu_scheduling.zip`. Based on the name, I’ll assume it’s related to CPU scheduling algorithms (like FCFS, SJF, Round Robin, etc.). Here’s everything you need to publish it on GitHub:

---

### ✅ Suitable GitHub Repository Title:

```
CPU-Scheduling-Algorithms-Simulator
```

---

### ✅ Description for GitHub:

```
🧠 A Python-based simulator for various CPU Scheduling Algorithms including First-Come-First-Serve (FCFS), Shortest Job First (SJF), Round Robin, and Priority Scheduling. Ideal for operating systems coursework, this tool visualizes process execution and computes essential metrics like turnaround time and waiting time.
```

---

### ✅ README.md File Content:

```markdown
# 🧠 CPU Scheduling Algorithms Simulator

This project is a simple Python-based simulation of classic **CPU scheduling algorithms** typically studied in Operating Systems courses. It helps visualize how different algorithms manage process execution, and calculates important metrics such as turnaround time and waiting time.

---

## 🚀 Features

- **First-Come-First-Serve (FCFS)**
- **Shortest Job First (SJF)**
- **Round Robin Scheduling**
- **Priority Scheduling**
- Console-based simulation and process input
- Calculates:
  - Turnaround Time
  - Waiting Time
  - Average Times

---

## 🛠 Technologies Used

- **Python 3.x**
- **Basic file I/O and user input**
- **Matplotlib (optional, if graphical plots are added)**

---

## 📁 Project Structure

```

cpu\_scheduling/
│
├── fcfs.py             # FCFS Scheduling Logic
├── sjf.py              # SJF Scheduling Logic
├── round\_robin.py      # Round Robin Algorithm
├── priority.py         # Priority Scheduling
├── client\_perf.py      # (If exists) Performance evaluation module
├── README.md           # Project documentation
└── sample\_input.txt    # (Optional) Example input for testing

````

---

## 🧪 How to Run

1. **Clone the repository**  
```bash
git clone https://github.com/bhavyakosuri/CPU-Scheduling-Algorithms-Simulator.git
cd CPU-Scheduling-Algorithms-Simulator
````

2. **Run a simulation**

```bash
python fcfs.py
python sjf.py
python round_robin.py
```

3. **(Optional)**: Run performance comparison

```bash
python client_perf.py
```

---

## 🧾 Sample Input Format

```text
Enter number of processes: 3
Enter Arrival Time and Burst Time for each process:
P1 0 5
P2 1 3
P3 2 8
```

---

## 📊 Output Example

```text
Gantt Chart: | P1 | P2 | P3 |
Average Waiting Time: 4.33
Average Turnaround Time: 9.33
```

---

## 📜 License

This project is licensed under the MIT License. See `LICENSE` file for more details.

---

## 🙋‍♀️ Author

**Bhavya Naga Sai Kosuri**
[LinkedIn](https://www.linkedin.com/in/bhavyakosuri2209/) | [GitHub](https://github.com/bhavyakosuri)

---
