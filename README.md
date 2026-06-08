# Performance Analysis of 5G Network Slicing

## Overview

This project presents a simulation-based framework for analyzing the performance of **5G Network Slicing** using Python and SimPy. The simulator models three standard 5G service categories—**URLLC (Ultra-Reliable Low Latency Communication)**, **eMBB (Enhanced Mobile Broadband)**, and **mMTC (Massive Machine Type Communication)**—and evaluates their behavior under dynamic traffic conditions.

The project demonstrates how network slicing improves Quality of Service (QoS), resource allocation, traffic isolation, and overall network efficiency compared to traditional non-sliced networks.

---

## Objectives

* Simulate multiple 5G network slices with independent resources.
* Analyze slice-specific performance under varying traffic loads.
* Implement QoS-aware priority scheduling.
* Demonstrate slice isolation and resource allocation.
* Measure latency, throughput, and packet loss.
* Compare network performance with and without slicing.
* Visualize network topology and real-time performance trends.

---

## 5G Slices Implemented

### URLLC (Ultra-Reliable Low Latency Communication)

**Applications**

* Autonomous Vehicles
* Remote Surgery
* Industrial Automation

**Characteristics**

* Lowest latency
* Highest priority
* Reliable communication

---

### eMBB (Enhanced Mobile Broadband)

**Applications**

* Video Streaming
* Online Gaming
* Video Conferencing

**Characteristics**

* High throughput
* Large bandwidth allocation
* Enhanced user experience

---

### mMTC (Massive Machine Type Communication)

**Applications**

* Smart Cities
* IoT Devices
* Sensor Networks

**Characteristics**

* Massive device connectivity
* Scalable communication
* Lower priority than URLLC

---

## Features

* 5G Network Slice Simulation
* Dynamic User Traffic Generation
* QoS-Based Priority Scheduling
* Slice Isolation
* Congestion Modeling
* Packet Loss Analysis
* Throughput and Latency Evaluation
* Network Topology Visualization
* Real-Time Animated Performance Monitoring
* Comparison of Sliced vs Non-Sliced Networks

---

## Technologies Used

* Python
* SimPy
* NumPy
* Pandas
* Matplotlib
* NetworkX
* Celluloid
* Google Colab

---

## System Workflow

1. Create URLLC, eMBB, and mMTC slices.
2. Configure bandwidth, priority, and user count.
3. Generate dynamic user traffic.
4. Apply QoS-aware priority scheduling.
5. Implement slice isolation.
6. Simulate congestion and packet loss.
7. Measure latency, throughput, and packet loss.
8. Compare sliced and non-sliced networks.
9. Visualize topology and performance metrics.
10. Analyze results.

---

## Performance Metrics

### Latency

Measures the delay experienced during packet transmission.

### Throughput

Measures the amount of successfully transmitted data.

### Packet Loss

Measures the number of packets dropped due to congestion.

---

## Network Topology

The simulator models:

* 5G Core Network
* Base Stations
* Connected Users
* Slice-Based Resource Allocation

Topology visualization is implemented using NetworkX.

---

## Results

The simulation demonstrates:

* URLLC achieves the lowest latency.
* eMBB provides high throughput for bandwidth-intensive applications.
* mMTC supports a large number of connected devices.
* Slice isolation prevents traffic in one slice from affecting others.
* Network slicing improves QoS and resource management compared to traditional networks.

---

## Sample Output

### Slice Performance Metrics

| Slice | Latency | Throughput | Packet Loss |
| ----- | ------- | ---------- | ----------- |
| URLLC | Low     | Medium     | Low         |
| eMBB  | Medium  | High       | Medium      |
| mMTC  | High    | Medium     | Higher      |

---


## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/5G-Network-Slicing-Simulator.git
cd 5G-Network-Slicing-Simulator
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the simulation:

```bash
python slicing_simulation.py
```

---

## Future Enhancements

* AI-Based Resource Allocation
* Reinforcement Learning Scheduler
* Edge Computing Integration
* Handover Simulation
* Energy-Efficient Scheduling
* Open5GS Integration
* Interactive Dashboard
* 3D Network Visualization

---

## Learning Outcomes

Through this project, the following concepts were explored:

* 5G Network Architecture
* Network Slicing
* Quality of Service (QoS)
* Resource Allocation
* Traffic Engineering
* Congestion Control
* Performance Analysis
* Event-Driven Simulation
* Network Visualization

---

## Author

**RIA JAVALAGI**

Computer Science Engineering Student

Project: Performance Analysis of 5G Network Slicing
