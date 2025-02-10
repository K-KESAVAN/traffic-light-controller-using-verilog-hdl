# traffic-light-controller-using-verilog-hdl
🚦 Traffic Light Controller using Verilog HDL
📌 Project Overview
This project implements a Traffic Light Controller using Verilog HDL and is simulated in ModelSim. The system operates using a Finite State Machine (FSM) to control traffic lights in a single direction.

🛠️ Features
✔️ Finite State Machine (FSM) based design
✔️ Three traffic light states:

🟥 Red Light (Stop) → 20s
🟨 Yellow Light (Caution) → 5s
🟩 Green Light (Go) → 15s
✔️ Synchronous state transitions with a clock signal
✔️ Reset functionality for initial conditions
✔️ ModelSim simulation for functional verification
🏗️ Finite State Machine (FSM)
The controller transitions through three states in a continuous loop:

1️⃣ State 1: Red Light ON (20 seconds)
2️⃣ State 2: Yellow Light ON (5 seconds)
3️⃣ State 3: Green Light ON (15 seconds)
🖥️ Simulation in ModelSim
The project was simulated in ModelSim, where the FSM transitions were verified.

🖼️ Simulation Waveform Output
📌 The waveform output confirms the correct timing and state transitions of the traffic lights.

(👉 Add a screenshot of your waveform output here 📷)

🚀 How to Run
1️⃣ Clone this repository

bash
Copy
Edit
git clone https://github.com/yourusername/traffic-light-controller-verilog.git
cd traffic-light-controller-verilog
2️⃣ Open ModelSim and load the Verilog files
3️⃣ Compile and simulate the project
4️⃣ Observe the FSM transitions and traffic light timings

📌 Applications
✔️ Can be extended for real-world traffic systems 🚦
✔️ Useful for learning FSM-based Verilog design 🏗️
✔️ Can be integrated into FPGA-based projects 🔬

📢 Future Enhancements
🔹 Expand the system for multi-directional traffic control
🔹 Add pedestrian crossing signals 🚶‍♂️🚦
🔹 Implement sensor-based adaptive traffic control

