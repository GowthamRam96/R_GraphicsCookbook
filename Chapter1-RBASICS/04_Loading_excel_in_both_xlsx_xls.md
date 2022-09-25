The xlsx package has the function read.xlsx() for reading Excel files. This will read
the first sheet of an Excel spreadsheet:

```
# Only need to install once
install.packages("xlsx")
library(xlsx)

data <- read.xlsx("04_datafile.xlsx", 1)
```

For reading older Excel files in the .xls format, the gdata package has the function 
read.xls():

```
# Only need to install once
install.packages("gdata")
library(gdata)

# Read first sheet
data <- read.xls("04_datafile.xls")
```

Note: Set JAVA_HOME Environment Variable