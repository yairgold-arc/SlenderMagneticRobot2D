# SlenderRobot2D

**Physics-Based Catheter Navigation and Magnetic Steering Simulator**

SlenderRobot2D is a research-oriented simulation framework for modeling flexible catheters and guidewires navigating through complex vascular geometries.

The simulator combines:

- Elastic rod mechanics
- Wall contact and friction
- Magnetic tip steering
- Vessel generation and bifurcations
- Navigation algorithms
- Real-time diagnostics dashboard
- Movie generation
- Physics validation tools

The project is intended as an experimental platform for investigating catheter navigation strategies before transferring concepts to physical systems.

---

# Demonstration Videos

## Magnetic Navigation Through Complex Vessel

[Watch the magnetic navigation demo](Movies/dashboard_movie4.mp4)

Demonstrates:

- Elastic catheter dynamics
- Magnetic steering
- Wall interaction
- Vessel navigation
- Real-time diagnostics

---

## Dashboard and Diagnostics

[Watch the dashboard and diagnostics demo](Movies/dashboard_movie5.mp4)

Demonstrates:

- Wall interaction monitoring
- Tip tracking
- B0 steering control
- Energy decomposition
- Navigation diagnostics

---

# Main Capabilities

## Elastic Rod Mechanics

The catheter is modeled as a discretized elastic rod.

Supported effects:

- Axial stretching
- Bending deformation
- Kinetic energy
- Viscous damping

---

## Vessel Contact

The catheter interacts with vessel walls through:

- Penalty contact forces
- Dynamic friction
- Multiple independent walls
- Complex vascular geometries

---

## Magnetic Steering

Distal catheter segments may carry magnetic moments.

An external magnetic field:

```text
B0