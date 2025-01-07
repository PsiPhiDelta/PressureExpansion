# Symbolic Pressure Derivatives in Mean-Field Models

This repository contains a Mathematica implementation for calculating higher-order derivatives of the thermodynamic pressure in mean-field thermal field theories using a Jacobian-based symbolic approach. The method avoids numerical instabilities associated with finite-difference schemes and provides a robust framework for studying thermodynamic properties in strongly interacting matter.

## Key Features
- **Symbolic Derivative Calculation**: Automatically handles higher-order pressure derivatives up to any desired order.
- **Examples Included**:
  - Single internal parameter models (e.g., constituent quark mass).
  - Two internal parameter models (e.g., constituent quark mass and diquark gap).
- **Comparison with Finite-Difference Methods**: Demonstrates improved stability and accuracy.

## Files
- **`symbolic_pressure_derivatives.nb`**: The main Mathematica notebook implementing the symbolic calculation of higher-order derivatives in models with one or two internal parameters. Includes:
  - Examples for calculating coefficients \( c_{mn} \) symbolically.
  - Recursive relations for extending to arbitrary orders.
- **`NJL-2f.nb`**: A Mathematica notebook containing calculations specific to the two-flavor NJL model discussed in the paper. This file includes:
  - Detailed derivations of pressure derivatives for the two-flavor NJL model.
  - Examples tailored to the theoretical framework presented in the paper.
These files are complementary to the paper and provides detailed insights and minimal tools for extending the analysis.

## Usage
1. Open the notebook `symbolic_pressure_derivatives.nb` in Mathematica.
2. Follow the instructions in the file to compute specific pressure derivatives for your chosen model.
3. For the two-flavor NJL model, refer to the `two_flavor_njl_calculations.nb` file for the detailed derivations and computations.
4. Customize the symbolic framework for additional constraints or parameters as needed.

## Author
**M. Hosein Gholami**  
TU Darmstadt  
Email: [mohammadhossein.gholami@tu-darmstadt.de](mailto:mohammadhossein.gholami@tu-darmstadt.de)
Email: [mohogholami@gmail.com](mailto:mohogholami@gmail.com)