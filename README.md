# **Analog LDO Voltage Regulator - SCL 180nm CMOS Technology**
Designed an Analog LDO Regulator in SCL 180nm CMOS Technology in "Power Management IC Design" Course under Prof. Madhav Pathak


## **Overview**
This project presents the design and analysis of a Low Dropout (LDO) Voltage Regulator implemented in **SCL 180nm CMOS technology** for power management applications. The regulator provides a stable **1.6V output** from a **1.8V input**, supporting load currents from **20mA to 100mA** with high efficiency and robust transient response.

## **Features**
- **Input Voltage:** 1.8V  
- **Output Voltage:** 1.6V  
- **Load Current:** 20mA – 100mA  
- **Reference Voltage:** 1V  
- **Bias Current:** 1µA  
- **Efficiency:** ≥ 88.46%  
- **Phase Margin:** ≥ 60°  
- **Load Regulation:** ≤ 0.045%  
- **Line Regulation:** ≤ 0.025%  
- **PSRR at 100kHz:** -35dB  
- **Settling Time:** ≤ 250ns  

## **Circuit Design**
The LDO consists of:
- **Pass Transistor (PMOS)**
- **Error Amplifier (OTA)**
- **Feedback Network**
- **Miller Compensation** for stability  

The **Miller compensation** technique enhances phase margin and extends bandwidth using a compensation capacitor **(Cc = 8.5pF)**.

## **Key Performance Metrics**
| Parameter | Value |
|-----------|-------|
| Efficiency | ≥ 88.46% |
| Phase Margin | ≥ 60° |
| Load Regulation | ≤ 0.045% |
| Line Regulation | ≤ 0.025% |
| PSRR (100kHz) | -35dB |
| Transient Overshoot | ≤ 130mV |
| Settling Time | ≤ 250ns |

## **Transient Response**
- **Step change from 20mA → 50mA:** 125.21mV overshoot, 0.2µs settling time.  
- **Step change from 50mA → 20mA:** 111.26mV undershoot, 0.2µs settling time.  

## **Power Consumption**
| Block | Power (µW) |
|-------|-----------|
| Feedback | ~16 |
| OTA | ~152 |
| Pass Transistor | 4mW – 20mW (varies with load) |

## **Files Included**
- `LDO_Schematic.png` – Circuit diagram   
- `LDO_Report_.pdf` – Detailed project report  

## **Tools Used**
- **Technology:** SCL 180nm CMOS  
- **Simulation Software:** Cadence Virtuoso  

## **Author**
Sushant Gudmewar  
Integrated B.Tech-M.Tech  
Electrical Engineering, IIT Gandhinagar  

---

