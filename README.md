# extractEulerianParticlesMod
Function object to identify particles traversing a faceZone in VOF simulations with [OpenFOAM v1906](https://openfoam.com/)

## Installation
- Unzip src.zip
- Source OpenFOAM v1906
- Execute "wmake" to compile the code

## Usage
- Settings for the function object must be included in system/controlDict
- An example can be found in the droplet test case
- All available settings can be found in the header of extractEulerianParticlesMod.H

## Droplet Test Case
- Unzip run.zip
- Source OpenFOAM v1906
- Execute "bash Allrun" to run the case
- Tracking results are written to <time>/lagrangian/
