# 🧠 CPU Scheduling Algorithms Simulator

A **Python + HTML/JavaScript-based simulator** for various **CPU Scheduling Algorithms**, including:

- **First-Come-First-Serve (FCFS)**
- **Shortest Job First (SJF)** (Preemptive & Non-Preemptive)
- **Round Robin**
- **Priority Scheduling**

The project features a dynamic **Gantt Chart UI** to visualize the execution of these scheduling algorithms. Users input process details such as **arrival time**, **burst time**, and **priority** (if applicable). The system then calculates and displays key metrics:

- **Waiting Time**
- **Turnaround Time**
- **Completion Time**

Gantt Charts are color-coded by process, with an interactive timeline to display execution order, start, and end times. Hovering over a process reveals detailed data. Below the chart, a process table presents the scheduling results, and additional graphical comparisons display performance metrics across algorithms for an intuitive, analytical experience.

✅ **Perfect for Operating Systems coursework and scheduling algorithm demonstrations.**

---

## 🚀 Features

- 🟦 FCFS, SJF, Round Robin, Priority Scheduling  
- 🔁 Preemptive + Non-Preemptive Support (SJF)  
- 📊 Gantt Chart Visualization (HTML + JavaScript)  
- 🔤 Inputs via Python CLI or Web Interface  
- 📈 Average Waiting & Turnaround Time Calculation  
- 🎨 Frontend Styling via Bootstrap  

---

## 🌐 Web Interface

**To open the web interface:**

```bash
Open `index.html` in your browser
```
The interface uses:

HTML

CSS (style.css, cpu-scheduler.css)

JavaScript (cpu-scheduler.js, MathJaxSetup.js)

Bootstrap for responsive layout


🛠 Technologies Used

Python 3.x

HTML / CSS / JavaScript

Bootstrap

📁 Project Structure
cpu_scheduling/
│
├── Web Files
│   ├── index.html
│   ├── cpu-scheduler.js / .css
│   ├── docs.html / .css
│   ├── explanation.css
│   ├── ganttcharts.html
│   ├── style.css / bootstrap-simplex.css
│   ├── MathJaxSetup.js
│   ├── bootstrap.min.js, bootstrap-slider.js, new.js
│
├── images/
│   ├── CPU_Scheduling_1.png
│   ├── CPU_Scheduling_3.png
│   └── ...
│
├── CpuSchedulingDemo.webm
└── README.md

📽️ Demo

▶️ Watch the demo video below:
🎥 CpuSchedulingDemo.webm


🧪 How to Run (Python CLI)
Clone the repository

bash
Copy
Edit
git clone https://github.com/bhavyakosuri/CPU-Scheduling-Algorithms-Simulator.git
cd CPU-Scheduling-Algorithms-Simulator

🙋‍♂️ Author
Bhavya Naga Sai Kosuri
🔗 LinkedIn | 💻 GitHub
