markdown<div align="center">
<img width="1560" height="640" alt="Pandas" src="https://github.com/user-attachments/assets/98e81d5a-5f34-440a-82e8-aacdd68db8b9" />

# pandas-journey

[![Python](https://img.shields.io/badge/Python-3.13+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.3.0+-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-2.3.0+-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10.3+-11557c?style=flat-square&logo=python&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.13.2+-3776AB?style=flat-square&logo=python&logoColor=white)](https://seaborn.pydata.org/)

[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Ruff](https://img.shields.io/badge/Ruff-Linter-D7FF64?style=flat-square&logo=ruff&logoColor=black)](https://github.com/astral-sh/ruff)
[![uv](https://img.shields.io/badge/uv-Package%20Manager-DE5FE9?style=flat-square&logo=python&logoColor=white)](https://github.com/astral-sh/uv)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)](https://github.com/Tams3d/pandas-journey)
[![Code style: Ruff](https://img.shields.io/badge/code%20style-ruff-000000.svg?style=flat-square)](https://github.com/astral-sh/ruff)
[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red?style=flat-square)](https://github.com/Tams3d/pandas-journey)

*A hands-on learning repository for data analysis with Pandas, NumPy, Matplotlib, and Seaborn*

</div>

## Overview

This repository is basically a collection of everything I've learnt while working with Pandas. I started from the basics like Series and DataFrames, and gradually moved towards more complex stuff like grouping, merging, and multi-index operations. Each notebook here represents a specific topic that I've explored in detail.

The whole idea was to learn by doing - working with actual datasets, experimenting with different methods, and visualising the results using Matplotlib and Seaborn. I've also used Ruff to keep the code clean and uv for managing dependencies efficiently.

## Getting Started

### Installation

First, clone this repository:

```bash
git clone https://github.com/Tams3d/pandas-journey.git
cd pandas-journey
```

It's better to create a virtual environment (highly recommended):

```bash
python -m venv .venv

# For Windows
.venv\Scripts\activate

# For macOS/Linux
source .venv/bin/activate
```

Now install all the required packages:

```bash
uv sync
```

This will automatically install pandas, matplotlib, seaborn, ruff, and all other dependencies mentioned in the `pyproject.toml` file.

## Topics Covered

### Fundamentals

- **Series Operations**: Creation, indexing, and basic operations
- **DataFrame Basics**: Structure, creation, and fundamental operations
- **Data Access**: Techniques for retrieving and filtering data

### Intermediate Techniques

- **Data Modification**: Updating, adding, and removing data
- **Built-in Methods**: Leveraging pandas' extensive method library
- **String Operations**: Text processing and manipulation

### Advanced Topics

- **GroupBy Operations**: Split-apply-combine workflows and aggregations
- **Merging DataFrames**: Joins, concatenation, and combining datasets
- **MultiIndex**: Working with hierarchical indices
- **Time Series**: Datetime handling and temporal analysis

### Visualization

- Creating plots with Matplotlib
- Statistical graphics with Seaborn
- Customizing visualizations for data presentation

You can go through the notebooks in order (recommended for beginners) or jump to any specific topic you want to learn about. Each notebook has proper explanations along with code examples and their outputs.

## About Me

I'm 18 and deeply interested in AI, machine learning, and data science. I've realised that the best way for me to learn is by actually building things and experimenting with real problems rather than just reading theory.

Apart from programming, I enjoy creative work like photo and video editing, and 3D design using Blender. I often try to combine these creative interests with technical skills to build useful tools and workflows.

Right now, I'm focusing on deep learning and generative AI. My long-term goal is to contribute to research work and open-source projects in the AI domain. This repository is part of building that foundation - understanding core tools like Pandas is essential for any serious work in data science or ML.

## Useful Resources

- Pandas Cheat Sheet – pandas.pydata.org (Official)  
[Download PDF](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)  
A handy reference guide summarizing the most common Pandas operations.

- Python for Data Analysis – Wes McKinney (English)  
[Read online](https://wesmckinney.com/book/)  
A comprehensive guide to using Pandas, written by its creator, great for both beginners and experienced users.

**Video Tutorials**  
[Corey Schafer's Pandas Playlist](https://www.youtube.com/watch?v=ZyhVh-qRZPA&list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS) – Really well-explained tutorials (slightly older but still relevant)  
[CampusX Tutorial in Hindi](https://www.youtube.com/watch?v=zCDVUyq8lkw) – Great for Hindi speakers, very beginner-friendly

- Pandas Tutorial – CampusX (Hindi)  
[Watch on YouTube](https://www.youtube.com/watch?v=zCDVUyq8lkw)  
Beginner-friendly, well-paced Pandas tutorial in Hindi, great for getting started with data analysis.

## Licence

This project is released under the MIT Licence. Check the [LICENSE](https://github.com/Tams3d/pandas-journey/blob/master/LICENSE) file for more details.

**Note**: This is primarily a learning repository. The code here reflects my learning process, so it might not always follow production-level best practices. The focus is on understanding concepts through hands-on experimentation.
