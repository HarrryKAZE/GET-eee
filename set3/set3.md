
# ⚡ 1. ELECTRICAL MACHINES (MOST IMPORTANT)

### Q1: Explain the working of an Induction Motor.

An induction motor works on **electromagnetic induction**.

• Three-phase AC supply to stator produces **rotating magnetic field**
• This field cuts rotor conductors
• **Induced current flows in rotor**
• Interaction of rotor current and stator field produces **torque**
• Rotor starts rotating

---

### Q2: What is Slip?

Slip is the **difference between synchronous speed and rotor speed**.

s = \frac{N_s - N_r}{N_s}

Ns = synchronous speed
Nr = rotor speed

Slip is necessary for **torque production**.

---

### Q3: What is Synchronous Speed?

Synchronous speed is the **speed of rotating magnetic field** in stator.

N_s = \frac{120f}{P}

f = supply frequency
P = number of poles

---

### Q4: Why is starting current high in induction motors?

At starting:

• Rotor speed = 0
• Back EMF = 0

So **motor behaves like short circuit**, causing **very high current**.

---

### Q5: Difference between Synchronous Motor and Induction Motor

| Induction Motor                 | Synchronous Motor               |
| ------------------------------- | ------------------------------- |
| Rotor speed < synchronous speed | Rotor speed = synchronous speed |
| Slip exists                     | Slip = 0                        |
| Self-starting                   | Not self-starting               |

---

### Q6: Why induction motors are widely used in industries?

Because they are:

• Simple construction
• Low cost
• Reliable
• Low maintenance
• No brushes

---

### Q7: What happens if motor load increases?

If load increases:

• Rotor speed decreases
• Slip increases
• Rotor current increases
• Torque increases to balance load

---

### Q8: What is Back EMF in DC Motor?

Back EMF is the **voltage generated in armature that opposes supply voltage** due to rotation in magnetic field.

It **limits current and protects motor**.

---

# ⚡ 2. TRANSFORMERS

### Q9: What is the working principle of a Transformer?

Transformer works on **mutual induction**.

• AC in primary winding creates **alternating magnetic flux**
• Flux links secondary winding
• **Induced voltage produced in secondary**

---

### Q10: Why transformer works only on AC?

Because transformer requires **changing magnetic flux**.

• AC → changing flux → induced voltage
• DC → constant flux → no induced EMF

---

### Q11: Types of Transformer Losses

1. **Copper Loss** – due to winding resistance
2. **Core Loss**

   * Hysteresis Loss
   * Eddy Current Loss

---

### Q12: Why laminated core is used?

Laminated core **reduces eddy current losses**.

Thin insulated sheets restrict circulating currents.

---

### Q13: Why transformer oil is used?

Transformer oil provides:

• Cooling
• Insulation
• Arc suppression

---

### Q14: What happens if transformer connected to DC?

• No inductive reactance
• Very high current flows
• Windings overheat and burn

---

# ⚡ 3. POWER SYSTEMS

### Q15: Why high voltage used in transmission?

Power loss in line is:

[
P_{loss} = I^2R
]

Higher voltage → lower current → **lower power losses**.

---

### Q16: What is Corona Effect?

Corona is **ionization of air around high-voltage conductors**, causing:

• power loss
• noise
• radio interference

Occurs in **transmission lines**.

---

### Q17: What is Power Factor?

Power factor is the **ratio of real power to apparent power**.

[
PF = \cos \phi
]

Higher PF → better efficiency.

---

### Q18: Why power factor correction is needed?

• Reduce transmission losses
• Improve system efficiency
• Reduce electricity cost
• Increase capacity

Usually corrected using **capacitor banks**.

---

### Q19: What is Reactive Power?

Reactive power is the power that **oscillates between source and reactive components** like inductors and capacitors.

Unit = **kVAR**

---

### Q20: What is Per-Unit System?

Per-unit system expresses electrical quantities **relative to a base value**.

It simplifies **power system calculations**.

---

# ⚡ 4. PROTECTION SYSTEMS

### Q21: What is a Circuit Breaker?

Circuit breaker is a **switching device that automatically interrupts current during fault conditions**.

---

### Q22: What is a Relay?

Relay is a **protective device that detects fault and sends trip signal to circuit breaker**.

---

### Q23: Difference between Fuse and Circuit Breaker

| Fuse                          | Circuit Breaker      |
| ----------------------------- | -------------------- |
| Metal wire melts during fault | Mechanical switching |
| One-time use                  | Reusable             |
| Cheap                         | Expensive            |

---

### Q24: What is Earthing?

Earthing is **connecting electrical equipment to ground** to prevent electric shock and equipment damage.

---

### Q25: Why earthing is important?

• Protect humans from shock
• Protect equipment
• Provide fault current path

---

### Q26: Types of Electrical Faults

• Line to Ground
• Line to Line
• Double Line to Ground
• Three Phase Fault

---

### Q27: Difference between MCB and MCCB

| MCB                    | MCCB                        |
| ---------------------- | --------------------------- |
| Used for small loads   | Used for large loads        |
| Current rating < 100 A | Current rating up to 2500 A |

---

# ⚡ 5. INDUSTRIAL ELECTRICAL (VERY IMPORTANT)

### Q28: What is a Motor Starter?

Motor starter is a **device used to limit starting current and protect motor**.

---

### Q29: Why Star-Delta Starter used?

In star connection:

[
V_{phase} = \frac{V_{line}}{\sqrt{3}}
]

So voltage and starting current **reduce by ~3 times**.

---

### Q30: What is Preventive Maintenance?

Maintenance performed **before failure occurs** to ensure reliability.

Examples:

• insulation testing
• cleaning
• lubrication
• thermal scanning

---

### Q31: What is LOTO?

LOTO means **Lock Out Tag Out**.

Procedure used to **ensure equipment is completely de-energized before maintenance**.

---

### Q32: How do you select cables for motors?

Based on:

• current rating
• voltage level
• temperature
• installation method
• voltage drop

---

# ⚡ 6. CONTROL SYSTEM

### Q33: What is PID Controller?

PID controller uses:

• **Proportional** → reduces error
• **Integral** → eliminates steady-state error
• **Derivative** → improves stability

Used in **process control systems**.

---

### Q34: What is Closed Loop Control System?

In closed-loop system:

• Output is fed back to input
• Error signal used to adjust system

Example: **Automatic temperature control**

---

### Q35: Why feedback used in control systems?

• Improve accuracy
• Increase stability
• Reduce disturbance effects

---

# ⚡ 7. ANALOG ELECTRONICS

### Q36: What is a Diode?

A diode is a **semiconductor device that allows current to flow only in one direction**.

---

### Q37: What is Rectification?

Rectification is **conversion of AC to DC** using diodes.

Types:

• Half-wave
• Full-wave
• Bridge rectifier

---

### Q38: What is Zener Diode?

Zener diode is used for **voltage regulation** and operates in **reverse breakdown region**.

---

### Q39: Ideal Characteristics of Op-Amp

• Infinite gain
• Infinite input impedance
• Zero output impedance
• Infinite bandwidth

---

# ⚡ 8. DIGITAL ELECTRONICS

### Q40: What is Flip-Flop?

Flip-flop is a **bistable memory element that stores one bit of data**.

---

### Q41: Difference between Latch and Flip-Flop

| Latch           | Flip-Flop      |
| --------------- | -------------- |
| Level triggered | Edge triggered |
| Faster          | More stable    |

---

### Q42: What is Boolean Algebra?

Boolean algebra is **mathematical system used for digital logic operations**.

Operations:

AND, OR, NOT.

---

# ⚡ 9. BASIC ELECTRICAL

### Q43: What is Ohm’s Law?

Relationship between voltage, current and resistance.

genui{"math_block_widget_always_prefetch_v2":{"content":"V = IR"}}

---

### Q44: Difference between AC and DC

| AC                         | DC                |
| -------------------------- | ----------------- |
| Alternating direction      | One direction     |
| Used in power transmission | Used in batteries |

---

### Q45: What is RMS Value?

RMS value is the **effective value of AC that produces same heating effect as DC**.

---

# 🎯 Final Interview Tip (Very Important)

When answering:

**Use 3 step format**

1️⃣ Definition
2️⃣ Principle
3️⃣ Application

