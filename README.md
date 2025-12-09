# arys-automotive-protection-harsh
Automotive Reverse-Polarity &amp; Load-Dump Protection Circuit — LTspice Simulation &amp; Documentation
# Automotive Reverse-Polarity & Load-Dump Protection Circuit
## arys-automotive-protection-harsh

###  Project Overview
This project involves designing a 12V automotive input protection circuit capable of:
- Reverse polarity protection  
- Load-dump protection (60–100 V transient)  
- High-frequency spike suppression  

The design uses automotive-grade MOSFETs, TVS diodes, and passive components.  
Simulations are performed using **LTspice**.

---

###  Repository Contents
- `schematics/` — LTspice circuit files  
- `report/` — Final PDF, report assets  
- `results/` — Waveforms, graphs, screenshots  
- `docs/` — Any additional documentation  
- `README.md` — Overview of the project  

---

### Tools Used
- LTspice XVII  
- GitHub for version control  
- KiCad / EasyEDA (optional for PCB)  
- ChatGPT for explanation + report structuring  
- Manual research from datasheets & ISO standards  

---

###  Technical Summary
The protection circuit is based on:
- **P-channel MOSFET** — Low-loss reverse polarity protection  
- **Primary TVS diode** — Absorbs load-dump surge  
- **Secondary TVS diode** — Clamps fast high-frequency spikes  

Simulations include:
- Normal 12 V operation  
- Reverse polarity  
- ISO load-dump surge  
- Transient spike suppression  

---

###  Author
Harsh Verma 
ECE, RVCE  
Team: Helios Racing  

---

### 📜 License
This project is academic in nature and for evaluation purposes.
