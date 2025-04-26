# 18650 Battery Module Design and Simulation

## Overview
This project features a 60-cell 18650 battery module designed in SolidWorks. It includes 3D modeling, exploded view, dimensioned drawings, and FEA stress testing to validate the lid and wall under uniform bolt pressure using real-world materials.

## Table of Contents
1. [CAD Models](#cad-models)
2. [Engineering Drawings](#engineering-drawings)
3. [Simulation Results](#simulation-results)
4. [Exploded View & Assembly](#exploded-view--assembly)
5. [Materials Used](#materials-used)

---

## CAD Models
SolidWorks `.SLDPRT` and `.SLDASM` files for:
- Lid
- Base Plate
- Side Walls
- Assembly file

## Engineering Drawings
Includes dimensioned and toleranced drawings for each part, using ANSI standard with real manufacturing tolerances (e.g., ±0.1 mm on hole locations, +0.13/0 mm on bolt diameters).

## Simulation Results
- Static stress simulation under 5000 N/m² uniform pressure on the lid.
- Max von Mises stress: ~9.7 kPa (well below Aluminum 6061-T6 yield of 55 MPa)
- Displacement plot confirms minimal flex at bolt hole regions.

## Exploded View & Assembly
An exploded view animation illustrates the full stack-up from base to lid, with proper part order and bolt hole alignment.

## Materials Used
- Lid & Casing: Aluminum 6061-T6
- Busbars: Copper (annealed)
- Battery Shells: Stainless Steel 304
