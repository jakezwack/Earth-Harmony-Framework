# Memphis Node: Earth-Harmony Seismic Damping Prototype

**Date:** April 02, 2026  
**Author:** Jacob Zwack  
**Goal:** Build the first real-world resonator to damp torsional stress in the New Madrid Seismic Zone. Zero-debt phase-lock at 1.673419 Hz (5/3 Hz bridge). No ancient sites, no religion—just measurable science.

## 1. Geology & Hazard Baseline (USGS/NMSZ Data)
- **Bedrock:** Soft Tertiary sands, silts, clays (Jackson Formation) — 10–30 m deep, over Paleozoic limestone/sediments.  
- **Sediment Layers:** Upper 30 m = loose sand/clay/loess — highly liquefaction-prone when vibrated.  
- **Hazard:** High risk zone. M7–8 events every \~500 years cause sand blows and lateral spreading. Memphis sits in the red zone on USGS hazard maps.  
- **Why Ideal for Test:** Soft ground amplifies micro-vibrations. If we drop torsional debt δ by even 5–10%, damping will show immediately before energy releases as a quake.

## 2. Local Rock Sources (Proxies for Resonator)
- **Primary:** Limestone or high-silica gravel from Memphis Stone & Gravel (Hernando, MS — \~20 min drive) or Vulcan Materials Memphis Yard (1074 Harbor Ave).  
- **Alternative:** Riverbed gravel or quarry stone from Nashville Basin limestone (easy to source locally).  
- **Sourcing Tip:** Buy 1–2 lb sample (< $10). Dense enough for piezo bonding, soft enough to mimic Memphis soil.

## 3. Resonator Design Basics (Low-Freq Piezo at 1.673419 Hz)
- **Core:** Cheap piezo disc (1–2 cm) bonded to rock with epoxy.  
- **Drive:** Function generator or phone app set to exact 5/3 Hz (1.673419 Hz).  
- **Damping Circuit:** Simple shunt R-L (R = 10 kΩ, L = 1 H for low-frequency). Energy dissipates as harmless heat/vibration instead of quake stress.  
- **Simulation Note:** η = 1 - δ. Model in PyTorch/SymPy using your March ledger (ΔG = 0.04, 12 Hz pulses, 1540 m/s sound speed).

## 4. Test Protocol (30-Second Bench)
1. Place rock sample on flat table (mimics soil).  
2. Bond piezo disc with epoxy.  
3. Set frequency generator to 1.673419 Hz.  
4. Baseline: Shake gently (hand or phone vibrator), measure vibration amplitude with phone app (Vibration Meter on Android or Sismo on iOS).  
5. Activate resonator → re-measure amplitude.  
6. Target: 5–10% drop = proof of concept.

## 5. Scale-Up Path
- First success → build trifecta: Memphis (damping) → Sedona (anchor) → Iceland (magnetic boost).  
- Link nodes with low-frequency hum (12 Hz Fibonacci multiple).  
- Global effect: Torsional stress redistributed instead of released as earthquakes.

**Next Action:** Run the bench test when piezo arrives. Then simulate δ reduction in the grand equation.

This is the first real step toward harmonizing Earth instead of milking it.  
Jacob Zwack
