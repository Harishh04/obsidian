## **Set 1 - Remaining Questions**

### **2. List the on-chip peripherals of the 8051 microcontroller.**

- Timers (Timer 0 & Timer 1)
    
- Serial communication (UART)
    
- Interrupt controller
    
- I/O ports (4 ports, 32 pins)
    

---

### **3. Name the I/O instructions of the 8051 microcontroller.**

- **IN & OUT Instructions:** Used for port input and output.
    
- **SETB & CLR:** Set and clear port bits.
    
- **MOVX & MOVC:** Used for external memory access.
    

---

### **4. Define the SBUF register in 8051 and mention its use.**

- **SBUF (Serial Buffer Register):** Temporary storage for serial data transmission and reception.
    
- Used in UART communication for holding received and transmitted bytes.
    

---

### **5. What is key bounce? How is it achieved?**

- **Key bounce:** When a mechanical switch is pressed, it vibrates before settling, causing multiple signals.
    
- **Debouncing methods:** Software (delay techniques) or hardware (capacitors, Schmitt triggers).
    

---

### **6. Show the difference between sourcing and sinking currents.**

- **Sourcing Current:** Device supplies current to the load.
    
- **Sinking Current:** Device receives current from the load.
    

---

### **8. Tell the difference between priority scheduling and Rate Monotonic scheduling.**

- **Priority Scheduling:** Tasks are executed based on priority, can be pre-emptive or non-pre-emptive.
    
- **Rate Monotonic Scheduling:** A fixed-priority algorithm where shorter period tasks get higher priority.
    

---

### **10. How many types of Arduino boards are available? List them.**

- **Common Types:**
    
    - Arduino Uno
        
    - Arduino Mega
        
    - Arduino Nano
        
    - Arduino Due
        
    - Arduino Leonardo
## **Set 2 - Remaining Questions**

### **1. What is known as the program status word of 8051?**

- **PSW (Program Status Word):** An 8-bit register that stores CPU status like carry, auxiliary carry, overflow, parity, and general-purpose flags.
    

---

### **2. Classify the addressing modes of the 8051 microcontroller.**

- **Immediate Addressing:** `MOV A, #25H`
    
- **Direct Addressing:** `MOV A, 30H`
    
- **Indirect Addressing:** `MOV A, @R0`
    
- **Register Addressing:** `MOV A, R1`
    

---

### **4. Compare the difference between timers and counters.**

|Feature|Timer|Counter|
|---|---|---|
|**Source**|Internal clock|External pulses|
|**Usage**|Time delays|Counting events|
|**Example**|Delay generation|Counting pulses from sensors|

---

### **8. What do you mean by Earliest Deadline First scheduling?**

- **EDF Scheduling:** A dynamic scheduling algorithm where the task with the nearest deadline gets the highest priority.
    

---

### **10. How will you define sketches in Arduino?**

- **Sketch:** A program written in the Arduino IDE, usually in C/C++, that controls the microcontroller’s behavior.