# EXPERIMENT 21: ANTENNA TRAINER KIT

## I. OBJECTIVES

* **Radiation Mapping:** To experimentally determine and plot the 2D radiation patterns of various resonant and non-resonant antennas in the polar coordinate system.
* **Parameter Evaluation:** To measure and compare critical antenna metrics such as gain, directivity, front-to-back ratio, and half-power beamwidth (HPBW).
* **Array Investigation:** To analyze the effect of parasitic elements (in Yagi-Uda arrays) and phasing (in antenna arrays) on the shape and concentration of electromagnetic fields.
* **Impedance Optimization:** To demonstrate the practical application of matching stubs in minimizing standing wave ratios (SWR) and maximizing power delivery.

---

## II. MATERIALS AND COMPONENTS USED

### System Equipment
* **Master Antenna Trainer Unit:** The central hub providing a regulated RF source (typically VHF/UHF), modulation controls, and a digital/analog display for signal strength.
* **Matching Stub:** A transmission line tuner used to cancel out reactance and match the antenna's impedance to the feeder line.
* **Transmitting Mast:** A rotatable support structure with a 360° scale used to adjust the angular position of the test antenna relative to the receiver.
* **Stationary Receiving Mast:** Holds the detector probe or receiving antenna at a fixed distance, ensuring measurements are taken in the "far-field" region.
* **RF Detector:** A high-sensitivity rectification circuit that converts captured electromagnetic energy into a readable DC signal.


### Detailed Antenna Element Catalog

1.  **Detector Antenna:** A small, specialized probe used specifically to capture the radiated field for the trainer's measurement system without distorting the field.
2.  **Slot Antenna λ/2:** A literal slot cut into a metal sheet. Based on Babinet's Principle, it radiates similarly to a dipole but with horizontal polarization if the slot is vertical.
3.  **Helix Antenna:** A wire shaped like a corkscrew. In "Axial Mode," it produces circular polarization, which is essential for satellite communication to prevent signal fading.
4.  **Yagi-UDA Folded Dipole (3E):** A three-element directional array. It uses a folded dipole as the "driven" element, a slightly longer "reflector" behind it, and a shorter "director" in front to focus energy forward.
5.  **Yagi-UDA Folded Dipole (5E):** An expanded array featuring three directors. The extra elements further compress the main lobe, significantly increasing forward gain.
6.  **Yagi-UDA Simple Dipole (5E):** Similar to the folded version but uses a standard straight dipole driver. This offers high gain but generally possesses a narrower operational bandwidth.
7.  **Yagi-UDA Simple Dipole (7E):** A high-performance array with five directors. It provides the narrowest beamwidth and highest directivity in this kit, used for long-distance point-to-point links.
8.  **Simple Dipole 3λ/2:** A long-wire harmonic antenna. Operating at three times the base frequency, it produces multiple lobes and nulls, showing higher directivity than a standard dipole.
9.  **Folded Dipole λ/2:** A dipole where the conductor is folded back on itself. This quadruples the input impedance (to ~300Ω) and broadens the bandwidth, making it ideal as a driver for Yagi arrays.
10.  **Simple Dipole λ/2:** The "Gold Standard" of antennas. A resonant half-wave wire that produces an omnidirectional toroid-shaped pattern with maximum radiation perpendicular to the wire.
11. **Simple Dipole λ/4:** A compact version often used as a monopole. It relies on a ground plane to "reflect" its other half, creating a radiation pattern similar to a full dipole but with higher elevation.
12. **Zeppelin (Zepp) Antenna:** An end-fed resonant λ/2 antenna. Traditionally used in airships, it is fed at a high-impedance point through a balanced matching section.
13. **Hertz Antenna:** A fundamental term for any balanced, "ungrounded" antenna (like a dipole). It is self-contained and does not require the Earth as part of the circuit.
14. **Combined Co-linear Array:** A vertical stack of dipoles. By phasing them together, the radiation is "squashed" toward the horizon, increasing omnidirectional gain for ground-based receivers.
15. **λ/2 Phase Array:** Two dipole elements spaced half a wavelength apart. Depending on the feed phase, they can reinforce signals to create specific interference patterns.
16. **λ/4 Phase Array:** An array with quarter-wave spacing. Often used to create "End-Fire" patterns where the signal is directed along the line of the elements.
17. **Cut Paraboloid Antenna:** A microwave dish reflector "cut" into a rectangular shape. It uses a primary feed (like a dipole) to bounce waves off a curved surface into a highly focused "pencil" beam.
18. **Broadside Array:** A configuration where all elements are fed in phase. This creates a massive main lobe perpendicular to the plane of the antenna elements. 
19. **Loop Antenna:** A closed circular or square conductor. It behaves primarily as a magnetic dipole and is highly effective at rejecting electrical noise in compact spaces.
20. **Log Periodic Antenna:** A wideband directional antenna. Its elements vary logarithmically in length, allowing it to maintain consistent gain and impedance across a huge frequency range.
21. **Ground Plane Antenna:** A vertical radiator with horizontal "radials" at the base. The radials simulate an artificial ground, allowing the antenna to be mounted high above the actual earth.
22. **Rhombus Antenna:** A large, diamond-shaped, non-resonant wire antenna. It is exceptionally wideband and produces high gain, often used for long-range high-frequency (HF) communication.
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
