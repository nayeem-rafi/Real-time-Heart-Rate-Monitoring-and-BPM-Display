# Real-time Heart Rate Monitoring and BPM Display
By [Naimur Rahman](https://github.com/nayeem-rafi), [Md.Nayon Khan](https://github.com/nayon045).

## [Click for Video Presentation](https://drive.google.com/drive/folders/1ES1MQiooYIQ9b5-67jWGU9l0O2tWrXez?usp=drive_link)
## Go to Documents Get Report for More Explanation with Project Demonstration.
## Project Overview

This project presents a practical and affordable heart rate monitoring system that detects, amplifies, and displays heartbeat rates in real-time using easily accessible components. Designed for applications in clinical diagnostics, fitness tracking, and health research, this device counts Beats Per Minute (BPM) and displays the result on a 7-segment display. The simple circuit design features components like a microphone, amplifier, filters, and counters, making it accessible for students and hobbyists alike.

## Table of Contents

1.  [Introduction](#introduction)
2.  [Project Description](#project-description)
3.  [Design and Components](#design-and-components)
4.  [Circuit Diagram and Explanation](#circuit-diagram-and-explanation)
5.  [Simulation Results](#simulation-results)
6.  [Hardware Implementation](#hardware-implementation)
7.  [Application Areas and Limitations](#application-areas-and-limitations)
8.  [Cost Estimation](#cost-estimation)
9.  [Conclusion](#conclusion)
10. [References](#references)

---

## 1. Introduction

Heart rate monitoring is crucial in healthcare as it provides insights into cardiovascular health. This project leverages a heartbeat sensor that integrates a microphone, amplifier, and low-pass filter to process heartbeat sounds. The design is optimized to display heart rate in BPM on a 7-segment display, offering an efficient and affordable way to monitor cardiovascular health.

## 2. Project Description

This heart rate monitoring device measures an individual’s BPM in real-time and is intended for various applications. It is low-cost, portable, and easy to build, making it accessible for non-professionals and ideal for educational and experimental purposes in healthcare, fitness, and research.

## 3. Design and Components

### Components Used

- **IC LM741 Operational Amplifier**: Amplifies weak signals from the microphone.
- **Capacitors and Resistors**: Control amplification and frequency filtering.
- **Microphone Condenser**: Captures heart sounds via a stethoscope.
- **7-Segment Display**: Shows BPM output in a readable format.
- **Binary Counter and Decoder ICs**: Convert the heart signal to a format for display.

### Key Circuit Components

- **Microphone and Amplifier**: Capture and boost the heartbeat signal.
- **Comparator and Counter**: Detect and count heartbeat signals.
- **BCD to 7-Segment Display**: Convert and display BPM on a 7-segment display.

## 4. Circuit Diagram and Explanation

### Block Diagram and Function

The circuit consists of several modules:
1. **Signal Capture**: Microphone captures the heartbeat sound.
2. **Amplification and Filtering**: Amplifier and low-pass filter refine the heartbeat signal.
3. **Conversion and Counting**: A binary counter counts BPM over 10 seconds.
4. **Display**: The CD4511 BCD-to-7-segment driver outputs the heart rate to a 7-segment display.

This design ensures an accurate and visually accessible heart rate monitoring experience.

## 5. Simulation Results

The simulation demonstrates the device’s accurate pulse detection, amplification, and digital display on the 7-segment output. This setup allows verification of signal integrity and output consistency.

## 6. Hardware Implementation

The hardware implementation includes all major components arranged on a veroboard for easy construction. Images of the final build can be referenced in the Document Report section.

## 7. Application Areas and Limitations

### Real-life Applications
- BPM monitoring for personal and clinical use
- Fitness tracking for performance monitoring
- Cardiac research and data collection
- Signal analysis in medical and experimental fields

### Limitations
- **Signal Interference**: Susceptible to environmental interference.
- **Diagnostic Capability**: Intended for basic monitoring, not medical diagnostics.

## 8. Cost Estimation

The project is cost-effective with a total cost of approximately 900 BDT. Below is a summary of primary components and their respective costs:

| Component                | Cost (BDT) |
|--------------------------|------------|
| Stethoscope              | 400        |
| Microphone Condenser     | 20         |
| ICs (Various)            | 300        |
| Resistors and Capacitors | 50         |
| Veroboard                | 30         |
| 7-Segment Display        | 60         |
| **Total**                | **900**    |

## 9. Conclusion

This heart rate monitoring system provides a cost-effective, functional way to measure heart rates accurately. Future enhancements could include more advanced components for improved signal processing and data storage capabilities, aiming for broader medical applications.

## 10. References

1. Op-Amp: [IC-741 Op-Amp Basics](https://www.electronicshub.org/ic-741-op-amp-basics/)
2. Microphone: [Microphone Specification](https://www.cuidevices.com/product/resource/cma-4544pf-w.pdf)
3. 74ls32: [Build Electronic Circuits](https://www.build-electronic-circuits.com/7400-series-integrated-circuits/74hc32-74ls32/)
4. And more sources as listed in the project document...

---


---

