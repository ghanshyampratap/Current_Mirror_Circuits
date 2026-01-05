#  MOSFET-Based Current Mirrors 

##  Overview
Recently, I completed an in-depth analysis of **MOSFET-based Current Mirrors** using **Cadence Virtuoso**, exploring four key configurations:
 **Simple Current Mirror**
 **Wilson Current Mirror**
 **Cascode Current Mirror**
 **Low Voltage Cascode Current Mirror**

Current mirrors are the backbone of **analog MOSFET circuits**, enabling precise current replication with minimal power loss—crucial for efficient circuit design! 

---

##  **Key Concepts**

###  1. Simple Current Mirror (MOSFET-Based)
- Utilizes **two MOSFETs** in a basic setup.
- **Pros:** Simple to implement.
- **Cons:** Channel length modulation reduces accuracy due to **lower output resistance**.

###  2. Wilson Current Mirror (MOSFET-Based)
- Incorporates **negative feedback** to stabilize output. 
- Uses **three MOSFETs**, providing **higher output impedance** and better accuracy.
- **Trade-off:** Slightly more complex design.

###  3. Cascode Current Mirror (MOSFET-Based)
- Combines mirroring with a **cascode setup** using **four MOSFETs**.
- **Pros:** Very high output resistance & precision. 
- **Cons:** Introduces **voltage headroom limitations**.

###  4. Low Voltage Cascode Current Mirror (MOSFET-Based)
- **Optimized for low supply voltage**, solving headroom issues of traditional cascode designs. 
- Ideal for **low-power, low-voltage applications**.
- **Challenge:** Increased layout complexity due to multiple MOSFETs. 

<img width="940" height="229" alt="Screenshot 2025-08-24 020505" src="https://github.com/user-attachments/assets/c59638d4-2443-43e7-8c72-b469d5584c6e" />


---

##  **Transient Analysis**

 **Simple Current Mirror** → Fast response but **notable deviations** due to lower output resistance.

 **Wilson Current Mirror** → Better **load regulation & stability**, but slightly slower response. 

 **Cascode Current Mirror** → **High accuracy, minimal output variation**, but the **slowest response** due to parasitics. 

 **Low Voltage Cascode Current Mirror** → **Similar performance** to the cascode but optimized for **lower voltages** with high precision. 

---

##  **Key Learnings**

1️ **Choosing the right MOSFET-based mirror** requires balancing **accuracy, voltage headroom, and complexity**. ⚖️

2️ **Cascode & Low Voltage Cascode designs** are essential for **precision analog applications**, especially in **low-power systems**. 🏆

---
