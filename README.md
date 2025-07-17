# SKA-Oil-Detection

**Entropy-Based Real-Time Oil Detection with Structured Knowledge Accumulation (SKA)**

This project applies the SKA learning framework to seismic waveform data for the detection of subsurface oil formations. SKA is an unsupervised, forward-only, entropy-driven learning model that tracks **informational regime changes** rather than of fitting predefined labels.

By measuring how information evolves in the seismic signal, SKA detects transitions between geological layers—such as the boundary between rock and oil—through sharp shifts in entropy. This makes it an ideal tool for real-time exploration and subsurface analysis.

## Features
- Synthetic seismic stream generator with oil-layer simulation
- Entropy-based detection using SKA principles
- Visual analysis of seismic transitions and entropy trajectories

## Why SKA Is Different

In classical analysis, models look for changes in the **signal itself** — peaks, noise, thresholds, or anomalies in amplitude. But SKA goes deeper.

> **SKA does not respond to signal changes — it responds to information changes.**

This means:
- A large spike in the seismic trace **may be ignored** if it carries no new information.
- A subtle variation in reflection **may trigger a strong entropy response** if it reveals uncertainty or a new subsurface layer.

This makes SKA uniquely suited for **exploration scenarios** where **information is sparse**, **labels are unavailable**, and **discovery is critical**.

## Call for Collaboration

We are actively seeking partnerships with **petroleum companies**, **research institutions**, and **geophysical service providers** willing to share:

- Legacy seismic datasets (2D or 3D)
- Seismic traces with known reservoir annotations
- Synthetic benchmark models used for training or internal validation

Our goal is to advance **open seismic research** by applying the **SKA framework** — a forward-only, entropy-based learning method — to **real-world oil detection scenarios**.

By contributing anonymized or deprecated datasets, you help:

- Enable next-generation subsurface analysis
- Accelerate unsupervised learning methods in exploration
- Foster collaboration between geoscientists and AI researchers

 If you or your organization are open to collaboration, please reach out via [GitHub Discussions](https://github.com/quantiota/SKA-Oil-Detection/discussions) or email us directly.


## License: 
MIT
