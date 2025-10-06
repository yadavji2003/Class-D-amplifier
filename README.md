# Class-D-amplifier
In this project, i have made class D amplifier without using specific IC 
# REQUIRED ELEMENTS
LM324
NE555D
IRLZ34N
SPEAKER
 Now Explain Each
 LM324: versatile — use it for the audio preamp, triangle oscillator (op-amp integrator + comparator), PWM comparator, and feedback amplifier. LM324 runs single-supply and can handle inputs near ground (handy).

NE555D: can be used as a stable high-frequency oscillator (gives square / ramp-ish at the timing capacitor) or as a timing/delay element to create dead-time or inverted PWM. If you prefer a purer triangle, use LM324 op-amp integrator + comparator instead.

IRLZ34N: N-channel MOSFETs for the switching output stage. They are logic-level, low Rds(on) when driven properly — used as switches in an H-bridge or half-bridge.
SPEAKER: It is output of the project .it connect to drain and source terminal of the MOSFET.
#


Here are the full forms of the main components used in your Class-D amplifier circuit:

PWM → Pulse Width Modulation

NE555D → “NE” stands for Manufacturer Series (by Signetics/Philips), and “555” is the Timer IC number. The suffix D usually means SOIC package (Surface-mount Dual). So full form:
→ NE555 Timer IC (Dual-In-line / Surface-mount package)

LM324 → Linear Monolithic 324 (a Quad Operational Amplifier)

“LM” means Linear Monolithic (Texas Instruments / National Semiconductor series).

“324” is the specific model — contains 4 op-amps in one chip.

IRLZ34N → International Rectifier Logic-Level Z-series 34 A N-channel MOSFET

IR → International Rectifier (original manufacturer)

L → Logic-level gate drive

Z → Advanced hexFET family

34 → Approximate drain current rating (34 A)

N → N-channel MOSFET

So, summarizing simply:

Symbol	Full Form / Meaning
PWM	Pulse Width Modulation
NE555D	Timer IC (NE series, 555 model, D = surface-mount)
LM324	Linear Monolithic Quad Operational Amplifier
IRLZ34N	International Rectifier Logic-Level N-Channel MOSFET (34 A)

 
