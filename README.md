## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** |  | **Reg. No.:** |  |
|---|---|---|---|
| **Date:** | | **Batch / Section:** | |

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram
<img width="943" height="610" alt="image" src="https://github.com/user-attachments/assets/69abaf1b-c35c-4bbc-81ad-63ef7167fff0" />



**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1235" height="786" alt="image" src="https://github.com/user-attachments/assets/9690495e-dc55-4d01-8646-094a29b3e13c" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1177" height="717" alt="Screenshot 2026-11-18 140854" src="https://github.com/user-attachments/assets/adf62025-7f0c-45d5-b089-ecdf61587c30" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1167" height="772" alt="Screenshot 2026-11-18 140908" src="https://github.com/user-attachments/assets/4f04770a-bc7a-40c2-9bf3-fea433da8110" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Theoritical |  |  |  | | |
| Practical | | | | | |

### B. KCL – Current measurements

| S. No. | Supply voltage Vs (V) | Total current It (A) | Branch current I1 (A) | Branch current I2 (A) | Branch current I3 (A) | I1 + I2 + I3 (A) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Theoritical | | | | | | |
| Practical | | | | | | |

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="462" height="577" alt="Screenshot 2026-11-18 141653" src="https://github.com/user-attachments/assets/66d39f16-f036-438b-8c71-736767da325f" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="462" height="628" alt="Screenshot 2026-11-18 141713" src="https://github.com/user-attachments/assets/439f0726-42b6-4270-b3d6-9a775954d967" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
