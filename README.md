# simple-sale-data-visulization_202401100300165-om-prakash-kannaujiya
1-Import Libraries:

Uses pandas for data handling and matplotlib.pyplot for visualization.
StringIO is used to treat the sales data as a file-like object.
2-Define Sales Data:

A multiline string stores product sales data with columns: Product, Quantity, and Revenue.
Load Data into Pandas DataFrame:

pd.read_csv(StringIO(data), delim_whitespace=True) reads the string as a table.
3-Calculate Total Revenue per Product:

df.groupby('Product')['Revenue'].sum() sums up revenue for each product type.
4-Create a Bar Chart:

The bar chart displays total revenue for each product category.
Labels and a legend are added for clarity.
5-Show the Chart:

plt.show() displays the final visualization.
