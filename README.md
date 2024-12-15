# Automated Radio Frequency Signals Detector for Energy Harvesting

## Project Overview

Radio frequency (RF) signals are everywhere, powering our IoT devices, mobile networks, and Wi-Fi systems. Yet, a significant portion of their energy is wasted as heat. This project automates RF signal detection and harvesting to convert this untapped energy into a renewable power source for IoT devices. By addressing inefficiencies in RF energy usage, the solution enhances sustainability in communication networks while powering low-energy devices.

### Key Features
- **Training Dataset:** Synthetically Generated Due to sampling scarcity.
- **RF Signal Detection:** Employs a CNN model to identify RF signals.
- **Signal Processing:** Normalizes and filters RF signals to reduce noise.
- **Energy Conversion:** Utilizes a CMOS rectifier to transform RF signals into usable energy.
- **IoT Compatibility:** Targets emissions from IoT sensors and RF sources.
- **User-Friendly Interface:** Streamlit app for system monitoring and visualization.

![alt text](<DALL·E 2024-12-15 13.03.48 - A conceptual illustration showing the process of converting radio frequency (RF) signals emitted by an IoT sensor into usable energy using a CMOS rect.webp>)

## Why This Matters

RF signals, emitted by devices like routers, smartphones, and IoT sensors, are a ubiquitous yet underutilized energy source. Capturing even small amounts of this energy can power sensors and reduce the need for traditional energy sources, advancing renewable energy goals and sustainability efforts.

## Energy Conservation Estimation

**Formula:**
```
Energy Harvested (mW) = Power Density (mW/cm²) × Antenna Area (cm²) × Efficiency
```

**Example:**
- Power Density: 0.01 mW/cm² (IoT device at close range)
- Antenna Area: 10 cm²
- Efficiency: 50%

**Result:**
```
Energy Harvested = 0.01 × 10 × 0.5 = 0.05 mW
```

While the energy per device is small, harvesting from 1,000 devices in an urban setup could significantly power multiple low-energy devices, like environmental sensors or smart city infrastructure.

**SAMPLE DETECTED RF SIGNAL IMAGE BY PROPOSED MODEL**
![alt text](<Screenshot (125)-1.png>)

## Technical Stack

- **Languages:** Python
- **Libraries:** TensorFlow/Keras, NumPy, Pandas, Streamlit
- **Hardware:** CMOS Rectifier, IoT sensors
- **Tools:** Signal normalization and filtering pipelines

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RF-Energy-Harvester.git
   cd RF-Energy-Harvester
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the Streamlit app:
   ```bash
   streamlit run app.py
   ```
4. Connect hardware (IoT sensors and CMOS rectifier) to start harvesting energy.

## Use Cases

- **Emergency Scenarios:** Provides energy to IoT devices in extreme weather or disasters.
- **IoT Sustainability:** Powers low-energy sensors, extending device lifespans.
- **Green Tech Research:** Advances renewable energy harvesting methods.

## Future Enhancements

- **Optimized Models:** Improve CNN efficiency for real-time processing.
- **Expanded IoT Support:** Broaden device compatibility.
- **Scalable Deployment:** Enable edge computing for larger networks.
- **Energy Storage:** Add storage capabilities with supercapacitors or batteries.

## Contributions

Contributions are welcome! Open an issue or submit a pull request with suggestions or improvements.


## Acknowledgments

Special thanks to Nokia Ideathon for inspiring this project and to researchers in RF energy harvesting and IoT sustainability.

"# Convoluted-RF-Signal-Harvester" 
