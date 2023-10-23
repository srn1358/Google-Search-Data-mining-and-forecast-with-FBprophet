## Forecasting with fbProphet
I prepared, analyzed and vidualized financial data and the change of that with user data (mined the Google search traffic data). I used time series model to forecast sale and price in different fincancial datasets.
I worked in Colab environment. Please find the link below:
https://colab.research.google.com/drive/1xOkeLHQcVrwSsDRP430uuG3s_ZcsMszx?usp=sharing

## Installation Guide
```python
  from IPython.display import clear_output
  !pip install pystan
  !pip install fbprophet
  !pip install hvplot
  !pip install holoviews
  import pandas as pd
  import holoviews as hv
  from fbprophet import Prophet
  import hvplot.pandas
  import datetime as dt
  %matplotlib inline
```
