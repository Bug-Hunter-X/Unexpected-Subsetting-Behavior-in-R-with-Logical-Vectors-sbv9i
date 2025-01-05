This repository demonstrates a common, yet subtle, error in R programming related to subsetting data frames using boolean vectors.  The `bug.R` file shows incorrect code that uses a redundant comparison (`== TRUE`), leading to unexpected results. The `bugSolution.R` file presents the correct approach, which avoids the redundancy and produces the expected output.  This example highlights the importance of understanding how R handles logical indexing efficiently.