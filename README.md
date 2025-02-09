# Memristor-Based Leaky Integrate-and-Fire (LIF) Neuron Model

## Overview
This project implements a Leaky Integrate-and-Fire (LIF) neuron model using memristors in MATLAB/Simulink. The model replicates the spiking behavior of biological neurons while leveraging the memristor's non-volatile memory and analog resistance properties for neuromorphic computing.

## Working Principle
The circuit operates in different phases to mimic neural activity:

<ol>
  <li><b>Initial State</b><br>
      A current source charges the capacitor. The memristor starts in its high-resistance state (HRS).
  </li>
  <li><b>Charging Phase</b><br>
      The capacitor voltage (V<sub>c</sub>) increases exponentially. The memristor remains in HRS.
  </li>
  <li><b>Threshold Detection</b><br>
      When V<sub>c</sub> reaches a threshold (V<sub>th</sub>), the memristor switches to a low-resistance state (LRS).
  </li>
  <li><b>Discharging Phase</b><br>
      The capacitor rapidly discharges through the memristor and MOSFETs. The system generates a spike (firing event).
  </li>
  <li><b>Reset Phase</b><br>
      The circuit resets as the capacitor discharges to 0V, and the memristor returns to HRS. The process repeats for each spike.
  </li>
</ol>

## Simulation Tools
<ul>
  <li>MATLAB</li>
  <li>Simulink</li>
  <li>Simscape</li>
</ul>

## Simulation Results
The model accurately replicates the spiking behavior of biological neurons. Below are snapshots of key phases:
<ul>
  <li><b>Charging Phase</b></li>
  <li><b>Threshold Detection</b></li>
  <li><b>Firing Event</b></li>
  <li><b>Reset Phase</b></li>
</ul>

## Spiking & Reset:
![Result](https://github.com/user-attachments/assets/1c69dd69-2518-4f24-898d-5adbb88a48ae)

## Applications
<ul>
  <li>Neuromorphic Computing</li>
  <li>Energy-efficient Neural Networks</li>
  <li>Brain-inspired AI Systems</li>
</ul>

## How to Run the Simulation
<ol>
  <li>Open MATLAB & Simulink.</li>
  <li>Load the provided .slx file.</li>
  <li>Run the simulation and observe neuron spiking behavior.</li>
</ol>

