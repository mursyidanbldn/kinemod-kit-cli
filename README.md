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

UASB-FILTRATION-RBC REACTOR KINETIC MODELING KIT

An Analytical Engine for POME Treatment Modeling

</div>

Author's Note: This platform serves as the core analytical engine for my thesis research, focusing on the data analysis and kinetic modeling of a combined reactor system for treating Palm Oil Mill Effluent (POME).

KINEMOD-KIT is a terminal-based toolkit designed for engineers and researchers, providing a powerful suite of tools to model, validate, and analyze data from a three-stage POME treatment reactor (UASB-Filtration-RBC).

Why KINEMOD-KIT?

Wastewater treatment process data is often complex and noisy. Manual analysis using spreadsheets is time-consuming and prone to errors. KINEMOD-KIT was created to solve this by providing a structured and automated workflow, right from your terminal.

Fast & Efficient: A GUI-free, command-line interface (CLI) that allows for rapid analysis and iteration.

Reproducible: Every analysis follows the same logic, ensuring consistent and scientifically defensible results.

Full Control: Gives the user granular control over every aspect of the modeling and analysis process.

► Engineer's Log: Stardate 2025.1

Welcome to the engine room, fellow engineer. What you're looking at isn't just a Python script. It's a unified analytical workstation, forged for a singular purpose: to transmute the chaotic data streams of Palm Oil Mill Effluent (POME) treatment into actionable kinetic insight.

Forget cumbersome spreadsheets. Here, we operate via a sophisticated command-line interface (CLI), engineered for maximum efficiency and total control. Consider this your cockpit for modeling, analyzing, and visualizing the performance of a complex, three-stage reactor system.

Prime Directive: To ingest raw field data and render it into solid model parameters, reliable predictions, and a deep, fundamental understanding of what's actually happening inside your reactors.

► Core Systems & Operational Capabilities

This toolkit is segmented into several key operational modules, each precision-engineered for a specific task.

🧠 Segmented Modeling Brain: Each treatment unit—UASB, Adsorption Filter, and RBC—is encapsulated as a distinct class. This isn't just code; it's a digital twin of each physical component, ensuring modularity and simplified debugging.

⚙️ High-Precision Parameter Calibrator: Leverages non-linear optimization algorithms (differential_evolution & curve_fit) to autonomously extract kinetic parameters from your dataset. No more manual guesswork.

📊 Internal Validation Subroutines: Ships with a suite of statistical validation protocols (R², RMSE, ANOVA) to evaluate model fidelity. The machine checks its own work.

🔬 Dual Sensitivity Analysis Module: Need to know which parameters are most volatile? Deploy Global Sensitivity Analysis (GSA) via Sobol methods or run Monte Carlo simulations to identify which variables exert the most influence on the final output.

🕹️ Interactive Terminal Interface: All functionalities are accessed through an intuitive, text-based menu system powered by rich. It's fast, responsive, and free of GUI-induced latency.

📈 Engineering-Grade Data Visualization: Generates high-quality plots (Time-Series, Parity, Heatmaps) using Seaborn and Matplotlib for clear, professional presentation of results.

► Ignition Sequence: How to Fire Up the Engine

Ready to engage? Follow the protocol below to bring the system online in your local workstation.

1. Acquire the Blueprints (Clone the Repository):
Open your terminal and execute the following command.

git clone [https://github.com/mursyidanbldn/kinemod-kit-cli.git](https://github.com/mursyidanbldn/kinemod-kit-cli.git)
cd kinemod-kit-cli



2. Install Required Components (Install Dependencies):
Ensure you have Python 3.8+ operational. Then, install all necessary sub-components from the requirements.txt manifest.

pip install -r requirements.txt



3. Engage the Main Reactor (Run the Script):
Confirm your data file (Model_Data.csv) is co-located in the directory. Then, ignite the main process.

python run_analysis.py



You will be greeted by the animated banner, and the main menu will materialize. Welcome to the cockpit.

► User Interface Schematics (Menu Navigation)

Once the system is live, you will interface via the main menu. This is your command guide:

[1] Data Exploration & Configuration: View summary statistics, visualize variable correlations in a heatmap, and inspect the current model configuration. Consider this your pre-flight diagnostic panel.

[2] Parameter Estimation: This is where the magic happens. Run a new estimation, load existing parameters from a .json file, or save your current calibration session.

[3] Model Performance & Visualization: Once parameters are calibrated, this menu allows you to generate performance tables (R², etc.), time-series plots, and parity plots to assess model accuracy.

[4] Sensitivity Analysis: Go deeper and stress-test your model. Run GSA or Monte Carlo analyses to understand parameter dynamics.

[5] File & Data Management: Sanitize your working directory by deleting legacy result files (.json, .csv).

[6] Exit: A graceful shutdown of the simulation core.

Developed and engineered by Rizky Mursyidan Baldan (2025). Godspeed, and try not to break anything.
