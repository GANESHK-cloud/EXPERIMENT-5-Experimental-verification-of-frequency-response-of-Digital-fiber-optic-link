
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

*(Insert block diagram here)*
<img width="697" height="404" alt="image" src="https://github.com/user-attachments/assets/29386b96-ae4f-4c21-b916-76e7e190c3f9" />

---


## CONNECTION DIAGRAM  
**Setting up a Digital Link**

*(Insert connection diagram here)*
![WhatsApp Image 2025-11-17 at 9 02 04 PM](https://github.com/user-attachments/assets/fa8ca070-e999-4f87-9a24-73a75340566b)

---

## TABULATION  
**Transmission through Digital Link**

![WhatsApp Image 2025-11-17 at 9 04 24 PM](https://github.com/user-attachments/assets/3b5717dd-49e9-42ff-9d44-c0fa4d32a048)

---

## MODEL GRAPH

*(Insert model graph here)*
<img width="1236" height="693" alt="image" src="https://github.com/user-attachments/assets/c20e0dea-9082-4ee4-a160-52df9991dace" />

---

## GRAPH
![WhatsApp Image 2025-11-23 at 18 36 37_dc9e6eb5](https://github.com/user-attachments/assets/4adce8da-3274-4ad2-9639-3d218dd6de82)

## RESULT

*(Summarize observations and conclusions here)*
Thus the optic fibre digital link is studied succesfully
