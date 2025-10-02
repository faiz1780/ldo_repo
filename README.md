# LTspice LDO Design (TSMC 180nm)

This repository contains the design and LTspice simulation of a **Low Dropout Regulator (LDO)** implemented in **TSMC 180nm technology**.  
The LDO provides a stable output voltage with minimal ripple, suitable for sensitive analog and digital circuits.

---

## 🔹 Project Specifications
- **Technology:** TSMC 180nm CMOS  
- **Architecture:** LDO with single-stage error amplifier and pass transistor  
- **Key Results:**
  - Dropout Voltage: 121 mV  
  - PSRR: -70.3 dB  

---

## 🔹 Why LDOs?
Low Dropout Regulators are widely used because they offer:  
- Stable output voltage with low ripple  
- High Power Supply Rejection Ratio (PSRR)  
- Low dropout for efficient voltage regulation  
- Simple and modular design for reuse  

---

## 🔹 Repository Contents
- `ldo_main.asc` → Full LDO schematic in LTspice  
- `erroramp.asc` → Single-stage op-amp used as the error amplifier  
- `.gitignore` → Ignores LTspice simulation files (`.raw`, `.log`, `.bak`, `.tmp`)  
- `README.md` → Project documentation  

---

## 🔹 How to Use
1. Open `ldo_main.asc`and include tsmc180 text file in **LTspice**  
2. Run **Transient (.tran)** or **AC (.ac) Analysis** to observe output voltage, load response, and PSRR  
3. Modify the **error amplifier** or **compensation network** to explore performance variations  

---

## 🔹 Results
- Dropout Voltage: 121 mV  
- PSRR: -70.3 dB  
- Simulations include transient response, load regulation, and PSRR  
- Modular design using a custom op-amp symbol improves reusability 
