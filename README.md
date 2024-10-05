# Unitary Matrix Rotation Representations and Transformations

This notebook provides a set of functions for working with 3D rotations through different representations, using the mathematical framework of Unitary matrices. These representations include rotation matrices, axis-angle forms, and Euler angles. The transformations between these representations are useful in fields such as physics, computer graphics, and robotics.

## Features

- **Axis-Angle to Unitary Matrix**: Convert a given rotation axis $( \hat{n} \)$ and angle $( \theta \)$ into a Unitary rotation matrix.
- **Euler Angles to Unitary Matrix**: Convert given Euler angles $( \beta, \gamma, \delta \)$ into a Unitary matrix.
- **Unitary Matrix to Euler Angles**: Extract Euler angles and phase factor from a Unitary matrix.
- **Axis-Angle to Euler Angles**: Convert the axis-angle form into Euler angles.
- **Euler Angles to Axis-Angle**: Retrieve the rotation axis and angle from Euler angles.

## Dependencies

- `numpy`: For matrix operations and numerical computations.
- `scipy`: For matrix exponentiation and other scientific calculations.

