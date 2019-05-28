# CRISPR-Chip Jupyter Notebook
---
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BauerLab/crispr-chip-notebook/master?filepath=TUSCAN_For_CRISPRChip.ipynb)
This Jupyter Notebook is designed to compare two sequences and identify CRISPR targets unique to each, which are then used to accurately and efficiently distinguish between the samples. The notebook utilises TUSCAN to identify highly active CRISPR sites in each sequence and uses the Hamming Distance metric to select targets which are significantly different from all targets from the opposing sequence. 
---
# Usage
1. Open the notebook by running this command in the directory
    ```sh
    $ jupyter notebook
    ```
2. Select the notebook file to open it
3. Paste in the two desired sequences for analysis (as strings)
4. Run the notebook
  

