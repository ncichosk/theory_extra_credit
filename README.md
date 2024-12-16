# Theory of Computing Extra Credit

1. For extra credit, I created five Turing machines to be used in Project 2 and shared them with the rest of the class. Two of these are non-deterministic, and three are deterministic. Together with the `a plus NTM` provided, these files create three NTM with DTM counterparts to be used for testing and comparison in the second project.

2. I chose to do this extra credit because I struggled with mapping machines on the first exams and was particularly struggling with the machines on Homework 8. Doing this exercise helped me practice drawing out Turing machines and transposing those rules into code. This forced me to think harder about machine design to ensure that the machines worked properly for the project. As a result, I am a lot more comfortable creating Turing machines and thinking through the logic for PDAs and DFAs.

3. Each of these CSV files represents a Turing machine in the format outlined by the Project 2 instructions. The CSV files are as follows:
   - **`data_a_plus_DTM_ncichosk.csv`**: A deterministic Turing machine that recognizes the language `{w | w = a+}`
   - **`data_abc_star_ncichosk.csv`**: A nondeterministic Turing machine that recognizes the language `{w | w = a*b*c*}`
   - **`data_abc_star_DTM_ncichosk.csv`**: A deterministic Turing machine that recognizes the language `{w | w = a*b*c*}`
   - **`data_equal_01s_ncichosk.csv`**: A nondeterministic Turing machine that recognizes the language `{w | w has the same number of 0s and 1s}`
   - **`data_equal_01s_DTM_ncichosk.csv`**: A deterministic Turing machine that recognizes the language `{w | w has the same number of 0s and 1s}`
