# gLayout Track Resources
> 🚧 **Under Construction** 

- [Brief Overview of the gLayout](./files/Glayout_Overview.pdf) 

- [gLayout GitHub Repo](https://github.com/ReaLLMASIC/gLayout)

- gLayout : [Getting Started](https://docs.google.com/document/d/e/2PACX-1vT1jADYn6HAjlp1b3KB7T0nAkxzmT5GXo7NzFjxZ47M9s9H3oyHdoU39wxUscF8DtTNeQ3Egeo_1e1s/pub)

    - [IIC-OSIC Docker Image setup](../IIC-OSIC-TOOLS/README.md)
    - [gLayout Specific Setup](./files/gLayout_Install.md)

- gLayout: [Contribution Guidelines](https://docs.google.com/document/d/e/2PACX-1vQ9F87BS4lC2H-BhqVhrEeN6cjHAp3Y6hl-7hd66XaX-45H-ELWVnJ2_sHwtAND5Kp36UI816LhIj6x/pub)
    - [Fork the gLayout Repo]() 
    - [Contribute]()
    - [Create Merge Request]()

# Glayout
### A PDK-agnostic layout automation framework for analog circuit design. 
Glayout is a powerful layout automation tool that generates DRC-clean circuit layouts for any technology implementing the Glayout framework. It is implemented as an easy-to-install Python package with all dependencies available on PyPI.

Key features:
- PDK-agnostic layout generation
    - Generic layer mapping
    - Technology-independent design rules
    - Support for multiple PDKs (sky130, gf180)
    - DRC-clean layout generation
- Basic Cell Generators
    - Via stack generation
    - Transistor generation (NMOS/PMOS)
    - Guard ring generation
    - And more...
- Natural language processing for circuit design
    - Convert natural language descriptions to layouts
    - Support for standard components
    - Custom component definitions
- Integration with Klayout for visualization and verification

## Citation

If you use Glayout in your research, please cite our papers:

```bibtex
@article{hammoud2024human,
  title={Human Language to Analog Layout Using Glayout Layout Automation Framework},
  author={Hammoud, A. and Goyal, C. and Pathen, S. and Dai, A. and Li, A. and Kielian, G. and Saligane, M.},
  journal={Accepted at MLCAD},
  year={2024}
}

@article{hammoud2024reinforcement,
  title={Reinforcement Learning-Enhanced Cloud-Based Open Source Analog Circuit Generator for Standard and Cryogenic Temperatures in 130-nm and 180-nm OpenPDKs},
  author={Hammoud, A. and Li, A. and Tripathi, A. and Tian, W. and Khandeparkar, H. and Wans, R. and Kielian, G. and Murmann, B. and Sylvester, D. and Saligane, M.},
  journal={Accepted at ICCAD},
  year={2024}
}
```
