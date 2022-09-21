The most common way to read in a file is to use comma-separated values (CSV) data:

```
data <- read.csv("datafile.csv")
```

Since data files have many different formats, there are many options for loading them.
For example, if the data file does not have headers in the first row:

```
data <- read.csv("datafile.csv",  header=FALSE)
```

![image](https://user-images.githubusercontent.com/84629235/191550712-7162b8b0-14b2-4526-ba93-31bde042fb43.png)



