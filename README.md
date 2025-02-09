
Memristor-Based Leaky Integrate-and-Fire (LIF) Neuron Model
<big>Overview<big/>
This project implements a Leaky Integrate-and-Fire (LIF) neuron model using memristors in MATLAB/Simulink. The model replicates the spiking behavior of biological neurons while leveraging the memristor's non-volatile memory and analog resistance properties for neuromorphic computing.

<big>#Working Principle<big/>
The circuit operates in different phases to mimic neural activity:

1️⃣ Initial State
A current source charges the capacitor.
The memristor starts in its high-resistance state (HRS).
<br>
2️⃣ Charging Phase
The capacitor voltage (Vc) increases exponentially.
The memristor remains in HRS.
<br>
3️⃣ Threshold Detection
When Vc reaches a threshold (Vth), the memristor switches to a low-resistance state (LRS).
<br>
4️⃣ Discharging Phase
The capacitor rapidly discharges through the memristor and MOSFETs.
The system generates a spike (firing event).
<br>
5️⃣ Reset Phase
The circuit resets as the capacitor discharges to 0V, and the memristor returns to HRS.
The process repeats for each spike.
<br />
#Simulation Tools
MATLAB
<br />
Simulink
<br />
Simscape
<br />
Simulation Results
The model accurately replicates the spiking behavior of biological neurons. Below are snapshots of key phases:

Spiking & Reset:
![Result](https://github.com/user-attachments/assets/1c69dd69-2518-4f24-898d-5adbb88a48ae)

Applications

✅ Neuromorphic Computing
<br />
✅ Energy-efficient Neural Networks
<br />
✅ Brain-inspired AI Systems


How to Run the Simulation

1️⃣ Open MATLAB & Simulink.
<br>
2️⃣ Load the provided .slx file.
<br>
3️⃣ Run the simulation and observe neuron spiking behavior.

