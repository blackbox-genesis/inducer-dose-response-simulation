# Parameter Sweep on Synthetic Gene Circuit Using Tellurium

This project simulates the effect of varying inducer concentrations on protein expression in a simple synthetic gene circuit. It uses [Tellurium](http://tellurium.analogmachine.org/) for modeling and simulation, and `matplotlib` for data visualization.

## What It Does

- Models a basic gene expression system (Inducer -> mRNA -> Protein).
- Varies inducer concentrations using a `for` loop.
- Simulates each condition and plots the resulting protein expression over time.
- Shows how the system responds to different input levels.


## Model Description

The circuit includes:
- Inducer as input molecule.
- Transcription and translation reactions.
- Protein degradation.
- Parameters like production and degradation rates.

## Technologies Used

- `tellurium` (SBML modeling, Antimony support)
- `roadrunner` (built-in simulator)
- `matplotlib` (for graphing results)
- Python 3.10+

## Files

- `inducer_simulation.ipynb` -> main simulation script.
- `inducer_effect_on_protein.png` -> sample plot of output.
- `README.md` ->  project explanation.

## How to Run

1. Install dependencies:
   ```bash
   pip install tellurium matplotlib
   ```

2. Run the script:
   ```bash
   python inducer_parameter_sweep.py
   ```

3. Output graph will be shown and saved as `inducer_effect_on_protein.png`.

## What I Learned

- How to create dynamic simulations by looping through input parameters.
- How to use Tellurium to build and simulate a gene circuit.
- How to visualize biological models with matplotlib.
- Debugging model reactions and correcting simulation logic.

---

## References

- *Engineering Genetic Circuits*, University of Colorado Boulder, Coursera
- Alon, U. (2006). *An Introduction to Systems Biology*. Chapman & Hall/CRC.
- [Tellurium Documentation](https://tellurium.readthedocs.io/)
- [SBOL Visual](https://sbolstandard.org/visual/)

---

> This project is part of a personal initiative to build **mini synthetic biology models** before formal coursework begins.
