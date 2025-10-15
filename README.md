# Voltage Controlled Switches 

## Project Overview
Designed and characterized two voltage-controlled switch circuits using MOSFETs to approximate ideal switching behavior. Both switches were analyzed for non-idealities including voltage drop, current leakage, and bidirectional performance.

---

## Switch Designs

### Switch Type 1 (Single-Pole Single-Throw)
- **Configuration:** 4-MOSFET design for improved performance
- **Control:** 0V = Closed, 5V = Open
- **Function:** Connects v₁ to v₂ when closed

### Switch Type 2 (Single-Pole Double-Throw)  
- **Configuration:** 6-MOSFET design for dual output
- **Control:** 0V = v₁ to Vₐ, 5V = v₁ to Vբ
- **Function:** Toggles between two output paths

---

## Performance Analysis

### Non-Idealities Characterized
- **Voltage Drop:** 0.17V-0.23V (vs. 0V ideal)
- **Current Leakage:** 2.2μA-60μA (vs. 0A ideal)  
- **Voltage Threshold:** 1.9V-2.2V minimum operating voltage
- **Bidirectional Performance:** Limited (0.05V-0.1V drop in reverse)

### Validation Methods
- **Simulation:** PSpice modeling for theoretical performance
- **Physical Testing:** Breadboard implementation with AD3 measurements
- **Comparative Analysis:** Simulation vs. real-world results

---

## Key Skills
- **MOSFET Circuit Design** - Switch topologies and component selection
- **Non-ideality Analysis** - Voltage drop, leakage current, threshold characterization  
- **Test Planning** - Systematic validation of switch parameters
- **PSpice Simulation** - Circuit behavior prediction
- **Design Trade-offs** - Performance vs. complexity vs. cost analysis

---

## Tools & Technologies
- **Simulation:** Cadence PSpice
- **Hardware:** Digilent AD3, MOSFETs, resistors
- **Analysis:** Comparative performance evaluation

*Project completed for ELEC ENG 2EI4 at McMaster University*
