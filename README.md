# Residential Load-Bearing Wall Calculator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/residential-calculators.svg?style=social)](https://github.com/yourusername/residential-calculators/stargazers)

A simple, web-based tool to estimate stud requirements for residential load-bearing walls based on the International Residential Code (IRC) 2021 and National Design Specification (NDS) for Wood Construction 2018. This calculator helps users determine the minimum stud size needed for given wall height, supported load, stud spacing, wood species, and wall type (interior or exterior).

**Note:** This is an estimation tool for educational purposes. Always consult a licensed structural engineer for actual designs. It assumes axial loads primarily; lateral forces (wind, seismic) require separate verification.

## Features

- **Input Parameters:**
  - Wall height (ft)
  - Supported load (pounds per linear foot, plf)
  - Stud spacing (12", 16", or 24" on center)
  - Wood species and grade (e.g., Douglas Fir-Larch No. 2)
  - Wall type (interior or exterior with conservative wind adjustment)

- **Outputs:**
  - Required stud size (e.g., 2x4, 2x6)
  - Maximum allowable load per stud and per linear foot
  - Status (meets or does not meet requirements)
  - Recommendations for blocking on tall walls
  - Warnings for heights exceeding IRC limits

- **Reference Table:** Dynamic capacity table for quick lookups at 10ft height.
- **Responsive Design:** Works on desktop and mobile.
- **No Dependencies:** Pure HTML, CSS, and JavaScript—runs in any modern browser.

## Demo

You can try the calculator live [here](https://oasisengineering.com/res-wood-wall-bearing-calculator/).

## Installation

No installation required! This is a static web page.

1. Clone the repository:
