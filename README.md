# Quadrature Down Converter (QDC) 

As part of a broader exploration into RF and analog front-end circuit design, we individually designed and simulated a complete **Quadrature Down Converter (QDC)** using **LTSpice**. The QDC is a critical component in communication receivers, responsible for translating a high-frequency RF signal down to baseband while preserving both amplitude and phase information through the generation of in-phase (I) and quadrature-phase (Q) signals.

## 🔧 What We Designed

This project involved the discrete design and integration of the following major analog blocks:

- 🎯 **Quadrature Oscillator**: Generated two sinusoidal outputs with a 90° phase difference to drive the I and Q mixer paths.
- ⚙️ **Double-Balanced Mixers**: Multiplied the RF input with LO signals to produce both I and Q intermediate frequencies (IF).
- 🎚️ **Low-Pass Filters (LPF)**: Removed high-frequency components from the mixer output to isolate the desired baseband signal.

## 🔍 Key Focus Areas

- **Phase Accuracy**: Designed and tuned the quadrature oscillator to produce precise 90-degree phase-shifted outputs.
- **Mixing Behavior**: Implemented double-balanced mixers for superior isolation and improved linearity.
- **Filtering**: Tailored LPFs to suppress LO and image frequencies, improving overall signal clarity.
- **System Integration**: Verified signal path integrity from RF input through to baseband I/Q outputs using transient and FFT analysis.
- **Low Phase Noise**: Ensured oscillator stability to maintain signal purity and minimize jitter.

## 🔬 Simulation Tools & Techniques

- **LTSpice** for schematic design and simulation
- **Transient Analysis** for observing time-domain waveforms
- **FFT (Frequency Domain)** analysis for validating frequency translation and filter behavior

## 🧠 Learning Outcomes

This hands-on project deepened our understanding of:
- RF front-end architecture
- Frequency translation via mixing
- Analog signal chain design and debugging
- Practical implementation and simulation of theoretical concepts

## 👩‍💻 Contributors

- Moksha Choksi  
- Dhanika Kothari  
- Kavya Veer

## Error 
In the final report the calculation part of Quadrature oscillator should be done without consideration of inductor
