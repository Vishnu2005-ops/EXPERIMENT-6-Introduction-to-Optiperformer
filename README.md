
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## AIM
Download and install OptiPerformer software on your computer and run a sample file.

---

## EQUIPMENTS REQUIRED:

Optisystem Software – OptiPerformer 22.0

## THEORY

Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses 
the full power of OptiSystem and creates specific dynamic design scenarios which can be used by 
students.
In this exercise, you will download and install OptiPerformer on your PC/laptop. Your license of 
OptiPerformer will be capable of loading and running OptiSystem simulations prepared for this 
course.
Once you have installed OptiPerformer, you can copy the first file (named:
‘Introduction_OptiPerformer.osp’) to your PC and run the simulation. The first file is a basic fiber 
optic system consisting of a transmitter, a fiber and a receiver. The system is “instrumented” with 
an optical power meter at the input to receiver (or the output of the fiber) and a bit error rate (BER) 
analyzer.

---

## PROCEDURE

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

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

![WhatsApp Image 2025-11-21 at 21 31 13_27bd1543](https://github.com/user-attachments/assets/b97ec0fb-e90a-4049-8af0-20ad7acb8dea)

---
## BLOCK DIAGRAM
-
<img width="1235" height="670" alt="image" src="https://github.com/user-attachments/assets/e1496dd8-cf75-4d3f-b4e0-15b361d1fc19" />
---


## Graphs

<img width="1909" height="975" alt="image" src="https://github.com/user-attachments/assets/78fe6d2e-33fc-4c3d-9bb6-d8e54d6ee21b" />

<img width="728" height="785" alt="image" src="https://github.com/user-attachments/assets/88e347fe-3ad6-47e1-bcd5-786572080970" />


---

## RESULT

The optical communication system was successfully simulated using OptiPerformer. As the fiber length increased from 50 km to 150 km, the following trends were observed: Received optical power decreased due to fiber attenuation. Q-factor gradually decreased, indicating signal quality degradation. Bit Error Rate (BER) increased with distance, showing higher error probability. The eye diagram became more closed at longer fiber lengths, confirming dispersion and noise effects. Hence, the simulation verified that optical signal performance deteriorates with increasing fiber length due to attenuation and dispersion losses.
