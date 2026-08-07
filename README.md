# Environment Setup

This project was built on top of the excellent **Bioimage and Data Analysis Scripts** repository developed by **Fernanda Fossati (@fefossa)**.

Before running any notebook or analysis contained in this repository, **please complete the installation steps described in the original repository README**, including:

- cloning the base repository;
- creating your analysis repository (if applicable);
- adding the repository as a submodule (if following the original workflow);
- creating the Conda environment.

The original README contains detailed instructions for setting up the base environment and should be considered the first installation step. :contentReference[oaicite:0]{index=0}

---

## Additional packages

After creating the base environment following the original instructions, install the additional packages required for this project.

If using **Conda**, update the environment with:

```bash
conda env update --file environment.yml --prune
```

Alternatively, if using **pip**, install the extra dependencies with:

```bash
pip install -r requirements.txt
```

These files (`environment.yml` and `requirements.txt`) contain only the additional packages required for the analyses in this repository.

---

## Summary

1. Follow the setup instructions in the original repository README.
2. Create and activate the base Conda environment.
3. Install the additional dependencies from this repository.
4. Run the notebooks in this project.
