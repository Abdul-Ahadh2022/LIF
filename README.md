
Memristor-Based Leaky Integrate-and-Fire (LIF) Neuron Model
#Overview
This project implements a Leaky Integrate-and-Fire (LIF) neuron model using memristors in MATLAB/Simulink. The model replicates the spiking behavior of biological neurons while leveraging the memristor's non-volatile memory and analog resistance properties for neuromorphic computing.

#Working Principle
The circuit operates in different phases to mimic neural activity:

1️⃣ Initial State
A current source charges the capacitor.
The memristor starts in its high-resistance state (HRS).

2️⃣ Charging Phase
The capacitor voltage (Vc) increases exponentially.
The memristor remains in HRS.

3️⃣ Threshold Detection
When Vc reaches a threshold (Vth), the memristor switches to a low-resistance state (LRS).

4️⃣ Discharging Phase
The capacitor rapidly discharges through the memristor and MOSFETs.
The system generates a spike (firing event).

5️⃣ Reset Phase
The circuit resets as the capacitor discharges to 0V, and the memristor returns to HRS.
The process repeats for each spike.

#Simulation Tools
MATLAB
Simulink
Simscape

Simulation Results
The model accurately replicates the spiking behavior of biological neurons. Below are snapshots of key phases:

Spiking & Reset:
![Result](https://github.com/user-attachments/assets/1c69dd69-2518-4f24-898d-5adbb88a48ae)

Applications
✅ Neuromorphic Computing
✅ Energy-efficient Neural Networks
✅ Brain-inspired AI Systems


How to Run the Simulation
1️⃣ Open MATLAB & Simulink.
2️⃣ Load the provided .slx file.
3️⃣ Run the simulation and observe neuron spiking behavior.

