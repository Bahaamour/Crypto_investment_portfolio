# Crypto_investment_portfolio

Financil Appliccation that cluster Cryptocurrencies by their performance in different time periods. 

![An image for the header of the Repository](/Images/crypto.png)


## Technologies
This platform uses `python 3.7.13` with the following libraries imported in the first code block includes: `Pandas`, `hvplot`, `scikit-learn`, `pathlib`.

---
## Installation Guide 

In case Pandas library is not available, run the following code in your terminal:

```python

pip install pandas
```


To install `scikit-learn`, `hvplot` , make sure your Conda `dev` environment is active, run the following command:

```python
pip install -U scikit-learn
```

```python
pip install -c pyviz hvplot
```

To confirm the  installation, run the following code in your terminal:

```python
conda list scikit-learn
conda list hvplot
 ```
 
---

## Usage

Libraries that we had to import are the following:

```
from pathlib import Path 
import pandas as pd
import hvplot.pandas
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```

---
## Contributors

Baha Amour
---

## License

MIT.