import pandas

pandas.set_option('display.max_columns', None)
pandas.set_option('display.max_rows', None)

data = pandas.read_csv('polomki.csv', index_col='Магазин')
print(data)
