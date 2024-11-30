# **5G Network Simulator**

## **Project Overview**
The **5G Network Simulator** is a tool designed to simulate the architecture and behavior of a 5G network. This simulator models key components of a 5G network, such as User Equipment (UE), gNodeBs (gNB), and the Core Network (CN), allowing users to experiment with network configurations and traffic flows.

The primary goal of this project is to provide an interactive platform for understanding the 5G architecture and to serve as a showcase project for learning and job application purposes.

---

## **Project Goals**
- Simulate the 5G network architecture, including:
  - **User Equipment (UE):** Devices that connect to the network.
  - **gNodeB (gNB):** Base stations that provide wireless connectivity.
  - **Core Network (CN):** Central part of the network for managing traffic and sessions.
- Provide a Command-Line Interface (CLI) for configuring and observing the simulation.
- Offer a modular codebase for easy extension and experimentation.
- Demonstrate proficiency in C++ for building efficient network simulators.

---

## **Features**
- Basic simulation of 5G network components and topology.
- Dynamic configuration of network parameters via CLI.
- Simulation logging and performance metrics.
- Expandable design for adding new features like additional protocols or enhanced visualization.

---

## **Getting Started**

### **Prerequisites**
Ensure the following tools are installed on your system:
1. **C++ Compiler**: GCC or Clang (supports C++17 or higher).
2. **CMake**: Version 3.10 or higher.
3. **Make**: For building the project.

### **Cloning the Repository**
```bash
git clone https://github.com/hamidaebadi/5G_Network_Simulator.git
cd 5G_Network_Simulator
```

## **Building the Project**

### ** Step1: Create a build directory**

`mkdir build`
`cd build`

### **Step 2: Run Cmake**
`cmake ..`

### Step3: Build the project
`make`


### Running the project
After a successfull build, run the simulator executable
`./5G_Simulator`

