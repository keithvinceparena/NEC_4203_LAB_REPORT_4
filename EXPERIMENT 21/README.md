# EXPERIMENT 21: ANTENNA TRAINER KIT

## I. OBJECTIVES
* **Radiation Mapping:** To experimentally determine and plot the 2D radiation patterns of various resonant and non-resonant antennas in the polar coordinate system.
* **Parameter Evaluation:** To measure and compare critical antenna metrics such as gain, directivity, front-to-back ratio, and half-power beamwidth (HPBW).
* **Array Investigation:** To analyze the effect of parasitic elements (in Yagi-Uda arrays) and phasing (in antenna arrays) on the shape and concentration of electromagnetic fields.
* **Impedance Optimization:** To demonstrate the practical application of matching stubs in minimizing standing wave ratios (SWR) and maximizing power delivery.

<img width="636" height="383" alt="image" src="https://github.com/user-attachments/assets/5c512238-7192-4eef-8b9e-78a56d5fa417" />

---

## II. MATERIALS AND COMPONENTS USED

### System Equipment
* **Master Antenna Trainer Unit:** The central hub providing a regulated RF source (typically VHF/UHF), modulation controls, and a digital/analog display for signal strength.
<img width="425" height="212" alt="image" src="https://github.com/user-attachments/assets/2f75de63-3d81-4bb4-a806-6f1833509940" />

* **Matching Stub:** A transmission line tuner used to cancel out reactance and match the antenna's impedance to the feeder line.
<img width="215" height="606" alt="image" src="https://github.com/user-attachments/assets/01f1c54d-f582-42fb-bfa2-0d508bc57860" />

* **Transmitting Mast:** A rotatable support structure with a 360° scale used to adjust the angular position of the test antenna relative to the receiver.
<img width="455" height="555" alt="image" src="https://github.com/user-attachments/assets/4b4b18e1-4543-4fa9-ab4e-571bf246fbd4" />

* **Stationary Receiving Mast:** Holds the detector probe or receiving antenna at a fixed distance, ensuring measurements are taken in the "far-field" region.
<img width="459" height="324" alt="image" src="https://github.com/user-attachments/assets/63fb2245-e9a5-44d7-9471-780fe950b3dd" />

* **RF Detector:** A high-sensitivity rectification circuit that converts captured electromagnetic energy into a readable DC signal.
<img width="409" height="512" alt="image" src="https://github.com/user-attachments/assets/b7b182d3-61a4-46e3-8f0a-1c3f165fe0ee" />
  
### Detailed Antenna Element Catalog

1.  **Detector Antenna:** A small, specialized probe used specifically to capture the radiated field for the trainer's measurement system without distorting the field.
<img width="222" height="746" alt="image" src="https://github.com/user-attachments/assets/fff51865-aeca-4fa1-bfe4-8c7b450aa820" />

2.  **Slot Antenna λ/2:** A literal slot cut into a metal sheet. Based on Babinet's Principle, it radiates similarly to a dipole but with horizontal polarization if the slot is vertical.
<img width="270" height="125" alt="image" src="https://github.com/user-attachments/assets/8c450921-6703-4405-8224-059b74f15747" />

3.  **Helix Antenna:** A wire shaped like a corkscrew. In "Axial Mode," it produces circular polarization, which is essential for satellite communication to prevent signal fading.
<img width="326" height="352" alt="image" src="https://github.com/user-attachments/assets/c443a311-0649-476d-9c76-0291d2b53cbc" />

4.  **Yagi-UDA Folded Dipole (3E):** A three-element directional array. It uses a folded dipole as the "driven" element, a slightly longer "reflector" behind it, and a shorter "director" in front to focus energy forward.
<img width="328" height="533" alt="image" src="https://github.com/user-attachments/assets/158dc70c-cf14-4a5e-8636-b60b226921cc" />

5.  **Yagi-UDA Folded Dipole (5E):** An expanded array featuring three directors. The extra elements further compress the main lobe, significantly increasing forward gain.
<img width="345" height="322" alt="image" src="https://github.com/user-attachments/assets/0ce972a8-2fb9-4857-bb5c-bce647e049d6" />

6.  **Yagi-UDA Simple Dipole (5E):** Similar to the folded version but uses a standard straight dipole driver. This offers high gain but generally possesses a narrower operational bandwidth.
<img width="350" height="501" alt="image" src="https://github.com/user-attachments/assets/0eba28e5-f599-4470-b2f9-0b52947881cd" />

7.  **Yagi-UDA Simple Dipole (7E):** A high-performance array with five directors. It provides the narrowest beamwidth and highest directivity in this kit, used for long-distance point-to-point links.
<img width="332" height="592" alt="image" src="https://github.com/user-attachments/assets/d7331c2a-1e38-4c11-a1d1-84f20e5da236" />

8.  **Simple Dipole 3λ/2:** A long-wire harmonic antenna. Operating at three times the base frequency, it produces multiple lobes and nulls, showing higher directivity than a standard dipole.
<img width="302" height="121" alt="image" src="https://github.com/user-attachments/assets/0e7d9a58-32fd-46c4-8535-9c40655a21df" />

9.  **Folded Dipole λ/2:** A dipole where the conductor is folded back on itself. This quadruples the input impedance (to ~300Ω) and broadens the bandwidth, making it ideal as a driver for Yagi arrays.
<img width="240" height="99" alt="image" src="https://github.com/user-attachments/assets/bb9fa79c-460b-4fcc-a7b3-7bc4d6f3fa55" />

10.  **Simple Dipole λ/2:** The "Gold Standard" of antennas. A resonant half-wave wire that produces an omnidirectional toroid-shaped pattern with maximum radiation perpendicular to the wire.
<img width="347" height="240" alt="image" src="https://github.com/user-attachments/assets/dcf02e93-5b30-4fa6-a3b0-6ce7afac4e67" />

11. **Simple Dipole λ/4:** A compact version often used as a monopole. It relies on a ground plane to "reflect" its other half, creating a radiation pattern similar to a full dipole but with higher elevation.
<img width="335" height="299" alt="image" src="https://github.com/user-attachments/assets/598c7c3a-28e5-41bd-98af-db284af1d334" />

12. **Zeppelin (Zepp) Antenna:** An end-fed resonant λ/2 antenna. Traditionally used in airships, it is fed at a high-impedance point through a balanced matching section.
<img width="305" height="88" alt="image" src="https://github.com/user-attachments/assets/9a078713-9c4e-4ba6-aff3-aefed913a8ef" />

13. **Hertz Antenna:** A fundamental term for any balanced, "ungrounded" antenna (like a dipole). It is self-contained and does not require the Earth as part of the circuit.
<img width="284" height="120" alt="image" src="https://github.com/user-attachments/assets/2a8f602d-2565-4860-8d46-dac148e1f623" />

14. **Combined Co-linear Array:** A vertical stack of dipoles. By phasing them together, the radiation is "squashed" toward the horizon, increasing omnidirectional gain for ground-based receivers.
<img width="297" height="497" alt="image" src="https://github.com/user-attachments/assets/56fd9a70-fc15-4556-9f6e-19188dc46a0a" />

15. **λ/2 Phase Array:** Two dipole elements spaced half a wavelength apart. Depending on the feed phase, they can reinforce signals to create specific interference patterns.
<img width="279" height="244" alt="image" src="https://github.com/user-attachments/assets/4966379a-c85e-4b6d-80ab-80e1ee91ac2c" />

16. **λ/4 Phase Array:** An array with quarter-wave spacing. Often used to create "End-Fire" patterns where the signal is directed along the line of the elements.
<img width="296" height="515" alt="image" src="https://github.com/user-attachments/assets/8658a008-ec3b-4ba0-a747-5bf36410b7a3" />

17. **Cut Paraboloid Antenna:** A microwave dish reflector "cut" into a rectangular shape. It uses a primary feed (like a dipole) to bounce waves off a curved surface into a highly focused "pencil" beam.
<img width="345" height="274" alt="image" src="https://github.com/user-attachments/assets/46accbfa-af90-48b4-8636-33262fb78af4" />

18. **Broadside Array:** A configuration where all elements are fed in phase. This creates a massive main lobe perpendicular to the plane of the antenna elements. 
<img width="343" height="227" alt="image" src="https://github.com/user-attachments/assets/eafabf15-cfe7-45ef-9251-e404cea09b10" />

19. **Loop Antenna:** A closed circular or square conductor. It behaves primarily as a magnetic dipole and is highly effective at rejecting electrical noise in compact spaces.
<img width="329" height="306" alt="image" src="https://github.com/user-attachments/assets/d206fe39-cda3-4a63-aa3e-d20c4f9fe18d" />

20. **Log Periodic Antenna:** A wideband directional antenna. Its elements vary logarithmically in length, allowing it to maintain consistent gain and impedance across a huge frequency range.
<img width="338" height="679" alt="image" src="https://github.com/user-attachments/assets/4ff82e7a-5593-4ceb-972e-7b02dcd4551b" />

21. **Ground Plane Antenna:** A vertical radiator with horizontal "radials" at the base. The radials simulate an artificial ground, allowing the antenna to be mounted high above the actual earth.
<img width="343" height="296" alt="image" src="https://github.com/user-attachments/assets/8c49b34e-e4ab-4fcd-b386-b6a5ac4a7348" />

22. **Rhombus Antenna:** A large, diamond-shaped, non-resonant wire antenna. It is exceptionally wideband and produces high gain, often used for long-range high-frequency (HF) communication.
<img width="291" height="247" alt="image" src="https://github.com/user-attachments/assets/8f1a3ce2-2e96-4fad-8249-bf0a4a9b2b67" />

### SETUP
<img width="313" height="420" alt="image" src="https://github.com/user-attachments/assets/809a51fe-589f-4993-9b21-c199c286cedd" />

---

## III. PROCEDURE

### A. Initial Bench Assembly
1.  **Placement:** Set up the **Transmitting Mast** and **Receiving Mast** on a flat surface, ensuring they are separated by at least 1-1.5 meters to stay within the "Far Field" zone.
2.  **Interconnection:** Connect the RF Output of the Trainer Unit to the **Matching Stub**, and the output of the stub to the Transmitting Mast.
3.  **Detector Setup:** Mount the **Detector Antenna** on the receiving mast and link it to the signal strength input on the main unit.

### B. Impedance Calibration
1.  Install the **Simple Dipole λ/2** on the transmitter.
2.  Power on the unit and adjust the sliding section of the **Matching Stub**. 
3.  Monitor the SWR or signal strength meter; stop when the signal is at its maximum peak, indicating a "matched" condition.

### C. Radiation Pattern Acquisition
1.  Rotate the Transmitting Mast to the **0° (Boresight)** position. 
2.  Adjust the "Gain" or "Range" knob on the trainer until the meter reads a full-scale value (e.g., 100% or 0dB).
3.  Slowly rotate the mast in **10-degree increments**. At each step, pause to let the meter stabilize and record the value.
4.  Complete a full **360° rotation** to map the entire radiation envelope.

### D. Comparative Testing
1.  Replace the dipole with the **7-Element Yagi-UDA**.
2.  Without changing the distance, repeat the 360° measurement. 
3.  Perform a **Polarization Test** by rotating the receiving antenna 90° to observe the "Null" caused by cross-polarization.

---

## IV. RESULTS AND DISCUSSION

The experimental data reveals a clear evolution of beam shaping. The **Simple Dipole** produced the characteristic "Figure-8" pattern, showing nearly equal radiation to the front and back. In contrast, the **Yagi-UDA arrays** exhibited a "Main Lobe" that became increasingly narrow and powerful as more directors were added. 



Specifically:
* **Gain vs. Elements:** The 7-Element Yagi showed significantly higher peak intensity at 0° compared to the 3-Element version.
* **Front-to-Back Ratio:** The reflector element in the Yagi effectively suppressed radiation behind the antenna (180° position), concentrating it forward.
* **Polarization:** The experiment confirmed that if the transmitter is vertical and the receiver is horizontal, the signal strength drops by over 20dB, proving the necessity of polarization alignment in RF links.

---

## V. REFLECTION / LEARNING SUMMARY

This laboratory session successfully visualized the "invisible" nature of electromagnetic fields. I learned that an antenna is not just a conductor, but a sophisticated spatial filter. The most significant insight was observing how the **Yagi-UDA parasitic elements** (which are not electrically connected to the source) can dramatically reshape a signal through mutual induction and phase shifting.

Additionally, the use of the **Matching Stub** highlighted the importance of "Maximum Power Transfer Theorem" in RF engineering. Even a high-gain antenna will perform poorly if its impedance is not matched to the transmitter. This experiment provided the foundational skills needed to design and troubleshoot real-world wireless communication systems where directivity and efficiency are paramount.
