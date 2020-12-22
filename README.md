At the moment the main functions on the import are:

`ingest()` which takes in a file name written as a string and reads it into a pandas dataframe based on file format

`linearreg()` which quickly produces a `statsmodels.api` OLS regression in summary. Other forms of regression may be added in future updates.

`regplot` which produces a plotly regression scatterplot. In future updates, seaborne options may be added for those who want a local experience. 

`regandplot` which attempts to fuse the two previous commands. Note that due to dimensions only a simple regression can be plotted. In future I might think about ways to introduce 3D plotting for 3 variable regression.

