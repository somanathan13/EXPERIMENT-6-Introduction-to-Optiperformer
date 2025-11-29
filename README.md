
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Aim
To analyze and evaluate the performance of an optical communication system by studying the relationship between fiber length, received power, Q factor and Bit Error Rate(BER) and to observe changes in the eye diagram with increasing fiber length using optiperformer.

---

## Theory

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Observation

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---




## Tabulation

**Transmission Analysis Across Fiber Lengths**
![WhatsApp Image 2025-11-17 at 22 20 19_0ea46e93](https://github.com/user-attachments/assets/2aaf9c2b-8253-4bbf-9372-b7e87589eb10)


---

## Block Diagram

<img width="744" height="427" alt="image" src="https://github.com/user-attachments/assets/03bc0a41-a555-4c34-ac88-e3496c3a00ce" />

## Graphs

<img width="728" height="785" alt="image" src="https://github.com/user-attachments/assets/f2d98e71-d102-455a-b643-25848059cd90" />
---

## RESULT

hence the optical performace of fiber cable studiend and proved at different rates.


