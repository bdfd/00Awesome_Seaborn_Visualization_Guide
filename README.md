<!--
 * @Author: BDFD
 * @Date: 2022-01-21 13:17:17
 * @LastEditTime: 2022-01-24 15:53:50
 * @LastEditors: BDFD
 * @Description:
 * @FilePath: \00Awesome_Seaborn_Visualization_Guide\README.md
-->

# Welcome to Seaborn(Matplotlib) Visualization World

Gather most common viz graph might see on your daily works with set up template to increase work efficiency。

## Important Characteristics for Make Effective Visualization:

- Convey correct and necessary information without distorting facts.
- Simple design make user easy to understand.
- Support the message aesthetically rather than obscure it.
- Dont overload information .

## Basic Setup Tempalte:

```
import numpy as np
import pandas as pd
import matplotlib as mpl
import matplotlib.pyplot as plt
import seaborn as sns
import warnings; warnings.filterwarnings(action='once')

large = 22; med = 16; small = 12
params = {'axes.titlesize': large,
          'legend.fontsize': med,
          'figure.figsize': (16, 10),
          'axes.labelsize': med,
          'axes.titlesize': med,
          'xtick.labelsize': med,
          'ytick.labelsize': med,
          'figure.titlesize': large}
plt.rcParams.update(params)
plt.style.use('seaborn-whitegrid')
sns.set_style("white")
%matplotlib inline

# Version
print(mpl.__version__)  #> 3.2.2
print(sns.__version__)  #> 0.11.2
```

notice: version show on Colab(Google Jupyternotebook on Date: 2022/01/21)

## Viz Graph Table of Contents

### Section 1. Relational Plot

- [ ] **1. Relplot**
- [ ] **2. Scatterplot**
- [ ] **3. Lineplot**

### Section 2. Distribution Plot

- [ ] **1. Displot**
- [ ] **2. Histplot**
- [ ] **3. Kdeplot**
- [ ] **4. Ecdfplot**
- [ ] **5. Rugplot**
- [ ] **6. Distplot**

### Section 3. Categorical Plot

- [ ] **1. Catplot**
- [ ] **2. Stripplot**
- [ ] **3. Swarmplot**
- [ ] **4. Boxplot**
- [ ] **5. Violinplot**
- [ ] **6. Boxenplot**
- [ ] **7. Pointplot**
- [ ] **8. Barplot**
- [ ] **9. Countplot**

### Section 4. Regression Plot & Matrix Plots

- [ ] **1. Lmplot**
- [ ] **2. Regplot**
- [ ] **3. Residplot**
- [ ] **4. Heatmap**
- [ ] **5. Clustermap**

### Section 5. Facet Grids, Pair Grids & Joint Grids

- [ ] **1. FacetGrid**
- [ ] **2. Pairplot**
- [ ] **3. Pairgrid**
- [ ] **4. Jointplot**
- [ ] **5. Jointgrid**
