# diversity
A data set for social diversity studies of GitHub teams

The data is presented in CSV format and can be directly imported 
in R.
It contains a number of standard measures of (GitHub) activity, 
including **number of committers**, **team size** (committers, 
pull request submitters, commenters, etc.), **number of commits** 
(the most encompassing form of coding contribution to a GitHub 
project and a representative facet of developer productivity in 
open source), **number of comments** (on commits, pull requests, 
and issues; a measure of the project’s social activity), **number 
of issues opened**, **number of forks**, and **number of watchers**. 

Then, for each quarter (at least 2 quarters of data per project, 
by construction), we compute the **project age** (in quarters), 
the **number of female and male contributors**, the **genders** 
and **countries** of team members (at least 75% resolved, by 
construction), their **GitHub tenures** (in days; capturing global 
GitHub presence, based on account creation date), **commit tenures** 
(in days; capturing global coding experience, based on participation 
in any GitHub repository), and **project tenures** (in quarters; 
local project experience, not restricted to coding), the **numbers 
of contributors leaving** (i.e., active in the previous quarter but 
inactive now), **joining** (defined analogously), and **staying** in 
the team (i.e., in common between w.r.t. previous quarter), as well 
as the **turnover ratio** (i.e., the fraction of the team in a given 
quarter that is different with respect to previous quarter). 

Finally, we compute **Blau indices** of team **gender** and **country 
diversity**, a well-established diversity measure for categorical 
variables, and **coefficients of variation** for GitHub, commit, and 
project tenure, as measures of team tenure diversity.