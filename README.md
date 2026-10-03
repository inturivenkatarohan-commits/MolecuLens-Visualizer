# MolecuLens-Visualizer
# ⚛️MolecuLens: Interactive Chemical Visualizer

**MolecuLens** is an interactive web app that converts chemical names or SMILES strings into energy-minimized 3D molecular structures and calculates key drug-likeness properties in real time.

---

## Features
* **3D Molecule Renderer:** Rotatable WebGL visualization (Stick, Sphere, Surface views).
* **Energy Minimization:** Optimizes 3D atomic geometry using the MMFF force field.
* **Property Calculation:** Computes Molecular Weight, LogP, and H-Bond Donors/Acceptors.
* **PubChem API:** Auto-resolves common compound names (e.g., *Caffeine*, *Aspirin*) into SMILES strings.

---

## Tech Stack
`Python` | `Streamlit` | `RDKit` | `py3Dmol` | `PubChemPy`

---

## Quick Start

1. **Clone & Install Dependencies:**
   ```bash
   git clone [https://github.com/your-username/mol3d-visualizer.git](https://github.com/your-username/mol3d-visualizer.git)
   cd mol3d-visualizer
   pip install -r requirements.txt
