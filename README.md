# VulcanPy

Open-source Python toolkit for volcanic analysis and eruption prediction.

## Purpose

VulcanPy is a general-purpose, reusable toolkit designed to assist volcanologists in processing and interpreting common data streams used for eruption prediction. The toolkit provides modules for seismic data filtering, thermal anomaly detection, volcano alert level logging, and more, based on expert knowledge in volcano monitoring.

## Planned Functionalities

- **Seismic Data Filter**: Ingest raw seismic waveform data (from CSV files) and apply band-pass filters to remove noise.
- **Thermal Anomaly Threshold Detector**: Process thermal radiation values and flag timestamps where values exceed defined thresholds.
- **Color Code State Logger**: Log changes to a volcano's Level of Concern Color Code (e.g., GREEN, YELLOW, ORANGE, RED) with timestamps.
- **Satellite Imagery Utilities**: Future support for analyzing thermal anomalies from satellite data.
- **Seismic Event Detection**: Identify volcanic earthquakes and tremor patterns.
- **Data Visualization**: Plotting tools for seismic and thermal time series.

## Directory Structure

```
VulcanPy/
├── src/           # Main Python source code
├── tests/         # Unit tests
├── docs/          # Documentation
├── LICENSE        # MIT License
└── README.md      # This file
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/z-teckson/VulcanPy.git
   cd VulcanPy
   ```

2. Install dependencies (requirements.txt will be added soon):
   ```bash
   pip install -r requirements.txt
   ```

3. Explore the modules in `/src`.

## Contributing

We welcome contributions from the community! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Write your code and add tests in `/tests`.
4. Ensure your code passes existing tests.
5. Submit a pull request with a clear description of your changes.

Refer to the open issues for ideas on what to work on.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or suggestions, open an issue on GitHub or contact the maintainers.

## Acknowledgments

- Inspired by the need for open-source tools in volcanology.
- Based on expertise in seismic monitoring, thermal anomaly detection, and eruption prediction.