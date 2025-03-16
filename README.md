# Epithelial Simulation

This repository contains a simulation of epithelial monolayer buckling, following the theoretical model in [PhysRevLett.107.078104](https://doi.org/10.1103/PhysRevLett.107.078104). The simulation generates animations that visualize different parameter effects.

## 📌 Features
- Simulates epithelial layer dynamics based on buckling instability.
- Saves animations to the `complete_second_order/` folder.
- Uses Python (`.ipynb` format) for interactive exploration.

## 📽️ Example Animation
Here’s a sample of the generated output:

![Example Animation](complete_second_order/w_tilde.mp4)

> **Note:** GitHub does not support direct `.mp4` previews. You may need to download and view the video locally.

## 📜 Mathematical Formulation
The evolution equation governing the system is:

$$ \frac{\partial w}{\partial t} = -\alpha \nabla^4 w + \beta \nabla^2 w - \gamma w $$

where:
- \( \alpha \) is the bending rigidity,
- \( \beta \) accounts for surface tension effects,
- \( \gamma \) represents external pressure forces.

For more details, refer to the [paper](https://doi.org/10.1103/PhysRevLett.107.078104).

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/epithelial_simulation.git
   cd epithelial_simulation
