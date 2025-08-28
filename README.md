# Pandas Study Material

This guide will walk you through installing the Pandas library and setting up Jupyter Notebook for an interactive data analysis environment.

## 1. Installing Pandas

Follow these steps to install Pandas on your Windows machine:

1.  **Open your Command Line Interface:**
    *   Search for "Command Prompt" or "PowerShell" in your Windows search bar and open it.

2.  **Install Pandas using pip:**
    *   In the Command Prompt/PowerShell window, type the following command and press Enter:
        ```bash
        pip install pandas
        ```

3.  **Verify the installation:**
    *   To confirm Pandas was installed correctly, enter the Python interpreter by typing:
        ```bash
        python
        ```
    *   Once you see the `>>>` prompt, type the following and press Enter after each line:
        ```python
        import pandas as pd
        print(pd.__version__)
        ```
    *   You should see the installed Pandas version printed. If you do, congratulations!

## 2. Using Jupyter Notebook

Jupyter Notebook provides an excellent interactive environment for working with Pandas.

1.  **Install Jupyter Notebook:**
    *   Open your Command Prompt/PowerShell (if not already open).
    *   Type the following command and press Enter:
        ```bash
        pip install notebook
        ```

2.  **Launch Jupyter Notebook:**
    *   Once installed, you can launch Jupyter Notebook from your Command Prompt/PowerShell by typing:
        ```bash
        jupyter notebook
        ```
    *   This will open a new tab in your web browser with the Jupyter interface.

---

Happy learning with Pandas and Jupyter!
