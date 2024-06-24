﻿# Anuket Documentation

Welcome to the Anuket Project Documentation repository. This repository contains the source files for https://docs.anuket.io/

## Installation

To get started with the Anuket documentation locally, clone this repository:

```bash
git clone https://github.com/anuket-project/Anuket-documentation.git
cd Anuket-documentation
```

## Install the required dependencies:

### Verify Python and Pip Installation

Ensure Python and pip are installed and accessible in your environment.

```bash
python --version
pip --version
```

### Install Sphinx

Install Sphinx using pip:

```bash
pip install sphinx
```

## Navigate to the Documentation Directory

Change to the directory containing your conf.py file and other source files.

```bash
cd docs
```

## Building the Documentation

To build the documentation locally, you can use the following commands. This example assumes you are using Sphinx:

```bash
python -m sphinx -b html . _build/html
```

## Open the Generated HTML

```bash
open _build/html/index.html  # macOS
xdg-open _build/html/index.html  # Linux
start _build/html/index.html  # Windows
```
