# Heat-Wave-Collapse

Update: this was presented on student research day in my first M.Sc. year. Preliminary (by no means rigorous), and... actually was a really fun exercise.

---

We introuce a dynamic model to map the tipping points of cities undergoing heat waves.

Current disaster planning relies on linear models, which assume a system stretches indefinitely (e.g., 1 degree hotter = 10 more deaths). Real systems don't stretch forever; they snap. 

We adapted standard population-flow math to track how people move between three states during a heat wave: Safe, Impacted, and Hospitalized. By factoring in system congestion, the math identifies a an asymptote - a "wall" where the system collapses on itself. 

Linear models are blind to this wall, this model finds it. We tested this against the 2021 British Columbia Heat Dome (Lytton); the model identified the collapse point just 0.7°C away from the peak temperature of the village before it burned down.

### Flow Diagram
<img width="1414" height="808" alt="Screenshot 2026-03-26 at 4 20 04 pm" src="https://github.com/user-attachments/assets/01d14d09-2899-42d2-a05b-021591abaa7e" />

### How to use
Open the `heat-wave-model.ipynb` file in Google Colab or Jupyter Notebook and run the cells. It simulates the theoretical model and plots the asymptote comparing both linear and dynamic outputs.
