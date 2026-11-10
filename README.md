# Project1-sequence-analysis
A Python program to identify and characterise next-generation sequencing reads with the aim of allowing easier identification of mutation patterns across samples based on treatment.
## Your README should include the following sections (~300 words in total), explaining:
Title & Purpose: What does your program do, and what biological question does it address? (~30 words)
## How to run the program: How do you open and run it in Colab? (~30 words)
1. Download the file and open it in Colab
2. Upload NGS reads and reference sequence, NGS reads should be named reads, and reference sequence should be named reference 
3. Run all - this is important, as not all functions will work without this
## Inputs: What input does it expect? What results does it return or display? (~60 words)
This program expects a .csv file containing the sample reads with columns called read_id, sample, group (containing what the sample was treated with or control) and sequence (containing the NGS read). For the compare_positions function, the name of the control group and treated group must be stated in the input.
## Outputs:
While each function will give you an output, using the final analysis will give you a summary that is easy to interpret. Final analysis will output two tables per group, summarising the reads and mismatches as well as the substitutions present, it will also state the top positions (up to 3) where there are mutations.  
## Code design: Explain 2-3 specific decisions (beyond the project specifications) that you made and why. For example: how you divided work between functions, chose data structures, or handled invalid reads. What alternatives did you consider? (120 words)
## Testing: Describe three informative tests that you ran to check the correctness or robustness your code. (60 words)
Refer to examples from your own code. Explain your reasoning rather than listing general principles of good programming.
