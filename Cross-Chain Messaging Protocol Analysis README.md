# Crosschain Analytics

Automated data collection and analysis tool for cross-chain messaging protocols and bridge volume metrics. This repository contains scripts to gather, process, and visualize performance data from major blockchain interoperability solutions.

## Project Overview

This tool automates the collection of key metrics from cross-chain messaging and bridge protocols including:

- LayerZero/Stargate
- Wormhole
- Hyperlane
- Across
- Axelar
- Chainlink CCIP
- deBridge
- Mayan
- Relay

## Features

- Automated data collection from protocol explorers and APIs
- Historical data storage for trend analysis
- Standardized metrics across different protocols
- Regular data updates for competitive analysis

## Repository Structure

```
crosschain-analytics/
├── data/                   # Collected data files
├── scripts/                # Data collection scripts
│   ├── layerzero.py        # LayerZero data collector
│   ├── wormhole.py         # Wormhole data collector
│   └── ...
├── analysis/               # Analysis notebooks and scripts
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
```

## Getting Started

### Prerequisites

- Python 3.8+
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nturl/crosschain-analytics.git
   cd crosschain-analytics
   ```

2. Set up a virtual environment:
   ```bash
   python -m venv venv
   
   # On Windows:
   venv\Scripts\activate
   
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Run data collection scripts:
   ```bash
   python scripts/layerzero.py
   python scripts/wormhole.py
   ```

2. View collected data in the `data/` directory

## Data Sources

This project collects data from:
- LayerZeroScan
- WormholeScan
- Hyperlane Dune Dashboard
- Across Protocol Stats
- AxelarScan
- Chainlink CCIP Dashboard
- deBridge Explorer
- Mayan Explorer

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).