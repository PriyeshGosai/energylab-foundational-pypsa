# EnergyLab Foundational PyPSA Course

This course is designed to give learners the foundational skills needed to work with Python and build energy system models using PyPSA (Python for Power System Analysis). It covers Python programming basics through to constructing real-world multi-node PyPSA models.

## About

This course provides a structured, hands-on path through the core skills required for energy system modelling. Starting from Python fundamentals and progressing through data tools and geospatial analysis, learners build up to developing stochastic and multi-node PyPSA models using real-world datasets. The materials are designed for engineers, researchers, and students entering the field of energy system modelling.

<div style="display: flex; align-items: center; justify-content: space-between; gap: 30px;">
  <div>
    <h3 style="margin-top: 0;">Instructor</h3>
    <p style="margin: 5px 0; font-size: 20px;"><strong>Priyesh Gosai</strong></p>
    <hr style="margin: 12px 0; border: none; border-top: 1px solid #ccc;">
    <p style="margin: 6px 0; font-size: 13px;"><a href="mailto:priyesh@innovateimpact.com">priyesh@innovateimpact.com</a></p>
    <p style="margin: 6px 0; font-size: 13px;"><a href="https://www.linkedin.com/in/gosaip/">LinkedIn</a> | <a href="https://github.com/PriyeshGosai">GitHub</a></p>
  </div>
  <div style="display: flex; align-items: center; gap: 20px;">
    <img src="img/ccg_logo.png" height="60" alt="CCG">
    <img src="img/energy-lab-logo.png" height="60" alt="Energy Lab">
    <img src="img/I4I%20Logo%202%20narrow%20(PNG).png" height="60" alt="I4I">
  </div>
</div>


## Quick Start

### Option 1: View Online

Visit the course website at: https://priyeshgosai.github.io/energylab-foundational-pypsa/

### Option 2: Google Colab

Run the notebooks directly in your browser — no installation required:
- Click the rocket icon at the top of any lesson page and select "Colab"

### Option 3: Local Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/PriyeshGosai/energylab-foundational-pypsa.git
   cd energylab-foundational-pypsa
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Lab:**
   ```bash
   jupyter lab
   ```

## Building the Book

If you'd like to build the Jupyter Book locally:

1. **Install jupyter-book:**
   ```bash
   pip install "jupyter-book<2"
   ```

2. **Build the book:**
   ```bash
   jupyter-book clean . --all
   jupyter-book build .
   ```

3. **View the book:**
   Open `_build/html/index.html` in your browser

## Course Contents

- **Lesson 1:** Python Introduction — core programming concepts and syntax
- **Lesson 2:** Introduction to Pandas — data manipulation and analysis
- **Lesson 3:** Introduction to GeoPandas — geospatial data for energy systems
- **Lesson 4:** GRDC Data Reader — working with real-world hydrological datasets
- **Lesson 5:** Zambia Stochastic Model — building a stochastic energy model
- **Lesson 6:** Japan PyPSA Model — building a multi-node PyPSA network model

## Case Study Disclaimer

**Disclaimer**

The models developed in this repository are intended exclusively for educational purposes. The models have been intentionally simplified and should not be construed as an accurate or comprehensive representation of the contemporary energy system being referenced. Consequently, these models are not suitable for application in substantive studies, policy analysis, or operational assessments.

**Data Sources**

The development of these models incorporates data and information from the following sources:

* DeSantis, D., James, B.D., Houchins, C., Saur, G. and Lyubovsky, M. (2021) 'Cost of long-distance energy transmission by different carriers', *IScience*, 24(12).

* Electric Power Research Institute (EPRI) (2024) 'Supply-Side Cost and Performance Data for Eskom Integrated Resource Planning: 2023–2024 Update', Technical Report 3002031032. Palo Alto, California: EPRI.

* Eskom Transmission Division (2020) *Transmission Development Plan 2020–2029*. Johannesburg, South Africa: Eskom Holdings SOC.

* Merven, B. (2024) 'ESRG Hourly Demand Model v2025 by Province', September. doi: 10.25375/uct.26942134.v5


## Resources

- **PyPSA Documentation:** https://pypsa.org
- **PyPSA-Earth:** https://github.com/pypsa-meets-earth
- **Course Repository:** https://github.com/PriyeshGosai/energylab-foundational-pypsa

## License

This course material is open source and available for educational purposes. See [LICENSE](LICENSE) for details.

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/).
