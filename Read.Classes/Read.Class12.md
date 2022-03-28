# Read: Class 12

---

> [Back to Home](../README.md)

---

> [references](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)

## What Are Pandas?

> What is it?

    pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.

> You can arrange multiple documents and activities side by side in the work area using tabs and splitters. Documents and activities integrate with each other, enabling new workflows for interactive computing, for example:

### examples

    import pandas as pd

    Object creation:
    s = pd.Series([1, 3, 5, np.nan, 6, 8])

    >>>>>>>>
    0  1.0
    1  3.0
    2  5.0
    3  NaN
    4  6.0
    5  8.0
    dtype: float64

> Creating a DataFrame by passing a NumPy array, with a datetime index and labeled columns:

    dates = pd.date_range("20130101", periods=6)

    DatetimeIndex(['2013-01-01', '2013-01-02', '2013-01-03', '2013-01-04',
               '2013-01-05', '2013-01-06'],
              dtype='datetime64[ns]', freq='D')

    df = pd.DataFrame(np.random.randn(6, 4), index=dates, columns=list("ABCD"))
                       A         B         C         D
                2013-01-01  0.469112 -0.282863 -1.509059 -1.135632
                2013-01-02  1.212112 -0.173215  0.119209 -1.044236
                2013-01-03 -0.861849 -2.104569 -0.494929  1.071804
                2013-01-04  0.721555 -0.706771 -1.039575  0.271860
                2013-01-05 -0.424972  0.567020  0.276232 -1.087401
                2013-01-06 -0.673690  0.113648 -1.478427  0.524988

---

> [Back to Home](../README.md)
