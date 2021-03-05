# Papadimitriou for 2SAT problem
Papadimitriou's randomized local search algorithm for 2SAT problem.

In input file, in each instance, the number of variables and the number of clauses is the same, and this number is specified on the first line of the file.  Each subsequent line specifies a clause via its two literals, with a number denoting the variable and a "-" sign denoting logical "not".  

Before applying the Papadimitriou's algorithm, a reduction is applied to the input files. The reduction method runs for many iterations. In every iteration it removes those pairs that contains a variable that are all negated or not negated. The reduction stops where all remained variables are only appearing in the input with only one sign (positive or negative)

