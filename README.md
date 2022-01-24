<!--
 * @Author: BDFD
 * @Date: 2022-01-21 13:17:17
 * @LastEditTime: 2022-01-24 14:07:12
 * @LastEditors: BDFD
 * @Description:
 * @FilePath: \00Seaborn_Common_Visualization\README.md
-->

# Welcome to Matplotlib & Seaborn Visualization World

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

- [ ] **1. Distplot (直方图)**
- [ ] **2. Joinplot (联合分布图)**
- [ ] **3. Pairplot (矩阵图)**
- [ ] **4. Barplot (条形图)**
- [ ] **5. Boxplot (箱型图)**
- [ ] **6. LM plot (LM 图)**
