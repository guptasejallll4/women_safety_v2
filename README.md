# 🚔 Women Safety Night Patrolling System (Version 2)

### Proactive Machine Learning Framework for Risk-Aware Patrol Routing

---

## 📌 Overview

This project presents a **Proactive Machine Learning Framework for Women’s Night-Time Safety**, focusing on **risk-aware patrolling and intelligent route optimization**.

Unlike traditional systems that react after incidents, this framework uses **crime data + risk scoring + graph algorithms** to proactively identify high-risk zones and generate **optimized patrol routes**.

The system ensures that patrol teams **prioritize vulnerable areas** and reach them efficiently using algorithmic decision-making.

---

## 🎯 Objectives

* Identify high-risk zones using historical crime data
* Assign risk scores to different locations
* Generate efficient patrol routes using graph algorithms
* Optimize multi-zone patrolling using Genetic Algorithm
* Improve response time and coverage of vulnerable areas

---

## 🧠 Key Concepts

* 🔴 **Risk-Based Patrolling** (not random patrolling)
* 🗺️ **Graph-Based City Modeling** (nodes = zones, edges = roads)
* ⚠️ **Risk Score Integration** (crime + environment factors)
* 🚀 **Algorithmic Route Optimization**

---

## ⚙️ Algorithms Used

### 1. Dijkstra Algorithm

* Finds **shortest and safest path** to a single high-risk zone
* Guarantees optimal solution

### 2. A* Algorithm

* Faster than Dijkstra using **heuristics**
* Used for efficient real-time routing

### 3. Genetic Algorithm (GA)

* Optimizes patrol routes covering **multiple high-risk zones**
* Balances:

  * Distance
  * Risk
  * Coverage

---

## 🛠️ Tech Stack

**Language:** Python
**Libraries:**

* NetworkX (Graph Modeling)
* DEAP (Genetic Algorithm)
* Pandas, NumPy

**Concepts:**

* Graph Theory
* Optimization Algorithms
* Risk Scoring
* Pathfinding

---

## 🔄 Methodology

### 1. Data Collection

* Historical crime data
* Zone-based risk indicators

### 2. Data Preprocessing

* Clean and structure data
* Assign risk scores to zones

### 3. Graph Creation

* Represent city as a graph
* Nodes → Locations
* Edges → Distance + Risk

### 4. High-Risk Zone Identification

* Select zones with highest risk scores

### 5. Path Planning

* **Dijkstra** → shortest safe path
* **A*** → faster heuristic-based routing

### 6. Route Optimization

* **Genetic Algorithm** used for:

  * Multi-zone patrol routes
  * Maximum coverage
  * Minimum risk + distance

### 7. Evaluation

* Compare routes based on:

  * Distance
  * Risk
  * Coverage efficiency

---

## 📊 Expected Output

* Identification of **high-risk zones**
* Efficient routes to reach vulnerable areas
* Optimized patrol routes covering multiple zones
* Improved patrolling strategy using data-driven insights

---

## 📁 Project Structure

```id="str12"
├── data/                # Crime datasets
├── notebooks/           # Jupyter notebooks (analysis & models)
├── src/                 # Core algorithm implementations
├── outputs/             # Graphs / route visualizations
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

```bash id="run22"
# Clone repository
git clone https://github.com/your-username/women-safety-v2.git

# Navigate to project
cd women-safety-v2

# Install dependencies
pip install -r requirements.txt

# Run notebook or script
jupyter notebook
```

---

## 📷 Output Visualization

(Add screenshots here)

* Graph representation of zones
* Shortest path (Dijkstra / A*)
* Optimized route (Genetic Algorithm)

---

## 🚧 Challenges Faced

* Limited availability of accurate crime data
* Designing and tuning Genetic Algorithm
* Modeling real-world city as a graph
* Balancing risk vs distance in routing

---

## 💡 Future Scope

* Integration with real-time data sources
* Live GPS-based patrol tracking
* Smart city integration
* AI-based dynamic risk prediction

---

## 📚 Research Paper

Based on research:
**"A Proactive Machine Learning Framework for Women’s Night-Time Safety Using Crime Forecasting and Anomaly Detection"**

---

## 👩‍💻 Author

**Sejal Gupta**
M.Sc. Information Technology
Mumbai, India

---

## ⭐ Key Highlight

✔ Shift from **Reactive → Proactive Safety System**
✔ Combines **Machine Learning + Graph Algorithms + Optimization**
✔ Real-world application in **Smart City Safety Systems**

---

## 📢 Note

This project is developed for **academic and research purposes** and demonstrates how algorithmic intelligence can improve urban safety systems.

---
