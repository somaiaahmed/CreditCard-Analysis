# Credit Card Exploratory Data Analysis (EDA) README

## Overview
This project involves an exploratory data analysis (EDA) on a credit card dataset to understand the distribution of fraudulent and normal transactions. The dataset contains various features that help in identifying patterns and anomalies associated with fraudulent activities.


### Pre-requisites

1. **Python Environment**: Ensure you have a Python environment set up. You can use Anaconda, Miniconda, or a virtual environment.
2. **Libraries**: Install the necessary Python libraries using pip or conda.
   ```sh
   pip install pandas numpy scipy matplotlib seaborn plotly
   ```


## Steps
1. **Import the Necessary Libraries**
2. **Upload the Dataset**
3. **Initial Data Exploration**
4. **Data Visualization**
5. **Feature Selection**

### 1. Import the Necessary Libraries
```python
import pandas as pd
import numpy as np
import scipy.stats as stats
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go
from pylab import rcParams
```

### 2. Upload the Dataset

![Dataset](<Resources/dataset.png>)

### 3. Initial Data Exploration
- **Class Distribution**: Split the data based on the 'Class' column to differentiate between fraud and normal transactions.

![  !\[Transaction Amount Distribution\](image-2.png)
](<Resources/Transaction Amount Distribution.png>)

### 4. Data Visualization
#### Class Distribution

- **Bar Plot**
 

- **Pie Chart**

  
  ![!\[Class Distribution\](image.png)](<Resources/Class Distribution.png>)


#### Transaction Amount Distribution

- **Histogram**
 
- **Box Plot**
 
- **Outliers**
  
![Resources/Comparison between Fraudulent and Normal transactions wrt amount.png  
](<Resources/Comparison between Fraudulent and Normal transactions wrt amount.png>)

#### Feature Analysis

- **Box Plots of Features**
  

- **Histograms of Features**

![  !\[Feature Analysis\](image-3.png)
](<Resources/Feature Analysis.png>)

### 5. Feature Selection Using Correlation

- **Heatmap and Column Dropping**

![  !\[Heatmap\](image-4.png)](Resources/Heatmap.png)

