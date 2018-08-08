%matplotlib inline
import pandas

data = pandas.read_csv('gapminder.csv', index_col='country')
years = data.columns.str.strip('gdpPercap_')
data.columns = years.astype(int)

data.loc['Australia'].plot()
