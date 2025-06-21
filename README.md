# CSCA5642-final-project
CSCA 5642 Introduction to Deep Learning Final Project

## Overview

This repository contains the final project for CSCA 5642: Introduction to Deep Learning. The project demonstrates concepts and applications of deep learning using Python and Jupyter notebooks.

## Project Structure

```
.
├── final-project.ipynb      # Main Jupyter notebook with code and analysis
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation
├── final/                   # Python virtual environment (do not edit directly)
```

## Getting Started

### 1. Clone the Repository

```sh
git https://github.com/ribasdev/CSCA5642-final-project.git
cd CSCA5642-final-project
```

### 2. Set Up the Environment

It is recommended to use the provided virtual environment in the `final/` directory:

- **Activate on Windows:**
  ```sh
  final\Scripts\activate
  ```
- **Activate on macOS/Linux:**
  ```sh
  source final/bin/activate
  ```

Or create a new environment:

```sh
python -m venv venv
venv\Scripts\activate  # On Windows
pip install -r requirements.txt
```

### 3. Install Dependencies

```sh
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```sh
jupyter notebook final-project.ipynb
```

## Notes

- All main code and analysis are in `final-project.ipynb`.
- Do not edit files inside the `final/` directory directly.
