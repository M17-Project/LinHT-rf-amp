[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

# LinHT-rf-amp

Standalone RF power amplifier module for the LinHT handheld, built around the **Guerrilla RF GRF5604**.  
This repository houses a proof-of-concept (PoC) board used to evaluate matching, biasing, efficiency, and linearity in the **420–450 MHz** band. Results from this effort will feed back into, and eventually be integrated with the
[main LinHT hardware project](https://github.com/M17-Project/LinHT-hw).


> Goal: validate a practical PA chain for LinHT. Once the approach is proven, the PA will be integrated into LinHT to enable higher output power (targeting ≈ 5 W at the radio level). This board is for laboratory development and characterization.

## Status

- **Work in progress.**
- Initial tuning follows the vendor EVB guidance for **~397–470 MHz** as a baseline

## Safety & Compliance

This hardware is intended for **licensed amateur radio** experimentation. Users are responsible for ensuring compliance with local regulations (spectral masks, occupied bandwidth, power limits, spurious emissions) before on-air use.

## License

This work is licensed under a  
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
