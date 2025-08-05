# 🧪 Bioanalytical-Calculator-Visualizer

A beginner-friendly Python tool designed for common **analytical** and **bioanalytical** calculations. It currently runs simple but essential concentration-related computations, with scope for expansion into visualizations and user interfaces in the future.

## ✨ Features

This calculator currently performs:

* ✅ **Molarity** (mol/L)
* ✅ **Molality** (mol/kg)
* ✅ **Normality** (eq/L)
* ✅ **Mass percentage composition** (%)

Planned additions:

* Dilution factor, ppm/ppb, percent concentration
* Spectrophotometric and titration-based calculations
* Calibration curves and visual outputs

## 🧠 What This Code Does

This script includes four core functions. You can run them by **editing the input values directly in the code** and executing the notebook.

### `calculate_molarity(mass_g, molar_mass_g_per_mol, volume_L)`

Calculates **molarity** (mol/L):

```python
result = calculate_molarity(1.0, 1.0, 1.0)
print("Molarity is:", result, "mol/L")
```

### `calculate_molality(mass_g, molar_mass_g_per_mol, solvent_kg)`

Calculates **molality** (mol/kg):

```python
result = calculate_molality(1.0, 1.0, 1.0)
print("Molality is:", result, "mol/kg")
```

### `calculate_mass_percentage_composition(mass_of_element_g, mass_of_whole_sample_g)`

Calculates **mass % composition**:

```python
result = calculate_mass_percentage_composition(1.0, 1.0)
print("Mass Percentage Composition is:", result, "%")
```

### `calculate_normality(weight_of_solute_g, equivalent_weight_of_solute_g_eq, volume_L)`

Calculates **normality** (eq/L):

```python
result = calculate_normality(1.0, 1.0, 1.0)
print("Normality is", result, "eq/L")
```

## 🧰 Tech Stack

* **Python** – Primary language
* **Matplotlib** *(planned)* – For future visual plots
* **Command-line/Notebook execution** – You run it via code, no GUI yet

## 🚀 How to Use

```bash
# Open and run in Jupyter Notebook or VS Code
python bio_calc_visualiser.ipynb
```

1. Open the notebook/script
2. Replace the sample values (`1.0`, `1.0`, `1.0`) in function calls with your own
3. Run the cell and read the printed result

## 🛣️ Future Plans

* 🖱️ GUI with selection menu (Tkinter or Streamlit)
* 📉 Plotting (e.g., concentration vs. volume, calibration graphs)
* 🧪 Advanced calculations (chromatography, electrophoresis)
* 🗂️ Exportable figures and data summaries

## 🧑‍🔬 Author Note

This tool is built as a part of my learning journey as a **Master's student in Bioanalytical Science**. It combines:

* Real lab concepts
* Python programming
* A passion to make scientific tools more accessible

This is just the beginning — future versions will include interactivity and advanced features!

Let me know if you'd like this exported as a `README.md` file now.
