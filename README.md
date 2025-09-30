LTspice LDO Design (TSMC 180nm)

Overview



This project contains a Low Dropout Regulator (LDO) designed in TSMC 180nm technology using LTspice. LDOs provide a stable output voltage with minimal ripple, making them essential for sensitive analog and digital circuits.



Design Highlights



Error Amplifier: Designed using a single-stage op-amp; then saved as a symbol for modular use in the LDO.



LDO Schematic: Includes pass transistor, reference voltage, feedback network, and compensation elements.



Key Results



Dropout Voltage: 121 mV



PSRR: -70.3 dB



Simulations: Transient response, load regulation, and PSRR



How to Use



Open ldo\_main.asc in LTspice.



Run .tran or .ac simulations to observe output voltage, load step response, and PSRR.



Modify error amplifier or compensation to explore performance variations.



Notes



Modular design using a custom op-amp symbol improves reusability.



Achieved low dropout and high PSRR, demonstrating effective voltage regulation.

