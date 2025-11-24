N.Sugandan
212222060260
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

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
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM
<img width="583" height="212" alt="image" src="https://github.com/user-attachments/assets/c35e54c0-0548-44fd-8a64-a0ba835c67d3" />


## CONNECTION DIAGRAM  
**Setting up an Analog Link**

<img width="586" height="124" alt="image" src="https://github.com/user-attachments/assets/ddf4d8d9-debb-4603-adc2-0da02a34f803" />



## TABULATION  
**Transmission through Analog Link**

<img width="1600" height="1312" alt="17639575538156220484554220972572" src="https://github.com/user-attachments/assets/918bf323-9e95-45b1-8790-6cb9b0e204c4" />

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----50Hz--------|-------138V-------------------|-----0.644---|----0.988--------|
|    8.33Hz              150V                          0.700       1.549
|    9.86Hz              138V                    |     0.691  |    1.605      |
     10.2Hz              148V                          0.691       1.605
     15KHz               148V                          0.684       1.624
     16KHz               148V                          0.672       1.726
     33KHz               148V                          0.682       1.824
     3MHz                136V                          0.28        1.934
     
## MODEL GRAPH

<img width="674" height="331" alt="17639574149906912604211665294583" src="https://github.com/user-attachments/assets/63a3f696-2def-4af5-8ce4-edc71f1aaa81" />

<img width="1350" height="990" alt="17639574777783351570689751360517" src="https://github.com/user-attachments/assets/52c2dbf4-758d-4a0c-a894-6d97f55277d8" />

## Result:

The experimental verification of frequency response of analog fiber optic is done successfully

esult:
