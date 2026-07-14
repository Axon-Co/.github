# Axon

Open-source brain-computer interface research and development.

Building accessible, low-cost BCI technology for robotic control, neural signal processing, and human-machine interaction.

## Projects

| Project | Description |
|---------|-------------|
| **Axis** | ESP32-based BCI. Reads NeuroSky TGAM EEG, controls servo motors in real-time. Core firmware + toolchain. |
| *(more coming)* | |

## Repository

This monorepo contains the Axon stack:

```
├── main/          Axis firmware (C, ESP-IDF)
├── tools/         Simulation, analysis, and visualization tools
├── docs/          Architecture guides, hardware docs, API reference
├── TASKS.md       Development roadmap
└── platformio.ini
```

## Getting Started

```bash
# No hardware? Run the simulation dashboard:
python tools/simulate_dashboard.py

# Build firmware:
idf.py set-target esp32 && idf.py build
```

## License

GPL v3 — All Axon projects are free and open-source.
