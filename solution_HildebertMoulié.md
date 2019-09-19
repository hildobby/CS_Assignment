- MCC Van Dyke et al., 2019
- JT Harvey, Applied Ergonomics, 2002
- DW Ziegler et al., 2005


```{python}
import pandas as pd
import plotly.express as px

df = pd.read_csv('istherecorrelation.csv')

fig = px.line(df, x = 'Year, y = 'WO [x1000]', title='NL Beer consumption [x1000 hectoliter]')
fig.show()
```
