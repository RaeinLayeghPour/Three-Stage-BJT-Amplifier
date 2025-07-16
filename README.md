# Three‑Stage BJT Amplifier

A fully discrete, three-stage bipolar junction transistor (BJT) amplifier designed for audio and signal applications. This project demonstrates cascading amplifier stages—common emitter, voltage gain, and output buffering—for low distortion and a modest increase in analog electronic circuits.

---

## Key Features

- **Triple-stage amplification** using BJTs (common-emitter → intermediate gain → output buffer)  
- Stable **DC biasing** for all stages, ensuring linear operation  
- **Coupling capacitors** between stages to block DC and allow AC signal flow  
- Simple **resistive–emitter stabilization** for temperature consistency  
- Breadboard-ready analog schematic with component values for educational use

---

## Tech & Design Details

- **Components:** 3× BJTs (e.g., 2N3904), coupling/decoupling capacitors, bias resistors  
- **Topology:** Multi-stage CE amplifier with emitter degeneration  
- **Design Tools:** NI Multisim
- **Outputs:** Bode plot/frequency response, gain (dB), and distortion measurements (if simulated or measured)

---

## How It Works

1. **First Stage (Common Emitter):** Provides voltage gain with emitter resistor stabilization.  
2. **Second Stage (Gain Boost):** Further amplifies via another BJT stage.  
3. **Third Stage (Buffer/Emitter Follower):** Lowers output impedance for driving loads.  
4. **Coupling Capacitors:** Pass AC between stages while blocking DC bias.  
5. **Performance Metrics:** Calculate gain, bandwidth, and distortion from simulation or measurement data.

---

## Design Results

- **Total gain:** e.g., 60 dB across three stages (verify with your values)  
- **−3 dB bandwidth:** e.g., 20 Hz – 100 kHz (show your full Bode plot in `simulations/`)  
- Linear, low-distortion performance in audio-range test setups

---

## Contact

Feel free to reach out with questions or collaboration ideas:

- 💼 [LinkedIn](https://www.linkedin.com/in/raeinlp)  
- ✉️ Email: raeen.layegh2017@gmail.com
