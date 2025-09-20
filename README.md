# Energy-Harvesting Microwatt SoC for Self-Powered Medical Implants

🏷️ 𝐵𝑎𝑡𝑡𝑒𝑟𝑦𝑙𝑒𝑠𝑠-𝑀𝑒𝑑𝑖𝑐𝑎𝑙-𝐼𝑚𝑝𝑙𝑎𝑛𝑡-𝑆𝑜𝐶: 𝐴 𝑐𝑜𝑚𝑝𝑙𝑒𝑡𝑒 𝑅𝑇𝐿-𝑡𝑜-𝐺𝐷𝑆𝐼𝐼 𝑑𝑒𝑠𝑖𝑔𝑛 𝑓𝑙𝑜𝑤 𝑜𝑓 𝑎𝑛 𝑢𝑙𝑡𝑟𝑎-𝑙𝑜𝑤-𝑝𝑜𝑤𝑒𝑟 𝑀𝑖𝑐𝑟𝑜𝑤𝑎𝑡𝑡-𝑏𝑎𝑠𝑒𝑑 𝑆𝑜𝐶 𝑤𝑖𝑡ℎ 𝑒𝑛𝑒𝑟𝑔𝑦 ℎ𝑎𝑟𝑣𝑒𝑠𝑡𝑖𝑛𝑔 𝑓𝑜𝑟 𝑠𝑒𝑙𝑓-𝑝𝑜𝑤𝑒𝑟𝑒𝑑 𝑚𝑒𝑑𝑖𝑐𝑎𝑙 𝑖𝑚𝑝𝑙𝑎𝑛𝑡𝑠. 𝐼𝑛𝑐𝑙𝑢𝑑𝑒𝑠 𝑅𝑇𝐿, 𝑡𝑒𝑠𝑡𝑏𝑒𝑛𝑐ℎ𝑒𝑠, 𝑠𝑦𝑛𝑡ℎ𝑒𝑠𝑖𝑠, 𝑃𝑛𝑅, 𝑝𝑜𝑤𝑒

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

<img width="1578" height="420" alt="image" src="https://github.com/user-attachments/assets/10cdee4f-7ef1-4778-b0d7-faa1e2b288c8" />

## Overview
This project presents a batteryless, energy-harvesting Microwatt SoC designed for self-powered medical implants. It converts ambient energy from the human body—such as kinetic energy from motion, temperature gradients, or RF signals—into electrical power to drive a Microwatt core, ADC, and secure on-chip memory. The system enables continuous real-time biometric monitoring while minimizing energy consumption and eliminating the need for battery replacement.

 # **Key Goals:**

• Enable long-term, self-powered medical implants

• Ultra-low-power real-time monitoring of vital signals

• Secure data storage and controlled wireless transmission

• Demonstrate practical feasibility via ASIC design

# **Motivation**

Traditional medical implants like pacemakers or biosensors rely on batteries with limited lifespan. When batteries deplete, patients require surgical replacement—risky and costly.
This Project addresses this problem by integrating energy harvesting into the SoC itself, ensuring long-term, maintenance-free operation.

# **Features**

• Microwatt RISC-V Core: Ultra-low-power CPU for continuous monitoring

• Energy Harvesting Module: Converts body motion, heat, or RF energy into electrical power

• Ultra-Low-Power ADC: High-precision signal acquisition of vital signs

• Secure SRAM & On-Chip Encryption: Ensures patient data privacy

• Always-On Operation: Continuous monitoring without frequent battery replacement

# BLOCK DIAGRAM

<img width="1837" height="997" alt="image" src="https://github.com/user-attachments/assets/fcbf5a0a-9ae5-4c81-95c4-fab4eaaedb07" />


# **Applications**

• Pacemakers & medical biosensors
   
• Long-term health monitoring implants

• Secure IoT medical devices 

• Ultra-low-power wearable systems  

# Significance of Chip Fabrication

Building the chip is necessary to verify the design in real silicon. Simulations show theoretical functionality, but only a fabricated chip can prove that the batteryless, energy-harvesting Microwatt SoC works reliably under real-world conditions, including power, leakage, and timing constraints.

It is also crucial for medical implants, where size, low power, and reliability are vital. Fabrication ensures the integration of all modules and demonstrates a practical, self-powered device prototype ready for real-life applications.


