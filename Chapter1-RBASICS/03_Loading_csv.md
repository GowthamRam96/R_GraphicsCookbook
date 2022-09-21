The most common way to read in a file is to use comma-separated values (CSV) data:

```
data <- read.csv("datafile.csv")
```

Since data files have many different formats, there are many options for loading them.
For example, if the data file does not have headers in the first row:

```
data <- read.csv("datafile.csv",  header=FALSE)
```




