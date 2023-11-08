---

# Magnetic Field Calculation in Neural Tissue

This Python script calculates the magnetic field strength (in femtotesla) generated by an electric current (in picoamperes) at a specified distance from a neuron in neural tissue. The calculations are based on the equations derived in the associated paper (reference #13).

## Prerequisites

Before using this code, you need to have the following:

- Python installed on your system.
- A Python environment with the `math` module available.

## Running the Code

1. **Opening the Code**:

   - Copy the code into a Python environment or a Python file (e.g., `magnetic_field_neural_tissue.py`).
   - Execute the script using your preferred Python environment.

2. **Input Values**:

   - The program will prompt you to enter the electric current (in picoamperes) and the distance from the neuron (in nanometers).
  
   ```python
   Enter the electric current (in picoamperes): [enter_value]
   Enter the distance from the neuron (in nanometers): [enter_value]
   ```

3. **Viewing the Results**:

   - The script will calculate the magnetic field strength (MF) and display the result in femtotesla.
  
   ```python
   The MF (B) calculated is: [result] femtotesla
   ```

## Usage Tips

- Ensure you provide accurate values for the electric current (I) and the distance from the neuron (r) based on your data or measurements.
- The calculation assumes a fixed value of μ (mu) for neural tissue. Review and adjust this value if necessary.

## Support and Contact

For any questions or issues, feel free to contact the author at k11shahryari@gmail.com

---
