<h1 align="center">Mobility Shield Parts</h1>

<p align="center">
  Open-source library of parametric CAD components and 3D-printable parts for the Mobility Shield modular robotics ecosystem.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OpenJSCAD-v1-2471A3?style=flat-square" alt="OpenJSCAD v1">
  <img src="https://img.shields.io/badge/Parametric_Parts-21-555555?style=flat-square" alt="21 parametric parts">
  <img src="https://img.shields.io/badge/STL_Models-3-555555?style=flat-square" alt="3 STL models">
  <a href="./LICENSE.md"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-008080?style=flat-square" alt="CC BY-SA 4.0"></a>
</p>

## Overview

**Mobility Shield Parts** provides reusable mechanical components for the [Mobility Shield Builder](https://builder.mobilityshield.com), including configurable structural elements, mounting brackets, profiles, and 3D-printable models.

The current parametric library uses the **legacy OpenJSCAD v1 API**.

## Parts Catalog

### Parametric Parts (JSCAD)

| Part | Description |
|---|---|
| [`L-plate.jscad`](./Parametric%20parts/L-plate.jscad) | L-shaped perforated mounting plate. |
| [`T-plate.jscad`](./Parametric%20parts/T-plate.jscad) | T-shaped structural connection plate. |
| [`U-plate.jscad`](./Parametric%20parts/U-plate.jscad) | U-shaped mounting plate. |
| [`angle-bracket.jscad`](./Parametric%20parts/angle-bracket.jscad) | Right-angle mounting bracket. |
| [`angle-girder.jscad`](./Parametric%20parts/angle-girder.jscad) | L-section structural girder with mounting holes. |
| [`circular-plate.jscad`](./Parametric%20parts/circular-plate.jscad) | Circular mounting plate with configurable holes. |
| [`circular-stripe.jscad`](./Parametric%20parts/circular-stripe.jscad) | Circular perforated strip for radial structures. |
| [`corner-brace-square.jscad`](./Parametric%20parts/corner-brace-square.jscad) | Square corner reinforcement brace. |
| [`corner-triangular-brace.jscad`](./Parametric%20parts/corner-triangular-brace.jscad) | Triangular corner reinforcement brace. |
| [`cross-plate.jscad`](./Parametric%20parts/cross-plate.jscad) | Cross-shaped structural connection plate. |
| [`curved-strip-with-slots.jscad`](./Parametric%20parts/curved-strip-with-slots.jscad) | Curved mounting strip with optional elongated slots. |
| [`curved-strip.jscad`](./Parametric%20parts/curved-strip.jscad) | Curved perforated structural strip. |
| [`gear.jscad`](./Parametric%20parts/gear.jscad) | Parametric involute spur gear with configurable teeth and dimensions. |
| [`miniprofile.jscad`](./Parametric%20parts/miniprofile.jscad) | 15 × 15 mm structural extrusion profile with adjustable length. |
| [`open-box.jscad`](./Parametric%20parts/open-box.jscad) | Parametric open-top enclosure. |
| [`plate-flanged.jscad`](./Parametric%20parts/plate-flanged.jscad) | Perforated mounting plate with configurable edge flanges. |
| [`plate.jscad`](./Parametric%20parts/plate.jscad) | Rectangular mounting plate with configurable hole pattern. |
| [`rectangular-frame.jscad`](./Parametric%20parts/rectangular-frame.jscad) | Rectangular structural frame with mounting holes. |
| [`strip-with-slots.jscad`](./Parametric%20parts/strip-with-slots.jscad) | Straight mounting strip with elongated slots. |
| [`strip.jscad`](./Parametric%20parts/strip.jscad) | Straight perforated structural strip. |
| [`triangular-plate.jscad`](./Parametric%20parts/triangular-plate.jscad) | Triangular perforated mounting plate. |

### Non-Parametric Parts (STL)

| Part | Description |
|---|---|
| [`Motor-Mount-28BYJ-48_M3INSERT.stl`](./Non%20Parametric%20parts%20%28STL%29/Motor-Mount-28BYJ-48_M3INSERT.stl) | Fixed motor mount for the 28BYJ-48 stepper motor with M3 inserts. |
| [`plate-5x6-Arduino-UNO_M3TAP.stl`](./Non%20Parametric%20parts%20%28STL%29/plate-5x6-Arduino-UNO_M3TAP.stl) | Fixed mounting plate for an Arduino Uno with M3 tapped holes. |
| [`wheel-hex_M3TAP.stl`](./Non%20Parametric%20parts%20%28STL%29/wheel-hex_M3TAP.stl) | 3D-printable wheel with hexagonal interface and M3 fastening. |

Parametric source files are located in [`Parametric parts`](./Parametric%20parts), while ready-to-print STL models are available in [`Non Parametric parts (STL)`](./Non%20Parametric%20parts%20%28STL%29).

## License

The repository's existing project license is [Creative Commons Attribution-ShareAlike 4.0 International](./LICENSE.md). Individual third-party components may carry separate licensing terms.

Project author and license attribution: [J. Rodrigo](https://jrodrigo.com).
