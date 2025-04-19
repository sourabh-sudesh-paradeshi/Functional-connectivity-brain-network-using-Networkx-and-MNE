Brain Connectivity Network Analysis
This project provides a general pipeline to compute and analyze brain connectivity networks using Python libraries such as NetworkX, MNE, and NumPy. It was developed as part of my research internship, during which I explored literature on the application of graph theory in understanding brain networks.

The repository includes:

Preprocessing EEG signal data

Computing functional connectivity (correlation/coherence)

Generating and analyzing networks for different frequency bands (delta, theta, alpha, beta, gamma)

Visualizations and spectral/graph-theoretic analysis

📁 Project Structure
bands/ – Scripts for generating and analyzing brain networks for each EEG frequency band

utils/ – Shared utility functions for preprocessing and computing connectivity

results/ – Outputs from each analysis

plots/ – Visualizations of the resulting networks

🧠 EEG Frequency Bands Covered
Delta (0.5–4 Hz)

Theta (4–8 Hz)

Alpha (8–13 Hz)

Beta (13–30 Hz)

Gamma (30–100 Hz)

Each band’s script runs the complete pipeline: data input → preprocessing → connectivity calculation → graph construction → analysis.

💡 Getting Started
Clone this repo

Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run any of the band scripts:

bash
Copy code
python bands/alpha_band.py
📌 Notes
The EEG data is assumed to be pre-recorded and available in .edf or compatible formats.

This is a basic, extendable pipeline and is intended as a starting point for anyone interested in applying graph-theoretic methods to neuroscience data.

📬 Contact
If you find this helpful or want to discuss improvements, feel free to reach out!

