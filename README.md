# SKA-Oil-Detection

**Entropy-Based Real-Time Oil Detection with Structured Knowledge Accumulation (SKA)**

This project applies the SKA learning framework to seismic waveform data for the detection of subsurface oil formations. SKA is an unsupervised, forward-only, entropy-driven learning model that tracks **informational regime changes** instead of fitting predefined labels.

By measuring how information evolves in the seismic signal, SKA detects transitions between geological layers—such as the boundary between rock and oil—through sharp shifts in entropy. This makes it an ideal tool for real-time exploration and subsurface analysis.





## Features
- Synthetic seismic stream generator with oil-layer simulation
- Entropy-based detection using SKA principles
- Visual analysis of seismic transitions and entropy trajectories

## Why SKA Is Different

In classical analysis, models look for changes in the **signal itself** — peaks, noise, thresholds. But SKA goes deeper.

> **SKA does not respond to signal changes — it responds to information changes.**

This means:
- A large spike in the seismic trace **may be ignored** if it carries no new information.
- A subtle shift in reflection **may trigger a strong entropy response** if it introduces uncertainty or reveals a new layer.

This makes SKA uniquely suited for **exploration scenarios** where **information is sparse** and **labels are unavailable**.



## License: 
MIT
