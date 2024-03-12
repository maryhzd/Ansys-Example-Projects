# Fluid Flow Simulation in a Manifold

## Objective

This report details the process and outcomes of simulating internal fluid flow in a manifold. The aim is to showcase the workflow for setting up geometry, defining physics, solving, and visualizing results using GPU-powered and CPU-based solvers.

## Assumptions

- The fluid flow is steady-state.
- The structure is made of steel, with air as the fluid.
- Radiative heat transfer is negligible.
- Properties of steel and air are constant.

## Geometry

The simulation uses a manifold detailed in the report.

## Material Data

- **Structure Material:** Steel
- **Fluid:** Air

## Boundary Conditions

Detailed boundary conditions for the simulation are provided in the report.

## Simulation Process

### GPU-powered Solver (Ansys Discovery)

- Initial simulations are performed using Ansys Discovery, focusing on the GPU-powered solver.

### CPU-based Solver (Ansys Fluent)

- Subsequent simulations use Ansys Fluent, emphasizing the CPU-based solver.
- A mesh size of 5 mm is applied, with automatic refinement in areas of curvature.
- Convergence is monitored through average static pressure and velocity vectors.

## Results

### GPU-powered Solver (Ansys Discovery)

- Results include visualizations of internal flow, velocity vectors, and contour maps of flow velocity and pressure.

### CPU-based Solver (Ansys Fluent)

- Results are presented with a focus on mesh refinement, convergence monitoring, and contour maps.

## Conclusion

The report compares results from GPU-based and CPU-based solvers, discussing the trade-offs between speed and accuracy. The GPU solver's speed advantage is noted alongside a detailed comparison of flow velocity and total pressure results between the two solvers.

## Reference and CAD file

- [Ansys Courses](https://courses.ansys.com/)

