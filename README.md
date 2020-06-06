Vaex- Reading And Processing Huge Datasets in seconds

What is Vaex?

Vaex is a high performance Python library for lazy Out-of-Core DataFrames (similar to Pandas), to visualize and explore big tabular datasets. It calculates statistics such as mean, sum, count, standard deviation etc, on an N-dimensional grid for more than a billion (10^9) samples/rows per second. Visualization is done using histograms, density plots and 3d volume rendering, allowing interactive exploration of big data.
Vaex uses memory mapping, zero memory copy policy and lazy computations for best performance (no memory wasted).

We can Read And Process Huge Datasets in seconds directly read data from AWS S3 Bucket advantage of S3 buckets that we can put any type of data fromat.

Fast and efficient join with help of Vaex does not copy Metarilised the right table when joining saving gigabytes of memory so sub second of joining on billion rows it is pretty much fast.

Create Data Set by calling pd.DataFrame, initialize value between 0 to 100 for size n_rows, n_cols
i.e. we are taking 1M records and 500 Coumns randomly all the no. will be initialized 0-100.

Give column Name by ranging from 0 to n_cols i.e. last col, put the column name as Col%d i.e. particular number in range of  1 -500
Created in form of Data Frame

Converting CSV file into HDF5 file i.e Hierarchical Data Format is set of file format which is designed to store and organized large amount of data, so after converting csv into HDF5 file format it become very easy to extract, analyze and do operation on it.

Don't waste memory or time with feature engineering, we (lazily) transform your data when needed.

We have 1M records thats wery huge!!!

Filtering and evaluating expressions will not waste memory by making copies where as in pandas it make an extra copy; the data is kept untouched on disk, and will be streamed only when needed. Delay the time before you need a cluster.

Fast groupby / aggregations
Vaex implements parallelized, highly performant groupby operations, especially when using categories (>1 billion/second).

Vaex is realy awesome!!!!!!!!!
