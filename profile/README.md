# Georgia State University - Data Science Projects - Fall 2025

[![gsu-ds](https://img.shields.io/badge/GSU-DS-blue.svg?style=flat-square)](https://catalogs.gsu.edu/preview_program.php?catoid=42&poid=12461&utm_source=program-list&utm_campaign=catalog)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/joshuapina)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](#license)

## About the Organization

Howdy, my name is **Josh**. I created the `Georgia State University - Data Science (GSU-DS) Organization` to organize our Senior Projects.

**Why this organization exists:**
* **Fairness & Attribution:** This org allows all contributors to highlight these projects on their own portfolios without needing to fork them.
* **Future Academic Utility:** The name `GSU-DS` is intentionally designed so that a GSU Professor may take over this organization in the future.
* **The End Goal:** To hand off this org to university faculty to serve as a hub to organize student projects and display student work centrally.

## Table of Contents

- [Project Index](#project-index)
- [Getting Started](#getting-started)
- [Usage & Workflow](#usage-workflow)
- [Documentation Standards](#documentation-standards)
- [Maintainers](#maintainers)
- [License](#license)

## Project Index

> This organization serves as the central hub for the following Summer/Fall 2025 Senior Projects.<br> Please navigate to the individual repositories for specific documentation and codebases.<br> All contributors are listed alphabetically.

| Project Name (Repo) | Course | Semester | Description | Contributor(s) | Tech Stack |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Campus Burglary Risk Prediction](https://github.com/gsu-ds/campus-burglary-risk-prediction)** | Data Science Capstone | Fall 2025 | *This project focuses on forecasting larceny risks across Atlanta’s 25 NPUs to improve campus safety.* | Gunn Madan, Harini Mohan, Joshua Piña, Yuntian 'Robin' Wu | PyTorch, LSTM, GeoPandas, Streamlit |
| **[Ticket-Heroes](https://github.com/gsu-ds/ticket-heroes)** | Fundamentals of Data Science | Fall 2025 | *An application aimed at tracking ticket resale prices and predicting future fluctuation through feature-based regression and time series analysis.* | Harini Mohan, Joshua Piña | Scikit-Learn, XGBoost, KNN, MongoDB |
| **[Mining Patterns from Large-Scale Flight Data](https://github.com/gsu-ds/fly-like-a-bird)** | Data Mining | Fall 2025 | *This project aims to extract knowledge from large-scale flight records to predict arrival delays.* | Joshua Piña, Yuntian 'Robin' Wu | Scikit-learn, Random Forest, Plotly, Streamlit |
| **[Living Library](https://github.com/gsu-ds/living_library)** | Database Systems | Fall 2025 | *A resource-stacked database charged with assisting the training of future DS students.* | Joshua Piña | Hugging Face, FastAPI Supabase (PostgreSQL) |
| **[Everything is a Graph](https://github.com/gsu-ds/graph-cut-imaging)** | Design & Analysis: Algorithms  | Fall 2025 | *This project uses Edmonds-Karp to create an image segmentation tool.* | Joshua Piña | NumPy, OpenCV, MatPlotLib |
| **[ML-HNSCC Study](https://github.com/JoshuaPina/ML-HNSCC-Study)** | Machine Learning | Summer 2025 | *Exploratory ML to improve head and neck cancer treatment plans, with a focus on maximizing KBRT.* | Abdul-Malik Mohamed, Joshua Piña, Somiya Rauf | PyTorch, XGBoost, MATLAB Flask |

> **Note:** Click the project names above to view their respective repositories.

## Getting Started

This section guides new developers or team members on how to set up their environment to contribute to GSU-DS projects.

### Prerequisites
Most projects in this organization utilize a standard Data Science stack. Ensure you have the following installed:
* [Git](https://git-scm.com/)
* [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) (Recommended for environment management)
* [VS Code](https://code.visualstudio.com/) or [JupyterLab](https://jupyter.org/)

### Installation & Setup
1.  **Clone the Repository:**
    Navigate to the specific project you wish to work on and clone it:
    ```bash
    git clone [https://github.com/GSU-DS/](https://github.com/GSU-DS/)[repository-name].git
    cd [repository-name]
    ```

2.  **Create Virtual Environment:**
    We recommend creating a fresh environment for each project to avoid dependency conflicts.
    ```bash
    conda create -n gsu-ds-project python=3.9
    conda activate gsu-ds-project
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage & Workflow

To ensure quality across all 5 repositories, we follow this general workflow:

1.  **Branching:** Do not push directly to `main`. Create a feature branch:
    `git checkout -b feature/analysis-name`
2.  **Commits:** Write clear, descriptive commit messages.
3.  **Pull Requests:** Submit a PR for review before merging into the main branch.

## Maintainers

* [@joshuapina](https://github.com/joshuapina) - Lead Maintainer / Program Manager

## Contributing

We welcome contributions from GSU students and faculty.
1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
