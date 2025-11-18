# Hexure Heat Pump Engine (HPE) Project

## Overview
This repository contains the complete technical documentation, analysis, and design files for the Hexure Heat Pump Engine (HPE) - a novel low-temperature thermal energy harvesting system using CO2/acetone phase transition expansion.

The HPE concept utilizes a closed-cycle system where a CO2/acetone mixture undergoes volumetric expansion at high pressure (70-120 bar) and moderate temperature (40°C), driving a turbine to generate electricity. The system incorporates a heat pump for thermal cycling and a secondary heat exchanger for energy recovery.

## Key Features
- Low-temperature operation (40°C hot side, 18-20°C cold side)
- High-pressure CO2/acetone mixture with up to 1000% volume expansion
- Closed-cycle design with energy recovery
- Potential for solar thermal or waste heat utilization

## Repository Structure
```
├── README.md                 # This file
├── SAFETY.md                 # Critical safety guidelines
├── LICENSE                   # Licensing information
├── docs/                     # Technical documentation
│   ├── executive_summary.md
│   ├── technical_whitepaper.md
│   ├── project_plan.md
│   └── experimental_protocol.md
├── analysis/                 # Quantitative analysis
│   ├── heat_pump_turbine_analysis.pdf
│   ├── heat_pump_turbine_detailed.csv
│   ├── heat_pump_turbine_analysis.png
│   └── hexure_analysis_release.zip
├── designs/                  # CAD and schematics
├── prototypes/               # Prototype documentation
└── references/               # Academic papers and references
```

## Analysis Results
Our analysis shows that the HPE system is theoretically viable in most operating conditions:
- 95.8% of cases produce positive net energy
- Maximum net energy achieved: 90.0 kJ/kg
- Minimum mass flow required for 100 kW output: 1.11 kg/s

See `analysis/heat_pump_turbine_analysis.pdf` for complete results.

## Safety Notice
This system involves high pressures (70-120 bar) and volatile solvents. Do NOT attempt construction without certified pressure-system engineers. See SAFETY.md for detailed guidelines.

## License
This project is licensed under the Open Hardware License v1.0 - see LICENSE file for details.

## Contact
For inquiries about collaboration or licensing, please open an issue or contact the repository owner.
