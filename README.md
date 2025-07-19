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
2. Open `index.html` in your web browser.

Alternatively, download the ZIP and open the HTML file directly.

## Usage

1. Enter the wall height, supported load, and select options for spacing, wood species, and wall type.
2. Click **Calculate** to view results.
3. If the wall height exceeds 8ft, a note suggests adding mid-height blocking.
4. For heights over 12ft, a warning advises professional engineering review.
5. Use the **Reset** button to clear inputs.

### Example

- Wall Height: 10 ft
- Supported Load: 1000 plf
- Stud Spacing: 16"
- Wood Species: Douglas Fir-Larch No. 2
- Wall Type: Interior

**Result:** Might require a 2x6 stud, with status "Meets Requirements" (depending on calculations).

## Technical Details

- **Calculations:** Based on NDS 2018 for axial compression capacity, adjusted by column stability factor (Cp) for height. Exterior walls apply a conservative 20% reduction for bending moments (simplified; actual wind analysis recommended).
- **Prescriptive Check:** Aligns with IRC Table R602.3(5) limits where applicable.
- **Limitations:** Does not account for eccentric loads, shear, or full combined stress checks. For complex scenarios, use professional software.

## Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

1. Fork the project.
2. Create a feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This tool provides estimates only and is not a substitute for professional engineering advice. Calculations are based on simplified assumptions from IRC 2021 and NDS 2018. Verify all designs with a licensed structural engineer to ensure compliance with local codes and site-specific conditions. Oasis Engineering assumes no liability for any use of this tool or for any errors, omissions, or damages arising from its use.

## Acknowledgments

- Inspired by HUD and IRC guidelines for residential construction.
- Wood properties sourced from NDS 2018 Supplement.

If you find this useful, star the repo! ⭐
