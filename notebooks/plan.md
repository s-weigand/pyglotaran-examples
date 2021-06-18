# PyGlotaran improvements
## Features or plugins
### Core
- K-Matrix as rendered matrix
- K-Matrix (Megacomplex) as rendered flow schematics
- Save initial spec data to model and parameters (no print_md)

- data selection in model file (pre-processing)

### Project management
- SQL in core
- DVC as additional plugin

## Documentation
- terminology overview table
    - DAS/SAS/EAS
    - SAS
- how and when to use
    - equal_area_penalties
    - spectral_constraints
    - spectral_relations

## (2021-05-20)

### pyglotaran-extras
- default no heatmap (performance?) -> plots are slow in general 30% only for creation
- easier way to display k_matrix of megacomplex (do all have a k_matrix? different name? jörn changes?)
-

## case studies
- CK
- DPS1
- bacterial reaction center (glotaran + notebook)

# joris 25.04.2021

## File readers
- defend against unordered coords
- defend against none unique coords

## IRF from data
- users need to also provide time data

## Ivo (2021-05-06)
- PAL open + closed
- mail pyglotaran0704.zip

## Ivo (2021-05-20)
input -> megacomplex_scale
dataset -> multiple megacomplexes
