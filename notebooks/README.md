# SICSS 2026 Notebooks on Data Collection/Annotation & Inferences with LLMs in Social Sciences

This folder contains the Python and R notebooks specifically designed for [SICSS 2026](https://sicss.io). You can choose either the Python or R notebooks based on your preference. The notebooks are organized in a way to guide you through the process of using large language models (LLMs) for data collection/annotation and inferential regression analysis in social sciences and humanities.

*Note*: For users of RStudio, use the `.qmd` files instead of the `.ipynb` files. The `.qmd` files are Quarto notebooks that can be run in RStudio, while the `.ipynb` files are Jupyter notebooks that can be run in VSCode, Jupyter Notebook or JupyterLab.

Use the notebooks in this order:
1. `1sicss_llm_data_collection_py.ipynb` or `1sicss_llm_data_collection_r.ipynb/qmd` - Notebook for familiarizing yourself with data collection/annotation using LLM APIs. **Internet access is required** for connecting to cloud LLM services.
- *Recommended setup*: Run these notebooks directly on Google Colab to reduce setup time and ensure smooth access to cloud LLM services. You can also run them on your local machine if you are comfortable setting up the environment yourself.

2. `2sane_llm_data_collection_py.ipynb` or `2sane_llm_data_collection_r.ipynb/qmd` - Notebooks for data collection/annotation using locally deployed open-weights LLMs. These notebooks do not require connection to any cloud services and can be run on your local machine or inside SANE. 
- *Recommended setup*: Run these notebooks inside SANE with sensitive data like LISS and FIRMBACKBONE to get a feeling of how to use LLMs for secure data collection/annotation without relying on cloud services. This is especially useful for when you develop your own projects later. 

3. `3llm_inferential_regression_py.ipynb` or `3llm_inferential_regression_r.ipynb` - Notebook for learning how to use LLMs for inferential regression analysis. 
- *Recommended setup*: The Python notebook can be run on Google Colab, in SANE or your local machine, while the R notebook can be run in SANE or yourlocal machine.