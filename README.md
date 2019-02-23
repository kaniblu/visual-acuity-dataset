# Korean Visual Acuity Dataset #

This dataset contains the statistics of visual acuity(시력) of 10m+ Koreans over the course of 2011 to 2017, grouped by gender, eye side, year, and age. Visual acuity is the measurement of one's ability to discern features from a distance, of which [Landolt C](https://en.wikipedia.org/wiki/Landolt_C) being the most common one.

The original data is publicly accessible from [Koraen Statistical Information Service](http://kosis.kr) and have been processed into a more friendly format suitable for data analysis.

* `visual-acuity-kr.pkl`: the data as `pd.DataFrame` object store in pickle form.
* `visual-acuity-kr.csv`: the same data in comma-separated format.

## Loading Dataset ##

```
>>> import pandas as pd
>>> df = pd.read_pickle("visual-acuity-kr.pkl")
>>> len(df)
2940
>>> df.columns
Index(['visual acuity', 'side', 'year', 'age', 'gender', 'n'], dtype='object')
```
