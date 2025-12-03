# pytutor2

A Jupyter notebook project for Python tutorials.

## Prerequisites

- Python 3.13 or higher

## Setup

### 1. Create a Virtual Environment

```bash
python3 -m venv venv
```

### 2. Activate the Virtual Environment

**On macOS/Linux:**
```bash
source venv/bin/activate
```

**On Windows:**
```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

## Project Structure

```
pytutor2/
├── .gitignore
├── README.md
├── requirements.txt
└── notebooks/
    ├── sample_notebook.ipynb
    └── python_data_science_tutorial.ipynb
```

## Notebooks

### Sample Notebook
A simple introductory notebook demonstrating basic Jupyter notebook structure.

### Python Data Science Tutorial
A beginner-friendly tutorial notebook introducing basic Python data science techniques including:
- NumPy arrays and operations
- Pandas DataFrames for data manipulation
- Data visualization with Matplotlib
- Basic statistical analysis

The tutorial includes 10 hands-on exercises with fill-in-the-blank sections and collapsible answer solutions.

## Deactivate Virtual Environment

When you're done working, deactivate the virtual environment:

```bash
deactivate
```
