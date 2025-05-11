# PLL (Phase-Locked Loop) Project

This project encompasses the design, simulation, and documentation of a Phase-Locked Loop (PLL) circuit. It includes PCB layouts created with KiCad and circuit simulations performed with LTSpice.

## Project Structure

The repository is organized as follows:

*   **`PCB/`**: Contains all KiCad project files related to the Printed Circuit Board (PCB) design of the PLL.
    *   **`PCB/prototype/`**: KiCad project files for a prototype version of the PLL PCB. ([`sahs.kicad_pro`](PCB/prototype/sahs.kicad_pro))
    *   **`PCB/sahs (2)/`**: Another iteration or version of the PLL PCB design. ([`sahs.kicad_pro`](PCB/sahs%20(2)/sahs.kicad_pro))
    *   **`PCB/testing/`**: KiCad project files used for testing purposes. ([`sahs.kicad_pro`](PCB/testing/sahs.kicad_pro))
    *   **`PCB/ugly_ahh_plaketa/`**: KiCad project files for an experimental or distinct version of the PCB. ([`ugly_ahh.kicad_pro`](PCB/ugly_ahh_plaketa/ugly_ahh.kicad_pro))
    *   **`PCB/simulator_kicad/`**: KiCad projects tailored for circuit simulation, potentially integrating SPICE models.
        *   `pll_sim/`: PLL simulation setup in KiCad ([`pll_sim.kicad_pro`](PCB/simulator_kicad/pll_sim/pll_sim.kicad_pro)).
        *   `basic_models/`: Contains SPICE models like [`OPA171.txt`](PCB/simulator_kicad/basic_models/OpAmps/OPA171.txt).
    *   **`PCB/Footprints/`**: Custom KiCad footprint libraries for components used in the designs (e.g., `74HC00/`, `LM324/`).
    *   **`PCB/Symbols/`**: Custom KiCad symbol libraries.
    *   Various KiCad project files (e.g., [`sahs.kicad_pro`](PCB/sahs.kicad_pro)).

*   **`simulations/`**: Contains LTSpice simulation files and related documentation.
    *   **`simulations/final.asc`**: An LTSpice simulation schematic.
    *   **`simulations/pll.asc`**: The primary LTSpice simulation schematic for the PLL.
    *   **`simulations/small_signal.asc`**: An LTSpice schematic for small-signal analysis.
    *   **`simulations/simulation_log/`**: LaTeX source files for the simulation report ([`report.tex`](simulations/simulation_log/report.tex), [`main.tex`](simulations/simulation_log/main.tex)).

*   **`report.pdf`**: A compiled PDF document, likely the simulation report generated from the LaTeX sources in `simulations/simulation_log/`.

## Software & Tools

*   **PCB Design**: KiCad EDA Suite
*   **Circuit Simulation**: LTSpice
*   **Documentation**: LaTeX

## Key Files

*   **Main PCB Project (Example)**: [`PCB/sahs.kicad_pro`](PCB/sahs.kicad_pro) (and other `.kicad_pro` files in respective subdirectories)
*   **Main PLL Simulation**: [`simulations/pll.asc`](simulations/pll.asc)
*   **Simulation Report (PDF)**: [`report.pdf`](report.pdf)
*   **Simulation Report (LaTeX Source)**: [`simulations/simulation_log/report.tex`](simulations/simulation_log/report.tex)

To explore the PCB designs, open the `.kicad_pro` files within the `PCB/` subdirectories using KiCad.
To run circuit simulations, open the `.asc` files in the `simulations/` directory using LTSpice.