# Thermal Management of CPUs

## Introduction
This project aims to analyze the thermal behavior of CPUs and assess the impact of heat sinks on their temperature regulation. We focus on understanding how different thermal management strategies affect CPU temperatures.

## Assumptions
- Steady-state thermal conditions are assumed.
- Radiative heat transfer is considered negligible.
- Thermal properties are constant throughout the process.
- Conductive heat transfer is treated as linear.

## Geometry
The document includes a figure illustrating the geometry of CPUs and the heat sink, providing a visual understanding of the setup.

## Material Data
- **CPU Material:** Silicon (from Ansys Discovery library).
- **Heat Sink Material:** Copper (from Ansys Discovery library).

## Boundary Conditions
Two sets of boundary conditions are discussed:
1. **Without Heat Sink:**
   - 200 W of heat distributed among 3 CPUs proportional to their volume.
   - The bottom face of the CPUs is insulated.
   - A convection coefficient of 10 W/m²°C for heat transfer between CPU surfaces and air at 20°C.
2. **With Heat Sink:**
   - Similar heat distribution as above.
   - Insulation applied to the entire bottom face of CPUs and heat sink.
   - The same convection coefficient applied across the entire assembly.

## Initial Simulation Results (Without Heat Sink)
The initial results highlight the temperature distribution across the CPUs without a heat sink, indicating high temperatures that underscore the necessity of heat sinks.

## Inclusion of Heat Sink
The document details the integration of the heat sink into the simulation, showing a significant temperature reduction and the physics connections representing heat conduction between the CPUs and the heat sink.

## Design Variation Analysis
The impact of varying heat sink heights on the maximum temperature is analyzed, demonstrating that an increase in heat sink height leads to lower temperatures.

## High Fidelity Analysis
The results from using the default mesh and a finer mesh are compared, showing minimal differences and highlighting the effectiveness of the selected heat sink design.

## Notes:
While the heat sink significantly reduces CPU temperatures, additional cooling measures like forced convection with a computer fan are recommended for optimal thermal management.

## Reference and CAD file

- [Ansys Courses](https://courses.ansys.com/)

