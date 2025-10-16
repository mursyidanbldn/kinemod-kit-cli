<div align="center">

<img src="assets/banner_demo.gif" alt="KINEMOD-KIT Animated Banner">

KINEMOD-KIT: Command-Line Interface

An integrated kinetic analysis workstation for Palm Oil Mill Effluent (POME) treatment data.

</div>

<p align="center">
<img alt="Python Version" src="https://www.google.com/search?q=https://img.shields.io/badge/python-3.8%252B-blue%3Fstyle%3Dfor-the-badge%26logo%3Dpython">
<img alt="License" src="https://www.google.com/search?q=https://img.shields.io/badge/license-MIT-green%3Fstyle%3Dfor-the-badge">
<img alt="Status" src="https://www.google.com/search?q=https://img.shields.io/badge/status-stable-brightgreen%3Fstyle%3Dfor-the-badge">
</p>

Author's Note: This platform serves as the core analytical engine for my thesis research, focusing on the data analysis and kinetic modeling of a combined reactor system for treating Palm Oil Mill Effluent (POME).

KINEMOD-KIT is a terminal-based toolkit designed for engineers and researchers, providing a powerful suite of tools to model, validate, and analyze data from a three-stage POME treatment reactor (UASB-Filtration-RBC).

Why KINEMOD-KIT?

Wastewater treatment process data is often complex and noisy. Manual analysis using spreadsheets is time-consuming and prone to errors. KINEMOD-KIT was created to solve this by providing a structured and automated workflow, right from your terminal.

Fast & Efficient: A GUI-free, command-line interface (CLI) that allows for rapid analysis and iteration.

Reproducible: Every analysis follows the same logic, ensuring consistent and scientifically defensible results.

Full Control: Gives the user granular control over every aspect of the modeling and analysis process.

✨ Key Features

🔬 Segmented Modeling: Each reactor stage (UASB, Filter, RBC) is modeled as a separate object for maximum modularity.

⚙️ Automated Parameter Calibration: Uses non-linear optimization algorithms to find the best-fit kinetic parameters from your data.

📊 Complete Statistical Validation: Automatically calculates R², RMSE, and ANOVA to evaluate model fit.

🚀 Dual Sensitivity Analysis: Equipped with Sobol (GSA) and Monte Carlo simulation methods to identify the most influential parameters.

🖥️ Modern Terminal Interface: Powered by rich for an interactive and visually appealing user experience.

🎨 Professional Visualization: Generates publication-quality plots and heatmaps using Seaborn.

🚀 Quick Start

1. Installation

Ensure you have Python 3.8 or newer installed.

# 1. Clone this repository
git clone [https://github.com/mursyidanbldn/kinemod-kit-cli.git](https://github.com/mursyidanbldn/kinemod-kit-cli.git)

# 2. Navigate into the project directory
cd kinemod-kit-cli

# 3. Install all required libraries
pip install -r requirements.txt


2. Usage

Make sure your data file (Model_Data.csv) is located inside the project folder. Then, run the application:

python run_analysis.py


The application will load the data and present you with an interactive main menu to begin your work.

Design Philosophy

Why a Command-Line Interface (CLI)?

In engineering and research, speed, scriptability, and reproducibility are key. A CLI excels in all these areas. This interface was designed for power users who require full control and may want to integrate this tool into a larger analytical workflow without being hindered by a graphical interface.

🤝 Contributing

Contributions are always welcome! If you have ideas for new features or find a bug, please open an issue or submit a pull request.

📄 License

This project is licensed under the MIT License. See the LICENSE file for more details.
