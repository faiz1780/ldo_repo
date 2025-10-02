\# \*\*1. Overview\*\*

This project contains a \*\*Low Dropout Regulator (LDO)\*\* designed in \*\*TSMC 180nm technology\*\* using \*\*LTspice\*\*. LDOs provide a stable output voltage with minimal ripple, making them essential for sensitive analog and digital circuits.



---



\# \*\*2. Design Highlights\*\*



\*\*2.1 Error Amplifier\*\*

\- Single-stage op-amp design.

\- Saved as a \*\*symbol\*\* for modular use in the LDO.



\*\*2.2 LDO Schematic\*\*

\- Includes pass transistor, reference voltage, feedback network, and compensation elements.



---



\# \*\*3. Key Results\*\*

\- \*\*Dropout Voltage:\*\* 121 mV

\- \*\*PSRR:\*\* -70.3 dB

\- \*\*Simulations:\*\* Transient response, load regulation, and PSRR



---



\# \*\*4. How to Use\*\*

1\. Open `ldo\_main.asc` in \*\*LTspice\*\*.

2\. Run `.tran` or `.ac` simulations to observe output voltage, load step response, and PSRR.

3\. Modify the \*\*error amplifier\*\* or \*\*compensation network\*\* to explore performance variations.



---



\# \*\*5. Notes\*\*

\- Modular design using a \*\*custom op-amp symbol\*\* improves reusability.

\- Achieved \*\*low dropout\*\* and \*\*high PSRR\*\*, demonstrating effective voltage regulation.



