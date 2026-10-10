# Intro to Data Science

Companion repository containing **Jupyter Notebooks** for the course "Introduction to Data Science" at the Democritus University of Thrace, Department of Humanities (2026-27).

## Structure
```text
.
├── notebooks/
│   ├── 01_Colab_Intro.ipynb
│   ├── 02_Python_Lab.ipynb
└── README.md
```

## Notebooks
- **01_Colab_Intro.ipynb**: Introduction to Google Colab / Jupyter and basic Python programming concepts.
- **02_Python_Lab.ipynb**: Hands-on lab session for practicing Python programming skills.

## Running the Notebooks
You can run the notebooks either locally or using a cloud-based Jupyter environment.

### Local Setup
This repository uses the **uv** package manager.

1. Install `uv` if you haven't already:
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```
   
2. Install dependencies:
   ```bash
    uv sync
    ```
   
You can use any package manager of your choice, but make sure to install the required dependencies listed in `pyproject.toml`.

### Cloud-Based Setup Jupyter Environment
You can also run the notebooks in a cloud-based Jupyter environment such as Google Colab. Simply upload the notebooks to your environment and ensure you have the necessary dependencies installed.

## Educational Use
This repository is intended for educational purposes and is part of the curriculum for the "Introduction to Data Science" course at the Democritus University of Thrace, Department of Humanitites. The notebooks are designed to provide hands-on experience with Python programming, data science concepts and algorithms.

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
