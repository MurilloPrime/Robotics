# Robotics Analysis for Kinematics, Workspace, and Trajectory Planning

> **Note:**
> - DH parameters are established to a specific position of the robot. Depending on your zero position (home), parameters may change.
> - Home position of these 3 robots is shown later.

> **Tip:**
> - All robots have only 3 axes. The same analysis can be followed for more axes.

## Table of Contents
-[Robot construction]
  - [Angular (Anthropomorphic)](#angular-anthropomorphic)
    - [Home Position](#Home-Angular)
    - [Links and joints](#LinksJointsA)
  - [Cylindrical](#cylindrical)
    - [Home Position](#Home-Cylindrical)
    - [Links and joints](#LinksJointsC)
  - [SCARA](#scara)
    - [Home Position](#Home-SCARA)
    - [Links and joints](#LinksJointsS)
- [Direct Kinematics](#direct-kinematics)
  - [Direct Kinematics Theory](#direct-kinematics-theory)
  - [Angular (Anthropomorphic)](#angular-anthropomorphic)
  - [Cylindrical](#cylindrical)
  - [SCARA](#scara)
- [Inverse Kinematics](#inverse-kinematics)
  - [Inverse Kinematics Theory](#inverse-kinematics-theory)
  - [Angular (Anthropomorphic)](#angular-anthropomorphic-1)
  - [Cylindrical](#cylindrical-1)
  - [SCARA](#scara-1)
- [Workspace](#workspace)
  - [Jacobian Matrix & Jacobian Theory](#jacobian-matrix--jacobian-theory)
  - [Angular (Anthropomorphic)](#angular-anthropomorphic-2)
  - [Cylindrical](#cylindrical-2)
  - [SCARA](#scara-2)
- [Trajectory Planning](#trajectory-planning)
  - [Linear Spline](#linear-spline)
    - [Theory](#theory)
    - [Angular (Anthropomorphic)](#angular-anthropomorphic-3)
    - [Cylindrical](#cylindrical-3)
    - [SCARA](#scara-3)
  - [Cubic Spline](#cubic-spline)
    - [Theory](#theory-1)
    - [Angular (Anthropomorphic)](#angular-anthropomorphic-4)
    - [Cylindrical](#cylindrical-4)
    - [SCARA](#scara-4)
