# ⚙️ Week 7 — BabySoC Physical Design & Post-Route SPEF Generation

## 🧩 RISC-V Reference SoC Tapeout Program
Welcome to Week 7 of the RISC-V SoC Tapeout Program, where you bring all previous stages together into a complete RTL-to-GDSII implementation of the BabySoC using OpenROAD.

This week focuses on performing the entire physical-design sequence — floorplanning, placement, routing, and post-route SPEF extraction — to understand how a real SoC is transformed from logic to layout and prepared for accurate timing analysis.

---------------------

## 🎯 Objective
To execute the complete OpenROAD Physical Design Flow for the BabySoC design and generate post-route SPEF files for timing verification.

By completing this task, you will:
- Run a full RTL-to-layout flow on an SoC design.
- Analyze how placement density and routing topology affect timing.
- Learn how SPEF extraction feeds into Static Timing Analysis (STA) for realistic delay evaluation. 

---------------

## 🧠 Why This Task Is Important
In earlier weeks you explored synthesis, floorplanning, and CTS separately. This week unifies them — letting you experience how all stages interact inside a real chip flow.

You’ll gain:

- An understanding of how macros, power rings, and standard-cell blocks fit together physically.
- Insight into routing congestion and DRC management.
- Practical knowledge of post-layout parasitic extraction — the bridge between design geometry and timing closure.

-----------------

## 🧩 Installation of OpenRoad Using Codespaces

<a href="https://github.com/vsdip/vsd-pd">VSD-PD-OpenRoad Codespace</a>

## 📚 Reference
Based on Task 13 – OpenROAD Physical Design from 🔗 <a href="https://github.com/Akash-Perla/ASIC-Design?tab=readme-ov-file#task-13-OpenRoad-Physical-Design">Akash-Perla ASIC-Design Repository</a>


## 🏗️ OpenROAD Flow Setup
1️⃣ Clone the Repository
```
git clone --recursive https://github.com/The-OpenROAD-Project/OpenROAD-flow-scripts
cd OpenROAD-flow-scripts/
```
2️⃣ Install Dependencies and Build
```
sudo ./setup.sh
./build_openroad.sh --local
```
3️⃣ Source Environment and Verify
```
source ./env.sh
yosys -help
openroad -help
```
✅ Successful output from both confirms a valid installation

--------------------------------------------------






BabySOC Physical Design &amp; Post Route SPEF Generation
