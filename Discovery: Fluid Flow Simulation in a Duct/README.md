# Fluid Flow Simulation in a Duct

## Introduction

This document provides insights into a fluid flow simulation conducted on a duct using Ansys Discovery and Ansys Fluent, aiming to analyze the flow dynamics and assess the design's effectiveness.

## Assumptions

- The fluid flow is steady-state.
- The duct is made of steel, with air as the fluid.
- Radiative heat transfer is negligible.
- Properties of steel and air are sourced from Ansys Discovery's default properties.

## Geometry

The simulation uses a specific duct geometry, illustrated in the accompanying PDF file.

## Material Data

- **Structure Material:** Steel
- **Fluid:** Air

## Cross-Section Analysis

An initial analysis of the duct's cross-section revealed no inherent flow, leading to the manual addition of flow volume using Discovery's volume extract feature.

## Boundary Conditions

The boundary conditions highlight varying temperatures at the inlets, requiring simultaneous solutions for temperature and fluid velocity.

## Results

Results showcase the velocity streamline and temperature distribution, indicating potential design inefficiencies through flow exit patterns and particle flow animations.

## High Fidelity Analysis with Fluent

A high-fidelity analysis using Ansys Fluent refined the simulation, focusing on value convergence and mesh size optimization, with detailed results on velocity streamline and temperature profiles.

## Conclusion

The report compares GPU-based and CPU-based solver results, discussing flow velocity and temperature discrepancies. It emphasizes the need to balance speed and accuracy in solver selection and suggests design optimization for improved flow distribution.

## Reference and CAD file

- [Ansys Courses](https://courses.ansys.com/)


