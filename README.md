## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| Name:DARUN GOPPI G |  | Reg. No.:26018292 |  |
|---|---|---|---|
| Date:18/11/2026| | Batch / Section:BE-CSE| |

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

<img width="1599" height="763" alt="KVL" src="https://github.com/user-attachments/assets/c9f322e8-be0c-40ac-be7b-428f38ae6241" />

**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1599" height="931" alt="KCL" src="https://github.com/user-attachments/assets/f76e01fa-595c-4e9c-b981-5d0f24612ac3" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1920" height="1066" alt="KVL PROTUES" src="https://github.com/user-attachments/assets/4bd39342-6e62-45a6-81c6-50eb8b00403f" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1920" height="1080" alt="KCL PROTUES" src="https://github.com/user-attachments/assets/754e1410-2fb2-4262-b600-2837ff1349ae" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

<img width="1600" height="708" alt="KVL TABLE" src="https://github.com/user-attachments/assets/c807d6c5-11fc-4c15-b1ef-53d6e07a0e35" />


### B. KCL – Current measurements

<img width="1600" height="655" alt="KCL TABLE" src="https://github.com/user-attachments/assets/8c68f896-eda7-455e-bdee-74c9a8bf0f38" />


## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="1188" height="1600" alt="KVL Calculation" src="https://github.com/user-attachments/assets/373097ec-c5b1-4825-80c0-d3119873f7ab" />

**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="1536" height="1024" alt="KCL CALCULATION" src="https://github.com/user-attachments/assets/1a7dbb2b-0a0b-4982-90e2-140cbb3111fb" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
