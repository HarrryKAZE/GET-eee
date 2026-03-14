
# ⚡ BASIC ELECTRICAL ENGINEERING

### 1. What is Ohm’s Law?

Ohm’s Law states that **current through a conductor is directly proportional to the voltage across it**, provided temperature and physical conditions remain constant.

genui{"math_block_widget_always_prefetch_v2":{"content":"V = IR"}}

Where
V = Voltage
I = Current
R = Resistance

---

### 2. What is the difference between AC and DC?

| AC                                                 | DC                                    |
| -------------------------------------------------- | ------------------------------------- |
| Alternating current changes direction periodically | Direct current flows in one direction |
| Used in power transmission                         | Used in batteries & electronics       |
| Frequency usually 50 Hz                            | Frequency = 0                         |

---

### 3. What are voltage, current, and resistance?

**Voltage:** Electrical potential difference between two points.

**Current:** Flow of electric charge through a conductor.

**Resistance:** Opposition offered to the flow of current.

---

### 4. What is electrical power and energy?

**Electrical Power:** Rate at which electrical energy is consumed.

P = VI

**Electrical Energy:** Total electrical work done over time.

---

### 5. What is RMS value?

RMS (Root Mean Square) value is the **equivalent DC value that produces the same heating effect as AC**.

For sinusoidal current:

[
I_{rms} = \frac{I_{max}}{\sqrt{2}}
]

---

### 6. What are active, reactive and apparent power?

**Active Power (P)**
Actual useful power consumed by load (kW).

**Reactive Power (Q)**
Power oscillating between source and reactive components (kVAR).

**Apparent Power (S)**
Total power supplied by source (kVA).

---

### 7. What is power factor?

Power factor is the **ratio of active power to apparent power**.

[
PF = \cos \phi
]

It indicates **how effectively electrical power is used**.

---

### 8. Why power factor correction is required?

To:

• Reduce line losses
• Improve system efficiency
• Reduce electricity charges
• Increase load carrying capacity

Usually done using **capacitor banks**.

---

### 9. What is a three-phase system?

A three-phase system consists of **three alternating voltages with equal magnitude but 120° phase difference**.

Advantages:

• Constant power transfer
• Efficient for motors
• Requires less conductor material

---

# ⚡ ELECTRICAL MACHINES

### 10. Explain the working of an induction motor.

When **three-phase AC supply** is given to the stator:

1. Rotating magnetic field is produced.
2. This induces EMF in the rotor.
3. Rotor current interacts with stator field.
4. Torque is produced → rotor rotates.

Principle: **Electromagnetic induction**.

---

### 11. Why induction motors are widely used in industries?

Because they are:

• Simple construction
• Low cost
• Rugged and reliable
• Low maintenance
• No brushes required

---

### 12. What is slip in an induction motor?

Slip is the **difference between synchronous speed and rotor speed**.

[
Slip = \frac{N_s - N_r}{N_s}
]

Where
Ns = synchronous speed
Nr = rotor speed

---

### 13. What is synchronous speed?

Speed of rotating magnetic field.

[
N_s = \frac{120f}{P}
]

Where
f = frequency
P = number of poles

---

### 14. What is the difference between synchronous motor and induction motor?

| Induction Motor                 | Synchronous Motor               |
| ------------------------------- | ------------------------------- |
| Rotor speed < synchronous speed | Rotor speed = synchronous speed |
| Slip exists                     | Slip = 0                        |
| Self-starting                   | Not self-starting               |

---

### 15. What is Back EMF in DC motor?

When armature rotates, it **cuts magnetic field lines**, generating an EMF opposite to supply voltage.

This is called **Back EMF**.

It **limits armature current**.

---

### 16. Why is starting current high in motors?

At starting:

• Rotor speed = 0
• Back EMF = 0

So current becomes very high.

---

# ⚡ TRANSFORMERS

### 17. What is the working principle of a transformer?

Transformer works on **mutual induction**.

When AC flows through primary winding → alternating magnetic flux is produced → induces voltage in secondary winding.

---

### 18. Why transformer works only on AC?

Because transformer requires **changing magnetic flux**.

AC produces alternating flux.
DC produces constant flux → no induced voltage.

---

### 19. What are transformer losses?

1. Copper Loss
2. Core Loss

   * Hysteresis Loss
   * Eddy Current Loss

---

### 20. Why laminated core is used in transformers?

To **reduce eddy current losses**.

Thin insulated laminations restrict circulating currents.

---

### 21. What happens if transformer connected to DC?

• No inductive reactance
• Very high current flows
• Windings may burn

---

### 22. Why transformer oil is used?

Transformer oil provides:

• Insulation
• Cooling
• Arc suppression

---

# ⚡ POWER SYSTEMS

### 23. Why high voltage used for transmission?

Because **power loss depends on current**.

[
P_{loss} = I^2R
]

Increasing voltage reduces current → reduces losses.

---

### 24. What is corona effect?

Corona is the **ionization of air around transmission conductors**, causing:

• power loss
• noise
• radio interference

Occurs in **high voltage lines**.

---

### 25. What is per-unit system?

Per-unit system expresses electrical quantities **relative to a base value**.

It simplifies power system calculations.

---

# ⚡ PROTECTION

### 26. What is a circuit breaker?

Circuit breaker is a **protective device that automatically interrupts current during fault conditions**.

---

### 27. What is a relay?

Relay is a **sensing device that detects abnormal conditions and sends trip signal to circuit breaker**.

---

### 28. Difference between fuse and circuit breaker?

| Fuse               | Circuit Breaker    |
| ------------------ | ------------------ |
| Melts during fault | Mechanically trips |
| One-time use       | Can be reset       |
| Cheap              | Expensive          |

---

### 29. What is earthing?

Earthing is **connecting electrical equipment to the ground to prevent electric shock and equipment damage**.

---

### 30. Types of electrical faults

• Line to ground fault
• Line to line fault
• Double line to ground fault
• Three phase fault

---

# ⚡ INDUSTRIAL ELECTRICAL (VERY IMPORTANT)

### 31. What is a motor starter?

A motor starter is a device used to **limit starting current and protect motor**.

---

### 32. Why star-delta starter is used?

To **reduce starting current of induction motors**.

In star connection voltage becomes:

[
V = \frac{V_{line}}{\sqrt{3}}
]

So starting current reduces.

---

### 33. Difference between DOL and Star-Delta starter

| DOL                   | Star-Delta               |
| --------------------- | ------------------------ |
| Full voltage start    | Reduced voltage start    |
| High starting current | Reduced starting current |
| Used for small motors | Used for large motors    |

---

### 34. What is VFD (Variable Frequency Drive)?

VFD controls **motor speed by changing supply frequency**.

Used for:

• conveyors
• pumps
• fans

---

### 35. What is preventive maintenance?

Maintenance done **before failure occurs**.

Examples:

• insulation testing
• lubrication
• thermal inspection

---

# ⚡ ANALOG ELECTRONICS

### 36. What is a diode?

A diode is a **semiconductor device that allows current to flow in only one direction**.

---

### 37. What is a rectifier?

Rectifier converts **AC to DC**.

Types:

• Half wave
• Full wave
• Bridge rectifier

---

### 38. What is a Zener diode?

A Zener diode is used for **voltage regulation**.

It operates in **reverse breakdown region**.

---

### 39. What is an operational amplifier?

Op-amp is a **high gain differential amplifier** used in signal processing.

---

# ⚡ DIGITAL ELECTRONICS

### 40. What are logic gates?

Logic gates perform **Boolean operations on digital signals**.

Examples:

AND, OR, NOT, NAND, NOR.

---

### 41. What is flip-flop?

Flip-flop is a **bistable memory device that stores one bit of data**.

---

# ⚡ CONTROL SYSTEM

### 42. What is a feedback control system?

A system where **output is fed back to input to improve stability and accuracy**.

---

### 43. What is transfer function?

Transfer function is **ratio of output to input in Laplace domain**.

---

### 44. What is PID controller?

PID controller uses:

• Proportional
• Integral
• Derivative

to control system output.

---

# ⚡ MEASUREMENT

### 45. What is a megger?

Megger measures **insulation resistance of cables and equipment**.

---

### 46. What is a clamp meter?

Clamp meter measures **current without disconnecting the circuit**.

---

### 47. What is an oscilloscope?

Oscilloscope displays **voltage waveform vs time**.

